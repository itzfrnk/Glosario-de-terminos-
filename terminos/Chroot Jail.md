[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Jaula Chroot / Chroot Jail 

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018),  definen que: “Una jaula chroot (`chroot jail`) es una operación que modifica el directorio raíz aparente para un proceso en ejecución y sus hijos, aislándolos del resto del sistema de archivos”. Esta limita el acceso de los procesos confinados a una sección específica del disco, mejorando la seguridad y previniendo accesos no autorizados a archivos críticos del sistema operativo.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107011101.png|338]]
*   **Anexo B (Comando/Código):**
  ![[Screenshot 2026-11-07 010905.png|510]]
*   **Anexo C (Conexiones):** Se conecta con [[Contenedor]] y [[Linux Namespaces]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 14.