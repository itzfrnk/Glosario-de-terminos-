[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

**init.rc / Archivo de Configuración de Inicialización (Android)**

- Según Robert Love (2010), define que: “`init.rc` es el archivo de configuración principal basado en scripts que el proceso `init` de Android procesa durante la arrancada (_boot_) para inicializar el sistema de archivos, configurar servicios esenciales del sistema (_daemons_) y establecer las propiedades del entorno de ejecución”. Este archivo utiliza un lenguaje declarativo propietario para definir acciones, comandos y activadores (_triggers_) que determinan el orden en que se levantan los componentes del espacio de usuario sobre el núcleo Linux.

*   **Anexo A (Diagrama):**
![[Screenshot 2026-11-07 111347.png]]
*   **Anexo B (Comando/Código):** 
  ![[Screenshot 2026-11-07 111420.png]]
*   **Anexo C (Conexiones):** Se conecta con [[Init Systemd]] y [[AOSP]]
  
- Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.