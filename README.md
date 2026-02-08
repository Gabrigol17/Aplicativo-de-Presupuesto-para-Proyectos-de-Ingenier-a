# Aplicativo de Presupuesto para Proyectos de Ingeniería

Aplicación de escritorio desarrollada en Python para automatizar el cálculo de presupuestos en proyectos de ingeniería y proyectos energéticos, reemplazando procesos manuales realizados en hojas de Excel.

---

## Problema a solucionar
En proyectos de ingeniería, el cálculo de presupuestos suele realizarse manualmente en Excel, lo que genera:

- Pérdida de tiempo en cálculos repetitivos  
- Alta probabilidad de errores  
- Dificultad para modificar salarios, roles o duración del proyecto  
- Falta de trazabilidad y análisis mensual de costos  

Este problema se agrava cuando los proyectos incluyen múltiples fases, distintos roles profesionales y gastos adicionales.

---

## Objetivo del proyecto
Desarrollar un aplicativo que permita calcular de forma automática el presupuesto de una oficina de ingeniería y proyectos energéticos, teniendo en cuenta:

- Estructura salarial configurable
- Diferentes roles profesionales
- Fases del proyecto (Ingeniería de detalle y Montaje)
- Asignación porcentual de cada rol por fase
- Gastos adicionales del proyecto
- Imprevistos sobre el valor final del presupuesto

---

## Alcance funcional
El aplicativo permite:

- Definir proyectos con nombre y duración
- Separar el proyecto en fases de ingeniería y montaje
- Configurar la estructura salarial (Auxiliar, Junior, Especialista)
- Armar el equipo de trabajo del proyecto
- Asignar porcentajes de dedicación por fase a cada rol
- Calcular:
  - Valor total del presupuesto
  - Valor mensual
  - Costos por fase
  - Costos por tipo de rol
- Agregar un porcentaje de imprevistos (máximo 15%)

---

## Roles contemplados
El sistema está diseñado para manejar roles como:

- Interventor mecánico  
- Interventor civil  
- Interventor eléctrico  
- Interventor de control  
- Interventor de planeación  
- Interventor SST  
- Director administrativo  
- Especialistas por disciplina  

Cada rol puede tener una asignación porcentual distinta en cada fase del proyecto.

---

## Estructura salarial
El aplicativo maneja una estructura salarial configurable por niveles:

- Ingeniero Auxiliar I – IV  
- Ingeniero Junior I – IV  
- Ingeniero Especialista I – IV  

Los salarios no están definidos en el código, sino en archivos de configuración editables.



## Gastos adicionales
Se contemplan gastos adicionales como:

- Alquiler de contenedor  
- Baños portátiles  
- Transporte local e intermunicipal  
- Transporte aéreo  
- Viáticos de alimentación  
- Hospedaje  
- Gastos de oficina  
- Caja menor  
- Otros gastos personalizados  





