# InformeLaboratorio4
**1. TEMA:**

Teorema de Superposición

**2. OBJETIVO**

**2.1. Objetivo General**

Comprobar experimentalmente el Teorema de Superposición

**2.2. Objetivos Específicos**

- Definir el teorema de Superposición.
- Entender sus pasos y la aplicación de estos.
- Realizar el circuito propuesto de manera correcta y funcional.
- Tomar las medidas de volatjes y corrientes en el circuito para comparar el teorema.
- Realizar el teorema de Superposición manualmente y comparar con las medidas obtenidas en Tinkercad.
- Observar los resultados y concluir si el teorema es funcional. 

**3. MARCO TEÓRICO**

**3.1. Teorema de Superposición**

El Teorema de Superposición establece que: El voltaje o corriente a través de cualquier elemento del circuito puede obtenerse sumando algebraicamente todos los voltajes o corrientes individuales generados por cada fuente actuando por sí sola, con todas las demás fuentes igualadas a cero.

[![Teorema-de-Superposici-n.png](https://i.postimg.cc/mgG5f5hY/Teorema-de-Superposici-n.png)](https://postimg.cc/PP241KWJ)

**4. EXPLICACIÓN DEL PROCEDIMIENTO**

**4.1.** Se realizará el siguiente circuito mixto en Tinkercad. Se utilizarán las siguientes herramientas:

- Una Placa de pruebas pequeña.
- Cuatro Resistencias.
- Dos Suminitradores de Energía.
- Un multímetro.

[![1.png](https://i.postimg.cc/HnqPLSzC/1.png)](https://postimg.cc/1VKKCrbW)

**4.2.** Conectaremos los dos suministradores de energía en la placa pequeña de tal forma que los dos negativos (tierra) se unan, esto debido a que seguiemos el mismo modelo dado en el diagrama.

[![2.png](https://i.postimg.cc/76gNVxMj/2.png)](https://postimg.cc/k6g8MPHy)

**4.3.** Ahora posicionaremos los resistores y los conectaremos con un cable verde, siguiendo el modelo. Al final conectaremos los resistores 2 y 4 al cable negro (negativo) para poder cerrar el circuito con los dos suministradores de energía.

[![4.png](https://i.postimg.cc/P5gZFgxH/4.png)](https://postimg.cc/fVvJVgmq)

[![3.png](https://i.postimg.cc/8zJM4pTw/3.png)](https://postimg.cc/VJwJLcrb)

**5. RESULTADOS OBTENIDOS**

**5.1**. Primero mediremos el voltaje Total de Va que pasa por la segunda resistencia. Lo haremos a través de Tinkercad.

[![5.png](https://i.postimg.cc/sD4QjMwM/5.png)](https://postimg.cc/CzdLJxy0)

El voltaje total medido es de 952mV

**5.2**. Ahora mediremos el Va cuando V1 = 0.

[![6.png](https://i.postimg.cc/HkvJffkn/6.png)](https://postimg.cc/tsPC6vPG)

El voltaje de Va es 7.48V cuando V1 = 0.

**5.3**. Ahora mediremos el Va cuando V2 = 0.

[![7.png](https://i.postimg.cc/m2M8ZyHT/7.png)](https://postimg.cc/SJSWD8dP)

El voltaje de Va es -6.53V cuando V2 = 0.

**5.4**. Para saber si las medidas hechas de Va cuando V1 y V2 son 0, debemos sumar sus voltajes y esta tendria que ser igual al voltaje total medido.

[![8.png](https://i.postimg.cc/fyLzMbL9/8.png)](https://postimg.cc/R6k5R4wS)

**5.5**. Ahora mediremos la Corriente total de Ix en Tinkercad.

[![9.png](https://i.postimg.cc/Jzk17nNf/9.png)](https://postimg.cc/jDRVZRkc)

La corriente total de Ix es: 25.5 mA.

**5.6**. Luego mediremos las corrientes de Ix cuando V1 = 0.

[![10.png](https://i.postimg.cc/pX16GJFv/10.png)](https://postimg.cc/KRBf4Lfp)

La corriente Ix = 0 mA, cuando V1 = 0.

**5.7**. Luego mediremos las corrientes de Ix cuando V2 = 0.

[![11.png](https://i.postimg.cc/7ZhybLgH/11.png)](https://postimg.cc/Tpzs4f7F)

La corriente Ix = 25.5 mA, cuando V2 = 0.

**5.8**. Para saber si las medidas hechas de Ix cuando V1 y V2 son 0, debemos sumar sus corrientes y esta tendria que ser igual a la corriente total medida.

[![12.png](https://i.postimg.cc/rpYGcfqy/12.png)](https://postimg.cc/zLKHFSL4)

**5.9**. Ahora mediremos la Va y Ix manualmente.

**5.10.** Cómo ya poseemos todos los datos necesarios; rellenamos la tabla con los voltajes.

| Voltaje   | Total (Va)  | Voltaje (Va)   |Cuando V1 = 0  |Voltaje (Va) |Cuando V2 = 0 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Calculado | Medido  | Calculado  | Medido  | Calculado  | Medido  |
| 925 mV  | 0.92 V  | 7.48 V  | 7.5 V  |-6.53 V  |-7 V  |

**5.11.** También rellenaremos los datos de corriente.

| Corriente   | Total (Ix)  | Corriente (Ix)   |Cuando V1 = 0  |Corriente (Ix) |Cuando V2 = 0 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Calculado | Medido  | Calculado  | Medido  | Calculado  | Medido  |
| 25.5 mA  | 25 mA  | 0 A  | 0 A  |25.5 mA  |25 mA  |

**6. VÍDEO**

https://www.youtube.com/watch?v=y2Q5UTEWODk

**7. CONCLUSIONES**

Con este laboratorio pudimos poner a prueba el teorema de Superposiciones. Vimos su definición y anotamos los pasos a seguir para tener una mejor idea de su uso. Al igual que otros informes, también notamos que muchas leyes (como las de Ohm y Kirchhoff) se aplican en este nuevo teorema; de igual manera pudimos notar algunos conceptos antiguos como mallas o nodos. 

Logramos recear el circuito propuesto y obtener los datos deseado. Mediamos sus voltajes y corrientes tanto con el circuito entero, como aplicando superposiciones. De igual manera hicimos los calculos manuales para lograr conseguir los datos medidos. Y gracias a esto pudimos concluir que el teorema de Superposición es válido y funciona para lograr encontrar los voltajes en un punto y las corrientes, cuando dicho circuito posee más de un suministrador de energía.

Con este laboratorio pudimos ver este teorema y aplicarlo de manera eficiente.

**8. BIBLIOGRAFÍA**

- Circuit. (2010). Multisim. Obtenido de https://www.multisim.com/create/
- Ministerio de Educaión . (2011). inet. Obtenido de http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf
- Eris, N. (20 de Noviembre de 2017). Sesoricx. Obtenido de https://sensoricx.com/circuitos-electricos-dc/analisis-de-circuitos-empleando-nodos/
- Hain, J. (14 de Septiembre de 2019). Khan Academy. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-node-voltage-method
