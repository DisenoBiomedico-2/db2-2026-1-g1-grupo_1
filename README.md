[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/qFqiZ1at)
*Plantilla de tu Proyecto: Edita esta plantilla usando el ícono del lápiz y coloca la información de tu grupo.*


# Proyecto de Diseño Biomédico 2

**Integrantes del Equipo:**
*   Katerin Estefania Moran Portilla
*   Gabriel Augusto Garzón Gavilán
*   Andres Felipe Calvo Arce
*   ...

**Nombre del Proyecto:** [Escribir aquí el nombre]
**Stakeholder/Cliente:** [Nombre de la empresa, institución o usuario]

---

## ⚠️ Instrucciones de Gestión (LEER OBLIGATORIAMENTE)
<details> <summary> Click aquí para expandir </summary>
   
Para la evaluación de este curso, utilizamos la metodología **"Si no está en el Issue, no existe"**.

### 1. Configuración Inicial (Semana 1)
1.  Vayan a la pestaña **Projects** de este repositorio.
2.  Creen un **New Project** y seleccionen la vista **Table**.
3.  Vayan a la pestaña **Issues** -> **Milestones** y creen 3 hitos:
    *   `Semana 5 - Diseño Conceptual`
    *   `Semana 11 - Pruebas y Validación`
    *   `Semana 17 - Entrega Final`
4.  Carguen todas sus tareas en el Project Board, asignen un **Responsable** y una **Fecha**.

### 2. Cómo entregar tareas
El profesor **NO revisará** carpetas al azar buscando archivos. El profesor revisará el **Project Board**.
*   Cada tarea completada debe tener un **Issue cerrado**.
*   Para cerrar un Issue válidamente, deben vincular la evidencia:
    *   **Si es código/diseño:** En el commit message usen `fixes #numero_issue`.
    *   **Si es documento/foto:** Arrastren el archivo dentro del comentario del Issue y ciérrenlo.

---

## 📂 Estructura del Repositorio (Design History File)

Este repositorio organiza el proyecto separando la evidencia documental de los archivos técnicos de ingeniería.

*   **/01_Gestion_del_Proyecto**: Cronograma, Presupuesto, Licencias, Cartas de intención, Acuerdos legales,...

*   **/02_DHF_Proceso_Diseno**: **DOCUMENTACIÓN (INFORMES Y EVIDENCIA)**
    *   *Fase_1_Investigacion*: Definición de requerimientos, normas y estado del arte, etc
    *   *Fase_2_Conceptual*: Matrices de selección, bocetos y definición de arquitectura, etc
    *   *Fase_3_Diseno_Detalle*: **Justificación ingenieril.** Aquí van los informes de cálculos, resultados de simulaciones, BOM final y especificaciones técnicas.
    *   *Fase_4_Validacion*: Protocolos de pruebas, resultados de validación con usuarios, análisis estadístico, etc

*   **/03_Ingenieria_Tecnica**: **ARCHIVOS FUENTE EDITABLES (HERRAMIENTAS)**
    *   *Calculos_Simulaciones*: Archivos de Excel, Scripts (MATLAB/Python), Simulaciones (Ansys/Proteus), simulaciones de SolidWorks, etc.
    *   *Mecanica_CAD*: Archivos nativos de modelado 3D y planos de fabricación.
    *   *Electronica*: Esquemáticos, diseño de PCB (Gerbers) y listas de materiales.
    *   *Software_Firmware*: Código fuente documentado.

*   **/04_Multimedia_Prototipo**: **MATERIAL DE DIVULGACIÓN.**
    *   Fotos de alta calidad del prototipo final.
    *   Video de funcionamiento (Demo) para la presentación final.
    *   Renders comerciales o material para el Póster/Pitch.

*   **/05_Reporte_Final_ABET**: 
    *   Aquí se entregará el documento final compilado ("Capstone Project") siguiendo la plantilla institucional.
    *   Este documento debe alimentarse de la información generada en la carpeta `02_DHF`.

</details>

---

## 📝 Resumen del Problema
*(Editar esta sección en la Semana 2)*
En un salón de uñas situado en Bochalema, Cali (Colombia), las trabajadoras dedicadas a servicios de manicura presentan dolor persistente en los dedos de las manos, con énfasis particularmente en el pulgar, durante y después de sus jornadas laborales. Esta sintomatología está asociada al uso continuo de herramientas manuales como corta cutículas, limas metálicas y pinzas para uñas, que requieren movimientos repetitivos finos y fuerzas de pinza sostenidas.

Tareas con movimientos repetitivos de las manos, fuerza aplicada sobre herramientas pequeñas y mantenidas posturas de muñeca se han identificado como factores de riesgo importantes para desarrollar trastornos musculoesqueléticos en la extremidad superior (Smith et al., 2023). Además, las herramientas de diseño tradicional tienden a generar cargas excesivas sobre las articulaciones interfalángicas y la articulación carpometacarpiana del pulgar, lo que puede conducir a inflamación de los tendones flexores y extensor del pulgar (López et al., 2022). Cuando este dolor se vuelve crónico, puede disminuir significativamente la funcionalidad manual y la capacidad para realizar tareas precisas y repetitivas.

