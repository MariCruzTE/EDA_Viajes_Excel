# Informe Halcón Viajes

---

## 1. Contexto y Problema Actual

Halcón Viajes enfrenta varios desafíos en la gestión de sus reservas de viajes. A pesar de contar con una plataforma robusta de reservas, se ha observado que la tasa de cancelación de reservas es alta y que existe una falta de visibilidad clara sobre las preferencias de los usuarios, lo que dificulta la personalización de ofertas y la optimización de las campañas promocionales.
A través de un análisis detallado de los datos de reservas y el comportamiento de los usuarios, la empresa busca identificar patrones específicos que puedan ayudar a reducir la tasa de cancelación y mejorar la experiencia de los clientes. Además, se necesita una herramienta visual que permita monitorear y evaluar de manera continua las métricas clave de negocio, como la tasa de conversión, la efectividad de promociones y las preferencias de los usuarios en términos de destinos y paquetes.

## 2. Objetivo Principal del Proyecto

El objetivo principal de este proyecto es crear uno o varios dashboards interactivos que faciliten la visualización de datos relevantes y proporcionen insights prácticos para la toma de decisiones estratégicas. Los dashboards permitirán a los directivos de la empresa:

- Identificar patrones de comportamiento relacionados con la tasa de cancelación, la duración de las estancias y la elección de destinos.
- Evaluar la efectividad de las promociones y el impacto de las campañas en las decisiones de compra de los usuarios.
- Optimizar las ofertas basándose en los intereses de diferentes segmentos de clientes, para incrementar la tasa de retención.
  En resumen, la creación de estos dashboards será clave para mejorar la eficiencia operativa y reducir la incertidumbre en la toma de decisiones comerciales.

## 3. Descripción de las Columnas del Conjunto de Datos

El conjunto de datos contiene información detallada sobre

- las reservas de los usuarios,
- las características de los viajes y
- el comportamiento posterior a la reserva.

A continuación, se presenta una breve descripción de las columnas más relevantes:
Datos de los Usuarios:

- **ID_Reserva**: Identificador único del usuario.
- **Edad**: Edad del viajero.
- **Género**: Género del usuario (Male, Female, Other).
- **Ubicación**: Ubicación geográfica del usuario (país o ciudad).
- **Tipo_Viajero**: Tipo de usuario (Turista, Negocios).
  Datos de la Reserva:
- **ID_Reserva**: Identificador único para cada reserva.
- **Fecha_Reserva**: Fecha en la que se realizó la reserva.
- **Fecha_Viaje**: Fecha programada para el viaje.
- **Antelacion_Reserva**: Número de días entre la fecha de reserva y la fecha del viaje.
- **Duracion_Viaje**: Duración del viaje en días.
- **Numero_Personas**: Número de personas incluidas en la reserva.
- **Tipo_Paquete**: Tipo de paquete reservado (Solo vuelo, Vuelo + Hotel, Vuelo + Hotel + Tour).
- **Costo_Total**: Monto total de la reserva.
  Detalles del Viaje:
- **Destino**: Destino del viaje (puede ser ciudad o país).
- **Tipo_Alojamiento**: Tipo de alojamiento reservado (Hotel, Airbnb, Resort, etc.).
- **Clase_Vuelo**: Clase de vuelo seleccionada (Económica, Ejecutiva, Primera clase).
- **Actividades_Reservadas**: Actividades adicionales reservadas (Tour, Excursión, etc.).
- **Numero_Noches_Estancia**: Número de noches de alojamiento.
  Comportamiento y Estado de la Reserva:
- **Promocion_Aplicada**: Indica si se aplicó una promoción o descuento en la reserva.
- **Fuente_Reserva**: Canal a través del cual se realizó la reserva (Sitio web, App móvil, Agente de viajes).
- **Estado_Reserva**: Estado de la reserva (Confirmada, Pendiente, Cancelada).
- **Cancelacion_Reserva**: Indicador binario que señala si la reserva fue cancelada (Sí/No).
  Información Temporal:
- **Mes_Reserva**: Mes en que se realizó la reserva.
- **Mes_Viaje**: Mes programado para el viaje.
- **Estacionalidad**: Indica si la reserva se realizó durante temporada alta o baja.
  Feedback del Usuario:
-     **Calificacion_Usuario**: Calificación proporcionada por el usuario (1 a 5).
-     **Comentarios**: Comentarios adicionales sobre la experiencia del usuario.

## 4. Próximos Pasos

1. Recepción de los datos completos: Obtener todos los datos históricos necesarios para el análisis.
2. Análisis Exploratorio de Datos (EDA): Realizar un análisis inicial de los datos, identificando patrones y posibles problemas (valores faltantes, outliers, etc.).
3. Diseño de Dashboards: Crear dashboards interactivos que resalten las métricas más relevantes para la empresa, con un enfoque en la tasa de cancelación y segmentación de clientes.
4. Presentación de Resultados: Entregar un informe final con los insights obtenidos y recomendaciones para reducir la tasa de cancelación y mejorar las ventas
