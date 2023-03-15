---
{"dg-publish":true,"permalink":"/podcast/temporada-1/t1-cap-1-instalacion-de-home-assistant/","title":{"{ title }":null},"tags":["podcast","homeassistant","domotica",1],"noteIcon":""}
---












## Escaleta


![caratula podcast 1.jpg](/img/user/Adjuntos/caratula%20podcast%201.jpg)


## Instalación de Home Assistant

Hola mi nombre es Óscar y mi casa me escucha, si y ademas algunas veces me obedece. Bienvenido al podcast en el que hablamos de Home Assistant y de todos esos CHISMES que nos gustan para hacer de nuestras casas algo mas inteligentes, aunque ahora que lo pienso los inteligentes deberíamos de ser nosotros y ellas obedientes, buen el cualquier caso si a ti también tu casa te escucha te doy a bienvenida a esta vida sin vida, bienvenido a Home Assistant


Bueno ya estamos aquí de nuevo, ¿ahora que toca? Pues instalar HomeAssistant. 

A las preguntas de como instalar y que opciones tengo intentare responder en este capitulo.

* 1     Que es lo que necesito y que quiero tener, esa es la primera pregunta que debemos de respondernos y debemos hacerlo nosotros y nadie mas, solo nosotros sabemos como es nuestra casa que necesidades tengo que cubrir y las posibilidades que puede ofrecerme Home Assistant según  el tipo de instalación que monte.
* 2      A día de hoy las instalaciones o mejor dicho el tipo de soporte sobre el que podemos instalar Home Assistant se reducen a 2/3 dependiendo el soporte sobre el que vayamos a instalar y en base a si tenemos o no ese soporte, maquina, host, mini pc, NAS, etc
* 3   Tengo una raspberry Pi 4/4 u 8 gigas recomendado un ssd en vez de sd, por precio a día de hoy casi interesa mas un ssd con una carcasa externa. Los pasos serian parecidos, descargamos BallenaEtcher, lo ejecutamos , con la memoria usb conectada a nuestro pc, indicamos en la opción **flash from url** pegamos la dirección que nos indica en la web de HA para la instalación de la raspberry ( tienes los enlaces en la literatura del podcast), seleccionamos el dispositivo (SSD o tarjeta de memoria) y esperamos a que termine. Una vez finalizo solo nos queda insertar la sd o conectar el disco ssd a nuestra Raspberry. ( atención fíjate si lo conectas a un puerto 3.0, si ves que no arranca cambia de puerto), para ver si esta cargando el SO podemos buscar a través de alguna aplicación de escaneo de red tipo FING y buscar el nuevo dispositivo, tendrá un nombre similar a Home Assistant, una vez encontrado solo nos queda abrir la dirección en un navegador web y configurar las credenciales. La dirección seria del tipo 192.168.X.XX:8123
* 4    Tengo un NAS que instalación puedo tener. Va a depender de tu modelo y marca, en la documentación de Home Assistant tienes la info de los modelos que soportan las instalaciones, en las notas del capitulo te dejo los enlaces.
* 5   Tengo un minipc, como instalo Home Assistant, pues en este caso la opciones son claras. Grabar la imagen en el HD de nuestro minipc, NUC, etc. Necesitamos una memoria usb, conectar una pantalla, teclado y ratón conectados al minipc y que este conectado a Internet por cable, grabamos una distribución de linux, recomiendo LinuxMint,la versión ** Cinnamon Edition** es fácil e intuitiva. Grabamos la imagen en el pendrive con BallenaEtcher , es sencillo, descargara la aplicación instalar y listo. Después de grabar la memoria con LinuxMint, conectamos a nuestro minipc y arrancamos desde esa memoria, dependerá de tu minipc, quizás pulsando F12, F2, mira la documentación del mini pc para saber como hacer que arranque desde el usb. Una vez conseguido eso solo nos queda abrir el navegador Firefox y buscar BallenaEtcher para descargar la app, es un appimage, por lo tanto tenemos que dar permisos de escritura y lectura. Eso se consigue seleccionando con botón izquierdo y la pestaña de permisos, marcar read & write y ejecutar como programa, aplicamos y con doble clic arrancamos. 
* 6   Abrimos la pagina de home assistant y nos vamos a la sección de instalar  generic x86-64 veremos las instrucciones , copiamos el link donde nos descargara la imagen de Home Assistant
* 7   Ahora en BallenaEtcher abrimos y en la opción que pone url pegamos esa dirección, nos descargara la imagen, el siguiente paso es grabar la imagen, seleccionamos el disco duro, tendremos avisos en amarillo indicando que es el disco duro , confirmamos y esperamos que termine. Con eso ya lo tendremos una vez terminado, cerramos ballenaetcher y reiniciamos pulsando en el menú abajo a la izquierda. No dice que desenchufemos el usb y pulsemos enter. Una vez reinicia nos saldrá el promp ( la pantalla negra de fondo con letras blancas)  una vez cargue todo el SO tendremos una dirección donde estará nuestro Home Assistant . 
*  8   Listo ahora ya solo nos queda cacharrear con nuestro Home Assistant y nuestros cacharritos. En el próximo capitulo veremos que ad-don (complementos) instalar y como hacerlo, HACS que es una tienda de la comunidad. Home Assistant Community Store



Enlaces:

[Instalación HA](https://www.home-assistant.io/installation/generic-x86-64)
[Descarga BallenaEtcher](https://www.balena.io/etcher)

Imagen Home Assistant Raspberry Pi 3b+
```text
https://github.com/home-assistant/operating-system/releases/download/9.5/haos_rpi3-64-9.5.img.xz
```


Imagen Home Assistant Raspberry Pi 4

```text
https://github.com/home-assistant/operating-system/releases/download/9.5/haos_rpi4-64-9.5.img.xz 
```


Imagen Home Assistant minipc
```text
https://github.com/home-assistant/operating-system/releases/download/9.5/haos_generic-x86-64-9.5.img.xz
```


Contacto: 
[Telegram](https://t.me/osckarsevilla)

Créditos Música

[Together by 2TECH-AUDIO](https://2tech-audio.bandcamp.com)
[Music promoted by](https://www.free-stock-music.com)

