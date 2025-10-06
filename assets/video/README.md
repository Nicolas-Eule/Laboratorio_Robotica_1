# 🎬 Videos del Laboratorio – Robótica Industrial

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=2400&pause=900&color=00E5FF&center=true&vCenter=true&width=900&lines=Aqu%C3%AD+puedes+visualizar%3A;Video+de+la+pr%C3%A1ctica+(laboratorio);Video+de+la+simulaci%C3%B3n+(RobotStudio)" alt="Animación videos">
</p>

---

## 📌 Video de la práctica (laboratorio)

<p align="center">
  <a href="https://youtu.be/gwcXK-_C6pA?si=X1zZq3yhsR2akUh2">
    <!-- Usa maxresdefault si existe; si no, cambia a hqdefault.jpg -->
    <img src="https://img.youtube.com/vi/gwcXK-_C6pA/maxresdefault.jpg" alt="Ver video de la práctica" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/gwcXK-_C6pA?si=X1zZq3yhsR2akUh2">
    <img src="https://img.shields.io/badge/Ver%20en%20YouTube-%F0%9F%94%B4-red?style=for-the-badge" alt="Ver en YouTube">
  </a>
</p>

### 🧩 Descripción del contenido del video
**Grabación real en laboratorio** ejecutando la secuencia programada en RAPID sobre un **ABB IRB 140 / IRC5**:

- **Homing**: posicionamiento inicial seguro (HOME) y verificación de **TCP/Tooldata**.
- **WorkObject** y parámetros de movimiento: trayectorias continuas.
- **Evento de inicio** por **DI_01** → arranque de la rutina de decorado.
- **Trayectorias**: letras y decoración con **MOVL/MOVC**, continuidad de trazo.
- **Salidas digitales**:
  - **DO_01** → luz indicadora.
  - **DO_02** → banda/variador al finalizar.
- **Retorno a HOME** y **modo mantenimiento** vía **DI_02**.

---

## 🧪 Video de la simulación (RobotStudio)

<p align="center">
  <a href="https://youtu.be/etMuTp3UyoM">
    <!-- Usa maxresdefault si existe; si no, cambia a hqdefault.jpg -->
    <img src="https://img.youtube.com/vi/etMuTp3UyoM/maxresdefault.jpg" alt="Ver video de la simulación en RobotStudio" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/etMuTp3UyoM">
    <img src="https://img.shields.io/badge/Ver%20simulaci%C3%B3n%20en%20YouTube-%F0%9F%94%B4-blue?style=for-the-badge" alt="Ver simulación en YouTube">
  </a>
</p>

### 🛰️ Descripción del contenido de la simulación
**Simulación completa en RobotStudio** de la estación **ABB IRB 140 / IRC5**, que refleja la lógica usada en el laboratorio:

- **Estación y referencia**: carga del proyecto `.rspag`, sistema mecánico y **WObj** del área de trabajo.
- **Herramienta**: definición de **Tooldata** (marcador) y verificación de **TCP** contra geometría.
- **Puntos y trayectorias**: definición/edición de *targets*; ejecución con **MoveJ/MoveL/MoveC**; zonas y velocidades.
- **Secuenciador**: rutina `main` con **HOME**, ejecución de letras y decoración, y retorno seguro.
- **IO digitales**: simulación de **DI/DO** para inicio, luz indicadora y control de banda (variador simulado).
- **Replicación de trazos**: misma secuencia en cuadrantes equivalentes del **WObj** (consistencia geométrica).
- **Pruebas y validación**: vista de trayectorias, tiempos de ciclo y comprobación de colisiones.

> Consejo: si la miniatura `maxresdefault.jpg` no carga en tu README, cambia la URL de la imagen a `hqdefault.jpg`.

---
