[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Stack Canaries / Canarios de Pila

- Según Andrew S. Tanenbaum y Herbert Bos (2014), definen que: “Los canarios de pila (_stack canaries_) son valores centinela colocados en la pila de ejecución entre las variables locales y la dirección de retorno, diseñados para detectar desbordamientos de búfer (_buffer overflows_) antes de que se pueda secuestrar el flujo de control del programa”. Si un atacante intenta sobrescribir el búfer para modificar el puntero de retorno, el valor del canario se corrompe; el sistema detecta esta alteración antes de retornar de la función y aborta inmediatamente. 
  
*   **Anexo C (Conexiones):** Se conecta con [[Buffer Overflow]] y [[Bit NX]]
  
  - Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2014). _Modern Operating Systems_ (4th ed.). Pearson.