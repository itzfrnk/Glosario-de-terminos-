[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Cuotas de CPU / cpu.max

- Según Tejun Heo (2019), define que: “El archivo `cpu.max` especifica la cuota de tiempo de CPU permitida para los procesos dentro de un grupo de control (_cgroup_), limitando el uso total del procesador en un periodo de tiempo determinado mediante los parámetros `quota` y `period`”. Este mecanismo de limitación estricta previene que un contenedor o grupo de procesos acapare los recursos de procesamiento del sistema.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107024852.png|339]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 024411.png|442]]
*   **Anexo C (Conexiones):** Se conecta con [[cgroups v2]] y [[Límites de RAM (memory.max)]]
  
  - Referencia bibliográfica Heo, T. (2019). _Control Group v2_. The Linux Kernel Documentation.