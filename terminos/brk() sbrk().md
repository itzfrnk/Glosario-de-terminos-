[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

brk() / sbrk()

De acuerdo con W. Richard Stevens and Stephen A. Rago (2013), define que: “Las funciones `brk` y `sbrk` son llamadas al sistema tradicionales que se utilizan para modificar dinámicamente la ubicación del límite del programa (program break), asignando o liberando así memoria en el montón”. Estas operaciones en pocas palabras configuran la base esencial mediante la cual los procesos solicitan ampliaciones de su segmento de datos en entornos UNIX.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107000353.png|390]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 000126.png|496]]

![[Screenshot 2026-11-07 000141.png|395]]
*   **Anexo C (Conexiones):** Se conecta con [[Montón (Heap)]], [[mmap()]] y [[Memory Leak]]
  
  - **Referencia bibliográfica**
Stevens, W. R., & Rago, S. A. (2013). _Advanced Programming in the UNIX Environment_ (3.ª ed.). Addison-Wesley. Cap. 7.