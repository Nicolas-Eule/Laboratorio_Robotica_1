# 🎬 Videos del Laboratorio – Robótica Industrial

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=2400&pause=900&color=00E5FF&center=true&vCenter=true&width=900&repeat=true&lines=Aqu%C3%AD+puedes+visualizar%3A;Video+de+la+pr%C3%A1ctica+(laboratorio);Video+de+la+simulaci%C3%B3n+(RobotStudio)" alt="Animación videos">
</p>

---

## 📌 Video de la práctica (laboratorio)

<p align="center">
  <a href="https://youtu.be/gwcXK-_C6pA?si=X1zZq3yhsR2akUh2">
    <img src="https://img.youtube.com/vi/gwcXK-_C6pA/hqdefault.jpg" alt="Ver video de la práctica" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/gwcXK-_C6pA?si=X1zZq3yhsR2akUh2">
    <img src="https://img.shields.io/badge/Ver%20en%20YouTube-%F0%9F%94%B4-red?style=for-the-badge" alt="Ver en YouTube">
  </a>
</p>

### 🧩 Descripción (práctica)
**Grabación real en laboratorio** ejecutando la secuencia programada en RAPID sobre un **ABB IRB 140 / IRC5**:
- **Homing** y verificación de **TCP/Tooldata** del marcador.
- Selección de **WorkObject** (superficie de decorado) y parámetros de movimiento.
- Disparo por **DI_01** → inicio de rutina; **MOVL/MOVC** para letras y logotipo.
- **DO_01** (luz indicadora) y **DO_02** (variador/banda) según estado.
- **Retorno a HOME** al finalizar y **pose de mantenimiento** por **DI_02**.

---

## 🧪 Video de la simulación (RobotStudio)

<p align="center">
  <a href="https://youtu.be/w56WQL795BM">
    <img src="https://img.youtube.com/vi/w56WQL795BM/hqdefault.jpg" alt="Ver video de la simulación en RobotStudio" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/w56WQL795BM">
    <img src="https://img.shields.io/badge/Ver%20en%20YouTube-%F0%9F%94%B4-blue?style=for-the-badge" alt="Ver en YouTube">
  </a>
</p>

### 🧩 Descripción (simulación)
**Simulación en RobotStudio** de la misma célula y lógica:
- **Estación** con IRB 140, herramienta tipo marcador y **banda transportadora**.
- **Tooldata/TCP**: calibración/ajuste del extremo de herramienta (comparación con CAD).
- **WorkObjects**: definición del plano de trabajo sobre la “torta/caja”.
- **Trayectorias**: generación de letras y logotipo con **MoveL / MoveC**; suavizado con **zonas (z10)** y **velocidades (v100–v1000)**.
- **I/O virtuales**: prueba de **DI_01/DI_02** y **DO_01/DO_02** (luz y banda).
- **Mensajería** en FlexPendant (TPWrite) y **retorno a HOME** para fin de ciclo.

> Consejo: si la miniatura no carga en alta resolución, cambia `hqdefault.jpg` por `maxresdefault.jpg`.
