[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Semáforo Contador / Counting Semaphore (sem_t)

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “Un semáforo contador (_counting semaphore_) es una primitiva de sincronización cuyo valor entero puede oscilar sobre un dominio irrestricto, utilizándose para controlar el acceso a un recurso compartido que cuenta con un número finito o múltiple de instancias disponibles”. Cada operación de espera (_wait_ o _P_) decrementa el contador, mientras que la operación de señalización (_signal_ o _V_) lo incrementa, permitiendo bloquear o liberar hilos de ejecución.

*   **Anexo C (Conexiones):** Se conecta con [[Semáforo Binario]] y [[Exclusión Mutua]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 6.