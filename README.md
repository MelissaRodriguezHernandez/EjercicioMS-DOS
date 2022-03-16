# Ejercicio MS-DOS

***

*La práctica se basa en crear directorios en MS_DOS recreando el menú de la página del Instituto CIFP Fransesc de Borja Moll*

***

## Comandos usados

Crear directorios o carpetas

`md [unidad\ruta]`

Visualizar un listado de todos los ficheros y directorios

`dir [unidad\ruta]`

Visualizar el contenido de un directorio en estructura de árbol

`tree [unidad\ruta]`

## Procedimiento

1. Elegimos la unidad que usaremos y creamos un directorio llamado ejercicio1 o menu (en mi caso elegi ejercicio1).

>md Ejercicio1

2. Dentro de este nuevo directorio empezamos a crear las carpetas principales con los nombres de las opciones del menú de la página. 
*Recomendación: No hace falta ejecutar el comando 'md' por cada carpeta que se crea, se puede crear varias carpeta a la vez como se ve a continuación*

>md Inici Centre Alumnat Webs_interes Oferta_formativa Orientacio Noticies Agenda Borsa_de_treball

3. A continuación crearemos las subcarpetas que tendran cada apartado

Ejemplo :
>md Horaris_localitzacio Contacte Equip_Directiu Consell_social

4. Finalmente ejcutamos el comando `tree` situados en nuestro directorio *ejercicio1* y visualmente se vería lo siguiente:

![arbol de directorios](https://github.com/MelissaRodriguezHernandez/EjercicioMS-DOS/blob/main/Captura1.png)
![arbol de directorios](https://github.com/MelissaRodriguezHernandez/EjercicioMS-DOS/blob/main/Captura2.png)
