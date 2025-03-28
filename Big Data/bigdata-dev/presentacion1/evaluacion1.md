# Evaluación 1 Caso 4 : Salud – Diagnóstico Asistido por IA en Hospital Público

Entrega de proyecto : 16/04/2025 21:10 hrs

## Contexto

El **Hospital San Juan** recibe 500 radiografías diarias y enfrenta:

1. Demora en diagnosticos (hasta 72 horas para resultados).
2. Errores humanos en detección temprana de neumonía.

### Datos disponibles

- Imágenes (rayos X de tórax).
- Historiales clínicos (texto libre con síntomas).
- Registros de diagnósticos pasados (correctos/incorrectos).

### StakeHolder

- Médicos radiólogos: Quieren apoyo en diagnósticos urgentes.
- Administración del hospital: Necesita reducir costos de retrasos.
- Pacientes: Esperan resultados más rápidos y precisos.

### Preguntas clave

**¿Cómo entrenar un modelo de Computer Vision con imágenes médicas?**
**¿Qué métricas usar para validar la precisión del modelo (ej: recall para evitar falsos negativos)?**
**¿Cómo integrar el sistema con el software legacy del hospital?**

### Instrucciones generales:

- Formato de entrega: Informe técnico (máx. 10 páginas) + presentación de 10 minutos.
- Requisitos técnicos: Justificar cada herramienta de GCP (ej: "Usamos BigQuery por su escalabilidad con datos estructurados")
- Entrega de justificación de por qué este es un proyecto de Big Data (qué condiciones cumple para considerarlo como tal).
- Objetivos a cumplir desde el punto de vista técnico
- Propuesta de arquitectura, especificar herramientas que se deben utilizar y cuáles no, justificándolas
- Propuesta para establecer un “gobierno de datos”
- Asociar la problemática a una arquitectura de referencia indicando elementos que pueden faltar o no ser requeridos.

---

### Links o recursos que se utilizarán para trabajar con el proyecto

- [Informe Word Drive](https://docs.google.com/document/d/1fYen3eX8xAYZzkzhBPpkCiP5DQIlwv52tCy4pYlnrYM/edit?tab=t.0#heading=h.cbbhtn70u1wl)
- [Google Cloud Skills Boost](https://www.cloudskillsboost.google/?locale=es) Cada vez que uses esta herramienta en Google Cloud Console, debemos entrar con una ventana en incognito y entrar con el usuario y password que te dan.
- [Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning](<https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5>)
- [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- [3rd place solution for the 2018 RSNA Pneumonia Detection Challenge](https://github.com/pmcheng/rsna-pneumonia)
- [Pneumonia-Diagnosis-using-XRays-96-percent-Recall](https://github.com/deadskull7/Pneumonia-Diagnosis-using-XRays-96-percent-Recall)
- [EfficientNet](https://paperswithcode.com/method/efficientnet)
- [¿Qué es el método Grad-CAM](https://datascientest.com/es/que-es-el-metodo-grad-cam)

### Desarrollo

Se realizaron modificaciones en el informe hoy 25/03/2025, gracias a buscar información y referencias (hubo uso de IA para entender mejor ciertas herramientas y modos de trabajo).
