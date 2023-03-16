 <center> <h2>Concepto básico de semáforo en los sistemas operativos</h2> </center>
 
#### Wander Jerez 2021-0990 

*Los semáforos son una herramienta de sincronización que provee el sistema operativo que no requiere espera ocupada. Para evitar la espera ocupada cuando un proceso tiene que esperar, se pondrá en una cola de procesos bloqueados esperando un evento*

*Un semáforo provee una simple pero útil abstracción para controlar el acceso de múltiples procesos a un recurso común en programación paralela, o entornos multiusuarios.*

*Solo se puede acceder a estos por medio de dos operaciones atómicas y mutuamente exlusivas: Wait y signal*

![foto1](/imagenes/imagen1.png)

*Cuando el proceso este bloqueado el proceso (Q) puede pasar a ejecución*

![foto2](/imagenes/imagen2.png)

## **Semáforos binarios y generales**

*Un semáforo binario es un indicador (S) de condición que registra si un recurso está disponible o no. Un semáforo binario sólo puede tomar dos valores: 0 y 1. Si, para un semáforo binario, S = 1 entonces el recurso está disponible y la tarea lo puede utilizar; si S = 0 el recurso no está disponible y el proceso debe esperar*

*Los Semáforos generales son aquellos que pueden tomar cualquier valor siempre y cuando no sean negativos, solo positivos.*

## **Relación entre los semáforos y la sincronización**

*Están relacionados porque en sistemas operativos la sincronización es la transmisión y recepción de señales que tiene por objeto llevar a cabo el trabajo de un grupo de procesos cooperativos y los semáforos son una herramienta que sirven para eficientizar la sincronización y minimizar el esfuerzo del CPU.*




