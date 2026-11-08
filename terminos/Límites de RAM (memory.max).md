[[00 - Índice General|Volver al Índice General]]

**Término técnico (Español e Inglés):** 

Límites de RAM / memory.max 

- Según Robert Love (2010), define que: “Un límite de memoria es un mecanismo de control implementado mediante grupos de control (_cgroups_) que restringe la cantidad máxima de RAM y espacio de intercambio (_swap_) que un conjunto de procesos puede consumir”. Esta restricción permite al núcleo del sistema operativo prevenir que procesos descontrolados o aplicaciones con fugas de memoria agoten los recursos globales, activando políticas de protección como el _OOM Killer_ para preservar la estabilidad del sistema.

*   **Anexo A (Diagrama):**
![[Pasted image 20261107135128.png|429]]
*   **Anexo B (Comando/Código):** 
  ![[Pasted image 20261107135158.png|484]]
*   **Anexo C (Conexiones):** Se conecta con [[cgroups v2]], [[Contenedor]] y [[Cuotas de CPU (cpu.max)]]
  
- Referencia bibliográfica Love, R. (2010). _Linux Kernel Development_ (3.ª ed.). Addison-Wesley Professional.