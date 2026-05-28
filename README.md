#Evidencia de ejemplos

ejemplo #1
<img width="1134" height="233" alt="image" src="https://github.com/user-attachments/assets/816043de-3ca2-4a11-8fdb-e7f35c92e852" />
¿Qué clase se define?
Se define la clase llamada Punto, la cual representa un punto con coordenadas x y y.

¿Qué operador se sobrecarga?
Se sobrecarga el operador +.

¿Cuántos operandos utiliza?
Utiliza dos operandos: el objeto actual (p1) y el objeto recibido como parámetro (p2).

¿Qué tipo de dato devuelve?
Devuelve un objeto de tipo Punto.

¿El operador modifica el objeto actual o crea uno nuevo?
El operador no modifica el objeto actual; crea y devuelve un nuevo objeto con la suma de las coordenadas.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite usar el operador + de manera natural y fácil de entender, como si se trabajara con tipos de datos básicos.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar realizar sumas manuales de atributos (x y y) cada vez que se quieran combinar puntos, reduciendo errores y haciendo el código más ordenado.

ejemplo #2
<img width="1133" height="165" alt="image" src="https://github.com/user-attachments/assets/76566e44-6eb1-4e7e-ac42-15180b5bbdf0" />
¿Qué clase se define?
Se define la clase llamada Libro, la cual representa un libro mediante su atributo titulo.

¿Qué operador se sobrecarga?
Se sobrecarga el operador ==.

¿Cuántos operandos utiliza?
Utiliza dos operandos: el objeto actual (a) y el objeto recibido como parámetro (b).

¿Qué tipo de dato devuelve?
Devuelve un valor de tipo bool (true o false).

¿El operador modifica el objeto actual o crea uno nuevo?
No modifica el objeto actual ni crea uno nuevo; únicamente compara los títulos de los libros.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite comparar objetos usando == de forma sencilla y natural, haciendo el código más fácil de leer.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar comparaciones manuales de atributos o comparar direcciones de memoria en lugar del contenido real de los objetos.

ejemplo #3
<img width="1126" height="174" alt="image" src="https://github.com/user-attachments/assets/246759da-b9a5-47f0-ba01-dcd6591e7048" />
¿Qué clase se define?
Se define la clase llamada Persona, la cual contiene el atributo nombre.

¿Qué operador se sobrecarga?
Se sobrecarga el operador <<.

¿Cuántos operandos utiliza?
Utiliza dos operandos: el flujo de salida cout y el objeto Persona.

¿Qué tipo de dato devuelve?
Devuelve un objeto de tipo ostream&.

¿El operador modifica el objeto actual o crea uno nuevo?
No modifica el objeto actual ni crea uno nuevo; solamente muestra la información del objeto en pantalla.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite imprimir objetos directamente usando cout, haciendo el código más limpio y fácil de entender.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar escribir instrucciones repetitivas para mostrar los atributos del objeto cada vez que se quiera imprimir su información.

ejemplo #4
<img width="1129" height="164" alt="image" src="https://github.com/user-attachments/assets/afe26229-c5b6-4ef4-b384-bf48d6de500f" />
¿Qué clase se define?
Se define la clase llamada Contador, la cual almacena un valor entero en el atributo valor.

¿Qué operador se sobrecarga?
Se sobrecarga el operador ++ de post-incremento.

¿Cuántos operandos utiliza?
Utiliza un solo operando: el objeto Contador.

¿Qué tipo de dato devuelve?
Devuelve un objeto de tipo Contador.

¿El operador modifica el objeto actual o crea uno nuevo?
El operador modifica el objeto actual aumentando su valor en 1, pero también crea y devuelve una copia temporal con el valor anterior.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite usar el operador ++ de forma similar a los tipos de datos básicos, haciendo el código más sencillo y entendible.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar incrementar manualmente el valor del objeto y cometer errores al manejar el valor original y el actualizado.

ejemplo #5
<img width="1124" height="189" alt="image" src="https://github.com/user-attachments/assets/094736f9-4a2e-45e5-9cc6-79cac4165c00" />
¿Qué clase se define?
Se define la clase llamada Cadena, la cual maneja un texto almacenado dinámicamente mediante un puntero char*.

¿Qué operador se sobrecarga?
Se sobrecarga el operador de asignación =.

¿Cuántos operandos utiliza?
Utiliza dos operandos: el objeto que recibe la asignación (a) y el objeto que se copia (b).

¿Qué tipo de dato devuelve?
Devuelve una referencia de tipo Cadena&.

¿El operador modifica el objeto actual o crea uno nuevo?
El operador modifica el objeto actual copiando el contenido del otro objeto en él.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite usar la asignación entre objetos de manera natural y similar a los tipos de datos básicos.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar problemas de memoria, como copias superficiales o liberar memoria incorrectamente, ya que realiza una copia profunda del texto.

ejemplo #6
<img width="1135" height="181" alt="image" src="https://github.com/user-attachments/assets/be748dbc-2356-4e43-be7d-5af432576345" />
¿Qué clase se define?
Se define la clase llamada Temperatura, la cual almacena un valor de temperatura en grados Celsius.

¿Qué operador se sobrecarga?
Se sobrecarga el operador de conversión a double.

¿Cuántos operandos utiliza?
Utiliza un solo operando: el objeto Temperatura.

¿Qué tipo de dato devuelve?
Devuelve un valor de tipo double.

¿El operador modifica el objeto actual o crea uno nuevo?
No modifica el objeto actual ni crea uno nuevo; únicamente convierte el valor almacenado a tipo double.

¿La sobrecarga hace que el código sea más claro?
Sí, porque permite convertir objetos de la clase a un tipo básico de manera automática y sencilla.

¿Qué error común ayuda a evitar este ejemplo?
Ayuda a evitar conversiones manuales repetitivas y facilita el uso del objeto en operaciones donde se requiere un valor numérico.




