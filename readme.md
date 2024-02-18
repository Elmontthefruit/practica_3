# Práctica Docker-compose Osmel
## Paso 1: Crear el docker compose YML
 ![alt](imagenes/dockercompose.png)

## Paso 2: Crear el dockerfile
 ![alt](imagenes/punto2.png)
Creado un archivo compatible, procedemos a levantarlo con compose
![alt](imagenes/punto2_1.png)
![alt](imagenes/punto2_2.png)
![alt](imagenes/punto2_3.png)
![alt](imagenes/paso2_4.png)

## Paso 3: Configurar nginx
 ![alt](imagenes/paso3_1.png)
Configurado, levantamos y vemos si funciona
 ![alt](imagenes/estorula.gif) 

## Paso 4: Al comprobar que funciona, probamos a hacer debug
![Peek 2024-02-18 17-49](https://github.com/Elmontthefruit/practica_3/assets/118209418/e5bb0438-c502-4394-bc26-97a46885764f)


## --NOTAS--
1.-Debido a que el ordenador ha decidido tener un kernel panic en medio de la tarea, la aplñicacion se ejecutaba en el puerto 8000, pero se bloqueó y ahora solo funciona en el puerto 8002 (de ahi que el primer screenshot salga con otro puerto)
2.-Debido a lo mismo, el equipo se niega a que Docker se comunique correctamente, así que el ultimo gif (el de debug) está hecho desde el equipo de Verónica con mi contenedor (Linux Mint y Ubuntu)
