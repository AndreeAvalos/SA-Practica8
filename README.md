# SA-Practica8
Practica 8 de Software Avanzado

## Descripcion
* Crear al menos dos contenedores en Docker Compose que involucren:
* * Un servidor web
* * Una base de datos 
* El servidor web debe hacer alguna consulta a la base (lenguaje libre) y presentar información en el puerto 80 del host.
* El Docker Compose debe poder darle los datos a la base en algún archivo que la base importe al iniciar y luego sea lo que presente.
* Entrega en repositorio y video de demostración (2 minutos máximo).

## Pre-Requisitos 📋
* docker
* docker-compose

## Ejecucion 🚀
Construccion de los contenedores
```
docker-compose up -d
```
**Donde:**
* -d indica que se corre en modo demonio

**O**
```
docker-compose up -d --build 
```
**Donde:**
* -d indica que se corre en modo demonio
* --build indica que vuelva a reconstruir los contenedores

## Comprobacion
Ingresamos a:
```
localhost:8080/viewAlumno
```
El resultado tendria que ser el siguiente
```
[
    {
        "carnet":201408580,
        "dpi":2977840130108,
        "nombre":"Andree",
        "apellido":"Avalos",
        "email":"aavalosoto@gmail.com",
        "telefono":"55555555"
    }
]
```

## Construido con 🛠️
* [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/) - Ambiente de trabajo
* [Node JS](https://nodejs.org/es/docs/)- Framework
* [MYSQL](https://dev.mysql.com/doc/)- MYSQL

## Autor ✒️
* Carlos Andree Avalos Soto - 201408580

## Referencias
* [Andree Avalos](https://github.com/andreeavalos)
* [Video Explicacion](https://drive.google.com/file/d/1uW2QrDLvHU77SuStVIL5Nr05H89-QkkR/view)