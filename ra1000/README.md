# Series_de_tiempo
# 📈 Series de Tiempo

Este repositorio está dedicado al estudio y aplicación de **series de tiempo**, una de las áreas más importantes de la estadística y el análisis de datos, especialmente en economía, finanzas, marketing y ciencias sociales. Aquí se exploran los principales modelos teóricos y prácticos para analizar, modelar y predecir el comportamiento de datos que evolucionan a lo largo del tiempo.

El objetivo es comprender tanto la lógica matemática detrás de los modelos como su aplicación práctica en datos reales.

---

## 1. Introducción a Series de Tiempo

Una **serie de tiempo** es una secuencia de observaciones ordenadas cronológicamente. Su análisis busca identificar patrones, estructuras y dependencias temporales para poder explicar el pasado y predecir el futuro.

Conceptos clave:
- Tendencia: comportamiento de largo plazo.
- Estacionalidad: patrones que se repiten en periodos fijos.
- Ciclos: fluctuaciones no regulares en el tiempo.
- Ruido o componente aleatorio.
- Estacionariedad: propiedad fundamental para muchos modelos, donde la media y varianza permanecen constantes en el tiempo.

Este bloque sienta las bases para entender por qué los modelos de series de tiempo funcionan y qué tipo de problemas pueden resolver.

---

## 2. Modelos ARIMA, SARIMA y Funciones de Autocorrelación

En esta sección se desarrollan los modelos clásicos de predicción:

### 🔹 ARIMA (AutoRegressive Integrated Moving Average)
Modelo que combina:
- **AR (p):** dependencia de valores pasados.
- **I (d):** diferenciación para lograr estacionariedad.
- **MA (q):** dependencia de errores pasados.

Se usa principalmente para series no estacionales.

---

### 🔹 SARIMA (Seasonal ARIMA)
Extiende el modelo ARIMA incorporando:
- Componentes estacionales.
- Patrones repetitivos en periodos fijos (mensual, trimestral, etc.).

Es ideal para datos con comportamiento periódico claro.

---

### 🔹 ACF y PACF

Herramientas fundamentales para identificar la estructura del modelo:

- **ACF (Autocorrelation Function):**  
  Mide la correlación entre una observación y sus rezagos.

- **PACF (Partial Autocorrelation Function):**  
  Mide la correlación directa entre una observación y un rezago específico, eliminando la influencia de los rezagos intermedios.

Estas funciones permiten elegir de manera informada los parámetros \(p\) y \(q\) en los modelos ARIMA/SARIMA.

---

## 3. Series de Tiempo Financieras: GARCH, EGARCH y Variantes

Las series financieras tienen una característica especial:  
la **volatilidad no es constante**, cambia en el tiempo y suele agruparse en periodos de alta y baja variabilidad.

Aquí entran los modelos de heterocedasticidad condicional:

### 🔹 GARCH (Generalized Autoregressive Conditional Heteroskedasticity)
Modelo que permite:
- Capturar la volatilidad cambiante.
- Modelar la varianza como una función de errores pasados y varianzas previas.
- Es fundamental en análisis de riesgo financiero y mercados bursátiles.

---

### 🔹 EGARCH (Exponential GARCH)
Variante que:
- Permite asimetrías en la volatilidad.
- Captura el efecto de “malas noticias” que suelen aumentar más la volatilidad que las buenas.
- No requiere restricciones de positividad en los parámetros.

---

### 🔹 Otras variantes
Incluyen modelos como:
- TGARCH  
- IGARCH  
- APARCH  

Todos diseñados para describir de forma más realista el comportamiento de la volatilidad financiera.

---

## 🎯 Objetivo del Repositorio

Este repositorio busca:
- Integrar teoría y práctica.
- Servir como material de estudio para la materia de Series de Tiempo.
- Mostrar aplicaciones reales en contextos económicos y financieros.
- Funcionar como portafolio académico de modelos estadísticos avanzados.

---

✨ Ideal para entender cómo los datos “vivos” en el tiempo pueden ser modelados, interpretados y utilizados para tomar decisiones informadas.
