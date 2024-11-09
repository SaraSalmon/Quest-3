# Análisis de Activos Financieros

Este proyecto consiste en realizar una serie de cálculos y gráficos para analizar un conjunto de activos financieros. A continuación, se detallan los pasos y las tareas que debes realizar para completar este análisis.

## Descripción del Proyecto

### Ejercicio 1: Carga de Precios de los Activos Financieros

En esta primera parte, el objetivo es cargar un fichero que contiene los precios históricos de los activos financieros a analizar. El archivo que contiene esta información es `financial_assets_prices.csv`.

#### Tareas:
- Cargar el fichero `financial_assets_prices.csv`.
- Calcular los **rendimientos diarios porcentuales** de cada uno de los activos.

### Ejercicio 2: Análisis de Rendimientos de los Activos

Una vez cargados los precios, deberás analizar los rendimientos de los activos:

#### Tareas:
- Calcular la **matriz de correlación** entre los 5 activos.
- Realizar un **gráfico de dispersión** entre los rendimientos de 2 activos seleccionados.

### Ejercicio 3: Análisis de la Cartera de Inversión

En este ejercicio, se debe cargar un segundo fichero llamado `portfolio_weights.csv`, que contiene los pesos de cada activo en la cartera a lo largo de los días.

#### Tareas:
- **Cargar el fichero `portfolio_weights.csv`**.
- **Gráfico de área** para visualizar la distribución de los pesos de cada activo en la cartera a lo largo del tiempo.
- Calcular la **rentabilidad histórica acumulada de la cartera**.
- Calcular la **rentabilidad anualizada de la cartera**.
- Calcular la **volatilidad anualizada de la cartera** utilizando el factor de anualización de 261 días.

### Ejercicio 4: Rentabilidad Diaria y Acumulada

Además de los análisis anteriores, se deben realizar los siguientes cálculos:

#### Tareas:
- **Calcular la rentabilidad diaria** de cada activo.
- **Calcular la rentabilidad acumulada**: Acumula la rentabilidad diaria multiplicativamente para obtener la rentabilidad total hasta cada día.
- **Graficar la rentabilidad acumulada**: Finalmente, genera un gráfico de la rentabilidad acumulada de la cartera a lo largo del tiempo.

### Gráfico Temporal de Precios de los Activos

Una vez que los precios de los activos estén cargados, deberás visualizar un gráfico temporal. Asegúrate de que todas las series de precios comienzan con el mismo valor para poder compararlas de manera efectiva.

## Requisitos

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes bibliotecas en Python:

- `pandas`: para la manipulación de datos.
- `matplotlib`: para la creación de gráficos.
- `numpy`: para cálculos numéricos.
- `seaborn` (opcional): para mejorar los gráficos y visualizaciones.

Puedes instalar las dependencias necesarias ejecutando:

```bash
pip install pandas matplotlib numpy seaborn
