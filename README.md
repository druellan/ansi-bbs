# PRemote Ansi BBS

![PRemote main menu](https://raw.githubusercontent.com/druellan/ansi-bbs/master/Screenshots/MENU1.ANS.png)

### Español
Este proyecto forma parte de un trabajo de investigación relazido entre los años **1993** y **1994**, sobre la transmisión, recepción e interpretación de códigos ANSI en terminales conectadas mediante modems. Investigando sobre el tema, se me ocurrió que podría ser posible implementar un sistema de menues interactivos que simplificara la interacción con el usuario y fuera más vistoso que un simple lisado de opciones con teclas asociadas.

Debido a que los códigos ANSI eran capaces de reposicionar el cursor en cualquier área de la pantalla, era posible redibujar pequeñas secciones, sin tener que descargar toda la pantalla nuevamente. Esta característica fue empleada para programar una librería que permitía controlar un menú de opciones mediante las flechas y la tecla ENTER. También se programaron animaciones simples, como la aparición de un reloj si el usuario estaba inactivo mucho tiempo.

El prototipo fue programado en QBasic, y contaba con un sistema de validación de usuarios, repositorio de archivos con capacidad de transmisión xmodem y zmodem, chat y mensajería privada. Nunca salió de su etapa experimental, ni se mantuvo conectado más de un par de veces.

Los siguientes archivos fueron rescatados de un disco de 3 1/2 pulgadas. Ignoro si se trataba de la versión más reciente del desarrollo. Asimismo, desconozco si es posible ponerlo en funcionamiento con las herramientas de QBasic modernas, y es posible que requiera la presencia física o virtual de un modem para inicializar correctamente.

Pueden encontrarse capturas PNG del layout en ANSI en la carpeta `screenshots`.

![PRemote enviar/recibir archivos](https://raw.githubusercontent.com/druellan/ansi-bbs/master/Screenshots/ARCHIVO2.ANS.png)

### English
This project is part of an early research I conducted on the years **1993**/**1994**. At this time I was very intrigued by BBS systems and the ability to transmit and parse ANSI codes via modem. Most BBS system had a very basic layout and an UI based on keybindings, and I was wondering if a more elegant and user friendly system was possible.

Most ANSI terminals were capable of repositioning the cursor anywhere on the screen, and redrawing a section without requiring a screen refresh. I used this feature to build a basic selection menu library, that could be controlled using the arrows and ENTER keys. The feature was also used for some animations, for example, a clock icon  showing up if the user was idle for a long time.

The prototype was programmed used QBasic, featuring a userbase, file transmision using xmodem and zmodem, internal message system and chat. It was mostly experimental, remaining online only a couple of times.

The following files were found on a 3 1/2 floppy disk, and I don't know if this version was the most up-to-date. Also, I'm not sure if this same code can be executed on any modern QBasic compiler: for starters, it would need a virtual modem in place, and to emulate the connection.

On the folder `screenshots` there are some PNG obtained from the original ANSI art.

![PRemote About Logo](https://raw.githubusercontent.com/druellan/ansi-bbs/master/Screenshots/logo.ans.png)

### Otros Autores
Este proyecto incluye el trabajo de los siguientes autores:

- AICHAT by Avatar (c) 1990 Serious Cybernetics
- GEDIT by Chris Patterson (c) 1993 The Developers Network, Inc.
- ZMODEM by Scott M. Baker (c) Scott M. Baker
