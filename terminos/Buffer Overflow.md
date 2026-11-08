[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** Buffer Overflow / Desbordamiento de Búfer

- Según Andrew S. Tanenbaum y Herbert Bos (2015), en su libro _Sistemas operativos modernos_, definen que: “Un desbordamiento de búfer ocurre cuando un programa escribe más datos en un búfer en la memoria de los que este puede contener, lo que sobrescribe ubicaciones de memoria adyacentes”. Representa una de las fallas de seguridad más críticas en la gestión de memoria de los sistemas operativos, ya que los atacantes pueden aprovechar esta vulnerabilidad para sobrescribir registros de control e inyectar código arbitrario o malicioso.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107002802.png|428]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 002841.png|485]]
*   **Anexo C (Conexiones):** Se conecta con [[Stack Canaries]] y [[Bit NX]]
  
- Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación. Cap. 9.