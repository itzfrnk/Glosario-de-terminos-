[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Journaling / Registro por Diario

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “El registro por diario (_journaling_) es una técnica de gestión de sistemas de archivos en la cual todas las modificaciones a los metadatos se escriben primero en un registro secuencial o diario (_journal_) antes de aplicarse en las estructuras de disco definitivas”. Si ocurre un fallo de energía o un bloqueo inesperado, el sistema operativo puede utilizar este registro durante la recuperación (_recovery_) para reproducir o deshacer transacciones incompletas.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107131245.png|429]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107131335.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Commit de Diario]] y [[Sistema de Archivos]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 11.