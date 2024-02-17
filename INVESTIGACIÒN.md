 QUE es GIT?
Hay muchos desarrolladores y es el más popular. Utilizarlo prácticamente ya es indispensable para cualquier desarrollador y programador. Debe dominar Git específicamente porque los softwares están complicando cada 
vez más y necesitamos mejores herramientas. A lo largo del tiempo, esto suena complicado para evitar gritar. Vamos a dar, desde luego, qué es lo que usted hablo y luego, si quieres aprenderlo, pues vamos a empezar 
hoy. Programa que controla o administra las distintas versiones de un programa. En este caso, voy a hablar de programas porque, por lo general, cuando un programador o un desarrollador lo utiliza es porque quiere 
controlar un proyecto que va a crecer a medida que el tiempo va haciendo cambios en su proyecto. Es decir, a medida que tu proyecto va creciendo, vas a ir cambiando archivos, vas a ir modificando o cómo está configurado 
tu aplicación, cómo está escrito el código, etcétera. Tu programa va a ir cambiando a medida que vas evolucionando y para controlar estos distintos cambios, la opción es utilizar sistemas de control de versiones. Hay una
 infinidad de sistemas de control de versiones, pero en realidad el más popular actualmente es Git. Así que si quieres ver cómo controlar real, pues te recomiendo aprender Git. Fue creado por el mismo creador del kernel 
 de Linux, fue creado por Linus Torvalds y él lo creó específicamente porque él necesitaba una manera controlada en los cambios que hacía en el código.

¿Cuáles son los comandos más importantes y para qué sirven?

git init: Crea un nuevo repositorio en un directorio vacío.
git add <archivo>: Agrega cambios de un archivo al área de preparación para ser guardados.
git status: Muestra el estado actual de tus archivos y del repositorio.
git commit: Guarda los cambios que has agregado al área de preparación en tu repositorio.
git push: Sube tus cambios guardados localmente al repositorio remoto.
git pull: Descarga los cambios del repositorio remoto y los fusiona con tu repositorio local.
git clone: Crea una copia local de un repositorio remoto en tu computadora.

¿Cuál es la diferencia entre Git y Github?

Git: Es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear los cambios en su código fuente durante el tiempo. Con Git, puedes realizar un seguimiento de todas las modificaciones,
 revertir a versiones anteriores, trabajar en colaboración con otros desarrolladores y más, todo ello de forma local en tu propio equipo.

GitHub: Por otro lado, GitHub es una plataforma en línea que utiliza Git para alojar repositorios de código. Proporciona herramientas adicionales para la colaboración en equipo, seguimiento de problemas (issues), 
gestión de proyectos, revisión de código (code review), entre otras características. GitHub permite a los desarrolladores alojar sus proyectos de forma remota y colaborar con otros de manera más sencilla.

Comandos para subir cambios a un repositorio en Git:

Para subir cambios a un repositorio en Git, generalmente se sigue este proceso:

git add <nombre_del_archivo>: Agrega los archivos modificados o nuevos al área de preparación (staging area).
git commit -m "Mensaje descriptivo": Confirma los cambios añadidos en el área de preparación junto con un mensaje que describe las modificaciones realizadas.
git push origin <nombre_de_la_rama>: Sube los cambios confirmados al repositorio remoto en la rama especificada.

¿Qué es una branch?:

Una branch, o rama en español, es una versión paralela de un proyecto Git. Permite a los desarrolladores trabajar en nuevas características, resolver problemas o realizar experimentos sin afectar
 la rama principal (generalmente llamada master o main). Las ramas son útiles para organizar el trabajo, facilitar la colaboración entre equipos y realizar pruebas sin interferir con el código estable del proyecto.
  Una vez que los cambios en una rama están listos y probados, pueden fusionarse (merge) de vuelta a la rama principal. Esto ayuda a mantener un flujo de trabajo ordenado y a evitar conflictos entre las diferentes
   partes del proyecto.
