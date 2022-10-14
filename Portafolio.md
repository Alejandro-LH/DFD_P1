# Presentacion 
## Problemas resueltos en clase con DFD
### Ejercicio 1. Imprimir el nombre de una persona.
#### 1.1 Analisis. 
Necesito imprimir mi nombre.
#### 1.2 DFD
![Captura de Pantalla 1](https://user-images.githubusercontent.com/113395327/190947211-1b3346fe-34f8-475e-998d-6a38966d95c8.png)
#### 1.3 Prueba de escritorio 
|Msg|salida |
|---|-------|
|nom|"Jahir"|
#### 1.4 Entradas.
Ninguna
#### 1.5 Salidas.
Jahir

### Ejercicio 2. Escribe el algoritmo que escriba el dia de hoy.
#### 1.1 Analisis
Se devera imprimir el dia de hoy.
#### 1.2 DFD
![Captura de pantalla 2](https://user-images.githubusercontent.com/113395327/190952900-cda167e4-43a5-4e51-a72f-40b6c68fc985.png)
#### 1.3 Prueba de escritorio 
|msg               |salida  |
|------------------|--------|
|"Dia de la semana"|Lunes   |
#### 1.4 Entradas 
Ninguna
#### 1.5 Salidas
Lunes

### Ejercico 3. Escribe un algoritmo que diga hola (nombre).
#### 1.1 Analisis
Insertar un simbolo de proceso para asignar la variable de nombre e imprimir "Hola" nombre.
#### 1.2 DFD
![Captura de pantalla 3](https://user-images.githubusercontent.com/113395327/190952978-e7b6cc0b-d8a8-4c07-8ff9-1868f114ae59.png)
#### 1.3 Prueba de escritorio
|msg    |salida  |
|-------|--------|
|nom=nom|hola nom|

#### 1.4 Entradas
Ninguna
#### 1.5 Salidas 
Hola nom
### Ejercicio 4. Escribe un algoritmo que diga buena dia(nombre).
#### 1.1 Analisis
Se necesita preguntar el nombre, despues imprimir "Buen dia" nombre.
#### 1.2 DFD
![Captura de pantalla 4](https://user-images.githubusercontent.com/113395327/190953007-61c92f8b-373d-4d58-ac2d-33d0e22966c3.png)
#### 1.3 Pruebas de escritorio
|msg               |entrada |salida          |
|------------------|--------|----------------|
|"¿como te llamas?"|Jahir   |"buen dia" Jahir|
#### 1.4 Entradas
Jahir
#### 1.5 Salidas
"Buen dia", Jahir

### Ejercio 5. Escriba un diagrama de flujo que calcule el cuadrado del dos.
#### 1.1 Analisis
Calcular el cuadrado de 2.
#### 1.2 DFD
![Captura de pantalla 5](https://user-images.githubusercontent.com/113395327/190953023-3e2b6ae7-e864-4469-9485-4ca20e506ec1.png)
#### 1.3 Prueba de escritorio
|msg                   |salida|
|----------------------|------|
|sacar el cuadrado de 2|2 * 2 |
#### 1.4 Entradas
Ninguna
#### 1.5 Salidas
2 * 2

### Ejercico 6. Escriba un DFD que calcule el cuadrado de n para n=5.
#### 1.1 Analisis
Se necesita Insertar un simbolo de proceso para asignar el valor de la variable n e imprimir su cuadrado.
#### 1.2 DFD
![Captura de pantalla 6](https://user-images.githubusercontent.com/113395327/190953037-41937145-00ac-4a69-b13a-a83efafed0bf.png)
#### 1.3 Prueba de escritorio
|msg           |salida                  |
|--------------|------------------------|
|n=5           |5 * 5                   |
#### 1.4 Entradas
Ninguna
#### 1.5 Salidas
5 * 5

### Ejercicio 7. Pregunta al usuasio el valor n y obtener el cuadrado.
#### 1.1 Analisis
Insertar el valor de n, despues sacar el cuadrado de n.
#### 1.2 DFD
![Captura de pantalla 7](https://user-images.githubusercontent.com/113395327/190953049-bb8e7144-f513-4313-8bd1-d62d0c01ecc4.png)
#### 1.3 Prueba de escritorio
|msg     |entrada   |salida  |
|--------|----------|--------|
|"dame n"|5         | 5 * 5  |
#### 1.4 Entradas 
5
#### 1.5 Salidas
5 * 5

### Ejercico 8. Obtenga el cuadrado de la suma de 2 numeros enteros.
#### 1.1 Analisis
Se debe obtener el cuadrado de la suma de dos numero.
#### 1.2 DFD
![Captura de pantalla 8](https://user-images.githubusercontent.com/113395327/190953065-a15b9ac4-48b6-463f-b5e5-bde77b4c4cdb.png)
#### 1.3 Prueba de escritorio
|msg                     |entrada  |salida       |
|------------------------|---------|-------------|
|"dame 2 numeros enteros"|num1,num2|(num1+num2)^2|
|num1,num2               |2,4      |(2+4)^2      |
#### 1.4 Entradas
num1,num2
#### 1.5 Salidas
(num1+num2)^2

### Ejercicio 9. Pregunte el año de nacimineto y saque la edad.
#### 1.1 Analisis
Se debera instertar el año de nacimineto y despues se tiene que restar por 2022 que es el año actual, y sacar su edad.
#### 1.2 DFD
![image](https://user-images.githubusercontent.com/113395327/190953625-37971679-ab3e-407a-84d9-38d40d1652cf.png)
#### 1.3 Prueba de escritorio
|msg                              |entrada|salida    |
|---------------------------------|-------|----------|
|"Digita tu año año de nacimiento"|a_nac  |2022-a_nac|
|2004                             |2004   |2022-2004 |
#### 1.4 Entradas
a_nac
#### 1.5 Salidas
2022-a_nac

### Ejercio 10. Pregunte el año de nacimineto de una persona y calcule su edad.
#### 1.1 Analisis 
Preguntar el año de nacimiento, despues el año actual, y restar el año actual con el año de nacimiento. 
#### 1.2 DFD
![Captura de pantalla 10](https://user-images.githubusercontent.com/113395327/190953078-09828078-9382-403b-87e3-ff71f16e477f.png)
#### 1.3 Prueba de escritorio
|ana |aac |aac-ana  |
|----|----|---------|
|2004|2022|2022-2004|
#### 1.4 Entradas
ana,aac
#### 1.5 Salidas
aac-ana

### Ejercio 11. Pregunte el año de nacimiento de una persona y el año actual y calcule su edad.
#### 1.1 Analisis
Preguntar el año de nacimiento de una persona, luego preguntar el año actual, y despues calcular su edad.
#### 1.2 DFD
![Captura de pantalla 11](https://user-images.githubusercontent.com/113395327/190953096-da109e2c-93b4-4e61-8b00-9687f63cc197.png)
#### 1.3 Prueba de escritorio
|a_nac|a_act|a_act>a_nac|a_act-a_nac|
|-----|-----|-----------|-----------|
|2004 |2022 |2022>2004  |2022-2004  |
#### 1.4 Entradas
a_nac,a_act
#### 1.5 Salidas
a_act-a_nac, el año de nacimineto no debe ser maayor al actual.

### Ejercicio 12. Pregunte el año de nacimiento y el actual, calcule el año de nacimeinto de la persona.
#### 1.1 Analisis
Preguntar el año de nacimineto, despues el actual, luego verificar si el año actual es mayor al de nacimiento y calcule su edad.
#### 1.2 DFD
![Captura de pantalla 12](https://user-images.githubusercontent.com/113395327/190953111-4072c6f9-ec22-4922-ab1c-7a17651b16f3.png)
#### 1.3 Prueba de escritorio
|a_nac|a_nac>0|a_act|a_act>0|a_act>a_nac|a_act-a_nac|
|-----|-------|-----|-------|-----------|-----------|
|2004 |2004>0 |2022 |2022>0 |2022>2004  |2022-2004  |
#### 1.4 Entradas
a_nac,a_act
#### 1.5 Salidas
a_act-a_nac


### Ejercicio 13. Escribe un DFD que ceunte del 1 al 10 y lo escriba.
#### 1.1 Analisis
Agregar un contador que cuente del 1 al 10 y lo escriba
Escribe un diagrama 
#### 1.2 DFD
![Captura de pantalla 13](https://user-images.githubusercontent.com/113395327/190953123-5d31472d-7af6-4d8a-8a2f-66fcd812790e.png)
#### 1.3 Prueba de escritorio
|"cont"|cont<=10|cont++|
|------|--------|------|
|1     |1<=10   |1+1   |
|2     |2<=10   |2+1   |
|3     |3>=10   |3+1   |
|4     |4<=10   |4+1   |
|5     |5<=10   |5+1   |
|6     |6<=10   |6+1   |
|7     |7<=10   |7+1   |
|8     |8<=10   |8+1   |
|9     |9<=10   |9+1   |
|10    |10<=10  |      |
#### 1.4 Entradas
Ninguna
#### 1.5 Salidas
"cont"

### Ejercicio 14. El resultado de la suma de los numeros naturales del 1 al 10.
#### 1.1 Analisis
calular el resultado de la suma de los numero naturales del 1 al 10.
#### 1.2 DFD
![Captura de pantalla 14](https://user-images.githubusercontent.com/113395327/190953146-193eeca9-1fcd-4967-b916-e4e8add91b5d.png)
#### 1.3 Prueba de Escritorio
|s=s+c   |c=<10|c=++ |s |
|--------|-----|-----|--|
|0=0+1   |1=<10|1=1+1|  |
|1=1+2   |2=<10|2=2+1|  |
|3=3+3   |3<=10|3=3+1|  | 
|6=6+4   |4<=10|4=4+1|  |
|10=10+5 |5<=10|5=5+1|  | 
|15=15+6 |6<=10|6=6+1|  |
|21=21+7 |7<=10|7=7+1|  |
|28=28+8 |8<=10|8=8+1|  |
|36=36+9 |9<=10|9=9+1|  |
|45=45+10|     |     |55|
#### 1.4 Entradas
Ninguna
#### 1.5 Salidas
s

### Ejercicio 15. Que genere numeros pares del 1 al 10.
#### 1.1 Analisis
Insertar un simbolo de proceso para contar numeros pares del 1 al 10.
#### 1.2 DFD
![Captura de pantalla 15](https://user-images.githubusercontent.com/113395327/190953155-31c7857a-70ca-4a79-9413-405c1743e814.png)
#### 1.3 Prueba de escritorio
|s=s+c   |c>=10 |c=c+2|
|--------|------|-----|
|0=0+2   |      |2=2+2|
|2=2+4   |      |4=4+2|
|6=6+6   |      |6=6+2|
|12=12+8 |      |8=8+2|
|20=20+20|10>=10|     |
#### 1.4 Entradas
Ninguna
#### 1.5 Salidas
c=c+2

### Ejercicio 16. Capture n numeros e imprima solo la suma de los pares.
#### 1.1 Analisis
Capture n numeros, despues imprimir la suma de los pares.
#### 1.2 DFD
![Captura de pantalla 16](https://user-images.githubusercontent.com/113395327/190995396-034d6fc2-3656-49bc-9a7d-1d0cae53a09e.png)
#### 1.3 Prueba de escritorio
|m|cont==m|n|cont+1|n%2==0|Suma par+n|suma par|
|-|-------|-|------|------|----------|--------|
|3|0==3   |4|0+1   |4%2==0|0+4       |        |
| |1==3   |2|1+1   |2%2==0|4+2       |        |
| |2==3   |8|2+1   |8%2==0|6+8       |        |
| |3==3   | |      |      |          |14      |
#### 1.4 Entradas
m,n
#### 1.5 Salidas
suma par

### Ejercicio 17. Digite si un numero es par o impar
#### 1.1 Analisis
Escribir un numero entero positivo e identificar si este es par o impar.
#### 1.2 DFD
![Captura de pantalla 17](https://user-images.githubusercontent.com/113395327/190953172-bfe029c5-cdfc-436d-8a67-00c134105e63.png)
#### 1.3 Prueba de escritorio
|n |n>0|n%2==0|"par"|"impar"|
|--|---|------|-----|-------|
|2 |2>0|n%2==0|par  |       |
|7 |7>0|      |     |impar  |
#### 1.4 Entradas
n
#### 1.5 Salidas
"par","impar"

### Ejercicio 18. Escriba un DFD que indique si un numero es mayor a 10.
#### 1.1 Analisis
Se debe pedir un numero, 
#### 1.2 DFD
![Captura de pantalla 18](https://user-images.githubusercontent.com/113395327/190954772-1d268f13-e5b7-4f56-b6d7-1d33aa6b7045.png)
#### 1.3 Prueba de escritorio
|n |n>10 |"Es mayor a 10"|"Es menor a 10"|
|--|-----|---------------|---------------|
|5 |     |               |5<10           |
|14|14>10|14>10          |               |
#### 1.4 Entradas
n
#### 1.5 Salidas
"Es mayor a 10", "Es menor a 10"

### Ejercio 19. Cuantos me falta para que llegue a 10.
#### 1.1 Analisis
Se debera capturar un numero y saber cuanto le hace falta para llegar a 10
#### 1.2 DFD
![Captura de pantalla 19](https://user-images.githubusercontent.com/113395327/190959270-bcc169b8-3728-47d9-855c-4ac2b7580b25.png)
#### 1.3 Prueba de escritorio
|n |n>10 |10-n|"Te falta", n, "para 10"|n-10 |"Te pasaste por", n|
|--|-----|----|------------------------|-----|-------------------|
|6 |     |10-6|Te falta, 4, para 10    |     |                   |
|12|12>10|    |                        |12-10|Te pasaste por, 2  |
#### 1.4 Entradas 
n
#### 1.5 Salidas
"Te pasaste por", n, "Te falta", n, "para 10"

### Ejercicio 20. Capture n numeros, al final indique cuantos son positivos y cuantos negativos, escriba 0 para terminar.
#### 1.1 Analisis
Capturar n numeros e indicar cuantos son positivos y negativos, cuando el usuario inserte un 0 se termeina la captura de datos.
#### 1.2 DFD
![Captura de pantalla 20](https://user-images.githubusercontent.com/113395327/190954426-5f0e9ba3-dc9f-43cd-a21a-c79aa8f10c82.png)
#### 1.3 Prueba de escritorio
|n |n==0|n>0|neg=neg+1|pos=pos+1|"Total de numeros negativos", neg|"Total de numero positivos", pos|
|- |----|---|---------|---------|---------------------------------|--------------------------------|
|3 |    |3>0|         |0=0+1    |                                 |                                |
|-5|    |   |0=0+1    |         |                                 |                                |
|0 |0==0|   |         |         |1                                |1                               |
#### 1.4 Entradas
n
#### 1.5 Salidas
"Total de numero negativos",neg, "Total de numeros positivos",pos

### Ejercicio 21. Capture un numero positivo o negativo, 0 para terminar.
#### 1.1 Analisis
Capturar un numero positivo o negativo, termina cuando sea 0.
#### 1.2 DFD
![Captura de pantalla 21](https://user-images.githubusercontent.com/113395327/190988506-46b97938-d366-4e64-a01d-06e0a0b50070.png)
#### 1.3 Prueba de escritorio
|n|n==0|cont==n|n>0|n+1|n-1|
|-|----|-------|---|---|---|
|2|    |0==2   |2>0|   |2-1|
| |    |0==1   |1>0|   |1-1|
| |    |0==0   |   |   |   |
#### 1.4 Entradas
n
#### 1.5 Salidas
n==0, cont==n

![Datos](https://user-images.githubusercontent.com/113395327/191012801-62540397-af72-4a58-928d-bc7ba899e168.png)
