
# Practica 9: ESTILOS DE PROGRAMACION

## Things

*El problema más grande se descompone en 'cosas' que tienen sentido para el dominio del problema.

*Cada 'cosa' es una cápsula de datos que expone los procedimientos al resto del mundo

Ejemplo, lo implementamos [aqui](https://github.com/GiedraAlexandra19/Final_Project_Software_Engineer/blob/main/Evento.py).


## Declared Intentions

*Existencia de un verificador de tipos en tiempo de ejecución

*Los procedimientos y funciones declaran qué tipos de argumentos esperan

Ejemplo, lo implementamos [aqui](https://github.com/GiedraAlexandra19/Final_Project_Software_Engineer/blob/main/Evento.py).
Cuando declaramos explicitamente un elemento y debe cumplir una condicion obligatriamente.

## Code Golf

*Pocas lineas de codigo como sea posible


# Practica 10: Codificacion legible

## 1.- Comentar y documentar
El codigo esa comentado en partes importantes y donde posiblemente no se entienda a simple vista.

![image](https://user-images.githubusercontent.com/83047121/185673813-dfd39d74-8a64-4bd1-b12b-9260d9fdf707.png)

## 2.- Indentacion Consistente

![image](https://user-images.githubusercontent.com/83047121/185671822-d0d27953-9030-40b1-98c7-cd075fcf5bb5.png)

## 3.- Agrupacion de Codigo

![image](https://user-images.githubusercontent.com/83047121/185673511-0676ffdb-27d4-4dbb-8666-d8987ebd0516.png)

## 4.- Organizacion en Archivos y Carpetas
Los archivos estan organizados en carpetas.

![image](https://user-images.githubusercontent.com/83047121/185671865-d0ab1788-ef2c-406d-8a49-fb02f95eb1eb.png)

## 5.- Sistema Consistente de Nombramiento
Se utiliza un sistema consistente de nombramiento para las variables, en la que varias variables temporales se vuelven a usar para representar una misma logica. El codigo usado con python se viene desarrollando con snake_casing, este estilo nombra a las variables siempre en minuscula y si se quieren representar espacios o separacion de palabras se utiliza un guion bajo _ .

![image](https://user-images.githubusercontent.com/83047121/185671621-16b5c762-c2ba-4e1b-a346-6b98c18a2efd.png)

# Practica 11: Principios SOLID

## Single Responsability Principle
"Una clase deberia tener una, y solo una razon para cambiar".
Cada archivo y clase presenta solo una funcionalidad. Por ejemplo en modelos tenemos un archivo para representar cada entidad.

![image](https://user-images.githubusercontent.com/83047121/185970492-262cb494-7075-47a8-8041-d63bbeae8ea8.png)

## Open/Closed
"Deberias ser capaz de extender el comportamiento de una clase, sin modificarla"
Podemos añadir funcionalidades sin modificar la base de datos.

![image](https://user-images.githubusercontent.com/83047121/185971562-83809607-befc-4509-88c6-e6bec0b8a202.png)
Imagen 1: Clase evento inicialmente

![image](https://user-images.githubusercontent.com/83047121/185971671-0db1bb24-209f-4cfb-82a9-6c4ce79a24a4.png)
Imagen 2: Clase evento añadiendo funcionalidades

## Interface segregation
"Haz interfaces que sean especificas para un tipo de cliente"
Es preferible contar con muchas interfaces que definan pocos metodos que tener una interfaz forzada a implementar muchos metodos a los que no dara uso.

![image](https://user-images.githubusercontent.com/83047121/185973059-285f9fab-370c-461b-9285-8b9c88e1d3c8.png)
