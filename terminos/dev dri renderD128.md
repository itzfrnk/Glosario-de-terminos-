[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

/dev/dri/renderD128

- Según Robert Love (2010), define que: “El nodo de dispositivo `renderD128` en el subsistema DRM del núcleo Linux proporciona acceso directo a la unidad de procesamiento gráfico (GPU) exclusivamente para tareas de renderizado sin cabeza, cálculo acelerado y procesamiento gráfico fuera de pantalla, omitiendo el servidor de pantalla”. Este componente permite a las aplicaciones modernas, entornos de contenedores y motores de renderizado interactuar de manera eficiente con el hardware gráfico sin requerir privilegios de administración de pantalla.

*   **Anexo A (Diagrama):**
![[Screenshot 2026-11-07 032549.png|297]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 032418.png|593]]
*   **Anexo C (Conexiones):** Se conecta con [[DRM KMS]] y [[Mesa DRI]]
  - Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.