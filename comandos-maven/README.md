# Ejecución inicial proyecto maven 

## Comandos

```
mvn clean
```
Limpia el proyecto, se usa antes de compilar. 

![alt text](1.png)

```
mvn compile
```
Compila el proyecto, se usa durante el desarrollo.

![alt text](2.png)

```
mvn test
```
Ejecuta pruebas, se usa para validar cambios.

![alt text](3.png)

```
mvn package 
```
Genera el .jar, se usa antes de ejecutar/desplegar.

![alt text](4.png)

```
mvn install 
```
Instala en .m2, uso profesional/CI.

![alt text](5.png)

## Atajo

```
mvn clean install
```
Hace todo:
- clean
- compile
- test
- package
- install