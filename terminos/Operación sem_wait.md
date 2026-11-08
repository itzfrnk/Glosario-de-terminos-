[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Operación sem_wait / sem_wait() (Wait o P)

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “`sem_wait()` es una función del sistema que decrementa el valor de un semáforo; si el valor resultante es menor que cero, el proceso o hilo llamante se bloquea automáticamente y se añade a la cola de espera del recurso”. Esta operación atómica se emplea para controlar el acceso concurrente a secciones críticas y garantizar la exclusión mutua.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107153227.png|411]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107153252.png|548]]
*   **Anexo C (Conexiones):** Se conecta con [[Semáforo Contador (sem_t)]], [[Operación sem_post]] y [[Sección Crítica]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 6.