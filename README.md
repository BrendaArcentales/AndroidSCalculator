# androidscalculator
Esta calculadora es implementada con diferentes widgets como botones, TextView, entre otros, con el fin de representar la interfaz de una calculadora cientifica, como se muestra en la siguiente imagen:

![abrirC](https://user-images.githubusercontent.com/66123679/130313317-59cdf242-8f14-4233-baed-a8c18b6b2331.PNG)

Donde al presionar cada boton, este va a ir esribiendo en la pantalla el valor numerico y la operación que le corresponda como en el siguiente ejemplo:

![escribirC](https://user-images.githubusercontent.com/66123679/130313345-e7a2c903-0bd2-43f4-a77c-1cf1be4a05e9.PNG)

Y el resultado aparece de la sigueinte manera, guardando la operación que se realizo y mostrandola encima de este, asi:

![resultado](https://user-images.githubusercontent.com/66123679/130313386-046a9cb3-6bfd-46f4-b70a-2eeaf942f2de.PNG)

Las funcionalidades de esta calculadora son: 
1. Implementación de aplicaciónes basicas:

![comp](https://user-images.githubusercontent.com/66123679/130313324-4e8a9704-e0bd-43b2-8a85-973c2f31f990.PNG)

2. Implementación de operaciones trigonometricas:
Función seno

![OperSin](https://user-images.githubusercontent.com/66123679/130313354-1d00add0-060e-4083-a9e4-ff82bbd5ed2a.PNG)

Función coseno

![opercos](https://user-images.githubusercontent.com/66123679/130313359-c88867c2-3956-44e7-9719-56d48f61e5b8.PNG)

Función tangente

![tan](https://user-images.githubusercontent.com/66123679/130313365-d4964763-099f-471a-b6ea-6a93b43f9c3d.PNG)

3. Implementación de operaciones logaritmicas:
Función logaritmo base 10

![log](https://user-images.githubusercontent.com/66123679/130313397-45c91625-0797-4223-9513-f56c77d066ea.PNG)

De forma general el pograma consta de diversas funciones donde se detalla la operación correspondiente resaltando de entre esas las siguientes: 
En primera instancia se definieron incialmente variables de los botones con el id que se le asigno a cada uno, de igual forma con los texview una constante con el valor de pi.
A continuación se asignaron a cada variable el valor que le correspondia en el botón asignado, como se muestra a continuación:
![image](https://user-images.githubusercontent.com/66123679/130313701-8c10c785-380c-4a94-b3bb-41035f0ce486.png)

De ahi se prosigio a definir cada operacion en la asignación correspondiente por ejemplo para las funciones trigonometricas se definio que al presionar igual los valores entraban en un condicional donde dependiendo de la operación se asignaba la operación haciendo uso de las librerias matematicas "Math" como se muestra a continuación:

![image](https://user-images.githubusercontent.com/66123679/130313727-13a4cb82-4a28-4252-b567-d01f39282c06.png)

Asi mismo se definio una función externa para el calculo del factor de un número dando como resultado la siguiente función:
![image](https://user-images.githubusercontent.com/66123679/130313755-269547d8-0205-47c6-b247-8fd1fd4ad59b.png)

De igual forma para las operaciones de borrado se definieron como se debia limpiar la pantalla, dando como resultado:
![image](https://user-images.githubusercontent.com/66123679/130313710-852fd5d4-66bc-40ca-a7a6-6c9e60bae19d.png)
