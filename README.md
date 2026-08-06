# SGCV-IA — Sistema de Gestión para Clínicas Veterinarias con Inteligencia Artificial

Proyecto Fin de Curso — Ingeniería de Requisitos (ISR-401), UTEQ, 4to "A", 2026.
Práctica Experimental Unidad IV (PE4): Validación, Gestión de Requisitos y Herramientas CASE.

## Integrantes

| Nombre | Rol |
|---|---|
| [NOMBRE INTEGRANTE A] | Bloque A — Inspección Fagan y Fundamento teórico 3.1–3.3 |
| [NOMBRE INTEGRANTE B] | Bloque B — Gestión del cambio (CCB) y RFC |
| Danela Arteaga | Bloque C — Líder del equipo · Trazabilidad y Configuración (CASE + Git) |

## Descripción del sistema

SGCV-IA centraliza la gestión clínica, administrativa y de inventario de clínicas
veterinarias, incorporando un módulo de asistencia diagnóstica mediante Inteligencia
Artificial (siempre sujeto a validación explícita del veterinario).

## Estructura de carpetas

```
01_ERS/            ERS_v1.0.pdf, ERS_v1.1.pdf, fuentes .tex
02_Inspeccion/      Anexo A (checklists), Anexo B (registro de defectos), métricas
03_CCB/             RFC-01, RFC-02, RFC-03, Acta del CCB
04_Trazabilidad/    Matriz de trazabilidad, export del tablero CASE (Trello), capturas
05_Informe/         Informe PE4 en LaTeX (.tex, .bib, .pdf), figuras
06_Evidencias/      Capturas de Git, fotos de la sesión, declaración de uso de IA
```

## Herramienta CASE utilizada

Trello — tablero "SGCV-IA" con 5 listas (Backlog, Análisis, Aprobado, Desarrollo, Hecho),
23 tarjetas (una por requisito funcional), prioridad MoSCoW mediante Etiquetas nativas,
y trazabilidad (fuente, caso de uso, clase, prueba) documentada en la Descripción de
cada tarjeta.

## Instrucciones de compilación del informe (PE4_U4_APELLIDO1_APELLIDO2.pdf)

Compilador: [PDFLATEX / XELATEX — confirma cuál usa tu plantilla]

```bash
cd 05_Informe
pdflatex PE4_U4_APELLIDO1_APELLIDO2.tex
bibtex PE4_U4_APELLIDO1_APELLIDO2
pdflatex PE4_U4_APELLIDO1_APELLIDO2.tex
pdflatex PE4_U4_APELLIDO1_APELLIDO2.tex
```

Dependencias: distribución LaTeX (MiKTeX o TeX Live) con los paquetes estándar de
artículo académico (no se requieren paquetes adicionales fuera de los incluidos en
una instalación completa).

Archivo principal: `05_Informe/PE4_U4_APELLIDO1_APELLIDO2.tex`

## Línea base

Ver tag `baseline-v1.1` y `CHANGELOG.md` para el historial de cambios aprobados por el CCB.
