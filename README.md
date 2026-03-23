<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/banners/header-dark.svg" width="100%"/>

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-dark.svg" width="100%"/>

<p align="center">
  <a href="https://ulogix-team.github.io"><img src="https://img.shields.io/badge/Sitio_Web-ulogix--team.github.io-000000?style=flat-square"/></a>
  &nbsp;
  <img src="https://img.shields.io/badge/APM_2026--1-UNAL-000000?style=flat-square"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Línea_de_Bebidas-FEMSA-000000?style=flat-square"/>
</p>

# ulogix-team

Repositorio principal del equipo Ulogix para el **Proyecto Integrador del curso Automatización de Procesos de Manufactura (APM) 2026-1**, Universidad Nacional de Colombia. Contiene la información general del proyecto, integrantes, flujo de trabajo y cronograma.

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Descripción del Proyecto

Línea automatizada de alto volumen de producción de bebidas **FEMSA / Coca-Cola**, que fabrica tres productos diferenciados en envases de bajo, medio y gran volumen. La solución integra:

- Arquitectura de automatización **ISA-95** (niveles 1–4)
- Control lógico-secuencial **PLC** (Studio 5000 / Logix Emulate)
- Celda robotizada **ABB** (RobotStudio)
- Gemelo digital (**Siemens NX** / Digital Factory)
- Supervisión **SCADA** (Ignition + OPC-UA)
- Análisis de producción y **OEE**
- Análisis técnico-económico (VPN, TIR, flujo de caja)
- MES con **Power BI** y analítica en Python

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Integrantes del Equipo

| Nombre | Correo | GitHub | Rol | Supervisa | Supervisado por |
|---|---|:---:|---|---|---|
| Andrés Mauricio Morales Martínez | amoralesma@unal.edu.co | [@mora200217](https://github.com/mora200217) | Arquitectura de Red | RobotStudio | Andrés F. Quenan |
| Andrés Felipe Quenan Pozo | aquenan@unal.edu.co | [@Andres-Felipe-Quenan](https://github.com/Andres-Felipe-Quenan) | Robótica / RobotStudio | Arquitectura de Red | Andrés M. Morales |
| Juan José Díaz Guerrero | judiazgu@unal.edu.co | [@Judiazgu](https://github.com/Judiazgu) | PLC / Programación | SCADA / HMI / MES | Juan F. Triana |
| Juan Manuel Beltrán Botello | jbeltranbo@unal.edu.co | [@JuanBeltran2024](https://github.com/JuanBeltran2024) | NX / Digital Factory | Planeación de Proceso | Samuel D. Sanchez |
| Jorge Nicolas Garzón Acevedo | jngarzona@unal.edu.co | [@Nicolas-Eule](https://github.com/Nicolas-Eule) | Planeación de Proceso | Finanzas | Juan M. Beltrán |
| Samuel David Sanchez Cardenas | samsanchezca@unal.edu.co | [@samsanchezcar](https://github.com/samsanchezcar) | Finanzas | NX / Digital Factory | Jorge N. Garzón |
| Juan Felipe Triana Aguilera | jutrianaa@unal.edu.co | [@jutrianaa](https://github.com/jutrianaa) | SCADA / HMI / MES | PLC / Programación | Juan J. Díaz |

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Profesores Supervisores

| Nombre | Correo |
|---|---|
| Carlos Julio Cortés | cjcortesr@unal.edu.co |
| Luis Miguel Méndez | lmmendezm@unal.edu.co |
| Víctor Hugo Grisales Palacio | vhgrisalesp@unal.edu.co |
| Ricardo Ramírez Heredia | reramirez@unal.edu.co |
| Ubaldo García | ugarciaz@unal.edu.co |
| Eduardo Barrera Gualdron | ebarrerag@unal.edu.co |

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Repositorios del Proyecto

| Repositorio | Descripción | Responsables |
|---|---|---|
| [ulogix-team](https://github.com/ulogix-team/ulogix-team) | Información general, integrantes, flujo de trabajo | Todos |
| [assets](https://github.com/ulogix-team/assets) | Identidad visual, logos SVG, banners, divisores | Todos |
| [ulogix-manufacturing](https://github.com/ulogix-team/ulogix-manufacturing) | Proceso, planta, NX, gemelo digital, Studio 5000, RobotStudio | Beltrán, Quenan, Morales, Díaz, Garzón |
| [ulogix-team.github.io](https://github.com/ulogix-team/ulogix-team.github.io) | Sitio web del proyecto | Todos |
| [ulogix-data-finance](https://github.com/ulogix-team/ulogix-data-finance) | OEE, tiempos, análisis financiero, Power BI | Garzón, Sanchez, Triana |
| [ulogix-scada-control](https://github.com/ulogix-team/ulogix-scada-control) | SCADA, HMI, Ladder, OPC-UA | Triana, Díaz, Morales |

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Flujo de Trabajo

```
main ──────────────────────────────────────► producción estable
  │
  └── develop ────────────────────────────► integración continua
        ├── feature/arquitectura-red
        ├── feature/robotstudio
        ├── feature/plc-ladder
        ├── feature/gemelo-digital
        ├── feature/scada-hmi
        ├── feature/oee-simulacion
        └── feature/financiero
```

**Convención de commits:** `tipo(módulo): descripción`

```
feat(plc): agregar lógica Grafcet producto A
fix(scada): corregir comunicación OPC
docs(proceso): actualizar VSM línea 2
```

Todo Pull Request requiere al menos una aprobación del compañero que supervisa el área.

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Cronograma

| Semana | Módulo | Entregable |
|---|---|---|
| 1–4 | Introducción a la Automatización | Arquitectura ISA-95, P&ID, instrumentación |
| 5–6 | Gestión y Evaluación de Producción | VSM, OEE, Takt time, simulación |
| 7 | Planeación y Evaluación de Proyectos | EDT, presupuesto, análisis financiero |
| **8** | **Entrega Semana 8** | **GitHub + Web + YouTube (≥30 min)** |
| 9–10 | Celda de Manufactura Robotizada | RobotStudio, análisis de riesgos |
| 11–12 | Digital Factory & Controladores | NX, Grafcet, Ladder, Logix Emulate |
| 13–14 | SCADA & Integración | Ignition, OPC-UA, integración gemelo |
| **15** | **Entrega Semana 15** | **Entrega final completa** |

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section-dark.svg" width="100%"/>

## Subcarpetas

- [`actas/`](actas/) — Actas de reunión del equipo
- [`cronograma/`](cronograma/) — Cronograma detallado y seguimiento
- [`flujo-trabajo/`](flujo-trabajo/) — Guía de flujo de trabajo Git

<img src="https://raw.githubusercontent.com/ulogix-team/assets/main/banners/footer-dark.svg" width="100%"/>
