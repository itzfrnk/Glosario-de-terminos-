[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Seccomp / Secure Computing Mode

- Según William Stallings (2017), define que: “Seccomp (_Secure Computing Mode_) es un mecanismo de aislamiento y seguridad a nivel de núcleo que restringe las llamadas al sistema (_syscalls_) que un proceso en espacio de usuario tiene permitidas ejecutar”. Esta herramienta defensiva minimiza la superficie de ataque en entornos de contenedores y aplicaciones endurecidas, bloqueando operaciones no autorizadas mediante políticas estrictas o filtros basados en BPF (_Berkeley Packet Filter_).

*   **Anexo A (Diagrama):**
![[Pasted image 20261107170820.png|567]]
*   **Anexo B (Comando/Código):
  ![[Pasted image 20261107170840.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Linux Capabilities]] y [[Contenedor]]
  
  - Referencia bibliográfica Stallings, W. (2017). _Operating Systems: Internals and Design Principles_ (9th ed.). Pearson.