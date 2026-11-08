[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Kernel Monolítico vs Emulado

- Según Andrew S. Tanenbaum y Herbert Bos (2015),  Robert Love (2010), y define que: “Un **kernel monolítico** ejecuta todos los servicios del sistema operativo  como la gestión de procesos, la memoria, la pila de red y los controladores de dispositivos  en un único espacio de direcciones del núcleo (_kernel space_) con privilegios máximos, ofreciendo un alto rendimiento a costa de una menor tolerancia a fallos. Por otro lado, un **kernel emulado** (o capa de emulación del núcleo) simula las llamadas al sistema (_syscalls_) y comportamientos de una arquitectura o sistema operativo distinto mediante una capa intermedia de traducción en el espacio de usuario o hipervisor, lo que permite la compatibilidad binaria entre plataformas heterogéneas con una penalización en la velocidad de ejecución”.


*   **Anexo C (Conexiones):** Se conecta con [[Núcleo Monolítico]] y [[Máquina Virtual]]
  
  Referencia bibliográfica Tanenbaum, A. S., & Bos, H. (2015). _Sistemas operativos modernos_ (4.ª ed.). Pearson Educación. Cap. 1.
Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional. Cap. 1.