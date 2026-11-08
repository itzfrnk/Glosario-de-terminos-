[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Colas Paralelas NVMe / NVMe Parallel Queues

- Según David A. Patterson y John L. Hennessy (2020), en su libro _Computer Organization and Design: The Hardware/Software Interface_, definen que: “Las colas paralelas NVMe son un mecanismo arquitectónico que permite al protocolo NVM Express gestionar hasta 64,000 colas de envío y recepción independientes, cada una con capacidad para 64,000 comandos simultáneos”. Este diseño aprovecha al máximo el paralelismo masivo de los dispositivos de estado sólido modernos y los procesadores multinúcleo, eliminando los cuellos de botella de los buses tradicionales como SATA o SAS.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107012545.png|381]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 012500.png|501]]
*   **Anexo C (Conexiones):** Se conecta con [[Protocolo NVMe]] y [[SSD]]
  
  - Referencia bibliográfica Patterson, D. A., & Hennessy, J. L. (2020). _Computer Organization and Design: The Hardware/Software Interface_ (6.ª ed.). Morgan Kaufmann. Cap. 6.