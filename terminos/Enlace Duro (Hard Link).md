[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Enlace Duro / Hard Link

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “Un enlace duro (_hard link_) es una asociación directa entre un nombre de archivo y un nodo-i (_inode_) específico en el sistema de archivos, lo que permite que múltiples nombres de ruta apunten exactamente al mismo bloque de datos físicos en el disco”. Dado que todos los enlaces duros de un archivo comparten el mismo identificador de nodo-i, cualquier modificación realizada a través de uno de ellos se refleja de inmediato en los demás.
*   **Anexo A (Diagrama):**
![[Pasted image 20261107072451.png|396]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 072338.png|474]]
*   **Anexo C (Conexiones):** Se conecta con [[Inodo]] y [[Enlace Simbólico (Symlink)]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 11.