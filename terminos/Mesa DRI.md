[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Mesa DRI / Mesa Direct Rendering Infrastructure

- Según Andrew S. Tanenbaum y Herbert Bos (2015), definen que: “Mesa DRI es un marco de trabajo (_framework_) arquitectónico del sistema operativo que permite el acceso directo y seguro del espacio de usuario al hardware gráfico sin necesidad de realizar costosos cambios de contexto hacia el núcleo”. Mediante esta infraestructura, las bibliotecas OpenGL interactúan de forma directa con los controladores gráficos del kernel para acelerar el procesamiento de gráficos 3D mediante la GPU, minimizando la sobrecarga de la CPU.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107142950.png|459]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107143013.png|472]]
*   **Anexo C (Conexiones):** Se conecta con [[DRM KMS]] y [[dev dri renderD128]]
  
  - Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación.