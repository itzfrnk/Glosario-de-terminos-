[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Tabla de Inodos / Inode Table

- Según Maurice J. Bach (1986), define que: “La tabla de inodos (_inode table_) es una estructura de datos residente en el núcleo que almacena los metadatos de todos los archivos activos en el sistema, conteniendo información crítica como permisos, propietarios, tamaños y los punteros a los bloques de datos en disco”. Esta tabla permite al sistema operativo asociar rápidamente un descriptor numérico único con la ubicación física y los atributos de control de cada fichero sin necesidad de consultar el directorio raíz en cada operación.
  
*   **Anexo A (Diagrama):**
![[Pasted image 20261107180027.png|373]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107180046.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Inodo]], [[Jerarquía de Directorios]] y [[Enlace Duro (Hard Link)]]
  
  - Referencia bibliográfica Bach, M. J. (1986). _The Design of the UNIX Operating System_. Prentice-Hall.