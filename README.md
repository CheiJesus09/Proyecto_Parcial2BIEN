# Proyecto_Parcial2
 Repositorio del Parcial 2

Características:
- Lecciones compuestas por un cuestionario.
- 5 posibles respuestas a la pregunta.
- Se evalúa la opción que se seleccione.
- Pasa a la siguiente pregunta después de un tiempo establecido.
- Proyecta un mensaje dependiendo de respuestas correctas o incorrectas.

¿Como se usa?
La primer pantalla es un menú de selección de lecciones, seleccionar una lección te llevara a un cuestionario de 5 preguntas. Aparecera un pop-up indicando la
lección que el usuario este escogiendo, asimismo con un botón para iniciar la lección.

El cuestionario generará una pregunta, requiere que el usuario lea con atención la pregunta y seleccione una respuesta ya que el botón de comprobar estará inhabilitado hasta haber seleccionado una respuesta; Al seleccionar una, se habilitará y dejara que el programa pueda comprobar la respuesta del usuario. Después se evaluara su respuesta; por lo que el programa hará una de dos opciones:

-Si la respuesta es correcta, esta se iluminara verde y soltará un mensaje diciéndole al usuario que su respuesta fue correcta.

-Si la respuesta es incorrecta, esta se iluminara rojo y soltará un mensaje diciéndole al usuario que su respuesta fue incorrecta.

Código
El código utilizado en este proyecto es el lenguaje C# de programación, orientada a objetos con el cual el mismo después de un tiempo adaptó las facilidades de la creación de código que tenía otro de sus lenguajes más populares, Visual Basic.

El programa usa un total de 5 scripts los cuales son:

Leccion: Contenido de las lecciones

Subject: La lista de las lecciones totales

Option: Contiene las opciones de las respuestas que estarán dentro de las preguntas de los cuestionarios
 
LevelContainer: Encargado de que el UI muestre las lecciones correctas con ayuda de la función OnUpdateUI() que revisa que el contenido no sea nulo, para asi mostrar el contenido asignado. La función EnableWindow() crea el Pop-up que muestra los botones de selección de nivel.

LevelManager: El alma del programa, al iniciar buscara la cantidad de preguntas que esten asignadas a la lección que se haya escogido
