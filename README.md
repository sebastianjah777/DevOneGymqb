# DevOneGymqb
🚴‍♂️💪 Este script ofrece un gimnasio realista para servidores de FiveM, permitiendo a los jugadores entrenar y mejorar su personaje con un sistema interactivo y progresivo. Incluye:  Estaciones de ejercicios con animaciones específicas. Escalado visual del personaje. Interacciones con props
1. Arquitectura del Script:

Modularidad: El script se divide en módulos claros: inicialización, detección de interacciones, lógica de ejercicios y progresión del jugador.
Compatibilidad: Integra sistemas como qb-core, qb-target, y ox-target para la detección de zonas de interacción.
NUICallback: Se utiliza para manejar interacciones personalizadas a través de interfaces HTML/CSS, como registros de progreso y estadísticas.

2. Funciones Principales:

Detección de Props:
Usa nativos de GTA para identificar máquinas y props cercanos.
Dispara interacciones al acercarse al rango adecuado.

Progresión del Jugador:
Escalado visual del personaje según el progreso.

Animaciones:
Asociadas a cada máquina o prop, sincronizadas con la actividad realizada.
Horarios y Penalizaciones:
Lógica de horarios de apertura del gimnasio.
Penalizaciones por inactividad en estadísticas.

3. Elementos Específicos:

Configuración de Props: Lista predefinida de identificadores de máquinas.
Sistema de XP: Incrementa la experiencia con cada ejercicio.
Sincronización: Datos almacenados en la base de datos mediante eventos del servidor.

4. Eficiencia y Optimización:

Uso eficiente de eventos del cliente y del servidor para minimizar el impacto en el rendimiento del servidor.
Estrategias para evitar redundancias en la detección de props y animaciones.
Esta estructura asegura escalabilidad, realismo y una experiencia inmersiva para los jugadores.
