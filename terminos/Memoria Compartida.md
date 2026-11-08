[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Memoria Compartida / Shared Memory

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “La memoria compartida es un mecanismo de comunicación entre procesos (_IPC_) en el cual dos o más procesos comparten una región del espacio de direcciones virtuales, permitiendo un intercambio de datos rápido y directo sin la intervención del núcleo”. Al eliminar la necesidad de copiar datos entre búferes del sistema operativo, este método ofrece el mayor rendimiento de transferencia, requiriendo sincronización para evitar condiciones de carrera.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107142532.png|403]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107142602.png|433]]
*   **Anexo C (Conexiones):** Se conecta con [[IPC]], [[mmap()]] y [[shmem]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 3.