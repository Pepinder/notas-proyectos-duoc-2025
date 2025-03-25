---
geometry:
  - margin=1in
  - a4paper
fontsize: 11pt
documentclass: article
lang: es
---

# Sistema de gestión de basura inteligente

La Municipalidad de San Joaquín ha decidido implementar un Sistema de Gestión de Basura Inteligente para optimizar la recolección de residuos en la comuna. El proyecto consiste en la instalación de sensores IoT en contenedores de basura pública, que enviarán datos en tiempo real sobre su nivel de llenado a un software de monitoreo. Esta información permitirá a las empresas recolectoras (externas, contratadas por la municipalidad) ajustar sus rutas de recolección y mejorar la eficiencia del servicio.

## Objetivos del proyecto

- Reducir la acumulación de basura y mejorar la limpieza de la comuna.
- Optimizar la frecuencia y rutas de recolección para reducir costos y tiempos.
- Disminuir la contaminación y el tráfico generado por camiones recolectores

Como alumno, debo aplicar los pasos de la gestión de riesgos para analizar los posibles problemas y proponer estrategias para mitigarlas.

### Entregables

1. Análisis de riesgos, identificando factores internos y externos.
2. Matriz de riesgos, evaluando la probabilidad e impacto de cada uno.
3. Estrategias de mitigación para los riesgos críticos.
4. Indicadores de monitoreo, para evaluar la efectividad del sistema.

---

## Desarrollo

### 1. Análisis de riesgos, identificando posibles riesgos

1. Fallos en sensores IoT, mal funcionamiento o daño físico
2. Ciberseguridad: Vulnerar el sistema de los contenedores de basura, hackeo y/o manipulación de datos
3. Problemas de conectividad : Fallas en red de comunicación, cabe decir que aqui justo la señal en esta zona es muy mala.
4. Vandalismo: Daño intencional a los contenedores IoT
5. Falta de adopción ciudadana: Desconocimiento o resistencia al cambio.

### 2.1 Matriz de riesgos.

| Riesgos                     | Causa                                    | Problema central                           | Efecto                                                      | Probabilidad | Impacto |
| --------------------------- | ---------------------------------------- | ------------------------------------------ | ----------------------------------------------------------- | ------------ | ------- |
| Fallos en sensores IoT      | Mal funcionamiento técnico o daño físico | Datos incorrectos sobre niveles de llenado | Rutas de recolección ineficientes, contenedores desbordados | B            | A       |
| Ciberseguridad              | Vulnerabilidades en el sistema IoT       | Hackeo o manipulación de datos             | Interrupción del servicio, información errónea              | B            | A       |
| Problemas de conectividad   | Fallas en red de comunicación            | Datos no transmitidos en tiempo real       | Decisiones basadas en información desactualizada            | M            | M       |
| Vandalismo                  | Daño intencional a sensores/contenedores | Equipos destruidos o inutilizables         | Costos de reparación, interrupción del servicio             | M            | A       |
| Falta de adopción ciudadana | Desconocimiento o resistencia al cambio  | Uso incorrecto de contenedores             | Datos inconsistentes, sistema menos efectivo                | A            | M       |

### 2.2 Evaluación de riesgos

Los riesgos mas críticos a priorizar son:

- Problemas de conectividad (Probabilidad M, Impacto A)
- Ciberseguridad (Probabilidad A, Impacto M)
- Falta de adopción ciudadana (Probabilidad A, Impacto M)

### 3. Estrategias de mitigación

- Problemas de conectividad:
  - Reducir: Sistema con multiples proovedores de conectividad (buscando distintas empresas que nos conecten, Movistar, Entel, Claro, etc.)
  - Aceptar: Tener un sistema de almacenamiento local temporal para cuando falle la conectividad.
- Fallos en sensores IoT:
  - Reducir: Realizar mantenimiento preventivo y calibración periódica.
  - Compartir: Contrato con proovedor que incluya garantías y soporte técnico rápido.
  - Aceptar: Tener sensores de repuesto para reemplazos al instante.
- Ciberseguridad:
  - Evitar: Diseñar sistema con protocolos de seguridad desde el inicio del proyecto, siguiendo normativas ISO.
  - Compartir: Contratar seguro contra ciberataques.
- Vandalismo:
  - Reducir: Tener un monitoreo cotidiano de los contenedores IoT, contratando personas encargadas en la ZONA de cuidar estos contenedores.
  - Compartir: Convenio con seguridad ciudadana para la seguridad de contenedores
- Falta de adopción ciudadana:
  - Reducir: Aplicar capacitaciones en la comuna, informando sobre este nuevo proyecto y los beneficios de un buen uso de estos.

### 4. Indicadores de monitoreo

**Efectividad del sistema**

- Porcentaje de contenedores con datos transmitidos correctamente (>95%)
- Tiempo promedio entre fallo de sensores y su reparación (<24 horas)
- Reducción de quejas por basura acumulada (-30% en 3 meses)

**Seguridad sistema**

- Numero de incidentes de contenedores reportados (3 máx. cada 6 meses)
- Tiempo de detección y respuesta a vulnerabilidades (<48 horas)

**Adopción sistema**

- Rutas optimizadas según datos del sistema (80% en 3 meses)
- Satisfacción de trabajadores con el sistema (90% el primes mes)
