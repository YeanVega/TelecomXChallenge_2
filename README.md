# 🔍 Análisis de Cancelación de Clientes

Este proyecto tiene como objetivo analizar y predecir la cancelación (churn) de clientes utilizando modelos de machine learning, y proponer estrategias de retención basadas en los resultados.


---

## 📌 Objetivo

Desarrollar modelos predictivos que:
- Identifiquen a los clientes con mayor probabilidad de cancelar el servicio.
- Analicen los factores que más influyen en esa decisión.
- Provean insights accionables para estrategias de retención.

---

## 🛠️ Tecnologías Usadas

- **Python 3.10+**
- **Pandas**, **NumPy** – procesamiento y análisis de datos
- **Scikit-learn** – modelos de machine learning
- **Matplotlib**, **Seaborn** – visualización
- **Jupyter Notebook** – entorno de análisis interactivo

---

## 📊 Modelos Implementados

Se entrenaron dos modelos principales:

| Modelo       | Normalización | Accuracy | F1 (cancelación) | Comentario |
|--------------|---------------|----------|------------------|------------|
| K-Nearest Neighbors | ✅ | 74.9%    | 0.50             | Modelo basado en distancia, limitado con alta dimensionalidad |
| Random Forest        | ❌ | **78.9%** | **0.58**          | Modelo robusto, mejor desempeño y explicabilidad |

---

## 🔍 Variables más Influyentes (Random Forest)

- `Charges.Total`
- `tenure`
- `Charges.Monthly`
- `Cuentas_Diarias`
- `Contract_Two year`
- `PaymentMethod_Electronic check`
- `InternetService_Fiber optic`

---

## 🧠 Estrategias de Retención Basadas en los Resultados

1. **Fidelización en los primeros meses**: campañas enfocadas en clientes nuevos.
2. **Ofertas personalizadas** para clientes con cargos mensuales altos.
3. **Incentivos para cambiar a contratos de 1 o 2 años.**
4. **Promoción de servicios adicionales** como soporte técnico y seguridad.
5. **Auditoría de calidad** para usuarios de fibra óptica.

---

## 📈 Resultados

- Mejora en la identificación de clientes en riesgo de cancelar.
- Generación de insights estratégicos para equipos de marketing y atención al cliente.
- Base para implementar una solución de scoring de churn en producción.

---

## 📩 Contacto

Desarrollado por: **Yeferson Andres Velazco**  
Correo: yvelazco@unal.edu.co

