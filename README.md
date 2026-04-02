# telecom-analysis
El objetivo de este proyecto es analizar el comportamiento de los clientes de la empresa de telecomunicaciones ConnectaTel (operaciones en México y Colombia) para identificar segmentos de uso, detectar patrones de consumo extremo y proponer estrategias comerciales basadas en datos.

**Fases del Análisis**
1. Preprocesamiento de Datos
-Tratamiento de Nulos: Se identificó un 10% de valores ausentes en la columna city, los cuales fueron gestionados para no afectar el análisis demográfico.
-Limpieza de Tipos: Conversión de fechas (reg_date) y estandarización de nombres.

2. Análisis de Outliers (Método IQR)
-Se aplicó el método del Rango Intercuartílico para detectar consumos extremos:

**Decisión: Se optó por mantener los outliers en minutos y mensajes.**
Justificación: Estos usuarios representan a los clientes más rentables que generan ingresos adicionales por excedentes.

3. Segmentación de Clientes
Se crearon nuevas dimensiones de análisis para entender mejor la base de usuarios:

-Grupo de Uso: Clasificados en Bajo uso, Uso medio y Alto uso (basado en llamadas y mensajes).

-Grupo de Edad: Segmentados en Joven (<30), Adulto (30-60) y Adulto Mayor (>60).

**Hallazgos Principales** 
Perfil del Cliente: El núcleo del negocio es el Adulto (30-60 años). Los adultos mayores tienen una presencia mayor que los jóvenes.
Comportamiento: El Uso Medio es la tendencia general, pero existe un segmento de "Power Users" que supera los 150 minutos mensuales.

Oportunidad: Los usuarios de "Alto uso" en planes básicos son candidatos ideales para migrar al plan Premium.

**Recomendaciones de Negocio**
Fidelización Senior: Crear promociones específicas para el grupo de Adultos Mayores, ya que son el segundo grupo más grande.
Estrategia de Up-selling: Dirigir campañas a usuarios de "Alto uso" para que contraten planes de mayor costo.
