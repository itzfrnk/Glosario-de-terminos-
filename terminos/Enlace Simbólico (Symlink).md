[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Enlace Simbólico / Symbolic Link (Symlink)

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “Un enlace simbólico (_symbolic link_ o _symlink_) es un archivo especial cuyo contenido es una cadena de caracteres que representa la ruta de acceso a otro archivo o directorio, funcionando esencialmente como un puntero abstracto”. A diferencia de los enlaces duros, un enlace simbólico posee su propio nodo-i (_inode_) independiente y puede abarcar diferentes particiones o sistemas de archivos en red sin embargo, si el archivo o directorio de destino es eliminado o reubicado.
*   **Anexo A (Diagrama):**
![[Pasted image 20261107072816.png|432]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 072747.png|571]]
*   **Anexo C (Conexiones):** Se conecta con [[Enlace Duro (Hard Link)]] e [[Inodo]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 11.