# Laboratorio-Nro.-5

INTEGRANTES 

HENRY MACIÍAS
SAID CARRIÓN
JOSÉ PILAGUANO 

Objetivos

1.- Objetivo General

Estudiar el teorema de Thévenin en circuitos mixtos apoyandose de los simuladores para comprobar que se cumple el teorema con los resultados analíticos mediante el presente laboratorio para relacionar y comprender de mejor manera la relación con los conocimientos aprendidos en un circuito eléctrico entendiendo de mejor manera dichos conceptos y aplicarlos en cualquier campo que se requieran.

OBJETIVOS ESPECÍFICOS

• Conocer el teorema de Thévenin para encontrar valores desconocidos, que nos pidan en un circuito eléctrico,

Identificar la resistencia de Thévenin con la ayuda del amperímetro y voltímetro en los simuladores

• Reconocer los diferentes instrumentos de medida que tenemos en el laboratorio asi como el funcionamiento del mismo, analizar el circuito y su comportamiento al

momento de hacer hacer cero las fuentes de voltaje y calcular la resistencia equivalente.

• Resolver el laboratorio para afianzar el conocimiento y utilización del teorema de Thévenin en los circuitos, para poder llevar a cabo lo teórico a lo práctico,

Comparar los datos en el simulador con resultados calculados y realizar el cálculo del error.

2.- Marco Teórico

![image](https://user-images.githubusercontent.com/116677175/211617175-8367d2cc-3a81-4f30-a29c-066a83d773b4.png)

![image](https://user-images.githubusercontent.com/116677175/211617241-51248312-2eed-478b-b3d0-5e3fcfd93ce9.png)

![image](https://user-images.githubusercontent.com/116677175/211617326-51cc2877-1e7b-4b32-94ea-83dc74440add.png)

3.- Diagramas

circuito general

![image](https://user-images.githubusercontent.com/116677175/211617440-64cf2cb9-9df5-4dce-9423-fb9960d5523e.png)

Voltaje y corriente en R5

![image](https://user-images.githubusercontent.com/116677175/211617533-437596c5-cdb4-4653-b7c1-c68f71075025.png)

Voltaje cuando la R5 se desconecta

![image](https://user-images.githubusercontent.com/116677175/211617632-66418033-0b07-48aa-9004-abfa471a7b5d.png)

R5 desconectada y dos fuentes de voltaje en 0, para medir la resistencia

![image](https://user-images.githubusercontent.com/116677175/211617723-accc6e68-9b34-4e07-a7df-e6de18dd73a5.png)

Implementación del circuito Thevenin

![image](https://user-images.githubusercontent.com/116677175/211617842-6b9c1110-f85d-43af-881b-e56dc13605b1.png)

4.- Lista de componentes

![image](https://user-images.githubusercontent.com/116677175/211617955-45b93fb0-ad63-42b7-8a46-fdcdf25f9156.png)

5.- Explicacion

5.1.- Procedimiento

![image](https://user-images.githubusercontent.com/116677175/211618050-11c1c915-8279-43db-ae67-ea04f1a361c4.png)

![image](https://user-images.githubusercontent.com/116677175/211618156-7e0b6cf5-6224-4553-b040-b97737d23a90.png)

![image](https://user-images.githubusercontent.com/116677175/211618206-9a9a281b-b471-4a01-b531-a5e86e95598b.png)

![image](https://user-images.githubusercontent.com/116677175/211618293-580365d8-8976-45eb-a199-4d6a17d1c52a.png)

Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.

Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 5 resistencias, multimetros digitales y dos fuentes de voltaje.

En la primera fuente de voltaje, se la configura con 12 V, mientras que la segunda fuente de voltaje tendrá un valor de 2 V.

Se procede a configurar cada resistencia con el valor ya establecido en el circuito.

De la fuente positiva de 12 V se conecta hacia un extremo de la resistencia de 560 ohmios.

Del extremo de la resistencia 1, se conecta hacia la resistencia de 4.7 kohms, del otro extremo de esta resistencia se la conecta hacia el negativo de la fuente

Se conecta la fuente de voltaje de 2 V, el lado negativo se conecta hacia el nodo de R1 y R2, el lado positivo irá conectado hacia un extremo de la resistencia de 330 ohmios.

Del otro extremo de la resistencia de 330 ohmios, se conectará hacia R2.

La resistencia de 100 ohms, va conectada en el nodo formado por la fuente de voltaje de 2 voltios y por la R3.

Finalmente la resistencia de 1 kohm, se conecta hacia la resistencia 4 y el otro extremo hacia la R3.

Semi el voltaje y la corriente en R5

Se desconecta el resistor 5 y con el voltímetro en paralelo se mide el voltaje, que es 5.06 V.

Las 2 fuentes de voltaje se hacen 0 y con el multímetro en paralelo se mide la resistencia que nos da un valor de 299 ohmios.

Con esos valores, se procede a hacer el circuito equivalente de Thevenin, con la resistencia de 299 ohms, el voltaje de 5 V y la resistencia de 1 kohm.

5.2.- Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla

Para medir el voltaje se tiene que conectar el voltímetro en paralelo a la resistencia y para medir la corriente se conecta en paralelo, poniendo la primera terminal al extremo de la R4 y la otra terminal al inicio de la R5.

5.3.- Desconecte la resistencia R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla

Para medir el voltaje se coloca en la R4 la terminal del multímetro y la otra terminal hacia la R3.

5.4.- Anule el efecto de las fuentes de alimentación. Desconectó R5 y desde el circuito abierto resultó mida la resistencia equivalente. Anote el valor medido en la tabla

Con la misma conexión que hicimos anteriormente se coloca el multímetro en Resistencia, y las fuentes de voltaje se las deja con un valor de 0.

5.5.- Implemente el circuito equivalente de Thévenin, agregue la resistencia R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla

Con el resultado que nos dio en el punto 5.4. se deja esa resistencia, con una sola fuente de voltaje con el valor que mide en el punto 5.3. a continuación, se conecta en serie con la R5.

Tabla de valores del Circuito Equivalente de Thévenin.

![image](https://user-images.githubusercontent.com/116677175/211618382-bce7cbdc-62c0-4073-8ecb-dfa3250e1a6f.png)

Tabla de comprobación del Teorema de Thévenin

![image](https://user-images.githubusercontent.com/116677175/211618466-c08c47be-5949-439b-995f-d935cbc68422.png)

Conclusiones
Sin la ayuda de los instrumentos de medición como el amperímetro o voltímetro nuestros datos no serían concretos, ya que estos nos ayudan en los cálculos de varios métodos como por ejemplo el cálculo con la ayuda de mallas.

El comportamiento del circuito al hacer cero las dos fuentes, dio la disponibilidad de un análisis mucho mas breve ya que se disminuían los elementos en el mismo.

En conclusión, al usar el método de Thevenin y el método de resolución por mallas, se observó que arrojaba un mínimo error ya que los valores calculados eran casi exactos.

Bibliografia
Floyd, TL (2007). Principios de circuitos eléctricos (Octava ed.)
