[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Proceso Zombie / Zombie Process (Defunct Process)

- Según W. Richard Stevens y Stephen A. Rago (2013), definen esta figura como: “Un proceso que ha terminado pero cuyo padre aún no ha obtenido su estado de salida mediante la llamada wait se denomina un proceso zombie”. Este proceso zombie mantiene temporalmente su entrada en la tabla de procesos reservando el identificador PID.
  
*   **Anexo C (Conexiones):** Se conecta con [[Proceso Huérfano]], [[waitpid()]] y [[Proceso]]
  
- **Referencia bibliográfica**
Stevens, W. R., & Rago, S. A. (2013). _Advanced Programming in the UNIX Environment_ (3.ª ed.). Addison-Wesley. Cap. 8.