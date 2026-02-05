- Roadmap: El Futuro de Shira Launcher -

1 - Sistema de Versiones y Modloaders
Detección Multiversión: Listado inteligente de versiones Vanilla, NeoForge, Forge y Fabric.

Auto-Inyección de SkinsRich: Descarga silenciosa del mod desde CurseForge e instalación automática en la carpeta de mods al seleccionar NeoForge 1.21.11 o 1.21.10 para una experiencia mas fluida.

Gestor de Modpacks: Capacidad de interpretar archivos de CurseForge/Modrinth para que usuarios No Premium puedan instalar modpacks que solo son jugables usando CurseForge.

2 - Rendimiento y Optimización Extrema
Inyección de Código: Optimización de Minecraft desde sus entrañas (código obfuscado) para maximizar FPS. (Mediante código inyectado o mixins - Prioridad baja)

Gestión de JVM Dinámica: Descarga automática de la versión de Java necesaria (Java 8, 17, 21, etc.) (Actualmente en progreso - Adoptium Funcionando - Faltante OpenJ9)

Soporte OpenJ9: Implementación de lógica para ajustar los argumentos de lanzamiento específicos para OpenJ9 ya que Adoptium admite argumentos que OpenJ9 no.

3 - Seguridad y Cuentas
Cifrado DPAPI (Prioridad Alta): Uso de la API de Windows para cifrar tokens de cuentas Premium. Los datos solo podrán ser descifrados en la PC que se crearon, protegiendo contra robo de cuentas en caso de un ataque por malware o virus.

Con el cifrado DPAPI viene obviamente:
Dualidad de Cuentas: Soporte para Premium y No Premium con lógica separada para los parámetros de lanzamiento (evitando el uso de parámetros no premium para cuentas reales)

4 - Experiencia de Usuario
Skins Globales en Local: Carga automática de skins premium basadas en el Nick, incluso en mundos Offline o redes LAN. (Pendiente modificación para SkinsRich - Veré que hago)

Bienvenidos a Shira-Highlight, la versión "Nightly" de mi launcher y un intento por hacer el mundo mejor.
Este es mi serie de retos a los que quiero llegar a completar sin mas, tengan un pésimo día y acuérdensen de que fumar hace mal.
