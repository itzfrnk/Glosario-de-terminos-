[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):**

 Descriptor de Archivo / File Descriptor (FD)

- Según Abraham Silberschatz, Peter B. Galvin y Greg Gagne (2018), definen que: “Un descriptor de archivo es un identificador abstracto, representado como un número entero no negativo, que el núcleo del sistema operativo utiliza para identificar y gestionar un archivo abierto u otro recurso de E/S, como una tubería o un _socket_”. Actúa como un índice dentro de una tabla de descriptores específica de cada proceso, permitiendo realizar operaciones de lectura y escritura de manera abstracta y segura. Esto aísla al espacio de usuario de los detalles físicos del hardware o de las estructuras internas de almacenamiento administradas por el núcleo.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107030644.png|404]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 030310.png|521]]
*   **Anexo C (Conexiones):** Se conecta con [[Descriptor Leak]] e [[Inodo]]
  
- Referencia bibliográfica Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). _Operating System Concepts_ (10th ed.). John Wiley & Sons. Cap. 11.