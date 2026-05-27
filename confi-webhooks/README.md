# Configuración de weebhooks

## Discord 

Crear un servidor 

![alt text](discord1.png)

Creamos nuestra plantilla

![alt text](discord2.png)

Omitimos pregunta

![alt text](discord3.png)

Asignamos un nombre y creamos

![alt text](discord4.png)

Nos iremos al servidor que creamos 

![alt text](discord5.png)

Seleccionamos el servidor y nos dirigimos a ajustes del servidor

![alt text](discord6.png)

Una vez allí debemos ir a la parte de aplicaciones e integraciones

![alt text](discord7.png)

Seleccionamos webhooks

![alt text](discord8.png)

Y creamos uno

![alt text](discord9.png)

Nos generará uno así 

![alt text](discord10.png)

Lo importante acá es copiar la url 

![alt text](discord11.png)

## Teams

Teams es muy limitado a funcionalidades y depende del tipo de cuenta con el que se ingrese, es por eso que en nuestro caso como primer paso debemos ingresar desde nuestra cuenta institucional soy.sena.edu.co

![alt text](teams1.png)

Después debemos dirigirnos a la sesión de equipos

![alt text](teams2.png)

Al tener restricciones por parte de la organización no podremos crear un equipo

![alt text](teams3.png)

Pero si podemos unirnos a uno

![alt text](teams4.png)

Nos aparecerá un listado grandísimo, podemos unirnos a cualquiera  

![alt text](teams5.png)

Una vez allí, debemos crear nuestro propio canal 

![alt text](teams6.png)

Asignamos nombre, la descripción es opcional y elegimos el tipo de canal, en mi caso seleccionaré privado porque no quiero que 265 miembros vean mi canal de pruebas

![alt text](teams7.png)

De igual manera omiteremos esta parte porque no es obligatorio hacerlo

![alt text](teams8.png)

Ahora ya podremos ver que nuestro canal se creó, debemos dirigirnos a él y presionar los tres puntos y ir a flujos de trabajo

![alt text](teams9.png)

Deberemos seleccionar una plantilla 

![alt text](teams10.png)

y escogeremos la siguiente

![alt text](teams11.png)

Configuramos el equipo, el canal y guardamos

![alt text](teams12.png)

Y listo, ya tenemos nuestro webhook hecho

![alt text](teams13.png)

## Telegram

Ahora para telegram debemos buscar un bot llamado BotFather

![alt text](telegram1.png)

Le escribimos /start para empezar una charla con él

![alt text](telegram2.png)

Creamos un nuevo bot, le asignamos nombre y el usuario

![alt text](telegram3.png)

Ahora debemos buscar nuestro botsito

![alt text](telegram4.png)

Debemos si o si generar una charla porque necesitamos el id 

![alt text](telegram5.png)

una vez echo esto, copiaremos este enlace con nuestro token de bot

```
https://api.telegram.org/bot[TOKEN_PERSONAL]/getUpdates
```
Nos saldrá algo así 

![alt text](telegram6.png)



