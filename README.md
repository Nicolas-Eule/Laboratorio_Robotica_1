<!-- ✦✦✦ FUTURE IS AUTOMATED ✦✦✦ -->
<!-- Banner superior “neón” -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:04041A,50:14213D,100:0A4D68&text=Laboratorio%20Rob%C3%B3tica%201&fontColor=E0FBFC&fontAlign=50&fontAlignY=30&desc=Decoraci%C3%B3n%20de%20Tortas%20Virtuales%20%E2%80%A2%20ABB%20IRB%20140%20%E2%80%A2%20RAPID&descAlign=50&descAlignY=60" alt="header" />
</p>

<h1 align="center">🤖 LABORATORIO ROBÓTICA 1 – DECORACIÓN DE TORTAS VIRTUALES</h1>

<p align="center">
  <img src="https://img.shields.io/badge/RAPID-ABB%20IRC5-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RobotStudio-2025-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Automation-Industrial-green?style=for-the-badge" />
</p>

<!-- Línea de texto mecanografiado (animado) -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&duration=3500&color=00E5FF&center=true&vCenter=true&lines=Rob%C3%B3tica+Industrial+2025%E2%80%93II;ABB+IRB+140+%E2%80%A2+RAPID+%E2%80%A2+RobotStudio;TCP+%2F+Tooldata+%E2%80%A2+WorkObjects+%E2%80%A2+IO+Digitales" alt="typing">
</p>

---

### 🛰️ Descripción general

Este repositorio implementa el **Laboratorio No. 1** de *Robótica Industrial 2025-II*: automatización de la **decoración de una torta virtual** con un robot **ABB IRB 140**, programado en **RAPID** y simulado en **RobotStudio**.  
Incluye trayectorias (MOVJ, MOVL, MOVC), calibración de herramienta (TCP/Tooldata), *workobjects* y control de **IO digitales** (luz indicadora y banda transportadora).

---

---

## 🧑‍🚀 Equipo

<!-- ===== INICIO BLOQUE ANIMACIONES EQUIPO (una animación por línea) ===== -->

<!-- Encabezado: Integrantes -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=22&duration=2000&pause=800&color=00E5FF&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Integrantes%3A" alt="Integrantes">
</p>

<!-- Nombre 1 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2400&pause=600&color=7F5AF0&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Jorge+Nicol%C3%A1s+Garz%C3%B3n+Acevedo+%E2%80%94+jngarzona%40unal.du.co" alt="Jorge Nicolás Garzón Acevedo">
</p>

<!-- Nombre 2 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2400&pause=600&color=7F5AF0&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Johan+Camilo+Pati%C3%B1o+Mogoll%C3%B3n+%E2%80%94+jopatinom%40unal.edu.co" alt="Johan Camilo Patiño Mogollón">
</p>

<!-- Nombre 3 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2400&pause=600&color=7F5AF0&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Gabriel+Eduardo+Bojaca+Munar+%E2%80%94+gbojaca%40unal.edu.co" alt="Gabriel Eduardo Bojaca Munar">
</p>

<!-- Encabezado: Docentes -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=22&duration=2000&pause=800&color=00E5FF&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Docentes%3A" alt="Docentes">
</p>

<!-- Docente 1 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2400&pause=600&color=39D353&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Manuel+Felipe+Carranza+Montenegro+%E2%80%94+mcarranza%40unal.edu.co" alt="Manuel Felipe Carranza Montenegro">
</p>

<!-- Docente 2 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2400&pause=600&color=39D353&center=true&vCenter=true&width=1000&repeat=true&v=1&lines=Pedro+Fabi%C3%A1n+C%C3%A1rdenas+Herrera+%E2%80%94+pfcardenash%40unal.edu.co" alt="Pedro Fabián Cárdenas Herrera">
</p>

<!-- ===== FIN BLOQUE ANIMACIONES EQUIPO ===== -->

# Laboratorio No. 01 - Robótica Industrial: Trayectorias, Entradas y Salidas Digitales.
## Introduccion
El proyecto consiste en realizar el dibujo de los nombres de los integrantes del equipo sobre una superficie plana (una caja), incluyendo además un elemento decorativo libre, que en este caso corresponde al logotipo del grupo de investigación Kyma.Toda la secuencia se ejecuta desde la posición Home del robot ABB, con la caja siendo transportada por una banda transportadora que se detiene en una posición previamente definida, permitiendo así la ejecución precisa del dibujo programado.Finalmente, se establece una posición de acceso seguro para el operario, la cual facilita el mantenimiento o el cambio de herramienta, garantizando comodidad y seguridad durante la intervención del robot.


## Descripción de la solución planteada
Para la decoración del pastel se propone el uso de una herramienta capaz de sostener un marcador borrable, la cual permitirá realizar los trazos solicitados —nombres y logotipo— sobre una caja de madera con superficie superior de acrílico.

La decoración consiste en la ejecución de trayectorias previamente diseñadas en la aplicación de simulación RobotStudio de ABB, donde se configuran tanto las trayectorias como el comportamiento dinámico del robot (posición y velocidad).Asimismo, se implementa una posición de mantenimiento en la que el robot se aleja del área de dibujo, permitiendo realizar de manera segura cambios o reparaciones en la herramienta de trabajo.

Todo el sistema se programa en la sección RAPID de RobotStudio, donde también se integran entradas y salidas digitales para controlar la ejecución de procedimientos y la señalización mediante indicadores luminosos.Todo esto al final para ser cargados al robot por medio del flexpendan.

### Herramienta de trabajo  flanche 
La herramienta de trabajo fue diseñada en la aplicación de modelado 3D Autodesk Inventor, tomando como base el soporte o flange del eslabón 6 del robot y usando la informacion de dimensionamiento ofrecida por ABB, el cual sirve como punto de acoplamiento para la herramienta.El diseño contempla la posibilidad de realizar cambios del marcador de manera sencilla, garantizando versatilidad durante la operación.

Posteriormente, la herramienta fue fabricada mediante impresión 3D utilizando material PLA. En el interior del soporte del marcador se incorporó un resorte, que permite un margen de tolerancia al momento de ejecutar el dibujo, evitando daños o presiones excesivas sobre la superficie.

Cabe resaltar que, durante el desarrollo del proyecto, inicialmente se trabajó en una herramienta diseñada por dos integrantes del equipo; sin embargo, posteriormente se integró un tercer miembro, quien ya contaba con su propia herramienta diseñada.A continuación, se presenta el desarrollo de ambas propuestas, destacando que la herramienta seleccionada como definitiva para el proyecto fue la diseñada por el tercer integrante.

### Pastel - superficie de dibujo
Se diseñó una caja que simula un pastel, con dimensiones de 15 cm × 15 cm × 15 cm, su caras laterales e inferior fueron construidas en madera, mientras que la cara superior se elaboró en acrílico, sirviendo como superficie de dibujo.En el interior de la caja se incorporó un contrapeso, con el fin de evitar balanceos o movimientos indeseados durante la ejecución del trazado por parte del robot.


## Diagrama de flujo de acciones del robot
Se presenta el diagrama de flujo del proceso desarrollado para garantizar el cumplimiento de los requerimientos del proyecto.
<p align="center">
  <img src="https://github.com/Nicolas-Eule/Laboratorio_Robotica_1/blob/main/assets/img/Flujo%20de%20proceso.drawio.png" alt="Flujo de proceso" width="500">
</p>

## Descripción de las funciones utilizadas 
Para efectuar correctamente el diagrama de flujo de procedimiento previamente mostrado se hacen uso de funciones de operadores lógicos y movimiento.
### Funciones de movimiento
<ul style="list-style-type: square;">
  <li>MoveJ: El robot se mueve de forma curva, calculando internamente los ángulos de cada articulación para llegar al punto final lo más rápido posible, sin preocuparse de seguir una línea recta       en el espacio donde la herramienta del robot hace una trayectoria curvada o arqueada, porque cada eje gira a distinta velocidad para optimizar el movimiento. </li>
  <li>MoveL: El robot mueve su herramienta en línea recta desde el punto actual hasta el punto destino donde la punta del robot (el TCP) sigue una trayectoria recta en el espacio cartesiano (XYZ)</li>
  <li>Target: Un target representa una posición y orientación específica del efector final del robot (TCP) dentro del espacio de trabajo al que el robot debe llegar o pasar durante su movimiento. </li>
  <li>Path: Es la ruta o secuencia de movimientos que el robot sigue entre varios targets donde internamente esta compuesta por funciones MoveJ,MoveL y MoveC. </li>
</ul>

### Funciones de operadores lógicos
Para este tipo de funciones se usaron  WHILE TRUE DO , AND , IF y ELSEIF donde estas permiten la secuencia de procedimiento al poner decisiones que son tomadas con las entradas digitales DI_01 y DI_02
<ul style="list-style-type: square;">
  <li> WHILE TRUE DO: La condición siempre es verdadera, por lo tanto, el ciclo nunca termina  a menos que dentro haya un comando que lo interrumpa </li>
  <li> AND: Combina dos condiciones lógicas; ambas deben ser verdaderas para que el resultado sea verdadero</li>
  <li> IF: Permite ejecutar una parte del código solo si se cumple una condición (si es verdadera).</li>
  <li> ELSEIF: Analiz a cada IF que contenga el bloque de comando donde si la primera (IF) no se cumple, se revisa la siguiente (ELSEIF), y así sucesivamente</li>
  
</ul>

## Codigo Rapid
Para la ejecución del procedimiento se desarrolló el código de funcionamiento en lenguaje RAPID, utilizado por RobotStudio para el control y movimiento del robot.  [Hacer clic aquí para ver el código RAPID](https://github.com/Nicolas-Eule/Laboratorio_Robotica_1/blob/main/rapid/RAPID_CODE.m)

## Plano de planta de los elementos de trabajo
El plano de planta se encuentra en el siguiente enlace. [Hacer clic aquí para ver el plano de planta en RobotStudio](https://github.com/Nicolas-Eule/Laboratorio_Robotica_1/blob/main/assets/img/Plano_de_planta.png)

## Simulación de la práctiva
Se muestra la implementacion de las dos herramientas en RobotStudio

Primera herramienta desarrollada
<p align="center">
  <img src="https://github.com/Nicolas-Eule/Laboratorio_Robotica_1/blob/main/assets/img/Screenshot%202025-10-05%20201650.png" alt="Flujo de proceso" width="500">
</p>

Segunda herramienta la cual es fue la definitiva a trabajar
<p align="center">
  <img src="https://github.com/Nicolas-Eule/Laboratorio_Robotica_1/blob/main/assets/img/Screenshot%202025-10-05%20201934.png" alt="Flujo de proceso" width="500">
</p>



## Video de la práctica  
Se muestra a continuación el video de la aplicación realizada en **RobotStudio**, efectuada en el **laboratorio LabSIR**.  



<p align="center">
  <!-- Miniatura de YouTube con enlace al video -->
  <a href="https://youtu.be/jfjOX9DQJSQ" target="_blank">
    <img src="https://img.youtube.com/vi/jfjOX9DQJSQ/hqdefault.jpg" alt="Ver la simulación y ejecución" width="600">
  </a>

