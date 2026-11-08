[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Copia al Escribir / Copy-on-Write (CoW) 

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “La copia en escritura es una técnica de gestión de recursos que permite que el proceso padre y el proceso hijo compartan inicialmente las mismas páginas de memoria, evitando la duplicación innecesaria; solo cuando uno de los procesos intenta modificar una página, el sistema operativo crea una copia privada de esa página específica”. Esta optimización mejora drásticamente el rendimiento en la creación de procesos  y en la gestión del sistemas.
  
  
*   **Anexo C (Conexiones):** Se conecta con [[fork()]] y [[Memoria Virtual]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 3.