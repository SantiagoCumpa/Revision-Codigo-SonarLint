# Revision-Codigo-SonarLint

![image](https://github.com/user-attachments/assets/c00d8555-737f-434e-b207-c93c65fdb40e)

### Refactorización: 
![image](https://github.com/user-attachments/assets/1fe8d9d6-ea49-4dee-94f9-ebef031c78ed)
La advertencia indica que se puede utilizar el mensaje definiéndolo como una variable ya que se utiliza 3 veces

![image](https://github.com/user-attachments/assets/6861288c-0e24-45f0-810c-df15caf4081c)
Como vemos en el código esta cadena se utiliza para mostrar enviar un mensaje de error.

### Clean Code:
![image](https://github.com/user-attachments/assets/2199d7a7-e63b-4c8f-bc5d-811ecab46f24)
En este caso se está presentando una violación al utilizar una variable con el nombre de un Identificador del propio lenguaje

Este problema se puede solucionar utilizando otro nombre, incluso utilizando uno más acorde a la data que se está manejando. En este caso se está leyendo un CSV de estudiantes por lo que la variable podría cambiarse de nombre como se muestra en la imagen:
![image](https://github.com/user-attachments/assets/d7e900a3-20a5-42cc-8eca-fa145d94bde4)

### Code Smells
![image](https://github.com/user-attachments/assets/63175e89-1bf6-4de0-b522-03a081fbb02b)
En la advertencia nos indica que debemos declarar los campos para que puedan ser match con la expresión regular ^[a-z][a-zA-Z0-9]*$. Esto debido a una convención en el mundo de la programación.

![image](https://github.com/user-attachments/assets/dbd6102c-f217-49c5-8f18-01fc687d52d3)
La solución más simple es utilizar camelCase para la nomenclatura de las variables

![image](https://github.com/user-attachments/assets/e1dfc4ee-680f-4317-9eb7-ff17116f818d)

