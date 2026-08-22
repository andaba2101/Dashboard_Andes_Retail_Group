# Dashboard_Andes_Retail_Group
Dashboard interactivo para entender el desempeño comercial de los años 2024–2025 de Andes Retail Group


# Proyecto 9: Dashboard de desempeño comercial

Como analista de datos en Andes Retail Group, una empresa de retail con operaciones en Perú, Chile y Colombia, la dirección ejecutiva necesitó un dashboard interactivo que permitiera entender el desempeño comercial de los años 2024–2025. La empresa comercializa productos en cuatro categorías:

🖥️ Electrónica
👕 Ropa
⚽ Deportes
🏠 Hogar

La información estaba dispersa en datos transaccionales y no existía una visión clara que permitiera responder preguntas estratégicas sobre ventas, rentabilidad y comportamiento de clientes por lo que se transformaron estos datos en información visual, clara y accionable.

Objetivo del proyecto

- Responder a las siguientes preguntas de negocio: ¿Cómo ha evolucionado el ingreso total entre 2024 y 2025?, ¿Qué segmentos de clientes aportan mayor ingreso y rentabilidad?, ¿Qué categorías de producto tienen mayor impacto en el negocio?, ¿Existen diferencias relevantes entre países o regiones?, ¿Qué patrones temporales se observan a lo largo del año?, ¿Dónde podrían existir oportunidades de mejora comercial?
- Conectar y validar un dataset transaccional.
- Preparar datos para análisis.
- Diseñar dashboards aplicando principios de diseño visual profesional.
- Construir visualizaciones claras que respondan preguntas de negocio.
- Implementar filtros e interacciones que permitan exploración dinámica.
- Construir una narrativa estratégica usando el modelo SQCA.
- Presentar hallazgos de forma ejecutiva, tanto en el dashboard como de manera asincrónica.

Datasets utilizados
El archivo Andes_Retail_Group_2024_2025.xlsx contiene transacciones de ventas del negocio retail Andes Retail Group correspondientes a los años 2024–2025. Cada fila representa un pedido individual, incluyendo información del cliente, ubicación geográfica, categoría de producto y métricas financieras como ingresos y costo. El dataset permitió analizar desempeño comercial, rentabilidad y comportamiento temporal del negocio. Para ello, se trabajó con una fuente de datos:

[Andes_Retail_Group_2024_2025.xlsx] (https://docs.google.com/spreadsheets/d/1KU6xqMxuyFk5PVxdPmvWbWNX7NqT3uOwOab4qH9vaJ8/edit?usp=drive_link)

El dataset contiene las siguientes columnas:

ID_Pedido	Numérico | (int) |	Identificador único del pedido	| 1
Fecha_Pedido	| Fecha	| Día en que se realizó la venta	| 2025-10-29
Estación	| Categórica	| Temporada del año según el hemisferio sur: Verano (dic–feb), Otoño (mar–may), Invierno (jun–ago) y Primavera (sep–nov) |	Primavera
ID_Cliente	| Categórica	| Identificador único del cliente	| C8382
Segmento_Cliente	| Categórica	| Tipo de cliente según valor comercial	| Estándar
Región	| Categórica |	Región geográfica dentro del país	| Sur
País	| Categórica	| País donde se realizó la venta	| Colombia
Categoría_Producto	| Categórica	| Tipo de producto vendido	| Hogar
Unidades_Vendidas	| Numérico (int)	| Cantidad de unidades vendidas	| 7
Precio_Unitario	| Numérico (decimal)	| Precio por unidad del producto	| 67
Ingresos	| Numérico (decimal)	| Total vendido (precio × unidades)	| 469
Costo	| Numérico (decimal)	| Costo asociado a la venta	| 325.44

Etapas del análisis realizadas
Paso Acción Resultado para el negocio (Flujo general del proyecto):

1. Conexión y exploración:	Importar el dataset y revisar tipos de datos, columnas y métricas clave para comprensión inicial del negocio y estructura del dataset.
2. Preparación de datos:	Validar tipos, crear columnas necesarias y revisar consistencia para un	dataset limpio y listo para análisis.
3. Aplicar principios de diseño visual:	Definir layout, jerarquía visual, colores y estructura antes de crear visualizaciones para un dashboard claro y profesional.
4. Crear visualizaciones efectivas:	Diseñar Vista General (overview) y Vista Detalle (análisis específico).	Visión ejecutiva + análisis profundo.
5. Filtros e interacciones:	Implementar filtros y configurar interacciones entre gráficos para una	exploración dinámica del negocio.
6. Narrativa con modelo SQCA:	Construir historia dentro del dashboard y comunicar hallazgos vía Slack para un	Insight estratégico claro y accionable.

Guía breve de reproducción
Vista 1: Overview ejecutivo debe responder: ¿Cómo está el negocio en general?
En esta vista busca ofrecer una lectura rápida del desempeño global.

📌 Un directivo debería entender la situación en pocos segundos considerando:
- Métricas clave de desempeño (ventas, ganancia, volumen, etc.)
- Evolución del negocio a lo largo del tiempo
- Comparaciones generales entre geografías o segmentos
- Elementos que resuman el estado actual del negocio
- Priorizar síntesis y claridad, no demasiados gráficos.

🔎 Vista 2: Análisis detallado debe responder: ¿Dónde están las diferencias, patrones u oportunidades?
Aquí se espera un análisis más profundo que permita explorar causas y detectar insights considerando:
- Comparaciones entre categorías, segmentos o regiones
- Visuales que permitan filtrar o profundizar
- Algún elemento de detalle (como tablas) si necesitas profundizar en los datos
- Esta vista debe facilitar la exploración y el diagnóstico, no solo mostrar totales.

Objetivo: profundidad analítica y soporte a decisiones.

Sigue el flujo de trabajo descrito en cada celda del Jupyter Notebook; ahí encontrarás instrucciones paso a paso, pre-código y notas que te servirán de guía para entender el proyecto realizado.
