# Aprende a depurar

Depurar código es la piedra angular para ser un programador. El primer significado del verbo "depurar" es remover errores, pero el significado que realmente importa es ver la ejecución de un programa al examinarlo. Un programador que no puede depurar está efectivamente a ciegas.

Los idealistas que piensan que saber acerca del diseño, el análisis, la teoría de complejidad y aspectos similares son más importantes que saber depurar, no trabajan como programadores. El que trabaja como programador no vive en un mundo ideal. Aún si eres es perfecto, estás rodeado y debes interactuar con código escrito por las principales compañías de software, organizaciones como GNU y tus colegas. La mayoría de este código es imperfecto e imperfectamente documentado. Sin la habilidad de visualizar la ejecución de este código, el más leve obstáculo te desviará permanentemente. A menudo esta visibilidad piede ser obtenida solo a través de la experimentación: es decir, depirando.

Debugging is about the running of programs, not programs themselves. If you buy something from a major software company, you usually don't get to see the program. But there will still arise places where the code does not conform to the documentation (crashing your entire machine is a common and spectacular example), or where the documentation is mute. More commonly, you create an error, examine the code you wrote, and have no clue how the error can be occurring. Inevitably, this means some assumption you are making is not quite correct or some condition arises that you did not anticipate. Sometimes, the magic trick of staring into the source code works. When it doesn't, you must debug.

To get visibility into the execution of a program you must be able to execute the code and observe something about it. Sometimes this is visible, like what is being displayed on a screen, or the delay between two events. In many other cases, it involves things that are not meant to be visible, like the state of some variables inside the code, which lines of code are actually being executed, or whether certain assertions hold across a complicated data structure. These hidden things must be revealed.

The common ways of looking into the ‘innards’ of an executing program can be categorized as:

- Using a debugging tool,
- Printlining - Making a temporary modification to the program, typically adding lines that print information out, and
- Logging - Creating a permanent window into the programs execution in the form of a log.

Debugging tools are wonderful when they are stable and available, but the printlining and logging are even more important. Debugging tools often lag behind language development, so at any point in time they may not be available. In addition, because the debugging tool may subtly change the way the program executes it may not always be practical. Finally, there are some kinds of debugging, such as checking an assertion against a large data structure, that require writing code and changing the execution of the program. It is good to know how to use debugging tools when they are stable, but it is critical to be able to employ the other two methods.

Some beginners fear debugging when it requires modifying code. This is understandable - it is a little like exploratory surgery. But you have to learn to poke at the code and make it jump; you have to learn to experiment on it and understand that nothing that you temporarily do to it will make it worse. If you feel this fear, seek out a mentor - we lose a lot of good programmers at the delicate onset of their learning to this fear.

Next [How to Debug by Splitting the Problem Space](02-How to Debug by Splitting the Problem Space.md)
