<!-- ✦✦✦ FUTURE IS AUTOMATED ✦✦✦ -->
<!-- Banner superior “neón” -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:04041A,50:14213D,100:0A4D68&text=Laboratorio%20Rob%C3%B3tica%201&fontColor=E0FBFC&fontAlign=50&fontAlignY=30&desc=Decoraci%C3%B3n%20de%20Tortas%20Virtuales%20%E2%80%A2%20ABB%20IRB%20140%20%E2%80%A2%20RAPID&descAlign=50&descAlignY=60" alt="header" />
</p>

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

## ⚙️ Estructura


---

## 🧠 Lógica de operación (fragmento ilustrativo RAPID)

```rapid
MODULE Module1
  PROC main()
    TPErase;
    TPWrite "Iniciando rutina";
    Reset Conveyor_FWD;  ! Asegurar banda apagada

    WHILE TRUE DO
      IF DI_01 = 1 THEN
        TPWrite "Decorando pastel virtual";
        Path_10;
        SetDO LuzIndicadora, 1;
        WaitTime 2;
        ResetDO LuzIndicadora;
      ENDIF

      IF DI_02 = 1 THEN
        TPWrite "Modo mantenimiento";
        MoveAbsJ home, v500, fine, tool0;
      ENDIF
    ENDWHILE
  ENDPROC
ENDMODULE


<p align="center">
  <img src="https://raw.githubusercontent.com/TU_USUARIO_GITHUB/TU_USUARIO_GITHUB/output/github-contribution-grid-snake.svg" alt="snake">
</p>
