# Prototipo de Órtesis Robótica para Rehabilitación de Miembro Inferior (TT2)

Este repositorio contiene la documentación técnica, el código fuente de control y los archivos de diseño asociados al desarrollo del **Trabajo Terminal II** para la obtención del título de **Ingeniero en Mecatrónica**.

El proyecto consiste en una órtesis robótica automatizada de dos grados de libertad (Flexión-Extensión de rodilla y Abducción-Aducción de cadera) controlada mediante una interfaz HMI.

---

## Institución

**Instituto Politécnico Nacional (IPN)**
**Unidad Profesional Interdisciplinaria en Ingeniería y Tecnologías Avanzadas (UPIITA)**

* **Proyecto:** Trabajo Terminal II (TT2)
* **Periodo:** 2025

<p align="center">
  <img src="logos/ipn_trans.pdf" alt="Logo IPN" width="100"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="logos/logoupiita.pdf" alt="Logo UPIITA" width="100"/>
</p>

---

## Equipo de Desarrollo

**Integrantes:**
* Baldera Reyes Diego Esaú
* Martínez Maldonado Sebastián
* Piña Hernández Alberto
* Ramirez Sabino Luis Enrique

---

## Documentación y Edición (LaTeX/Overleaf)

Este proyecto utiliza **LaTeX** para la generación de la memoria técnica y la documentación formal. El repositorio está configurado para sincronizarse y facilitar la edición colaborativa.

* **Estructura:** El archivo principal es `main.tex`.
* **Integración:** Este repositorio sirve como puente para la edición en **Overleaf**.
    * La rama `main` contiene la versión estable y actual del documento (anteriormente rama `tt2`).
    * La rama `backup` contiene el historial previo (anteriormente rama `main`).
* **Compilación:** Se utilizan paquetes personalizados ubicados en la carpeta `configuracion/` (e.g., `upiitatesis.sty`).

---

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera para separar la documentación del código y los recursos:

```text
├── capitulos/              # Archivos .tex con el contenido de cada capítulo
│   ├── tt1/                # Capítulos correspondientes al Diseño (TT1)
│   └── tt2/                # Capítulos de Implementación y Pruebas (TT2)
├── configuracion/          # Estilos .sty y configuraciones de LaTeX
├── figure/                 # Imágenes, diagramas y planos
│   ├── s1_estructural/     # Fotos y renders de la estructura mecánica
│   ├── s4_energía/         # Diagramas eléctricos y fotos de fuentes
│   ├── s7_control/         # Diagramas de flujo y esquemáticos
│   ├── pantallas_interfaz/ # Capturas de la GUI
│   └── planos_manufactura/ # PDFs de planos para maquinado
├── preliminares/           # Portada, resumen, agradecimientos, etc.
├── styles.py               # Hoja de estilos para la GUI
├── main.tex                # Archivo maestro de LaTeX
└── README.md               # Este archivo

```

## Tecnologías Implementadas
 **Hardware:**
* Raspberry Pi 4 (Procesamiento Central)
* Motores Nema 34 (con reducción 10:1) y Nema 23
* Drivers HSS86 y HSS57 (Lazo cerrado)
* Fuentes Conmutadas Mean Well (48V, 24V)

**Software:**
* **Lenguaje:** Python 3
* **Interfaz Gráfica:** PyQt5
* **Control de Motores:** Librería `pigpio` (Generación de pulsos por hardware)


* **Documentación:** LaTeX

---

## Estado del ProyectoActualmente, el proyecto se encuentra en la fase final de **Implementación y Pruebas (TT2)**.

* ✅ Estructura mecánica ensamblada y validada.
* ✅ Sistema de energía con topología de seguridad implementada.
* ✅ Algoritmos de control de movimiento funcional.
* ✅ Interfaz HMI operativa.
* 🔄 Redacción final del reporte y análisis de costos en proceso.

---

> *Este proyecto es de carácter académico y propiedad intelectual de los autores y del Instituto Politécnico Nacional.*