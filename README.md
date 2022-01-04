# Informe Laboratorio 1 
1. OBJETIVOS 

   Objetivo general
   * Analizar y comprobar de forma teorica y experimental veracidad que tiene el Teorema de Superposición con respecto a los voltajes y corrientes de un circuito electrico, esto se llevara a cabo mediante el desarrollo del presente laboratorio que abordará temas conocidos en la asignatura, un circuito eléctrico mixto planteado por el tutor de la asignatura, cabe recalcar que el presente circuito ya ha sido resuelto mediante un simulador virtual, por lo que se espera los mismos resultados, se utilizara simuladores virtuales de circuitos eléctricos los cuales brindaran oportunidad de corroborar la exactitud de los datos teóricos obtenidos.

   Objetivos específicos
   
   
   * Identificar el circuito electrico equivalente de Thevenin dentro de un circuito electrico 
   
   * Conocer el comportamiento de la corriente dentro de diferentes nodos y como estas interactúan con los componentes que integran dichos nodos.

   * Identificar que tipo de nodos pueden presentarse dentro de un circuito electrico y determinar los nodos principales y nodo referencial.

   * Comprender el uso de la ley de Kirchhoff y como aplicarlo dentro de un circuito mixto utilizando simuladores virtuales que permitan su corroboración o en su defecto permita la localización de fallas.

   * Identificar las diferencias obtenidas por medio de la ejecución de un circuito mixto, dichas respuestas serán obtenidas de manera teórica, experimental y de simuladores.
   
2. MARCO TEORICO

   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/1efe998a577881a633282e56a10d05b0280b48ea/Laboratorio.jpeg)

3. EXPLICACION DEL PROCEDIMIENTO

   Encontrar los valores de VA y IX del siguiente circuito de la figura 1, aplicando el teorema de superposicion 
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ANALISIS.PNG)
   
   *Figura 1. Analisis del circuito por superposicion.*
   
   Colocamos los componentes del circuito mostrado anteriormente y lo representamos en el protoboard como muestra en la figura 2
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/51a4d0ed9b10a2303f81fb9be111a6e45ecaaf90/Circuito.PNG)
   
   *Figura 2. Circuito en protoboard.*

   Tomamos los datos que nos dan en el informe cuando V2=0, reemplazando el valor de 12v por 0v vemos con los multimetros los valores de voltaje en Va y los valores de la intensidad en Ix como se muestra en la figura 3. En este circuito tomamos mucha atencion al sentido de la corriente en este caso en sentido horario.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/51a4d0ed9b10a2303f81fb9be111a6e45ecaaf90/V2=0.PNG)
   
   *Figura 3. Valores de Va y Ix cuando V2=0.*
   
   Igualmente colocamos el valor del voltaje V1=0, mostrado en la figura 4, Teniendo en cuenta y ver nuevos datos Va y Ix del circuito en este caso el sentido de la corriente es antihorario que es un dato que nos servira mas adelante en el desarrollo del problema.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/51a4d0ed9b10a2303f81fb9be111a6e45ecaaf90/V1=0.PNG)
   
   *Figura 4. Valores de Va y Ix cuando V1=0*
   
   En la figura 5, colocamos los valores de los voltaje de 20v y 12v teniendo encuentra que las mediciones de Va y Ix es el total de todo el circuito ya que los otros valores son aplicando R=0 por lo tanto el voltaje se cortocircuita, y obtenemos los datos mostrados en el protoboard.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/51a4d0ed9b10a2303f81fb9be111a6e45ecaaf90/PROTOBOARD.PNG)
   
   *Figura 5. Valores totales de Va y Ix.*
   
    
4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

   Ahora realizamos el proceso el cual obtuvimos las respuestas para colocar los valores de la tabla 1 y tabla 2 de nuestro laboratorio para verificar tanto el valor teorico y calculado para poder encontrar el calculo de error.
   
   Primeramente en nuestro circuito de la figura 6, iremos en orden teniendo que V2=0, por lo que el voltaje de 12v se cortocircuita

   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ANALISIS.PNG)
   
   *Figura 6. Circuito.* 
   
   Como el componente de 12v se cortocircuita, tenemos el siguiente circuito esquematico el cual podemos observar que podemos realizar un analisis de malla o un proceso en el cual sea mas accesible a resolver, en nuestro caso utilizamos analisis de malla teniendo en cuenta 3 corrientes y que necesitamos encontrar Vx y Ix los cuales podemos sacar los valores mediante ley de ohm en el caso de Vx necesitamos el valor de la corriente I2 para aplicar la siguiente formula V = I.R y para encontrar Ix necesitamos los valores de I2 y I3 realizando un analisis adecuado. En la figura 7 dibujamos las corrientes y el sentido en el que van dichas corrientes por el circuito.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ANALSIS%20V2=0.PNG)
   
   *Figura 7. Circuito esquematico V2=0.*
   
   Ahora tomamos en cuenta en el analisis de malla las leyes kichhoff la sumatoria de los voltajes es igual 0 por lo que mediante ley de ohm V = I.R, por lo que reemplazamos lo valores en la formula y procedemos a encontrar las 3 ecuaciones de las 3 mallas mostrando en la figura 8 por lo que una vez ordenado y obtenido las ecuaciones formamos el sistema de ecuaciones como se muestra en la figura 9. Por lo que colocamos dichas ecuaciones en una calculadora tanto fisica o online el cual nos permita obtener los valores de las 3 corrientes en este caso los valores de las corrientes se encuentran en la figura 10. y luego realizamos un analisis con los valores encontrados.
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ANALSIS%20DE%20MALLA.PNG)
   
   *Figura 8. Analisis de malla.*
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ECUACIONES.PNG)
   
   *FIgura 9. Ecuaciones I1,I2 y I3*
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/CORRIENTES.PNG)
   
   *Figura 10. Valores de las corrientes*
   
   Nuestra incognita es Vx' y Ix' por lo que realizamos el siguiente analisis con los datos obtenidos y como sacamos los valores mostrados en la figura 11, el cual totamos en cuenta que la I2 pasa por la resistencia de 820 y aplicamos ley de ohm despejando V por lo cual Vx = 9.12(0.82) y encontramos el valor de Vx'= 7.47 mV
   
   Ahora para encontrar Ix teniendo en cuenta las corrientes que pasan por dicho tramo como en la figura 6. que en Ix pasa las corrientes I3 y I2 el cual podemos deducir lo siguiente Ix = (I2-I3) o Ix = (I3-I2) por lo cual sus valores son los mismo y nos darian un valorde Ix' = 0 mA
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/IXYVX.PNG)
   
   *Figura 11. Valores de Vx y Ix cuando V2=0*
   
   Ahora analizaremos cuando V1 = 0, por lo que en este circuito realizaremos otro procedimiento para encontrar las incognitas Vx'' y Ix'' que buscamos el voltaje de 20V se cortocircuita y luego redibujamos el circuito para ir analizando de mejor manera.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/ANALISIS.PNG)
   
   *Figura 12. Circuito*
   
   Observando nuevamente el circuito podemos deducir que para encontrar los valores Vx'' y Ix'' podemos ir reduciendo nuestro circuito encontrando sus resistencias equivalente y resistencia total. Por lo cual en la figura 13 hacemos el proceso para encontrar la resistencia equivalente 1. para luego analizar nuevamente nuestro circuito.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/Req1.PNG)
   
   *Figura 13. Resistencia equivalente 1.*
   
   Una vez redibujado nuestro circuito analisamos nuevamente teniendo encuentra ahora que podemos encontrar otra resistencia total mostrando en la figura 14, el cual dichas resistencias se encuentran en serie y podemos sumar como se ve el procedimiento.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/rt.PNG)
   
   *Figura 14. Resistencia total*
   
   Por ultimo nos quedan 2 resistencias las cuales estan en paralelo y podemos encontrar una resistencia equivalente total para encontrarlos valores correspondientes.
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/Req2.PNG)
   
   *Figura 15. Resistencia equivalente 2*
  
   En este caso encontramos la intensidad total de todo el circuito y tenemos un dato importante la corriente que fluye en dicho circuito es en sentido antihorario, por lo cual la intensidad total no es la que queriamos encontrar pero para comprobar si estamos haciendo un procedimiento adecuado y verificando con los valores del multimetro.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/intensidadTotal.PNG)
   
   *Figura 16. Intensidad total del circuito*
   
   Ahora para encontrar la Ix vamos hacer el siguiente analisis mostrado en la figura 17. Como podemos observar la resistencia de 0.47 y la resistencia total de 1.51 se encuentran en paralelo por cual sabemos por teoria que en paralelo el voltaje es el mismo en cada componente y la corriente es diferente por cual para encontrar Ix = V/R y para Vx'' encontramos la corriente "IA" por lo que dichas resistencias se encuentran en serie y la corriente es la misma en el cual realizamos el proceso de la figura1 18 para econtrar Vx y Ix cuando V1=0.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/IXV1=0.PNG)
   
   *Figura 17. Valor de Ix cuando V1=0*
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/fbdb92bdff0ccc5b1c9ee1cc7b6edffecac2376c/VX''0.PNG)
   
   *Figura 18. Valor de Vx cuando V1=0*
   
   Ahora una vez encontrado los valores cuando V1=0 y V2=0 realizamos el analisis para encontrar el Vx y Ix total de todo el circuito con las dos fuentes de voltaje de 12v y 20v, por lo tanto realizamos lo siguiente redibujamos el circuito esquematico pero ahora dibujaremos con las sdos fuentes de voltaje y agregandoles las corrientes que fluye en el circuito como se muestra en la figura 19. Para analizar lo siguiente Ix va ser la suma de Ix' + Ix'' por lo que la dirrecion de corriente tienen el mismo sentido por lo cual se suman y encontrarmos el valor total de Ix 
   
   Por ultimo para Vx teniendo en cuenta la corriente que pasa por Vx = Vx' - Vx'' , porque Vx'' se resta al analizar la corriente de la fuente de 12v va ser (- + ) y por otro lado Vx' de 20v va ser (+ - ) por lo que quedaria de la siguiente manera (+ -) (- +) el cual Vx'' se resta y encontramos Vx total de todo el circuito.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/7c8bb3d19e472bc47657a97232d20854d5f79439/TOTAL.PNG)
   
   *Figura 19. Valores de Vx y Ix con las dos fuentes de voltaje.*
   
   Una vez obtenido y verificando los datos tanto teorico y calculado por diferentes metodos de resolver colocamos los valores en las tabla 1 y tabla 2 las cuales nos poden colocar valor de Vx total y cuando V1 =0 y V2=0. Luego colocamos en la siguiente tabla los valores de Ix total y cuando V1=0 y V2=0.
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/f165597578833f825665beb697d3bee633a58e40/TABLA1.PNG)
   
   *Tabla 1. Valores de los voltajes*
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/f165597578833f825665beb697d3bee633a58e40/TABLA2.PNG)
   
   *tabla 2. Valores de las corrientes*
   
   Realizamos el calculo de error tanto del Vx y Ix mostrando en la figura 20. 
   
   ![](https://github.com/jlcastro5/Laboratorio1_2p/blob/7c8bb3d19e472bc47657a97232d20854d5f79439/ERROR.PNG)
   
   *Figura 20. Calculo de error*
   
   En el siguiente documento presentamos el procedimiento de todo nuestro circuito.
   
   https://github.com/jlcastro5/Laboratorio1_2p/blob/80f55367b04ee510d7779f4736bcddc5f53a30a6/SUPERPOSICION.pdf

  
5. VIDEO

   https://www.youtube.com/watch?v=F2n1sdGK9ag


6. CONCLUSIONES

      * El teorema de superposición han permitido obtener resultados muy exactos entre los datos obtenidos mediante el desarrollo teórico y la simulación, mismos que fueron recopilados desde tinkercad. Considerando que los elementos son ideales, podemos concluir que los datos obtenidos en este circuito eléctrico a partir del teorema de superposición son precisos por lo que el método es muy fiable para resolver este tipo de circuitos eléctricos.	


7. BIBLIOGRAFÍA 

   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
 
   Charles K & Sadiku M. (2006).Fundamentos de Circuitos eléctricos: Tercera Edición.
