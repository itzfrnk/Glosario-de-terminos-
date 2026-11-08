[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

fork()

- Según W. Richard Stevens y Stephen A. Rago (2013), definen indicando: “Un proceso existente puede crear uno nuevo llamando a la función fork, la cual es llamada una vez, pero retorna dos veces: una en el padre y otra en el hijo”. La función fork es la técnica primitiva fundamental en entornos UNIX para duplicar los procesos en ejecución.

*   **Anexo A (Diagrama):**
![[Screenshot 2026-11-07 091118.png|520]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 091210.png]]
*   **Anexo C (Conexiones):** Se conecta con [[execve()]], [[Copy-on-Write (CoW)]] y [[Proceso Zombie]]
  
  - **Referencia bibliográfica**
Stevens, W. R., & Rago, S. A. (2013). _Advanced Programming in the UNIX Environment_ (3.ª ed.). Addison-Wesley. Cap. 8.