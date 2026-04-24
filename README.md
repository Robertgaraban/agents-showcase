# IntegraciÃ³n de Agentes IA â HydroAbyss & ABYSS STCW

**HydroAbyss Technology and Innovation**  
Agentes de IA especializados integrados en sistemas de formaciÃ³n marÃ­tima en producciÃ³n

---

## Â¿QuÃ© es esto?

Agentes de IA con personalidad, flujo de trabajo y entregables definidos, adaptados al dominio marÃ­timo y operando dentro de los sistemas **HydroAbyss** y **ABYSS STCW** en producciÃ³n real.

No son prompts genÃ©ricos. Son agentes especializados con conocimiento del marco regulatorio STCW, DGMM y DPC, con flujos de trabajo especÃ­ficos para cada tarea del dominio y reglas de dominio no negociables.

---

## Sistemas donde operan

| Sistema | Rol de los agentes |
|---|---|
| **Generador de Manuales HydroAbyss** | GeneraciÃ³n, normalizaciÃ³n y auditorÃ­a de manuales STCW |
| **ABYSS STCW** | Tareas de gestiÃ³n acadÃ©mica, control de calidad, procesamiento de contenido |
| **HydroAbyss** | AutomatizaciÃ³n de procesos operativos de la escuela |

---

## Arquitectura de integraciÃ³n

```
Sistema (HydroAbyss / ABYSS STCW)
â
âââ .agent/
â   âââ AGENT.md              â Contexto, reglas y conocimiento del sistema
â   âââ skills/
â       âââ generar_manual/
â       â   âââ SKILL.md      â Flujo: ingesta â compilaciÃ³n â QA
â       âââ [otras skills]/
â
âââ scripts/                  â Pipeline determinista (Python / Bash)
âââ docs/
    âââ PROMPT_MAESTRO_*.md   â Prompts estÃ¡ndar por tarea recurrente
```

---

## Agentes especializados (dominio marÃ­timo)

| Agente | Especialidad adaptada |
|---|---|
| Backend Architect | Arquitectura PHP/Node + dominio marÃ­timo |
| Technical Writer | DocumentaciÃ³n tÃ©cnica normativa STCW |
| Database Optimizer | MySQL/PostgreSQL con datos de historial marÃ­timo |
| Security Engineer | Datos sensibles de alumnos y certificaciones |
| Evidence Collector | QA visual y paridad de reportes DPC |
| Reality Checker | Gate de calidad antes de publicar a producciÃ³n |

Cada agente tiene reglas de dominio marÃ­timo incorporadas: no puede ignorar la paridad normativa DPC, no puede proponer cambios que rompan el histÃ³rico, y conoce la diferencia entre el dominio espaÃ±ol (DGMM) y el brasileÃ±o (DPC).

---

## Por quÃ© agentes y no solo scripts

Los scripts automatizan lo determinista. Los agentes cubren lo que requiere criterio: estructurar un capÃ­tulo manteniendo coherencia con el manual, identificar mÃ³dulos activos vs. cÃ³digo huÃ©rfano, o evaluar si un cambio preserva paridad con los reportes DPC.

**Pipeline determinista para lo repetible + agente para lo que requiere juicio.**

---

## Estado de producciÃ³n

| IntegraciÃ³n | Estado |
|---|---|
| Generador de Manuales â skill `generar_manual` | â En producciÃ³n |
| HydroAbyss â `AGENT.md` con contexto del sistema | â En producciÃ³n |
| ABYSS STCW â agentes especializados adaptados | â En producciÃ³n |
| Prompts maestros por tarea recurrente | â En producciÃ³n |

---

## Acceso

Brief tÃ©cnico pÃºblico. Definiciones completas en repositorios privados de cada sistema.

Solicitar acceso: **robertgaraban@gmail.com** â Asunto: `[RevisiÃ³n tÃ©cnica] Agentes IA HydroAbyss / STCW`

---

*HydroAbyss Technology and Innovation â FormaciÃ³n marÃ­tima profesional*