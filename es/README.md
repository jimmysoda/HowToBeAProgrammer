# C�mo ser un programador: versi�n comunitaria

Robert L. Read con la comunidad

Copyright 2002, 2003, 2016 Robert L. Read

Licensiado bajo [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

## Introducci�n
Ser un buen programador es dif�cil y noble. La parte m�s dif�cil de materializar la visi�n colectiva de un proyecto de software es tratar con los colegas y clientes. Escribir programas de computadora es importante y requiere gran inteligencia y habilidad. Pero es realmente un juego de ni�os a comparaci�n del resto de lo que un buen programador debe hacer para que un sistema de software sea exitoso para el cliente y la mir�ada de colegas por los cu�les es parcialmente responsable. En este ensayo intento resumir lo mas conc�samente posible aquellas cosas que desar�a que alguien me hubiera explicado cu�ndo ten�a venti�n a�os.

Esto es muy subjetivo y, por lo tanto, este ensayo est� destinado a ser personal y algo opinionado. Me confino a los problemas que un programador muy probablemente encontrar� en su trabajo. Muchos de estos problemas y sus soluciones son tan generales a la condici�n humana que probablemente parecer�n un serm�n. Espero que este ensayo sea �til a pesar de �sto. 

La programaci�n de computadoras es ense�ado en cursos. Los libros excelentes c�mo The Pragmatic Programmer [Prag99], Code Complete [CodeC93], Rapid Development [RDev96] y Extreme Programming Explained [XP99] ense�an programaci�n de computadoras y los problemas m�s grandes de ser un buen programador. Los ensayos de Paul Graham [PGSite] y Eric Raymond [Hacker] deben con certeza ser le�dos antes o en compa��a de �ste art�culo. Este ensayo difiere de esos excelentes trabajos al enfatizar los problemas sociales y comprensivamente resumir el conjunto completo de habilidades que yo veo necesarias. 

En este ensayo el t�rmino _jefe_ es usado para referirse a qui�n te asigna proyectos. Uso las palabras _negocio_, _compa��a_ y _tribu_ como sin�nimos excepto que _negocio_ connota hacer dinero, _compa��a_ connota el sitio de empleo contempor�neo y _tribu_ es generalmente la gente con qui�n compartes tu lealtad.

Bienvenido a la tribu.

## Contenido

1. [Principiante](1-Beginner)
	- Habilidades personales
		- [Aprende a depurar](1-Beginner/Personal-Skills/01-Learn To Debug.md)
		- [C�mo depurar dividiendo el espacio del problema](1-Beginner/Personal-Skills/02-How to Debug by Splitting the Problem Space.md)
		- [C�mo eliminar un error](1-Beginner/Personal-Skills/03-How to Remove an Error.md)
		- [C�mo depurar usando un registro de texto](1-Beginner/Personal-Skills/04-How to Debug Using a Log.md)
		- [C�mo entender problemas de rendimiento](1-Beginner/Personal-Skills/05-How to Understand Performance Problems.md)
		- [C�mo arreglar problemas de rendimiento](1-Beginner/Personal-Skills/06-How to Fix Performance Problems.md)
		- [C�mo optimizar bucles](1-Beginner/Personal-Skills/07-How to Optimize Loops.md)
		- [C�mo manejar los costos de entrada y salida (I/O)](1-Beginner/Personal-Skills/08-How to Deal with IO Expense.md)
		- [C�mo manejar la memoria](1-Beginner/Personal-Skills/09-How to Manage Memory.md)
		- [C�mo lidiar con errores intermitentes](1-Beginner/Personal-Skills/10-How to Deal with Intermittent Bugs.md)
		- [C�mo aprender habilidades de dise�o](1-Beginner/Personal-Skills/11-How to Learn Design Skills.md)
		- [C�mo conducir experimentos](1-Beginner/Personal-Skills/12-How to Conduct Experiments.md)
	- Habilidades de equipo 
		- [Por qu� son importantes los estimados](1-Beginner/Team-Skills/01-Why Estimation is Important.md)
		- [C�mo estimar tiempo de programaci�n](1-Beginner/Team-Skills/02-How to Estimate Programming Time.md)
		- [C�mo encontrar informaci�n](1-Beginner/Team-Skills/03-How to Find Out Information.md)
		- [C�mo usar a otros como fuentes de informaci�n](1-Beginner/Team-Skills/04-How to Utilize People as Information Sources.md)
		- [C�mo documentar sabiamente](1-Beginner/Team-Skills/05-How to Document Wisely.md)
		- [C�mo trabajar con mal c�digo](1-Beginner/Team-Skills/06-How to Work with Poor Code.md)
		- [C�mo usar sistemas de control de c�digo](1-Beginner/Team-Skills/07-How to Use Source Code Control.md)
		- [C�mo usar pruebas unitarias](1-Beginner/Team-Skills/08-How to Unit Test.md)
		- [Descansa cu�ndo est�s estancado](1-Beginner/Team-Skills/09-Take Breaks when Stumped.md)
		- [C�mo saber cu�ndo marcharse a casa](1-Beginner/Team-Skills/10-How to Recognize When to Go Home.md)
		- [C�mo tratar con gente dif�cil](1-Beginner/Team-Skills/11-How to Deal with Difficult People.md)
2. [Intermedio](2-Intermediate)
	- Habilidades personales
		- [C�mo mantenerse motivado](2-Intermediate/Personal-Skills/01-How to Stay Motivated.md)
		- [C�mo ser ampliamente confiado](2-Intermediate/Personal-Skills/02-How to be Widely Trusted.md)
		- [C�mo equilibrar el tiempo contra el espacio](2-Intermediate/Personal-Skills/03-How to Tradeoff Time vs Space.md)
		- [C�mo hacer pruebas de estr�s](2-Intermediate/Personal-Skills/04-How to Stress Test.md)
		- [C�mo balancear brevedad y abstracci�n](2-Intermediate/Personal-Skills/05-How to Balance Brevity and Abstraction.md)
		- [C�mo aprender nuevas habilidades](2-Intermediate/Personal-Skills/06-How to Learn New Skills.md)
		- [Aprende a teclear](2-Intermediate/Personal-Skills/07-Learn to Type.md)
		- [C�mo hacer pruebas de integraci�n](2-Intermediate/Personal-Skills/08-How to Do Integration Testing.md)
		- [Lenguajes de comunicaci�n](2-Intermediate/Personal-Skills/09-Communication Languages.md)
		- [Herramientas pesadas](2-Intermediate/Personal-Skills/10-Heavy Tools.md)
		- [C�mo analizar datos](2-Intermediate/Personal-Skills/11-How to analyze data.md)
	- Habilidades de equipo
		- [C�mo administrar el tiempo de desarrollo](2-Intermediate/Team-Skills/01-How to Manage Development Time.md)
		- [C�mo manejar riesgos debido a software de terceros](2-Intermediate/Team-Skills/02-How to Manage Third-Party Software Risks.md)
		- [C�mo manejar consultores](2-Intermediate/Team-Skills/03-How to Manage Consultants.md)
		- [C�mo comunicar lo suficiente](2-Intermediate/Team-Skills/04-How to Communicate the Right Amount.md)
		- [C�mo discrepar honestamente y salirte con la tuya](2-Intermediate/Team-Skills/05-How to Disagree Honestly and Get Away with It.md)
	- Juicio
		- [C�mo equilibrar calidad contra tiempo de desarrollo](2-Intermediate/Judgment/01-How to Tradeoff Quality Against Development Time.md)
		- [C�mo manejar las dependencias entre sistemas de software](2-Intermediate/Judgment/02-How to Manage Software System Dependence.md)
		- [C�mo decidir si el software es muy inmaduro](2-Intermediate/Judgment/03-How to Decide if Software is Too Immature.md)
		- [C�mo decidir entre comprar y construir](2-Intermediate/Judgment/04-How to Make a Buy vs Build Decision.md)
		- [C�mo crecer profesionalmente](2-Intermediate/Judgment/05-How to Grow Professionally.md)
		- [C�mo evaluar candidatos en entrevistas de empleo](2-Intermediate/Judgment/06-How to Evaluate Interviewees.md)
		- [C�mo saber cuando aplicar inform�tica elegante](2-Intermediate/Judgment/07-How to Know When to Apply Fancy Computer Science.md)
		- [C�mo hablarle a los no-ingenieros](2-Intermediate/Judgment/08-How to Talk to Non-Engineers.md)
3. [Avanzado](3-Advanced)
    - Juicio t�cnico
        - [C�mo distinguir lo dif�cil de lo imposible](3-Advanced/Technical-Judgment/01-How to Tell the Hard From the Impossible.md)
        - [C�mo usar lenguajes para sistemas incrustados](3-Advanced/Technical-Judgment/02-How to Utilize Embedded Languages.md)
        - [C�mo escoger lenguajes](3-Advanced/Technical-Judgment/03-Choosing Languages.md)
    - Comprometi�ndose sabiamente
        - [C�mo luchar contra la presi�n de los horarios](3-Advanced/Compromising-Wisely/01-How to Fight Schedule Pressure.md)
        - [C�mo entender al usuario](3-Advanced/Compromising-Wisely/02-How to Understand the User.md)
        - [C�mo obtener un ascenso de empleo](3-Advanced/Compromising-Wisely/03-How to Get a Promotion.md)
    - Sirviendo a tu equipo
        - [C�mo desarrollar talento](3-Advanced/Serving-Your-Team/01-How to Develop Talent.md)
        - [C�mo escoger tu trabajo](3-Advanced/Serving-Your-Team/02-How to Choose What to Work On.md)
        - [C�mo aprovechar tus compa�eros al m�ximo](3-Advanced/Serving-Your-Team/03-How to Get the Most From Your Teammates.md)
        - [C�mo dividir los problemas](3-Advanced/Serving-Your-Team/04-How to Divide Problems Up.md)
        - [C�mo manejar las tareas aburridoras](3-Advanced/Serving-Your-Team/05-How to Handle Boring Tasks.md)
        - [C�mo obtener apoyo para un proyecto](3-Advanced/Serving-Your-Team/06-How to Gather Support for a Project.md)
        - [C�mo manejar el crecimiento de un sistema](3-Advanced/Serving-Your-Team/07-How to Grow a System.md)
        - [C�mo comunicarse bien](3-Advanced/Serving-Your-Team/08-How to Communicate Well.md)
        - [C�mo decirle a la gente lo que no desean escuchar](3-Advanced/Serving-Your-Team/09-How to Tell People Things They Don't Want to Hear.md)
        - [C�mo lidiar con los mitos administrativos](3-Advanced/Serving-Your-Team/10-How to Deal with Managerial Myths.md)
        - [C�mo lidiar con el caos organizacional](3-Advanced/Serving-Your-Team/11-How to Deal with Organizational Chaos.md)
4. [Glosario](GLOSSARY.md)
5. [Ap�ndice A - Bibliograf�a y referencias web](5-Bibliography.md)
6. [Ap�ndice B - Historia (hasta enero de 2016)](6-History.md)
7. [Ap�ndice C - Contribuciones (hasta enero de 2016)](7-Contributions.md)


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">C�mo ser un programador: version comunitaria</span> por <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Robert L. Read con la comunidad</span> es licensiabo bajo la licencia <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
