# Semaforo-con-lenguaje-ensamblador
Semáforo con lenguaje ensamblador 
Cuenta del 25 al 0 Esta echo por pixeles dados por cordenadas

Primero creamos una grilla de 320 X 200 
![image](https://user-images.githubusercontent.com/66086428/179620254-8dc69442-4f15-4afb-9081-c8bca9a49d37.png)
![image](https://user-images.githubusercontent.com/66086428/179620286-1e64883f-339b-4c4a-b659-c80205820a80.png)
![image](https://user-images.githubusercontent.com/66086428/179620330-5a62e84c-9afc-4c07-9e4c-a4157f72bb9b.png)
![image](https://user-images.githubusercontent.com/66086428/179620380-62d093c5-a629-4355-ab3c-a8d0b3a98cff.png)
![image](https://user-images.githubusercontent.com/66086428/179620423-248f711f-fbcf-49eb-8ee9-b49526897977.png)



Declaramos las variables de texto y las librerías
![image](https://user-images.githubusercontent.com/66086428/179617040-1e86850e-147b-426e-bdc1-a5e95c9f64d6.png)

Iniciamos en el main a crear la pagina de presentación

INT 10H Esta interrupción controla los servicios de pantalla del PC.

INT 21H esta rutina finalizará el programa y devolverá el control al DOS

![image](https://user-images.githubusercontent.com/66086428/179617601-76a671b8-02a0-419a-ac55-e09ee1a1c114.png)

Iniciamos llamando y colocando el texto en los renglones que asignamos 

![image](https://user-images.githubusercontent.com/66086428/179617688-a1134950-9467-41c6-ae34-418e4bde50ab.png)
![image](https://user-images.githubusercontent.com/66086428/179619121-6ab8c138-5d4b-4352-b041-b9968c39de02.png)

Aquí vamos a crear un retardo en este caso por ser la portada le pusimos 5 segundos pero en los demás retardos solo tiene un segundo 

INT 15h es la forma abreviada de la interrupción 0x15. Esta interrupción controla los servicios extendidos del PC.

![image](https://user-images.githubusercontent.com/66086428/179619462-8b6e2e04-788a-4b72-9b9e-4303fbe20e39.png)

![image](https://user-images.githubusercontent.com/66086428/179620631-b9d2eb5c-b24f-4d69-9094-4b6d80b4cbaa.png)


Este sirve para crear las líneas en las que se pintan los pixeles 

Esta parte sirve para borrar todo lo que teníamos en la pantalla anterior 

Ponemos la pagina en modo video para empezar a poner las coordenadas en pixeles 

![image](https://user-images.githubusercontent.com/66086428/179620014-06208db4-7b79-4ada-ba43-184585dd8c37.png)

Este sirve para crear las líneas en las que se pintan los pixeles 

![image](https://user-images.githubusercontent.com/66086428/179620103-5de9b03e-6d3a-462f-9031-906aee738da3.png)

Por ultimo le ponemos esta pausa que al dar Enter para salir del programa 

![image](https://user-images.githubusercontent.com/66086428/179662626-97c5f4a1-729c-4bd7-b18f-da92a5b60831.png)












