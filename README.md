# Laboratorio_3
<p align="center">
ROBÓTICA

<p align="center">
Hugo Alejandro Camargo Barrera
<p align="center">
email: hcamargob@unal.edu.co

<p align="center">
Santiago Hernández Lamprea
<p align="center">
email: shernandezl@unal.edu.co


<p align="center">
INGENIERÍA MECATRÓNICA
<p align="center">
Facultad de Ingeniería
<p align="center">
Universidad Nacional de Colombia Sede Bogotá

Para cumplir satisfactoriamente los requerimientos y tareas propuestas, se siguió el siguiente proceso:

### 1) Configuración de entradas y salidas

Siguiendo la guía, se hizo la conexión del IRB140 con el tablero de entradas que disponía el controlador. Estas se configuraron en RobotStudio de la siguiente manera:
1. Se selecciona la opción _I/O System_, que se encuentra en el controlador.
![image](https://user-images.githubusercontent.com/112737454/194687410-c56312bc-cce9-43ae-b486-540575efbc1b.png)
2. Al abrirse la ventana de entradas y salidas, se selecciona la opción _Signal_ con click, la cual abre a su vez la ventana de nueva señal. 
![image](https://user-images.githubusercontent.com/112737454/194687520-c51352df-a9fb-4157-81e1-c060891d310d.png)
![image](https://user-images.githubusercontent.com/112737454/194687526-2dbad04d-8635-4ff6-9e85-0ae5a2bedbd5.png)
Se le asigna un nombre a la señal y se configura como _Digital Input_ (Entrada Digital).
3. Se crean otras dos señales digitales de entrada y una de salida.
4. Se reinicia el controlador.
5. Se configura la simulación para entradas y salidas
![image](https://user-images.githubusercontent.com/112737454/194687733-a033029e-1d01-44d5-a252-872217ca87a1.png)
6. Al seleccionar la simulación, se abre un panel con las entradas y salidas creadas en el paso 2 y 3. Se hace la configuración de las trayectorias creadas con las entredas. Se sincroniza el simulador con el módulo RAPID. Finalmente se hace la simulación.

[![Watch the video](https://user-images.githubusercontent.com/112737454/194688205-2ae0fe15-c79b-4d1b-8bcb-7df7d76300d5.png)](https://www.youtube.com/watch?v=bMmIV-oO5IU)

### 2) Puesta en marcha
Se subió el código al robot IRB140 del laboratorio, se ejecutó la secuencia y se observó el siguiente resultado:

[![Watch the video](https://user-images.githubusercontent.com/112737454/194688703-223c5149-daf2-4678-8877-68e0fa03d440.png)](https://www.youtube.com/watch?v=93VOe-NtV4s)

En el siguiente video se observa el funcionamiento del panel del controlador:

[![Watch the video](https://user-images.githubusercontent.com/112737454/194688782-b08aed6e-91de-4c95-a3cb-ebabbdf1b756.png)](https://www.youtube.com/watch?v=Il_TQljtz2A)

Finalmente, se obtiene:


![image](https://user-images.githubusercontent.com/112737454/194687016-597f4887-6073-445d-a736-a2945d1b462b.png)
