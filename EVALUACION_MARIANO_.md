# APELLIDO Y NOBRE: 
# CHUCHON NUÑEZ, MARIANO

0. Clonar el repositorio [`oneAPI-samples`](https://github.com/oneapi-src/oneAPI-samples) [1 punto]
## RESPUESTA_0:
comando: 
u185966@login-2:~$ git clone https://github.com/oneapi-src/oneAPI-samples

![respuesta 00](rspst_00_01_clonar_.png)

1. Cambiar al directorio del ejemplo `Nbody`  [1 punto]
    - Directorio: `oneAPI-samples/tree/master/DirectProgramming/C++SYCL/N-BodyMethods/Nbody`
## RESPUESTA_1:
comando:
u185966@login-2:~/COMPUTACION_/EVALUACION/oneAPI-samples/DirectProgramming/C++SYCL/N-BodyMethods/Nbody$ pwd
/home/u185966/COMPUTACION_/EVALUACION/oneAPI-samples/DirectProgramming/C++SYCL/N-BodyMethods/Nbody

![respuesta 00](rspst_01_01_cambio_direc_.png)

2. Explicar brevemente el algoritmo de `Nbody` [3 puntos]
## RESPUESTA_2:

El código del algoritmo Nbody simula un sistema dinámico de partículas de 16 000 partículas en diez pasos de integración. Los parámetros de posición, velocidad y aceleración de cada partícula dependen de otras (N-1) partículas.


3. Acceder en modo interactivo a un nodo de cómputo con GPUs (`gen9` o `gen11`) [3 puntos]
    - Compilar y ejecutar `Nbody`
    - Proporcionar screenshot(s) de los resultados
        - Por cada screenshot, añadir una breve descripción
## RESPUESTA_3:
Se accede al nodo 11 como se muestra en la figura siguiente:

![respuesta 00](rspst_03_01_nodo_.png)

Se lista el directorio Nbody

![respuesta 00](rspst_03_02_compil_01_.png)

Se compila el Nbody

![respuesta 00](rspst_03_02_compil_02_.png)

Se continua compilando Nbody

![respuesta 00](rspst_03_02_compil_03_.png)


4. Realizar un análisis de _**GPU Hotspots**_ con VTune [8 puntos]
    - Indicar los hotspots del programa
    - Proporcionar screenshot(s) de los resultados
      - Por cada screenshot, añadir una breve descripción
## RESPUESTA_4:

En la figura se muestra la generacion de archivo para VTUNE

![respuesta 00](rspst_04_01_compil_01_.png)

![respuesta 00](rspst_04_01_compil_02_.png)

![respuesta 00](rspst_04_01_compil_03_.png)

Generacion del archivo para VTUNE

![respuesta 00](rspst_04_02_archivo_01_.png)

Analisis de VTUNE

![respuesta 00](rspst_04_03_vtune_01_.png)

![respuesta 00](rspst_04_03_vtune_02_.png)

![respuesta 00](rspst_04_03_vtune_03_.png)

5. Realizar un análisis _**Roofline**_ con Advisor [4 puntos]
    - Indicar los hotspots del programa
    - Proporcionar screenshot(s) de los resultados
      - Por cada screenshot, añadir una breve descripción
    - Indicar potenciales soluciones para optimizar la ejecución del programa
## RESPUESTA_5:

![respuesta 00](rspst_05_01_compil_01_.png)

![respuesta 00](rspst_05_01_compil_02_.png)

Generacion de archivo para VTUNE

![respuesta 00](rspst_05_02_advisor_01_.png)

Evaluacion con VTUNE

![respuesta 00](rspst_05_02_advisor_02_.png)

![respuesta 00](rspst_05_02_advisor_03_.png)

![respuesta 00](rspst_05_02_advisor_04_.png)

