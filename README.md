# 📦 Inventory Data Dashboard

> Proyecto *end-to-end* de análisis de datos y visualización orientado al proceso de inventario de activos fijos, desde la limpieza de datos brutos hasta la construcción de un dashboard gerencial para apoyar la toma de decisiones financieras y operativas.

## 📑 Contenido
- [Objetivo](#-objetivo)
- [Contexto y Problema](#-contexto-y-problema)
- [Solución Desarrollada](#-solución-desarrollada)
- [Proceso y Flujo de Trabajo](#-proceso-y-flujo-de-trabajo)
- [Resultados y Valor Aportado](#-resultados-y-valor-aportado)
- [Vista Previa del Proyecto](#%EF%B8%8F-vista-previa-del-proyecto)
- [Documentación Adicional](#-documentación-del-proyecto)

## 📝 Objetivo
Transformar una base de datos de inventario cruda y desestructurada en información útil, dinámica y precisa para el control, análisis y visualización a nivel ejecutivo.

## 📖 Contexto y Problema
Este proyecto presenta un caso aplicado basado en el inventario de activos fijos de una institución con múltiples sedes. 

**El Problema:** La información original se encontraba desordenada, desactualizada y sin una estructura clara de clasificación topológica (por sede y área). Adicionalmente, presentaba desafíos de consistencia y legibilidad (campos nulos o duplicados), lo que imposibilitaba el análisis cruzado, el control real del inventario y la generación de reportes financieros confiables.

## 💡 Solución Desarrollada
Se ejecutó un proceso completo de Inteligencia de Negocios que abarcó:
- Limpieza profunda y transformación de datos (ETL).
- Estandarización de campos y reglas de validación.
- Análisis exploratorio descriptivo.
- Definición de indicadores clave de rendimiento (KPIs).
- Construcción de un dashboard gerencial en Power BI.

### 🛠️ Herramientas Utilizadas
- **Tratamiento Avanzado:** Python (Pandas).
- **Procesamiento de Datos:** Microsoft Excel, Power Query.
- **Visualización:** Microsoft Power BI (DAX).
- **Ecosistema de Apoyo:** Microsoft Power Platform.

## 🔄 Proceso y Flujo de Trabajo

### Paso a paso:
1. Revisión de la base de datos original (auditoría de calidad de datos).
2. Limpieza y normalización de campos (texto, fechas, monedas).
3. Identificación y tratamiento de inconsistencias y valores nulos (*missing values*).
4. Análisis exploratorio de los datos limpios.
5. Definición de métricas y KPIs con los *stakeholders*.
6. Diseño UI/UX y desarrollo del dashboard interactivo.

### Arquitectura de Datos:
```mermaid
flowchart LR
    A["Datos brutos (Excel)"] --> B["Limpieza y normalización"]
    B --> C["Transformación (ETL)"]
    C --> D["Análisis exploratorio"]
    D --> E["Definición de KPIs"]
    E --> F["Dashboard en Power BI"]
    F --> G["Apoyo a decisiones"]
```

## 📊 Resultados y Valor Aportado

### Indicadores Generados
- Total de activos registrados físicamente.
- Distribución contable por categoría de activo.
- Concentración de activos por ubicación (Sede/Área).
- Estado de conservación de los activos.
- Hallazgos relevantes (bajas, extravíos, mermas).

### Valor Aportado a la Institución
- **Control Real:** Identificación del inventario real por sede y determinación del porcentaje de activos faltantes.
- **Impacto Financiero:** Apoyo directo al área de finanzas para estimar la valorización y depreciación del inventario por sede.
- **Visibilidad y Tiempo:** Reducción drástica del tiempo invertido en análisis manual, entregando visibilidad 24/7 a las áreas de gestión.

## 👁️ Vista Previa del Proyecto

<p align="center">
  <img src="images/inventario_difuminado 1.png" alt="Vista general del dashboard" width="48%">
  <img src="images/inventario_difuminado 2.png" alt="Vista analítica del dashboard" width="48%">
</p>

> **Nota:** Por confidencialidad, las imágenes muestran datos difuminados, ficticios o adaptados del caso real para no exponer información contable sensible de la institución.

## 🚀 Próximas Mejoras (Roadmap)
- Automatización programada de la actualización de datos vía Power Automate.
- Integración directa con nuevas fuentes (Ej. ERP Institucional) mediante API.
- Incorporación de alertas tempranas para activos que cumplen su vida útil.

## 📚 Documentación del Proyecto
Este repositorio incluye documentación complementaria detallada sobre el caso:
- 🏢 [Contexto de negocio](docs/business-context.md)
- 🧹 [Proceso de limpieza y preparación de datos](docs/data-cleaning-process.md)
- 📈 [Insights e indicadores clave](docs/insights-and-kpis.md)

## 📫 Contacto
Si quieres conocer más sobre mis proyectos de análisis de datos corporativos, puedes contactarme:
- 📧 **Email:** [claudio.duran.m@gmail.com](mailto:claudio.duran.m@gmail.com)
- 💼 **LinkedIn:** [Claudio Durán Molina](https://www.linkedin.com/in/claudio-duran-molina-41580677)
