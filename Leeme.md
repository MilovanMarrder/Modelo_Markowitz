# Optimización de Cartera con el Modelo de Markowitz
---
```
Hecho por Milovan Marrder
```

## Descripción del Proyecto

Este proyecto implementa una herramienta de optimización de cartera utilizando el Modelo de Markowitz. Permite a los inversores encontrar la asignación óptima de activos para un conjunto dado de inversiones, equilibrando el riesgo y el rendimiento basándose en su tolerancia al riesgo.

## Características

- Entrada de datos para los rendimientos históricos de múltiples activos
- Cálculo de rendimientos esperados y matriz de covarianza
- Generación de carteras aleatorias
- Visualización de la frontera eficiente
- Identificación de la cartera óptima basada en el ratio de Sharpe
- Gráfico interactivo para explorar diferentes composiciones de cartera

## Requisitos

- Python 3.7+
- pandas
- numpy
- matplotlib
- plotly

## Instalación

1. Clona este repositorio:
   ```
   git clone https://github.com/tuusuario/optimizacion-cartera.git
   ```
2. Navega al directorio del proyecto:
   ```
   cd optimizacion-cartera
   ```
3. Instala los paquetes requeridos:
   ```
   pip install pandas numpy matplotlib plotly
   ```

## Uso

1. Abre el notebook de Jupyter o el script de Python en tu entorno preferido (por ejemplo, Jupyter Lab, Google Colab).

2. Actualiza la lista `Inversiones` con tus propios datos de activos, o modifica el código para leer desde un archivo CSV.

3. Establece tu monto total de inversión y el riesgo máximo aceptado:
   ```python
   total_inversion = 1430000  # Modifica esto a tu monto de inversión
   max_accepted_risk = 0.20   # Ajusta este valor según tu tolerancia al riesgo
   ```

4. Ejecuta las celdas/script para generar el análisis de la cartera.

5. Explora el gráfico interactivo para ver diferentes composiciones de cartera y sus respectivos perfiles de riesgo-rendimiento.

## Componentes Clave

- `portfolio_performance()`: Calcula el rendimiento y el riesgo de una cartera dada.
- Gráfico de Frontera Eficiente: Visualiza el equilibrio entre riesgo y rendimiento para diferentes composiciones de cartera.
- Identificación de Cartera Óptima: Encuentra la cartera con el ratio de Sharpe más alto dentro del nivel de riesgo aceptado.
- Gráfico Interactivo: Permite a los usuarios explorar diferentes composiciones de cartera pasando el cursor sobre los puntos en el gráfico de dispersión.

## Ejemplo de Salida

El script proporciona varias salidas:

1. Un gráfico de dispersión que muestra la frontera eficiente
2. Detalles de la cartera óptima (máximo ratio de Sharpe)
3. Asignación de activos para la cartera óptima
4. Gráfico circular que visualiza la composición de la cartera óptima
5. Análisis de rendimientos históricos basado en la asignación óptima
6. Crecimiento proyectado de la inversión durante 5 años

## Personalización

Puedes personalizar el proyecto:
- Modificando la lista de activos y sus rendimientos históricos
- Ajustando el nivel de tolerancia al riesgo
- Cambiando el monto total de inversión
- Añadiendo nuevos activos o eliminando los existentes de la cartera

## Contribuciones

Las contribuciones para mejorar el proyecto son bienvenidas. Por favor, siéntete libre de enviar un Pull Request.

## Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## Descargo de Responsabilidad

Esta herramienta es solo para fines educativos. No constituye asesoramiento financiero. Siempre consulta con un asesor financiero calificado antes de tomar decisiones de inversión.
