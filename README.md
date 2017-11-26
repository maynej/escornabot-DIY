# AVISO!! En construcción, estos días retocaré muchas cosas aunque lo esencial siempre lo tendrás a mano :P
  
# Escornabot DIY  
  
Material recopilado de [Xoan Sampaiño](https://github.com/xoan), [Rafa Couto](https://github.com/rafacouto), [XDeSIG](https://github.com/xdesig) y [mgesteiro](https://github.com/mgesteiro)   
  
Web oficial del robot escornabot http://escornabot.com
  
  
![Escornabot DIY](imagenes/EscornabotDIY.jpg)
  
  
  
# Piezas Impresas3D Necesarias
  
Descripción         | imagen          | archivo         
------------- | ------------- | ------------- 
Sujeción bola v2|![ballcaster-v2.stl](imagenes/ballcaster-v2.png) | [ballcaster-v2.stl](archivos-stl/ballcaster-v2.stl)  
Sujeción batería|![battery-bracket.stl](imagenes/battery-bracket.png) | [battery-bracket.stl](archivos-stl/battery-bracket.stl)  
Sujeción motores|![MotorBracket.stl](imagenes/MotorBracket.png) | [MotorBracket.stl](archivos-stl/MotorBracket.stl)  
Sujeción protoboard 170 puntos|![board-bracket.stl](imagenes/board-bracket.png) | [board-bracket.stl](archivos-stl/board-bracket.stl)  
Sujeción placa botonera|![Addon-KeypadBracket-PCB.stl](imagenes/Addon-KeypadBracket-PCB.png) | [Addon-KeypadBracket-PCB.stl](archivos-stl/Addon-KeypadBracket-PCB.stl)  
Rueda izquierda|![wheel-l.stl](imagenes/wheel-l.png) | [wheel-l.stl](archivos-stl/wheel-l.stl)  
Rueda derecha|![wheel-r.stl](imagenes/wheel-r.png) | [wheel-r.stl](archivos-stl/wheel-r.stl)  
  
  
### Opcional
  
En mi caso, no monto la pieza "sujeción interruptor". Dejo los cables para conectar macho con hembra y enseñar a los peques la conexión de los cables.

Descripción         | Imagen          | Archivo          
------------- | ------------- | ------------- 
Sujeción interruptor|![Addon-SwitchHolder.stl](imagenes/Addon-SwitchHolder.png) | [Addon-SwitchHolder.stl](archivos-stl/Addon-SwitchHolder.stl)
  
  
  
### Diseños de piezas antiguas
  
Algunas piezas van evolucionando, te dejo las versiones viejas para que las tengas a mano

Descripción         | Imagen          | Archivo          
------------- | ------------- | ------------- 
Sujeción bola trasera|![BallCaster.stl](imagenes/BallCaster.png) | [BallCaster.stl](archivos-stl/BallCaster.stl)
Rueda x2|![WheelNG.stl](imagenes/WheelNG.png) | [WheelNG.stl](archivos-stl/WheelNG.stl) 
  
  
  
# Placa Botonera XDeSIG 
  
Una de las partes más problemática es la placa botonera. Eso se soluciona con la PCB diseñada por [XDeSIG](https://github.com/xdesig)

![Placa XDeSIG](imagenes/Placa-XDeSIG.jpg)
  
La puedes pedir aquí - [Placa XDeSIG en PCBWay](https://www.pcbway.com/project/shareproject/W50475ASN5_Escorna_bot_2_1_Gerber.html)

Estos son los materiales que necesitas soldar en la placa:

- 5 resistencias 10k
- 1 resistencia 22k
- Pines acodados
- 5 botones 12mm (también puedes poner los pequeños)
  
### Para esta placa necesitas imprimir esta sujeción de placa
  
Puedes ponerle carcasa :)
  
Descripción         | Imagen          | Archivo          
------------- | ------------- | ------------- 
Sujeción placa botonera XDeSIG|![Addon-KeypadBracket-5Buttons.stl](imagenes/Addon-KeypadBracket-5Buttons.png) | [Addon-KeypadBracket-5Buttons.stl](archivos-stl/Addon-KeypadBracket-5Buttons.stl)
Cubierta botonera XDeSIG|![Addon-KeypadCover.stl](imagenes/Addon-KeypadCover.png) | [Addon-KeypadCover.stl](archivos-stl/Addon-KeypadCover.stl)
Botones XDeSIG|![Addon-KeypadButtons-Graphics.stl](imagenes/Addon-KeypadButtons-Graphics.png) | [Addon-KeypadButtons-Graphics.stl](archivos-stl/Addon-KeypadButtons-Graphics.stl)
  
  
  
# Guías y manuales
  
Guía de montaje del CFR Ferrol, es en la que me basé para montar mi primer escornabot. Tienes instrucciones detalladas para montar la botonera - [Guía montaje CFR Ferrol](https://www.edu.xunta.gal/centros/cfrferrol/aulavirtual2/pluginfile.php/18631/mod_resource/content/0/doc/Proxecto_K-KuriBOT_CFR_FERROL.pdf)

Listado completo de materiales necesarios, web original escornabot. Todos los componentes que te haran falta para poner al pequeñajo a caminar - [Listado materiales](http://escornabot.org/wiki/index.php/Lista_de_materiales_(Brivoi))

Guía de montaje sin incluir ensamblaje de botonera, web original escornabot - [Guía montaje](http://escornabot.org/wiki/index.php/Gu%C3%ADa_de_montaje_(Brivoi))

Como comprobar la lectura de la botonera para luego modificar los valores en el archivo "configuration.h" - [Comprobación botonera](https://escornabot.com/web/es/content/comprobacion-y-configuracion-de-las-lecturas-de-botonera)

Diferentes versiones de ![Rafa Couto](https://github.com/rafacouto) realizadas hasta ahora [Versiones arduino para escornabot](https://github.com/escornabot/arduino/releases)  
