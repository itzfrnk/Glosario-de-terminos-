[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Administrador de renderizado directo y configuración del modo del kernel / Direct Rendering Manager y Kernel Mode-Setting

- Según Robert Love (2010),  define que: “DRM KMS es un subsistema del núcleo Linux que permite gestionar la configuración de los modos de visualización de vídeo, las resoluciones, las tasas de refresco y la asignación de búferes de memoria directamente desde el espacio del núcleo, eliminando la necesidad de un servidor gráfico externo para cambiar de modo gráfico”. Este subsistema unifica la inicialización de pantallas y el acceso a la unidad de procesamiento gráfico (GPU), permitiendo que las interfaces modernas y los entornos de escritorio arranquen con rapidez.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107042803.png|366]]
*   **Anexo B (Comando/Código):** 
![[Screenshot 2026-11-07 042743.png|374]]
*   **Anexo C (Conexiones):** Se conecta con [[dev dri renderD128]] y [[Compositor Wayland]]
  
   Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.
  
  