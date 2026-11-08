[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

ext4 / Fourth Extended File System

- Según Andrew S. Tanenbaum y Herbert Bos (2015), definen que: “El sistema de archivos `ext4` es el estándar de alto rendimiento en Linux, el cual introduce mejoras clave como el uso de extensiones en lugar de mapas de bloques tradicionales para reducir drásticamente la fragmentación y optimizar la gestión de archivos masivos”. Esta arquitectura mejora notablemente la velocidad de lectura y escritura, incorpora un registro (_journaling_) avanzado para garantizar la integridad de los datos y permite manejar volúmenes de almacenamiento.
  
*   **Anexo A (Diagrama):**
![[Pasted image 20261107081423.png|424]]
*   **Anexo B (Comando/Código):**
  ![[Screenshot 2026-11-07 081440.png|453]]
*   **Anexo C (Conexiones):** Se conecta con [[Journaling]], [[Sistema de Archivos]] y [[Inodo]]
  
  - Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación. Cap. 9.