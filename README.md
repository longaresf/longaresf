# Automatización de Datos e Ingeniería Operativa para Empresas

Ayudo a **PyMEs y medianas empresas** a eliminar el trabajo manual en planillas Excel, integrar sus fuentes de datos (ERP, ventas, inventarios, finanzas) y obtener visibilidad gerencial diaria mediante **Sprints de implementación de 10 días hábiles**.

> **Enfoque:** Procesos primero, código después. Arquitecturas modulares, auditables y sin cajas negras.

---

### Soluciones Empaquetadas (Sprints de 2 Semanas)

| Solución | Problema que resuelve | Entregable Principal |
| :--- | :--- | :--- |
| **Torre de Control Operativa** | Horas semanales perdidas cruzando exportaciones del ERP con múltiples planillas Excel y cifras que no cuadran entre áreas. | Pipeline automatizado + Tablero gerencial único actualizado cada mañana. |
| **Radar de Caja y Conciliación** | Ceguera de liquidez real, cruces manuales entre cartolas bancarias, facturación y cuentas por cobrar vencidas. | Motor de conciliación automática + Proyección de flujo de caja y alertas de mora. |
| **Escudo de Stock y Cumplimiento** | Quiebres de inventario en productos críticos, sobrestock inmovilizado o vencimientos documentales sin alerta previa. | Semáforo de reposición sugerida por SKU + Auditoría automática de anomalías. |

---

### Arquitecturas de Referencia (Código Auditable)

* **[Pipeline de Consolidación y Calidad de Datos (Arquitectura Medallion)](https://github.com/longaresf/ecommerce-medallion-lakehouse-pipeline):** Ingesta automatizada, limpieza, validación de reglas de negocio y capa analítica lista para consumo gerencial con pruebas automatizadas (CI/CD).
* **[Motor de Pronóstico de Demanda y Reposición de Inventario](https://github.com/longaresf/retail-demand-forecasting-engine):** Modelado estadístico y de Machine Learning para anticipar demanda por producto, optimizar compras y reducir quiebres de stock.
* **[Motor Predictivo de Fuga de Clientes y Riesgo de Mora B2B (XGBoost)](https://github.com/longaresf/b2b-churn-credit-risk-xgboost):** Pipeline de clasificación en XGBoost de grado productivo para evaluar el riesgo de fuga de clientes y mora en facturas B2B. Incluye preprocesamiento automatizado, ajuste de hiperparámetros, explicabilidad con SHAP y CI/CD.

---

### Utilidades Abiertas (GitHub Gists)
* **[Validador y Normalizador de RUT Chileno (Módulo 11)](https://gist.github.com/longaresf/33be05e4c8c38d86e0618396dd11eb8d):** Librería en Python puro para estandarizar IDs tributarios y aislar errores en cuarentena.
* **[Conciliador SQL SII vs. ERP vs. Cartola Bancaria](https://gist.github.com/longaresf/79bf0ddf59d284837790f97a68797532):** Consulta analítica compatible con DuckDB y PostgreSQL con tolerancia conservadora y clasificación de excepciones.
* **[Parser de Fechas Mixtas y Moneda CLP en Excel](https://gist.github.com/longaresf/362b6c51eb23508b29729e0a4f1979d8):** Limpieza trazable en `pandas` sin conversión silenciosa de errores a cero.

---

### Stack Tecnológico
`Python` · `SQL (PostgreSQL / DuckDB)` · `FastAPI` · `Arquitectura Medallion` · `Docker` · `GitHub Actions (CI/CD)` · `Redis` · `Power BI / Metabase`

---

### Contacto Profesional
* **Consultoría y Diagnósticos B2B:** `csc@a2b.cl`
* **LinkedIn:** [[Enlace a Perfil de LinkedIn]](https://www.linkedin.com/in/longaresf/)
