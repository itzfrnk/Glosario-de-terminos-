[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Descriptor Leak / Fuga de Descriptores

Según W. Richard Stevens y Stephen A. Rago (2013), describe que: “Una fuga de descriptores se produce cuando un proceso abre recursos del sistema, como archivos o sockets, y omite cerrarlos, lo que termina por agotar los límites de la tabla de procesos”. En pocas palabras la fuga de descriptores ocasiona fallos operativos muy graves al impedir la apertura de los nuevos flujos de comunicación o archivos.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107031027.png|365]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 031054.png|632]]
*   **Anexo C (Conexiones):** Se conecta con [[Descriptor de Archivo (FD)]] y [[Memory Leak

- **Referencia bibliográfica**
Stevens, W. R., & Rago, S. A. (2013). _Advanced Programming in the UNIX Environment_ (3.ª ed.). Addison-Wesley. Cap. 3.