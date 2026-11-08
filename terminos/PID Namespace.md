[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

PID Namespace / Espacio de Nombres de PID

- Según Robert Love (2010),  define que: “Un espacio de nombres PID (_PID namespace_) aísla el árbol de identificadores de procesos del núcleo, permitiendo que un grupo aislado de procesos mantenga su propia numeración independiente comenzando desde el PID 1”. Esta abstracción garantiza que los contenedores posean su propia jerarquía de gestión de procesos, ocultando las tareas del sistema anfitrión y de otros entornos aislados.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107155529.png|544]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107155559.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Linux Namespaces]] y [[PID (Process ID)]]
  
  Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.