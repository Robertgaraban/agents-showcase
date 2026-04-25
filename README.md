# 🤖 Integración de Agentes IA — HydroAbyss & ABYSS STCW

<div align="center">

**HydroAbyss Technology and Innovation**

*Agentes de IA especializados integrados en sistemas de formación marítima en producción*

![Estado](https://img.shields.io/badge/estado-producción-brightgreen)
![Dominio](https://img.shields.io/badge/dominio-marítimo-blue)
![Marco](https://img.shields.io/badge/marco-STCW%20%7C%20DGMM%20%7C%20DPC-orange)

</div>

---

## ¿Qué es esto?

Agentes de IA con personalidad, flujo de trabajo y entregables definidos, adaptados al dominio marítimo y operando dentro de los sistemas **HydroAbyss** y **ABYSS STCW** en producción real.

> **No son prompts genéricos.** Son agentes especializados con conocimiento del marco regulatorio STCW, DGMM y DPC, con flujos de trabajo específicos para cada tarea del dominio y reglas de dominio no negociables.

---

## 🖥️ Sistemas donde operan

| Sistema | Rol de los agentes |
|---|---|
| **Generador de Manuales HydroAbyss** | Generación, normalización y auditoría de manuales STCW |
| **ABYSS STCW** | Tareas de gestión académica, control de calidad, procesamiento de contenido |
| **HydroAbyss** | Automatización de procesos operativos de la escuela |

---

## 🏗️ Arquitectura de integración

```
Sistema (HydroAbyss / ABYSS STCW)
│
├── .agent/
│   ├── AGENT.md              → Contexto, reglas y conocimiento del sistema
│   └── skills/
│       ├── generar_manual/
│       │   └── SKILL.md      → Flujo: ingesta → compilación → QA
│       └── [otras skills]/
│
├── scripts/                  → Pipeline determinista (Python / Bash)
└── docs/
    └── PROMPT_MAESTRO_*.md   → Prompts estándar por tarea recurrente
```

---

## 🧠 Agentes especializados (dominio marítimo)

| Agente | Especialidad adaptada |
|---|---|
| **Backend Architect** | Arquitectura PHP/Node + dominio marítimo |
| **Technical Writer** | Documentación técnica normativa STCW |
| **Database Optimizer** | MySQL/PostgreSQL con datos de historial marítimo |
| **Security Engineer** | Datos sensibles de alumnos y certificaciones |
| **Evidence Collector** | QA visual y paridad de reportes DPC |
| **Reality Checker** | Gate de calidad antes de publicar a producción |

Cada agente tiene reglas de dominio marítimo incorporadas: no puede ignorar la paridad normativa DPC, no puede proponer cambios que rompan el histórico, y conoce la diferencia entre el dominio español (DGMM) y el brasileño (DPC).

---

## ⚡ Por qué agentes y no solo scripts

Los scripts automatizan lo determinista. Los agentes cubren lo que requiere criterio: estructurar un capítulo manteniendo coherencia con el manual, identificar módulos activos vs. código huérfano, o evaluar si un cambio preserva paridad con los reportes DPC.

> **Pipeline determinista para lo repetible + agente para lo que requiere juicio.**

---

## ✅ Estado de producción

| Integración | Estado |
|---|---|
| Generador de Manuales — skill `generar_manual` | ✅ En producción |
| HydroAbyss — `AGENT.md` con contexto del sistema | ✅ En producción |
| ABYSS STCW — agentes especializados adaptados | ✅ En producción |
| Prompts maestros por tarea recurrente | ✅ En producción |

---

## 📬 Acceso

Brief técnico público. Definiciones completas en repositorios privados de cada sistema.

Solicitar acceso: **robertgaraban@gmail.com** → Asunto: `[Revisión técnica] Agentes IA HydroAbyss / STCW`

---

<div align="center">

*HydroAbyss Technology and Innovation — Formación marítima profesional*

</div>
