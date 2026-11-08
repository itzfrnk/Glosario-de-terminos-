[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

execve()

- Según W. Richard Stevens y Stephen A. Rago (2013), describen que: “La llamada al sistema execve reemplaza la imagen del proceso actual con una nueva imagen de programa leída de un archivo ejecutable”. Esta operación permite a un proceso hijo transformar su código y espacio de memoria para ejecutar un programa totalmente diferente.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107081134.png|371]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 081102.png]]
*   **Anexo C (Conexiones):** Se conecta con [[fork()]] y [[waitpid()]]
  
  - **Referencia bibliográfica**
Stevens, W. R., & Rago, S. A. (2013). _Advanced Programming in the UNIX Environment_ (3.ª ed.). Addison-Wesley. Cap. 8.