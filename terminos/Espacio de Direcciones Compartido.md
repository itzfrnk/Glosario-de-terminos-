[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

Espacio de Direcciones Compartido / Shared Address Space

- Según Andrew S. Tanenbaum y Herbert Bos (2015), definen que: “Un espacio de direcciones compartido permite que dos o más procesos diferentes accedan a la misma región de memoria física mediante la configuración de sus respectivas tablas de páginas para que apunten a los mismos marcos de memoria”. Este mecanismo de gestión de memoria virtual facilita una comunicación entre procesos (_IPC_) de ultra alta velocidad al eliminar la necesidad de copiar datos entre los espacios de direcciones aislados de cada proceso. 

*   **Anexo A (Diagrama):**
![[Pasted image 20261107073436.png|450]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 073458.png|451]]
*   **Anexo C (Conexiones):** Se conecta con [[Memoria Compartida]] e [[IPC]]
  
  - Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación. Cap. 3.