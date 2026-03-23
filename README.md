<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/banners/header-banner.svg" alt="Ulogix Banner" width="100%"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-main.svg" width="100%"/>
</p>

<p align="center">
  <a href="https://ulogix-team.github.io"><img src="https://img.shields.io/badge/Sitio%20Web-ulogix--team.github.io-7C3AED?style=flat-square&logo=github"/></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Curso-APM%202026--1-a855f7?style=flat-square"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Universidad-UNAL-7C3AED?style=flat-square"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Proceso-Línea%20de%20Bebidas-0e0525?style=flat-square"/>
</p>

# Ulogix — Automatización de Procesos de Manufactura

Equipo de trabajo para el **Proyecto Integrador** del curso **Automatización de Procesos de Manufactura (APM) 2026-1**, Universidad Nacional de Colombia. Diseñamos, simulamos y validamos una línea automatizada de alto volumen de producción de bebidas, integrando control lógico-secuencial, robótica, gemelo digital, SCADA y análisis financiero.

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 🏭 Descripción del Proyecto

La solución propuesta corresponde a una **línea automatizada de bebidas** que fabrica al menos tres productos diferenciados (agua, bebida energética y jugo) en envases de bajo, medio y gran volumen. El sistema integra:

- Arquitectura ISA-95 con PLC (Studio 5000 / Logix Emulate)
- Celda robotizada (RobotStudio)
- Gemelo digital (NX / Digital Factory)
- Supervisión SCADA (Ignition + OPC)
- Análisis de producción y OEE
- Análisis técnico-económico y propuesta de valor

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 👥 Integrantes del Equipo

| Foto | Nombre | Rol | GitHub | Correo | Supervisa | Supervisado por |
|:---:|---|---|:---:|---|---|---|
| — | **Andrés M. Morales Martínez** | Arquitectura de Red | [@mora200217](https://github.com/mora200217) | amoralesma@unal.edu.co | RobotStudio | Andrés F. Quenan |
| — | **Andrés F. Quenan Pozo** | Robótica / RobotStudio | [@Andres-Felipe-Quenan](https://github.com/Andres-Felipe-Quenan) | aquenan@unal.edu.co | Arquitectura de Red | Andrés M. Morales |
| — | **Juan José Díaz Guerrero** | PLC / Programación | [@Judiazgu](https://github.com/Judiazgu) | judiazgu@unal.edu.co | SCADA / HMI / MES | Juan F. Triana |
| — | **Juan Manuel Beltrán Botello** | NX / Digital Factory | [@JuanBeltran2024](https://github.com/JuanBeltran2024) | jbeltranbo@unal.edu.co | Planeación y Manufactura | Samuel D. Sánchez |
| — | **Jorge N. Garzón Acevedo** | Planeación de Proceso | [@Nicolas-Eule](https://github.com/Nicolas-Eule) | jngarzona@unal.edu.co | Finanzas | Juan M. Beltrán |
| — | **Samuel D. Sánchez Cardenas** | Finanzas | [@samsanchezcar](https://github.com/samsanchezcar) | samsanchezca@unal.edu.co | NX / Digital Factory | Jorge N. Garzón |
| — | **Juan Felipe Triana Aguilera** | SCADA / HMI / MES | [@jutrianaa](https://github.com/jutrianaa) | jutrianaa@unal.edu.co | PLC / Programación | Juan J. Díaz |

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 👨‍🏫 Profesores Supervisores

| Nombre | Correo |
|---|---|
| Carlos Julio Cortés | cjcortesr@unal.edu.co |
| Luis Miguel Méndez | lmmendezm@unal.edu.co |
| Víctor Hugo Grisales Palacio | vhgrisalesp@unal.edu.co |
| Ricardo Ramírez Heredia | reramirez@unal.edu.co |
| Ubaldo García | ugarciaz@unal.edu.co |
| Eduardo Barrera Gualdron | ebarrerag@unal.edu.co |

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 🗂️ Repositorios del Proyecto

| Repositorio | Descripción | Responsable principal |
|---|---|---|
| [ulogix-team](https://github.com/ulogix-team/ulogix-team) | Información general, integrantes, flujo de trabajo | Todos |
| [assets](https://github.com/ulogix-team/assets) | Identidad visual, logos SVG, banners, divisores | Todos |
| [ulogix-manufacturing](https://github.com/ulogix-team/ulogix-manufacturing) | Proceso, planta, NX, gemelo digital, Studio 5000 | Beltrán, Quenan, Morales, Díaz |
| [ulogix-team.github.io](https://github.com/ulogix-team/ulogix-team.github.io) | Página web del proyecto | Todos |
| [ulogix-data-finance](https://github.com/ulogix-team/ulogix-data-finance) | OEE, tiempos, análisis financiero, Power BI | Garzón, Sánchez |
| [ulogix-scada-control](https://github.com/ulogix-team/ulogix-scada-control) | SCADA, HMI, PLC Ladder, Ignition, OPC | Triana, Díaz |

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 🔄 Flujo de Trabajo

```
main ──────────────────────────────────────────► producción estable
  │
  ├── develop ──────────────────────────────────► integración continua
  │     │
  │     ├── feature/arquitectura-red
  │     ├── feature/robotstudio
  │     ├── feature/plc-ladder
  │     ├── feature/gemelo-digital
  │     ├── feature/scada-hmi
  │     ├── feature/oee-simulacion
  │     └── feature/financiero
```

**Convención de commits:** `tipo(módulo): descripción breve`

- `feat(plc): agregar lógica Grafcet producto A`
- `fix(scada): corregir comunicación OPC`
- `docs(proceso): actualizar VSM línea 2`

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 📅 Cronograma General

| Semana | Módulo | Entregable |
|---|---|---|
| 1–4 | Introducción a la Automatización | Arquitectura ISA-95, P&ID |
| 5–6 | Gestión y Evaluación de Producción | VSM, OEE, Takt time |
| 7–8 | **Entrega Semana 8** | GitHub + Web + YouTube (≥30 min) |
| 9–10 | Celdas Robóticas | RobotStudio, análisis de riesgos |
| 11–12 | Digital Factory & Controladores | NX, Grafcet, Ladder, Logix Emulate |
| 13–14 | SCADA & Planeación Económica | Ignition, OPC, flujo de caja |
| 15 | **Entrega Semana 15** | Entrega final completa |

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/dividers/divider-section.svg" width="100%"/>
</p>

## 🔗 Links del Proyecto

- 🌐 **Sitio web:** [ulogix-team.github.io](https://ulogix-team.github.io)
- 📁 **Organización GitHub:** [github.com/ulogix-team](https://github.com/ulogix-team)
- 🎥 **YouTube:** _(próximamente)_

<p align="center">
  <img src="https://raw.githubusercontent.com/ulogix-team/assets/main/banners/footer-banner.svg" width="100%"/>
</p>
