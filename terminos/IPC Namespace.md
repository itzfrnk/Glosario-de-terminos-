[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

IPC Namespace / Espacio de Nombres de IPC

- Según Robert Love (2010), define que: “Un espacio de nombres IPC es una característica de aislamiento del kernel que aísla los recursos de comunicación interprocesos —tales como las colas de mensajes System V, los semáforos y los bloques de memoria compartida— entre distintos grupos de procesos”. Al empaquetar estos mecanismos dentro de un namespace independiente, los contenedores evitan que procesos en entornos aislados interfieran o accedan a los canales de comunicación de otros contenedores o del propio sistema anfitrión.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107115211.png]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 115238.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Linux Namespaces]] y [[IPC]]
  
  - Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.