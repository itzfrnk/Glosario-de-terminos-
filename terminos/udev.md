[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Gestor de Dispositivos / Userspace Device Manager

- Según Daniel P. Bovet y Marco Cesati (2005), definen que: “udev es el administrador de dispositivos del espacio de usuario para el núcleo Linux que gestiona dinámicamente los archivos de nodos de dispositivos en el directorio `/dev` en respuesta a los eventos generados por el núcleo cuando se conecta o desconecta hardware”. Este componente reemplazó a los antiguos nodos estáticos, permitiendo nombrar y configurar los dispositivos de manera flexible y automatizada mediante reglas personalizables.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107181518.png|502]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107181539.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Device Driver]] y [[sys]]
  
  - Referencia bibliográfica Bovet, D. P., & Cesati, M. (2005). _Understanding the Linux Kernel_ (3rd ed.). O'Reilly Media.