[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Bit de Presencia / Present Bit (Valid Bit)

· Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “Cada entrada de la tabla de páginas tiene un bit de validez o de presencia asociado. Si el bit se establece en 1, la página correspondiente está en la memoria física; si se establece en 0, la página no está actualmente en la memoria física”. Esto actúa como un indicador de control para que la MMU detecte si los datos están disponibles de inmediato en la memoria principal.

*   **Anexo A (Diagrama):**
![[Pasted image 20261106234912.png|347]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-06 234433.png|543]]

![[Screenshot 2026-11-06 234455.png|374]]
*   **Anexo C (Conexiones):** Se conecta con [[PTE (Page Table Entry)]] y [[Fallo de Página (Page Fault)]]
  
  ·**Referencia bibliográfica** Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Fundamentos de sistemas operativos_ (9.ª ed.). McGraw-Hill. Cap. 9.