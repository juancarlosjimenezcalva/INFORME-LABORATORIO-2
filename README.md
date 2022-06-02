# INFORME LABORATORIO 2

## OBJETIVOS

### OBJETIVO GENERAL

Realizar el análisis de mallas aplicando la Ley de voltaje de Kirchhoff y la Ley de Ohm por medio de la elaboración de un circuito eléctrico para determinar los valores de las corrientes de malla.

### OBJETIVOS ESPECIFICOS

•	Elaborar un circuito eléctrico mixto
•	Realizar el análisis de mallas del circuito elaborado con el fin de encontrar las corrientes de malla.

## MARCO TEÓRICO

### ANÁLISIS DE MALLAS

El análisis de mallas es un método para resolver circuitos eléctricos planos y complejos, este método se basa en la ley de voltaje de Kirchhoff y la Ley de Ohm en donde contempla los nodos, ramas y mallas.
Es esencial conocer los conceptos de las leyes mencionadas y acerca de los nodos y ramas. Por tanto:

### LEY DE VOLTAJE DE KIRCHOFF

Según Floyd, la Ley de voltaje de Kirchhoff dicta que, la suma de todas las caídas de voltaje localizadas en una trayectoria cerrada es igual al voltaje de fuente total encontrado en dicha espira. (Floyd, 2007)

Su fórmula es:

![image](https://user-images.githubusercontent.com/105565683/171547368-18880470-5fed-42a8-b24d-df25044924a8.png)

Otra forma de expresar la fórmula es:

![image](https://user-images.githubusercontent.com/105565683/171547458-be306383-6b23-441f-afd7-f91ca91fd9a0.png)

### LEY DE OHM

La ley de Ohm dicta que la corriente es directamente proporcional al voltaje e inversamente proporcional a la resistencia, manteniendo una relación entre voltaje, corriente y resistencia.

Sus fórmulas son:

![image](https://user-images.githubusercontent.com/105565683/171547731-d068276f-ccde-4709-bcb4-3325d6cce7d4.png)

### Nodos

Un nodo es la unión de dos o más elementos que se conectan.

### Ramas

Las ramas son elementos dentro de un circuito eléctrico, por ejemplo, una rama podría ser un resistor.

### Mallas

Una malla es un circuito cerrado que no tiene otros circuitos cerrados dentro de ella.

Todos estos conceptos que se aplican en el análisis de mallas generan un sistema de ecuaciones de x variables dependiendo el circuito, en dónde al resolver el sistema de ecuaciones se obtendrá los valores de las corrientes solicitadas.

Entonces los pasos para el análisis de mallas son:

#### Paso 1

Asignar y dibujar las corrientes individuales en cada malla.

#### Paso 2

En cada malla se debe aplicar la Ley de voltaje de Kirchhoff y la Ley de Ohm, en donde partiendo del punto y siguiendo la corriente se irá obteniendo las ecuaciones de cada malla.

#### Paso 3

Se resuelve el sistema de ecuaciones en donde se encontrará los valores de cada corriente individual solicitada.

## EXPLICACIÓN DEL PROCEDIMIENTO

### ELABORACIÓN DEL CIRCUITO

#### MATERIALES

![image](https://user-images.githubusercontent.com/105565683/171676375-ef3bce34-fd90-497d-bbd5-a045e63daa5d.png)

![image](https://user-images.githubusercontent.com/105565683/171677248-f09de0e8-e95b-417c-a162-b76ff99316b0.png)

#### PROCESO

1.	Ubicamos las resistencias como se muestra en el esquema del circuito.

![image](https://user-images.githubusercontent.com/105565683/171678227-c96927b5-9a2c-4c01-8fd4-a8c2ed497e5a.png)

2.	Conectar las resistencias por medio de los cables de acuerdo con el esquema, que cumpla con el circuito mixto.

![image](https://user-images.githubusercontent.com/105565683/171679087-ea674298-4c8f-4e65-b149-a7e00bbd9b84.png)

3.	Conectamos las fuentes de voltaje C.D. (en caso de simulador), de acuerdo al esquema, en los polos positivo y negativo de las resistencias.

![image](https://user-images.githubusercontent.com/105565683/171679208-83f1e2f6-e551-4cd2-983d-f6d8f70a1449.png)

### CALCULO DE LOS VOLTAJES Y CORRIENTES

![image](https://user-images.githubusercontent.com/105565683/171548070-deec4c3b-bd98-4278-bc1f-3359c1bee2e8.png)

Basándonos en el esquema de circuitos, podemos ver que existen tres mallas y dos nodos, quedando de la siguiente forma:

![image](https://user-images.githubusercontent.com/105565683/171548108-83017050-d822-47e9-8cec-3a09cc065d7b.png)

### CALCULOS DE LOS NODOS

![image](https://user-images.githubusercontent.com/105565683/171548170-c849ca95-9d5a-49b3-be8e-476977020dec.png)

![image](https://user-images.githubusercontent.com/105565683/171548191-771ec00c-d0e3-4c8b-97a3-b08f5fe83709.png)

![image](https://user-images.githubusercontent.com/105565683/171548239-bde0322d-72a7-402d-b2dd-1765cae895fa.png)

### CALCULOS DE LAS MALLAS

![image](https://user-images.githubusercontent.com/105565683/171548329-94246771-45bb-4fcf-926d-23b44349c256.png)

![image](https://user-images.githubusercontent.com/105565683/171548344-66330c66-eb69-4dad-829c-c4cc054477ad.png)

![image](https://user-images.githubusercontent.com/105565683/171548373-1250ceb2-f45f-40c8-8e12-4fddca577420.png)

### SISTEMA DE ECUACIONES:

![image](https://user-images.githubusercontent.com/105565683/171548479-ced5255a-13fb-4918-b53d-58c57544dad8.png)

Resolviendo el sistema de ecuaciones usando una calculadora online:

![image](https://user-images.githubusercontent.com/105565683/171548507-538a188b-9870-429a-9153-ee378a5f99ff.png)

![image](https://user-images.githubusercontent.com/105565683/171548536-60aa56ed-016e-4aa4-b0be-5f050631149f.png)

Teniendo las resistencias y la corriente, calculamos el voltaje:

![image](https://user-images.githubusercontent.com/105565683/171683970-1760d77f-0f0a-4d28-a21d-18abedda3405.png)

## RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

### MEDICIONES DE VOLTAJE Y CORRIENTE

1. Medir el voltaje en cada elemento del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/171684059-e194f463-dd4d-4715-9da4-2b7f67f26849.png)

2. Medir la corriente en cada elemento del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/171686424-05fb1942-6586-416c-b3f5-f3bd3e098442.png)

### RESULTADOS

## VIDEO

## CONCLUSIONES

•	Se utilizó un análisis y compresión adecuado del esquema del circuito eléctrico para su elaboración, por medio de los materiales adecuados respetando su trayectoria y polaridad con el fin de que cumpliera con lo solicitado
•	Se determinó que gracias al análisis de mallas se puede obtener los valores de las corrientes de mallas por medio de un sistema de ecuaciones, siendo útil este método para un circuito eléctrico complejo.

## BIBLIOGRAFÍA

- Floyd, T. (2007). Principios de circuitos eléctricos. Octava edición. México: PEARSON EDUCACIÓN.
- McAllister, W. (2022). Khan Academy. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method
- Zapata, F. (1 de Noviembre de 2019). Lifeder. Obtenido de https://www.lifeder.com/analisis-de-mallas/





















