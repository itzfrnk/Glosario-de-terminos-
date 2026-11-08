[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Subsistema Gráfico Linux / Linux Graphics Subsystem

- Según Daniel P. Bovet y Marco Cesati (2005), definen que: “El subsistema gráfico en Linux tradicionalmente se ha estructurado sobre el Servidor X (X11) interactuando con el núcleo a través de controladores de pantalla en modo usuario, aunque las arquitecturas modernas integran el núcleo mediante gestores de modos directos (_DRM_) y renderizado acelerado por hardware con KMS”. Basicamente gestiona  las tramas de vídeo y la sincronización directamente al espacio del núcleo, optimizando el rendimiento.

*   **Anexo A (Diagrama):**

![[Screenshot 2026-11-07 174201.png|477]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107174234.png]]
*   **Anexo C (Conexiones):** Se conecta con [[DRM KMS]], [[Servidor X11]] y [[Compositor Wayland]]
  
  - Referencia bibliográfica Bovet, D. P., & Cesati, M. (2005). _Understanding the Linux Kernel_ (3rd ed.). O'Reilly Media.