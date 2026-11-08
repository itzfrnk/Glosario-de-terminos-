[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):

 Espera Circular / Circular Wait

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), en su obra _Operating System Concepts_, definen que: “La espera circular es una condición necesaria para que se produzca un interbloqueo (_deadlock_), la cual se manifiesta cuando existe un conjunto de procesos $\{P_0, P_1, \dots, P_n\}$ tal que cada proceso espera por un recurso que se encuentra retenido y es propiedad del siguiente miembro de la cadena, conformando un ciclo cerrado de dependencias”. Esta situación bloquea de manera permanente a todos los procesos involucrados, ya que ninguno puede liberar su recurso ni continuar su ejecución.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107075044.png|350]]
*   **Anexo B (Comando/Código):**
  ![[Screenshot 2026-11-07 075019.png|381]]
*   **Anexo C (Conexiones):** Se conecta con [[Condiciones de Coffman]] y [[Prevención de Interbloqueos]]
  
  - Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 8.