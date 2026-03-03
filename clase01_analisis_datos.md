# Clase 1: Pensar como un Analista de Datos 🧠
**Academia:** Unicorn
**Objetivo:** Entender las necesidades empresariales y el ciclo de vida de un proyecto de datos.

---

## 1. El Rol del Analista: De la Incertidumbre a la Evidencia
El analista no solo "mira datos", sino que resuelve problemas de negocio. Su función principal es **recolectar, limpiar y dar valor** a los datos para dar claridad a las empresas.

| Problema de la Empresa | Respuesta del Analista |
| :--- | :--- |
| "No sabemos por qué bajan las ventas" | Analiza causas y detecta patrones. |
| "No sabemos dónde perdemos dinero" | Identifica ineficiencias operativas. |
| "No sabemos qué producto es más rentable" | Cruza datos y calcula márgenes reales. |
| "Las decisiones se toman por intuición" | Aporta evidencia basada en datos. |
| "¿Funcionó la campaña de marketing?" | Mide el impacto real y el retorno (ROI). |

---

## 2. Casos de Estudio y Proyectos Reales
A continuación, se presentan ejemplos de cómo la analítica transforma negocios:

### 📊 Ejemplo 1: BI Financiero (Consultoría)
* **Problema:** Reportes manuales en Excel que tomaban días.
* **Stack:** Excel, Power Query, DAX, Power BI Desktop/Service.
* **Resultado:** Reducción del **90% en tiempo de reporting** (de días a minutos). Visibilidad diaria en lugar de mensual.

### 🎓 Ejemplo 2: Optimización de Academia Online (Freelance)
* **Problema:** Inversión ineficiente en capacitación.
* **Stack:** Python, Estadísticas CRM, Google Analytics, RRSS.
* **Resultado:** Definición del perfil óptimo de alumno y mejora en la segmentación, bajando el costo de adquisición.

### ✈️ Ejemplo 3: Modelo de Riesgo (Empresa de Viajes - Pandemia)
* **Problema:** Riesgo de impagos y gestión reactiva.
* **Stack:** SQL para limpieza, SAP para extracción, QlikView para visualización.
* **Resultado:** Creación de un *scoring* de riesgo para acciones preventivas y control de cartera.

---

## 3. El Ciclo de Vida de un Proyecto
> **Regla de oro:** No importa la herramienta, sino que la solución funcione para el negocio.

### Etapa 1: Entender el Negocio (Documentación Inicial)
Antes de tocar los datos, hay que entender el contexto:
* ¿Qué vende la empresa? ¿Cómo genera dinero?
* **Análisis básico:** ¿Existen ventas cruzadas? ¿Cuáles son las palancas de crecimiento?
* **Pregunta Norte:** Definir el foco del análisis para que el trabajo no sea infinito.

### Etapa 2: El Origen de los Datos (Arquitectura)
1.  **Sistemas de Información:** Los datos nacen en el ERP o Software donde se registra la operación.
2.  **Extracción (ETL):** Los ingenieros/arquitectos descargan los datos crudos a una base de datos (Ej: Google BigQuery).
3.  **Acceso:** Como analistas, accedemos a estos datos mediante **SQL** cuando el volumen supera las capacidades de Excel.

### Etapa 3: Transformación y Limpieza
Los **datos crudos** suelen venir con errores humanos o de software.
* **Limpieza:** Corregir formatos, eliminar nulos o errores de ingreso.
* **Campos Calculados:** Columnas nuevas creadas mediante fórmulas (ej. calcular el margen restando costo de venta) que no vienen en la fuente original.

---

## 4. Próximos Pasos 🚀
* **Clase 2:** Transformación de datos (Google Sheets a SQL).
* **Análisis de Negocio:** Creación de un dashboard completo en Looker Studio.
* **Objetivo:** Cuantificar pedidos en números y generar impacto real.
*
