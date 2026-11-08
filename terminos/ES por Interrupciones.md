[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 E/S por Interrupciones / Interrupt-Driven I/O

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “La E/S por interrupciones es un mecanismo de transferencia de datos en el cual la unidad central de procesamiento (_CPU_) emite una orden de E/S a un dispositivo periférico y procede a ejecutar otras tareas, mientras el dispositivo notifica al procesador mediante una señal de interrupción de hardware en cuanto la operación de lectura o escritura ha finalizado”. Este enfoque elimina la ineficiencia del sondeo activo (_polling_), permitiendo un uso mucho más productivo del tiempo.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107073112.png|427]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 073048.png|433]]
*   **Anexo C (Conexiones):** Se conecta con [[Polling]], [[Interrupción por Hardware]] y [[DMA]]

- Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 13.