[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Wakelocks

- Según William Stallings (2017), define que: “Los _wakelocks_ son primitivas de sincronización del núcleo que impiden que el sistema o componentes específicos de hardware entren en un estado de bajo consumo o suspensión mientras una aplicación o servicio requiera procesamiento continuo”. Este mecanismo garantiza que tareas críticas en segundo plano no se interrumpan abruptamente, aunque requiere una gestión rigurosa para evitar el consumo excesivo de batería (_drain_) por bloqueos prolongados.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107184037.png|403]]
*   **Anexo B (Comando/Código):**
  ![[Pasted image 20261107184054.png|414]]
*   **Anexo C (Conexiones):** Se conecta con [[AOSP]] y [[Determinismo Temporal]]
  
  - Referencia bibliográfica Stallings, W. (2017). _Operating Systems: Internals and Design Principles_ (9th ed.). Pearson.