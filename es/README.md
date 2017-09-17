# Cómo ser un programador: versión comunitaria

Robert L. Read con la comunidad

Copyright 2002, 2003, 2016 Robert L. Read

Licensiado bajo [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

## Introducción
Ser un buen programador es difícil y noble. La parte más difícil de materializar la visión colectiva de un proyecto de software es tratar con los colegas y clientes. Escribir programas de computadora es importante y requiere gran inteligencia y habilidad. Pero es realmente un juego de niños a comparación del resto de lo que un buen programador debe hacer para que un sistema de software sea exitoso para el cliente y la miríada de colegas por los cuáles es parcialmente responsable. En este ensayo intento resumir lo mas concísamente posible aquellas cosas que desaría que alguien me hubiera explicado cuándo tenía ventiún años.

Esto es muy subjetivo y, por lo tanto, este ensayo está destinado a ser personal y algo opinionado. Me confino a los problemas que un programador muy probablemente encontrará en su trabajo. Muchos de estos problemas y sus soluciones son tan generales a la condición humana que probablemente parecerán un sermón. Espero que este ensayo sea útil a pesar de ésto. 

La programación de computadoras es enseñado en cursos. Los libros excelentes cómo The Pragmatic Programmer [Prag99], Code Complete [CodeC93], Rapid Development [RDev96] y Extreme Programming Explained [XP99] enseñan programación de computadoras y los problemas más grandes de ser un buen programador. Los ensayos de Paul Graham [PGSite] y Eric Raymond [Hacker] deben con certeza ser leídos antes o en compañía de éste artículo. Este ensayo difiere de esos excelentes trabajos al enfatizar los problemas sociales y comprensivamente resumir el conjunto completo de habilidades que yo veo necesarias. 

En este ensayo el término _jefe_ es usado para referirse a quién te asigna proyectos. Uso las palabras _negocio_, _compañía_ y _tribu_ como sinónimos excepto que _negocio_ connota hacer dinero, _compañía_ connota el sitio de empleo contemporáneo y _tribu_ es generalmente la gente con quién compartes tu lealtad.

Bienvenido a la tribu.

## Contenido

1. [Principiante](1-Beginner)
	- Habilidades personales
		- [Aprende a depurar](1-Beginner/Personal-Skills/01-Learn-To-Debug.md)
		- [Cómo depurar dividiendo el espacio del problema](1-Beginner/Personal-Skills/02-How-to-Debug-by-Splitting-the-Problem-Space.md)
		- [Cómo eliminar un error](1-Beginner/Personal-Skills/03-How-to-Remove-an-Error.md)
		- [Cómo depurar usando un registro de texto](1-Beginner/Personal-Skills/04-How-to-Debug-Using-a-Log.md)
		- [Cómo entender problemas de rendimiento](1-Beginner/Personal-Skills/05-How-to-Understand-Performance-Problems.md)
		- [Cómo arreglar problemas de rendimiento](1-Beginner/Personal-Skills/06-How-to-Fix-Performance-Problems.md)
		- [Cómo optimizar bucles](1-Beginner/Personal-Skills/07-How-to-Optimize-Loops.md)
		- [Cómo manejar los costos de entrada y salida (I/O)](1-Beginner/Personal-Skills/08-How-to-Deal-with-IO-Expense.md)
		- [Cómo manejar la memoria](1-Beginner/Personal-Skills/09-How-to-Manage-Memory.md)
		- [Cómo lidiar con errores intermitentes](1-Beginner/Personal-Skills/10-How-to-Deal-with-Intermittent-Bugs.md)
		- [Cómo aprender habilidades de diseño](1-Beginner/Personal-Skills/11-How-to-Learn-Design-Skills.md)
		- [Cómo conducir experimentos](1-Beginner/Personal-Skills/12-How-to-Conduct-Experiments.md)
	- Habilidades de equipo 
		- [Por qué son importantes los estimados](1-Beginner/Team-Skills/01-Why-Estimation-is-Important.md)
		- [Cómo estimar tiempo de programación](1-Beginner/Team-Skills/02-How-to-Estimate-Programming-Time.md)
		- [Cómo encontrar información](1-Beginner/Team-Skills/03-How-to-Find-Out-Information.md)
		- [Cómo usar a otros como fuentes de información](1-Beginner/Team-Skills/04-How-to-Utilize-People-as-Information-Sources.md)
		- [Cómo documentar sabiamente](1-Beginner/Team-Skills/05-How-to-Document-Wisely.md)
		- [Cómo trabajar con mal código](1-Beginner/Team-Skills/06-How-to-Work-with-Poor-Code.md)
		- [Cómo usar sistemas de control de código](1-Beginner/Team-Skills/07-How-to-Use-Source-Code-Control.md)
		- [Cómo usar pruebas unitarias](1-Beginner/Team-Skills/08-How-to-Unit-Test.md)
		- [Descansa cuándo estés estancado](1-Beginner/Team-Skills/09-Take-Breaks-when-Stumped.md)
		- [Cómo saber cuándo marcharse a casa](1-Beginner/Team-Skills/10-How-to-Recognize-When-to-Go-Home.md)
		- [Cómo tratar con gente difícil](1-Beginner/Team-Skills/11-How-to-Deal-with-Difficult-People.md)
2. [Intermedio](2-Intermediate)
	- Habilidades personales
		- [Cómo mantenerse motivado](2-Intermediate/Personal-Skills/01-How-to-Stay-Motivated.md)
		- [Cómo ser ampliamente confiado](2-Intermediate/Personal-Skills/02-How-to-be-Widely-Trusted.md)
		- [Cómo equilibrar el tiempo contra el espacio](2-Intermediate/Personal-Skills/03-How-to-Tradeoff-Time-vs-Space.md)
		- [Cómo hacer pruebas de estrés](2-Intermediate/Personal-Skills/04-How-to-Stress-Test.md)
		- [Cómo balancear brevedad y abstracción](2-Intermediate/Personal-Skills/05-How-to-Balance-Brevity-and-Abstraction.md)
		- [Cómo aprender nuevas habilidades](2-Intermediate/Personal-Skills/06-How-to-Learn-New-Skills.md)
		- [Aprende a teclear](2-Intermediate/Personal-Skills/07-Learn-to-Type.md)
		- [Cómo hacer pruebas de integración](2-Intermediate/Personal-Skills/08-How-to-Do-Integration-Testing.md)
		- [Lenguajes de comunicación](2-Intermediate/Personal-Skills/09-Communication-Languages.md)
		- [Herramientas pesadas](2-Intermediate/Personal-Skills/10-Heavy-Tools.md)
		- [Cómo analizar datos](2-Intermediate/Personal-Skills/11-How-to-analyze-data.md)
	- Habilidades de equipo
		- [Cómo administrar el tiempo de desarrollo](2-Intermediate/Team-Skills/01-How-to-Manage-Development-Time.md)
		- [Cómo manejar riesgos debido a software de terceros](2-Intermediate/Team-Skills/02-How-to-Manage-Third-Party-Software-Risks.md)
		- [Cómo manejar consultores](2-Intermediate/Team-Skills/03-How-to-Manage-Consultants.md)
		- [Cómo comunicar lo suficiente](2-Intermediate/Team-Skills/04-How-to-Communicate-the-Right-Amount.md)
		- [Cómo discrepar honestamente y salirte con la tuya](2-Intermediate/Team-Skills/05-How-to-Disagree-Honestly-and-Get-Away-with-It.md)
	- Juicio
		- [Cómo equilibrar calidad contra tiempo de desarrollo](2-Intermediate/Judgment/01-How-to-Tradeoff-Quality-Against-Development-Time.md)
		- [Cómo manejar las dependencias entre sistemas de software](2-Intermediate/Judgment/02-How-to-Manage-Software-System-Dependence.md)
		- [Cómo decidir si el software es muy inmaduro](2-Intermediate/Judgment/03-How-to-Decide-if-Software-is-Too-Immature.md)
		- [Cómo decidir entre comprar y construir](2-Intermediate/Judgment/04-How-to-Make-a-Buy-vs-Build-Decision.md)
		- [Cómo crecer profesionalmente](2-Intermediate/Judgment/05-How-to-Grow-Professionally.md)
		- [Cómo evaluar candidatos en entrevistas de empleo](2-Intermediate/Judgment/06-How-to-Evaluate-Interviewees.md)
		- [Cómo saber cuando aplicar informática elegante](2-Intermediate/Judgment/07-How-to-Know-When-to-Apply-Fancy-Computer-Science.md)
		- [Cómo hablarle a los no-ingenieros](2-Intermediate/Judgment/08-How-to-Talk-to-Non-Engineers.md)
3. [Avanzado](3-Advanced)
    - Juicio técnico
		- [Cómo distinguir lo difícil de lo imposible](3-Advanced/Technical-Judgment/01-How-to-Tell-the-Hard-From-the-Impossible.md)
		- [Cómo usar lenguajes para sistemas incrustados](3-Advanced/Technical-Judgment/02-How-to-Utilize-Embedded-Languages.md)
		- [Cómo escoger lenguajes](3-Advanced/Technical-Judgment/03-Choosing-Languages.md)
	- Comprometiéndose sabiamente
		- [Cómo luchar contra la presión de los horarios](3-Advanced/Compromising-Wisely/01-How-to-Fight-Schedule-Pressure.md)
		- [Cómo entender al usuario](3-Advanced/Compromising-Wisely/02-How-to-Understand-the-User.md)
		- [Cómo obtener un ascenso de empleo](3-Advanced/Compromising-Wisely/03-How-to-Get-a-Promotion.md)
	- Sirviendo a tu equipo
		- [Cómo desarrollar talento](3-Advanced/Serving-Your-Team/01-How-to-Develop-Talent.md)
		- [Cómo escoger tu trabajo](3-Advanced/Serving-Your-Team/02-How-to-Choose-What-to-Work-On.md)
		- [Cómo aprovechar tus compañeros al máximo](3-Advanced/Serving-Your-Team/03-How-to-Get-the-Most-From-Your-Teammates.md)
		- [Cómo dividir los problemas](3-Advanced/Serving-Your-Team/04-How-to-Divide-Problems-Up.md)
		- [Cómo manejar las tareas aburridoras](3-Advanced/Serving-Your-Team/05-How-to-Handle-Boring-Tasks.md)
		- [Cómo obtener apoyo para un proyecto](3-Advanced/Serving-Your-Team/06-How-to-Gather-Support-for-a-Project.md)
		- [Cómo manejar el crecimiento de un sistema](3-Advanced/Serving-Your-Team/07-How-to-Grow-a-System.md)
		- [Cómo comunicarse bien](3-Advanced/Serving-Your-Team/08-How-to-Communicate-Well.md)
		- [Cómo decirle a la gente lo que no desean escuchar](3-Advanced/Serving-Your-Team/09-How-to-Tell-People-Things-They-Don't-Want-to-Hear.md)
		- [Cómo lidiar con los mitos administrativos](3-Advanced/Serving-Your-Team/10-How-to-Deal-with-Managerial-Myths.md)
		- [Cómo lidiar con el caos organizacional](3-Advanced/Serving-Your-Team/11-How-to-Deal-with-Organizational-Chaos.md)
4. [Glosario](GLOSSARY.md)
5. [Apéndice A - Bibliografía y referencias web](5-Bibliography.md)
6. [Apéndice B - Historia (hasta enero de 2016)](6-History.md)
7. [Apéndice C - Contribuciones (hasta enero de 2016)](7-Contributions.md)


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Cómo ser un programador: version comunitaria</span> por <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Robert L. Read con la comunidad</span> es licensiado bajo la licencia <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
