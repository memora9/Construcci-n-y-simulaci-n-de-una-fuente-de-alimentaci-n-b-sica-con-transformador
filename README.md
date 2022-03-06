Construcción y simulación de una fuente de alimentación básica con transformador
Trabajo extra-Construcción de un timbre eléctrico con Electroimán
1. OBJETIVOS

Objetivo General:

•	Construcción y simulación de fuente de alimentación básica regulable de hasta 15 voltios de corriente continua, con la implementación de un trasformador.

Objetivos Específicos:

•	Diseñar una simulación del proyecto para compararlo con el resultado real obtenido.

•	Crear un circuito que logre transformar corriente alterna a corriente continua.

2. MATERIAL Y EQUIPO REQUERDIDO

   ![2 Material y equipo requerido](https://user-images.githubusercontent.com/93946423/156901387-755395fa-05d5-4a6c-a250-17dd4773c651.png)



3. MARCO TEÓRICO
 ![image](https://user-images.githubusercontent.com/93946423/156900213-7ec7abbb-bd49-4d95-b599-d29138f3a89c.png)
 
4. EXPLICACIÓN DEL PROCEDIMIENTO
   
   4.1.Simulación del circuito
•	Para el desarrollo de esta práctica, se procedió primero a realizar una simulación del circuito armado en el simulador MULTISIM para comprobar el correcto funcionamiento del mismo.

•	El elemento más importante del proyecto es el trasformador el cual permite modificar la potencia eléctrica de corriente alterna a un determinado valor de tensión, en este caso va a disminuir siendo el trasformador de 220/120 Voltios de entrada a 9 voltios de salida, y como se observa en la figura 1 el voltaje en corriente alterna es de 11.68 V aproximadamente.
![image](https://user-images.githubusercontent.com/93946423/156907359-afa94dd9-3f4c-4c95-907e-e77b45ee07ad.png)

•	El siguiente elemento indispensable son los diodos rectificadores, específicamente un puente de diodos rectificadores cuya función es rectificar la corriente alterna (CA) en corriente continua (CC), en la figura 3 se muestra el voltaje rectificado en corriente continua, siendo este de 10.35 voltios aproximadamente.
![image](https://user-images.githubusercontent.com/93946423/156907705-ca8b7f9d-9491-4ca2-9e5a-72035ce1afa1.png)


•	El siguiente elemento es un capacitor específicamente un condensador electrolítico de 220 microfaradios a 16 voltios, que almacenara la energía en forma de carga eléctrica.
•	En la figura 4 se puede observar el voltaje medido una vez instalado el condensador, arrojando un valor de 15.81 voltios (CC) aproximadamente

![image](https://user-images.githubusercontent.com/93946423/156908035-ce1e0170-11db-497a-aebb-aaab59fec50f.png)

•	Finalmente agregamos un potenciómetro de 10k Ohms para regular el voltaje.
•	En la figura 5, podemos observar que al momento de mover la perilla del potenciómetro en su máximo valor el voltaje llega hasta 15.23 voltios (CC). aproximadamente. 
![image](https://user-images.githubusercontent.com/93946423/156908265-b55ca94c-e17e-41cc-b986-fbb96a1d835e.png)












