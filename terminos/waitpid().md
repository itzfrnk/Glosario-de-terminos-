[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 waitpid()

- Según Maurice J. Bach (1986), define que: “La función waitpid()es una llamada al sistema que permite a un proceso padre suspender su ejecución hasta que un proceso hijo específico cambie de estado, ya sea porque ha finalizado su ejecución, se ha detenido o ha sido reanudado”. Esta rutina es esencial para la sincronización de procesos y la gestión adecuada de recursos, ya que permite recolectar el estado de salida del hijo y evita la acumulación de procesos huérfanos o zombis (_zombie processes_) en el núcleo.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107183809.png|582]]
*   **Anexo B (Comando/Código):** 
![[Pasted image 20261107183831.png]]
*   **Anexo C (Conexiones):** Se conecta con [[fork()]], [[Proceso Zombie]] y [[Estado Terminado]]
  
  
  Referencia bibliográfica Bach, M. J. (1986). _The Design of the UNIX Operating System_. Prentice-Hall.