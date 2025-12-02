<div align="center">

# 📊 A/B Testing & Hypothesis Prioritization

### Data-Driven Decision Making for Business Growth

<img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
<img src="https://img.shields.io/badge/Python-Data%20Analysis-blue" />
<img src="https://img.shields.io/badge/Frameworks-ICE%20%7C%20RICE-orange" />
<img src="https://img.shields.io/badge/Statistics-A%2FB%20Testing-purple" />

---

### 👤 Author
**Yessid Diaz Gutierrez**

---

🚀 *This project demonstrates how to prioritize business hypotheses and validate them through A/B testing and statistical analysis.*

📈 Convert data into decisions.  
🧠 Reduce risk.  
✅ Increase impact.

---

</div>



📌 Descripción del Proyecto

Este proyecto analiza y prioriza hipótesis de negocio utilizando los frameworks ICE y RICE, y posteriormente evalúa una prueba A/B para determinar si los cambios implementados generan mejoras reales en el comportamiento del usuario y en los ingresos.

El objetivo principal es apoyar la toma de decisiones estratégicas basada en datos, minimizando riesgos y maximizando impacto.

🧠 Priorización de Hipótesis

Se utilizaron dos enfoques de análisis ampliamente usados en analítica de producto:

🔹 Framework ICE

ICE = (Impact × Confidence) / Effort
Este framework prioriza hipótesis según:

📈 Impacto potencial
✅ Nivel de confianza
⚙️ Esfuerzo requerido

✅ Hipótesis con mejor puntuación:

- Lanzar una promoción con descuentos por volumen
- Agregar nuevos canales de adquisición de tráfico
- Añadir un formulario de suscripción visible
- Mostrar banners promocionales
- Incluir recomendaciones de productos

❌ Hipótesis con menor puntuación:

- Cambiar el color del fondo
- Modificar la estructura de categorías
- Agregar una página de opiniones

🔹 Framework RICE

RICE = (Reach × Impact × Confidence) / Effort

Se añade el factor Reach (alcance del usuario):

✅ Mejor priorizadas:

- Añadir formulario de suscripción
- Recomendaciones personalizadas
- Nuevos canales de adquisición
- Banners promocionales

Ofertas especiales

🔍 Comparación ICE vs RICE
- Aspecto	ICE	RICE
- Alcance	❌ No incluido	✅ Incluido
- Precisión a escala	Media	Alta
- Utilidad principal	Ejecución rápida	Decisiones estratégicas

📌 Conclusión:
RICE es más efectivo cuando las decisiones impactan grandes volúmenes de usuarios.

📊 Análisis de Prueba A/B

- Se compararon dos grupos (A y B) en:
- Ingresos
- Conversión
- Tamaño de pedidos

💰 Ingresos acumulados

Se detectaron valores atípicos (outliers) causados por pedidos extremadamente altos.

🔍 Conclusión:
Los outliers distorsionan los ingresos y requieren ser filtrados.

🛒 Tamaño promedio de pedido

No se observa diferencia sostenida entre grupos.

📈 Conversión diaria

Resultados volátiles con diferencia pequeña entre grupos.

🚨 Detección de Outliers
Número de pedidos

Percentil 95: 2 pedidos
Percentil 99: 4 pedidos

✅ Criterio de filtrado: más de 4 pedidos = usuario atípico

Precio de pedido
Percentil 95: 435.54
Percentil 99: 900.90
Valores por encima fueron filtrados.

📐 Pruebas Estadísticas
📍 Datos sin filtrar
Conversión (Z-Test)

A: 2.68%
B: 3.10%
p-value = 0.0167 ✔️ Significativo
Tamaño de pedido (Mann-Whitney)
p-value = 0.6915 ❌ No significativo

📍 Datos filtrados
Conversión

A: 2.63%
B: 3.05%
p-value = 0.0157 ✔️ Sigue siendo significativo
Tamaño de pedido
p-value = 0.9332 ❌ Sin diferencia real

✅ Decisión Final

Aunque el grupo B presenta una conversión ligeramente mejor,
❗ No existe diferencia significativa en ingresos ni ticket promedio.

📌 Recomendación:

El experimento puede considerarse exitoso solo en conversión,
pero no justifica una implementación completa sin más validaciones.

🛠️ Herramientas Utilizadas
🐍 Python
🧮 Pandas, NumPy
📊 Matplotlib, Seaborn
📈 Análisis estadístico
🧪 Pruebas A/B
📐 Frameworks ICE y RICE
🏁 Conclusión General

Este proyecto demuestra cómo aplicar:

- Técnicas de priorización estratégica
- Análisis de experimentación real
- Identificación de datos atípicos
- Validación estadística

📍 Todo orientado a tomar decisiones basadas en datos reales.
