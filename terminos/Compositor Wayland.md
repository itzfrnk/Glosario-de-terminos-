[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Compositor Wayland / Wayland Compositor

- Según Andrew S. Tanenbaum y Herbert Bos (2015), definen que: “Un compositor de Wayland es el servidor gráfico y gestor de ventanas encargado de centralizar la gestión de superficies, la composición de fotogramas y la interacción directa con el núcleo del sistema operativo mediante el controlador gráfico del núcleo (_KMS_)”. Actúa como el núcleo central del subsistema gráfico recibiendo las solicitudes de renderizado de las aplicaciones y combinándolas en una única escena visual para presentarlas de manera eficiente en la pantalla, eliminando los cuellos de botella del modelo tradicional de X11.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107015620.png|287]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 015644.png|459]]
*   **Anexo C (Conexiones):** Se conecta con [[Servidor X11]], [[Weston]] y [[Sway]]
  
  - Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación. Cap. 10.