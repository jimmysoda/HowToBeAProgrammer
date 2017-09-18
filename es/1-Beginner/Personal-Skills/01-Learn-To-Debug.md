# Aprende a depurar
[//]: # (Version:1.0.0)
Depurar código es la piedra angular para ser un programador. El primer significado del verbo "depurar" es remover errores, pero el significado que realmente importa es ver la ejecución de un programa al examinarlo. Un programador que no puede depurar está efectivamente a ciegas.

Los idealistas que piensan que saber acerca del diseño, el análisis, la teoría de complejidad y aspectos similares son más importantes que saber depurar, no trabajan como programadores. El que trabaja como programador no vive en un mundo ideal. Aún si eres es perfecto, estás rodeado y debes interactuar con código escrito por las principales compañías de software, organizaciones como GNU y tus colegas. La mayoría de este código es imperfecto e imperfectamente documentado. Sin la habilidad de visualizar la ejecución de este código, el más leve obstáculo te desviará permanentemente. A menudo esta visibilidad piede ser obtenida solo a través de la experimentación: es decir, depirando.

La depuración se enfoca en la ejecución de los programas, no de los programas en si. Si compras algo de una compañía grande de software, usualmente no ves el programa. Aún así puedes notar partes dónde el código no concuerda con la documentación (un bloqueo completo de tu equipo es un ejemplo común y espectacular) o dónde documentación enmudece. Más comúnmente, creas un error, examinas el código que escribiste y no tienes idea de cómo el error puede estar ocurriendo.  Inevitablemente, esto significa que alguna suposición no es correcta u ocurre alguna condición que no anticipabas. Algunas veces funciona el truco mágico de fijamente mirar el código fuente. Cuándo no, debes depurar.

Para visualizar la ejecución de un programa debes tener la facilidad de ejecutar y observar el código. Algunas veces esto es visible, como cuando el programa se muestra en una pantalla o cuando existe un atraso entre dos eventos. En muchos casos, involucra cosas que intencionalmente no son visibles, como el estado de algunas variables en el código, que líneas de código están siendo ejecutadas o si ciertas aserciones se sostienen a través de una estructura de datos complicada. Estas cosas secretas deben ser reveladas.

Las formas más comunes de ver las 'entrañas' de un programa en ejecución pueden ser categorizadas como:

- El uso de una herramienta de depuración,
- Registro en la consola - Hacer una modificación temporal al programa, típicamente agregando líneas para registrar información en una ventana de comando o consola, y
- Visualización del registro - Crear una ventana permanente en el programa para visualizar su ejecución como un registro.

Las herramientas de depuración son maravillosas cuando son estables y están disponibles, sin embargo, es aún más importante el registro de información en la consola o una ventana en el programa. Las herramientas de depuración a menudo están atrasadas respecto al desarrollo de los lenguajes de programación, entonces es posible que hayan momentos en que no estén disponibles. Adicionalmente, las herramientas de depuración en algunos casos pueden ser imprácticas al sutilmente cambiar la ejecución del programa. Finalmente, algunos tipos de depuración, tales como revisar una aserción respecto a una estructura de datos grande, requieren escribir código y cambiar la ejecución del programa. Es bueno saber cómo usar herramientas de depuración cuando son estables, pero es crucial poder emplear los otros dos métodos. 

Algunos principiantes temen depurar cuando requiere cambiar el código. Esto es entendible - es casi como cirugía exploratoria. Pero debes aprender a hurgar el código y hacerlo brincar; debes aprender a experimentar en él y entender que nada de lo que temporalmente le hagas lo va a empeorar. Si sientes este temor, busca un mentor - perdemos muchos buenos programadores en el delicado comienzo de su aprendizaje por este temor.

Próximo [Cómo depurar dividiendo el espacio del problema](02-How-to-Debug-by-Splitting-the-Problem-Space.md)
