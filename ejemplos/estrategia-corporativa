# 📊 Caso de Estudio 1: Estrategia Corporativa y Riesgos

**Escenario:** Eres el Director de Estrategia de una empresa, Tienes 2 reportes densos de tendencias de la industria en PDF y 2 documentos internos con los presupuestos y minutas de tu equipo, necesitas saber si la estrategia actual de la empresa está alineada con la realidad del mercado antes de una junta directiva.

---

### 📥 1. Los Inputs
* `Reporte_Tendencias_Gartner_2026.pdf` (45 páginas)
* `Analisis_Sector_Tech_Latam.pdf` (30 páginas)
* `Minutas_Comite_Directivo_Q1.docx` (Acuerdos internos)
* `Presupuesto_Innovacion_2026.xlsx` (Exportado a PDF)

---

### 🗣️ 2. El Prompt (Usando el Framework FAA)

> **[ANCLAJE]** Cruza la información de los reportes externos de mercado (Gartner y Latam) con nuestros documentos internos (Minutas y Presupuesto)
>
> **[DIRECTRIZ]** Actúa como un Consultor Estratégico de "Big 4" (McKinsey, BCG), tu objetivo es realizar un diagnóstico de alineación estratégica, busca brechas peligrosas entre lo que el mercado exige (según los reportes externos) y lo que nosotros estamos planeando/financiando (según los documentos internos)
>
> **[RESTRICCIÓN]**
> - Basa tu análisis estrictamente en los datos de los documentos, No alucines
> - Si estamos invirtiendo en un área que los reportes externos marcan como "obsoleta" o "de bajo crecimiento", resáltalo como ALERTA CRÍTICA
> - Cita la fuente exacta para cada afirmación
>
> **[FORMATO]**
> 1. Un diagnóstico de salud estratégica (Semáforo: Verde, Amarillo, Rojo)
> 2. Una tabla Markdown de Brechas: [Iniciativa Interna] | [Presupuesto Asignado] | [Realidad del Mercado (Externa)] | [Nivel de Riesgo]
> 3. 3 Recomendaciones de pivoteo estratégico

---

### 🪄 3. El Output de NotebookLM

#### Diagnóstico de Salud Estratégica: 🟡 AMARILLO (Riesgo Moderado)
*Existe una desalineación del 30% en la asignación de capital frente a las macrotendencias de adopción tecnológica en LATAM para 2026*

#### Matriz de Brechas Estratégicas

| Iniciativa Interna (Minutas) | Presupuesto | Realidad del Mercado (Reportes) | Riesgo |
| :--- | :--- | :--- | :--- |
| Desarrollo de App Nativa | $150,000 USD | El `Reporte_Gartner_2026.pdf` (cita 3) indica que el 70% de los usuarios prefieren WebApps progresivas y las descargas de apps nativas han caído un 22%. | 🚨 CRÍTICO |
| Implementación de Agentes IA | $20,000 USD | `Analisis_Sector_Tech_Latam.pdf` (cita 7) señala que la automatización con IA es el factor #1 de supervivencia en el sector. | ⚠️ SUB-FINANCIADO |
| Expansión a Mercado Físico | $300,000 USD | El sector inmobiliario comercial proyecta un estancamiento (`Reporte_Gartner`, cita 12). | 🟡 MEDIO |

#### Recomendaciones de Pivoteo Estratégico
1. **Reasignación de Capital:** Congelar el desarrollo de la App Nativa y transferir el 50% de ese presupuesto a la iniciativa de Agentes IA.
2. **Revisión de Expansión:** Exigir al equipo de operaciones un modelo de ROI a 6 meses para la expansión física antes de desembolsar los fondos aprobados en la minuta de enero.
