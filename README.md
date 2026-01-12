# VR-Unity-3D


Temario clásico

- Google Cardboard y Oculus Rift
- Input
- Mecánica en juegos de VR

**Integración CardBoard**

Importar SDK de Unity
1. Abrir Unity - > Proyecto 3D
2. Windows > Package Manager
3. Importar CardBoard (no existen ya)
4. Ir a samples > Import into Project
5. Add Open Scene > Hello CardBoard

**Integración Oculus Rift**

Usar GearVR
1. Crear un proyecto vacío
2. Cambiar plataforma a Android > Edits > ProjectSettings> Dentro de Other Settings [OK] Virtual Reality Support
3. Incluir un archivo signature (firma) de Oculus file
4. Se construye. Insertar el dispositivo a Headset y ver el skybox con el seguimiento de la cabeza (headtracking)

**Input mecánica en juegos de VR**
Crear un mundo en el que formar parte o ser protagonista.
Ej: Ver una casa sin construir, pilotar un aviñon o montar en una montaña rusa.
VR habitualmente ha sido soportado por plugins externos a Unity.

Contras:
- Cada dispositivo tiene plugin diferente.
- Los plugins entran en conflicto entre sí
- Cambiar plugins para soportar multiples dispositivos: trabajo extra
- Cambiar entre VR y no VR no es trivial
- Optimizaciones de bajo nivel en motores no son posibles

El VR de Unity agrega tener dispositivos VR sin plugins externos. Este proporciona una API base y caracteresticas contando con compatibilidad para dispositivos y software. 
La API se irá expandiendo con los años.

**Mecánicas que intervienene en la realidad virual:**
- Gráficos 3D: permiten tener una percepción real de lo que se verán en las gafas.
- Técnicas estereoscópica: da a los gráficos 3D profundidad y realismo. Superponiendo dos imagenes paralelas se consigue esa sensación de profundidad.
- Simulacion del comportamiento: los movimientos del presonaje son improvisados y tienen multiples variables en evolución.
- Facilidad a la hora de navegar: a la hora de controlar al personaje tiene su propia visión que se fusiona en la aplicación. Hace el desarrollo más intuitivo.
- Técnica de inmersión total: las gafas VR aislan del mnd real, se consigue inmersión más completa. El sonido y la vista son sentidos que más estímulos reciben.

