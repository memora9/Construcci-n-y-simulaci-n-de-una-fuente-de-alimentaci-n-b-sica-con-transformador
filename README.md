Construcción y simulación de una fuente de alimentación básica con transformador

1. OBJETIVOS

Objetivo General:

•	Construcción y simulación de fuente de alimentación básica regulable de corriente continua, con la implementación de un trasformador.

Objetivos Específicos:

•	Diseñar una simulación del proyecto para compararlo con el resultado real obtenido.

•	Crear un circuito que logre transformar corriente alterna a corriente continua.

•Obtener una fuente de alimentacion basica mayor o igual a 15 voltios.

2. MATERIAL Y EQUIPO REQUERDIDO

![image](https://user-images.githubusercontent.com/93946423/157068539-380d11fa-6328-40dc-821a-8d64dfd7bfb5.png)



3. MARCO TEÓRICO


 ![image](https://user-images.githubusercontent.com/93946423/156900213-7ec7abbb-bd49-4d95-b599-d29138f3a89c.png)
 
4. EXPLICACIÓN DEL PROCEDIMIENTO
   
   4.1.Simulación del circuito
   
•	Para el desarrollo de esta práctica, se procedió primero a realizar una simulación del circuito armado en el simulador MULTISIM para comprobar el correcto funcionamiento del mismo.

•	El elemento más importante del proyecto es el trasformador el cual permite modificar la potencia eléctrica de corriente alterna a un determinado valor de tensión, en este caso va a disminuir siendo el trasformador de 220/120 Voltios de entrada a 9 voltios de salida, y como se observa en la Ilustracion 1 el voltaje en corriente alterna es de 11.68 V aproximadamente.
![image](https://user-images.githubusercontent.com/93946423/156907359-afa94dd9-3f4c-4c95-907e-e77b45ee07ad.png)

•	El siguiente elemento indispensable son los diodos rectificadores, específicamente un puente de diodos rectificadores cuya función es rectificar la corriente alterna (CA) en corriente continua (CC)

• En la Ilustracion 2 se muestra el voltaje rectificado en corriente continua, siendo este de 10.35 voltios aproximadamente.
![image](https://user-images.githubusercontent.com/93946423/156907705-ca8b7f9d-9491-4ca2-9e5a-72035ce1afa1.png)


•	El siguiente elemento es un capacitor específicamente un condensador electrolítico de 220 microfaradios a 16 voltios, que almacenara la energía en forma de carga eléctrica.

•	En la Ilustracion 3 se puede observar el voltaje medido una vez instalado el condensador lo cual arroja un valor de 15.81 voltios (CC) aproximadamente



![image](https://user-images.githubusercontent.com/93946423/156908035-ce1e0170-11db-497a-aebb-aaab59fec50f.png)

•	Finalmente agregamos un potenciómetro de 10k Ohms para regular el voltaje.

•	En la Ilustracion 4, podemos observar que al momento de mover la perilla del potenciómetro en su máximo valor el voltaje llega hasta 15.23 voltios (CC). aproximadamente. 
![image](https://user-images.githubusercontent.com/93946423/156908265-b55ca94c-e17e-41cc-b986-fbb96a1d835e.png)

4.2. Creación del circuito


•	Una vez realizado la simulación del circuito, se procede a armarlo, primero se realiza las conexiones del transformador con la corriente eléctrica alterna con la ayuda de los bornes y el cable de alimentación, posteriormente se conecta al protobard y se mide el voltaje (AC).
•	Como se observa en la Ilustracion 5 el voltaje (AC) es de 11.6 Voltios y en la simulación un voltaje de 11.68 siendo los dos valores cercanos.

![image](https://user-images.githubusercontent.com/93946423/157065724-6f6aba44-e9c7-49f8-b55b-1e753462875b.png)


•	Se procede a instalar el puente rectificador de diodos  (1n4007) en la protoboard , de tal manera que queden en serie de forma cuadrangular, se mide el voltaje (CC) rectificado.

•	En la Ilustracion 6 se observa  que el voltaje (CC) es de 10.22 Voltios mientras que en la simulación da como resultado 10.35 voltios.


![image](https://user-images.githubusercontent.com/93946423/157066212-371e7c46-ccac-45d0-9ce8-e2724a16afe9.png)


•	Se conecta el condensador electrolítico de 220 microfaradios a 16 voltios  que almacenara la energía en forma de carga eléctrica.

•	En la Ilustracion 7 se puede observar el voltaje medido una vez instalado el condensador, arroja un valor de 15.93 voltios (CC)  minetras que en la simulación da 15.81 Voltios aproximadamente.
![image](https://user-images.githubusercontent.com/93946423/157067699-60de12fe-16c1-43e7-a7ae-287ad61e0d69.png)

•	Finalmente se instala el potenciómetro de 10kOhms para regular el voltaje(CC)

• Como se observa en la Ilustracion 8 la perilla del potenciómetro está en su máximo valor, y el voltaje que arroja es de 15.22 voltios (CC), mientras que en el simulador fue 15.23 voltios (CC) siendo estos dos valores equivalentes.

![image](https://user-images.githubusercontent.com/93946423/157068043-7f8620b0-b47a-4bcc-a88e-39771b846f9c.png)

•	Tenemos una fuente de alimentación básica regulable que puede ir desde hasta 15.22 Voltios (CC) aproximadamente.

5. VIDEO

https://www.youtube.com/watch?v=OMANB2FrWHI



6. CONCLUSIONES

•	El transformador puede modificar la potencia eléctrica de corriente alterna a un determinado valor de tensión, y si a eso instalamos un puente de diodos rectificador este rectifica  la tensión en la corriente alterna dando como resultado un voltaje rectificado en corriente continua, si a dicha corriente la agregamos además un condensador electrolítico este almacenara la energía en forma de carga eléctrica y con la ayuda del potenciómetro podemos regular esta fuente de alimentación.

7.BIBLIOGRAFIA

Torre. F.(2019). Transformadores-Accionamientos electromecanicos.

https://rephip.unr.edu.ar/bitstream/handle/2133/16745/21503-19%20ACCIONAMIENTOS%20ELECTROMEC%C3%81NICOS%20Transformadores.pdf?sequence=3&isAllowed=y


ElectronicaLED.(26 de Diciembre del 2020).Fuente de alimentación de 9v con transformador. Fácil de hacer.
https://www.youtube.com/watch?v=9WrKlmaXLkQ













