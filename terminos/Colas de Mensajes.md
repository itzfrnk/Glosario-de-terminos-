[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** Colas de Mensajes / Message Queues

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), en su obra _Operating System Concepts_, definen que: “Una cola de mensajes es un mecanismo de comunicación interprocesos (IPC) que permite a los procesos intercambiar datos mediante el envío y la recepción de mensajes estructurados depositados en un búfer gestionado por el núcleo del sistema operativo”. Facilita la sincronización y la comunicación desacoplada entre procesos concurrentes, ya que los remitentes y receptores no necesitan interactuar de forma simultánea. El sistema operativo administra el orden de entrega y el almacenamiento temporal de los datos, optimizando la flexibilidad en la arquitectura de software concurrente.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107011531.png|269]]
*   **Anexo B (Comando/Código):**
  ![[Screenshot 2026-11-07 011236.png|476]]

![[Screenshot 2026-11-07 011300.png|326]]
*   **Anexo C (Conexiones):** Se conecta con [[IPC]] y [[Binder IPC]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 3.