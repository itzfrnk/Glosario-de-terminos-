[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

lmkd / Low Memory Killer Daemon

- Según Robert Love (2010), define que: “`lmkd` es un demonio en el espacio de usuario de Android y Linux que supervisa dinámicamente la presión de la memoria del sistema (_memory pressure_) utilizando estadísticas del núcleo para prevenir situaciones críticas de falta de recursos”. Cuando la RAM libre desciende por debajo de umbrales predefinidos, `lmkd` calcula la puntuación de penalización de los procesos en ejecución y termina de forma selectiva a las aplicaciones menos prioritarias o en segundo plano para liberar memoria.
  
*   **Anexo C (Conexiones):** Se conecta con [[Límites de RAM (memory.max)]] y [[AOSP]]
  
  - Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.