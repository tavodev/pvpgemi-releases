# 🎮 PVPGEMI — Cómo jugar

Bienvenido a la arena. Esta guía es para **jugar**, no para programar: elige tu
sistema, sigue tres pasos y estás dentro.

---

## 🪟 Windows

1. Descomprime el archivo `pvpgemi-vX.Y.Z-windows-x64.zip` en cualquier carpeta.
2. Doble clic en **`pvpgemi_client.exe`**.
3. Windows mostrará un aviso azul de *"Windows protegió su PC"*. Es normal: el
   juego no está firmado con un certificado comercial. Pulsa
   **`Más información`** → **`Ejecutar de todas formas`**.

> No hace falta instalar nada más. El ejecutable ya lleva todo dentro.

---

## 🍎 macOS (Apple Silicon e Intel)

1. Descomprime `pvpgemi-vX.Y.Z-macos.zip`.
2. Doble clic en **`JUGAR.command`** (no en `pvpgemi_client` directamente).
3. La primera vez macOS puede preguntar si quieres abrirlo: acepta.

> `JUGAR.command` existe porque macOS bloquea las aplicaciones descargadas de
> internet que no están firmadas por Apple. El script retira esa marca y arranca
> el juego. Si prefieres hacerlo a mano:
> ```bash
> xattr -dr com.apple.quarantine /ruta/a/la/carpeta
> ./pvpgemi_client
> ```

---

## 🐧 Linux

1. Descomprime el paquete:
   ```bash
   tar -xzf pvpgemi-vX.Y.Z-linux-x86_64.tar.gz
   cd pvpgemi-vX.Y.Z-linux-x86_64
   ```
2. Da permisos de ejecución y arranca:
   ```bash
   chmod +x pvpgemi_client
   ./pvpgemi_client
   ```

> Si falta alguna librería gráfica, instala las de X11/OpenGL de tu distribución:
> ```bash
> # Debian / Ubuntu
> sudo apt install libx11-6 libxrandr2 libxi6 libxcursor1 libxinerama1 libgl1
> ```

---

## 🌐 Entrar a la partida online

### Datos del servidor

| Campo | Valor |
| :--- | :--- |
| **IP Servidor** | `74.208.117.242` |
| **Puerto UDP** | `7001` |
| **Contraseña** | *te la pasa Tavo por privado* |

En el menú principal:

1. Escribe tu **Apodo**.
2. Rellena la **IP del servidor** y el **Puerto** que te haya pasado quien lo aloja.
3. Escribe la **Contraseña** del servidor (déjala vacía si no tiene).
4. Pulsa **`CONECTAR AL SERVIDOR 3D`**.

¿Sólo quieres probar el juego sin conectarte a nadie? Pulsa
**`JUGAR LOCAL 3D (3 BOTS IA)`** y empiezas al instante contra bots.

### Si no consigues entrar

| Mensaje | Qué significa |
| :--- | :--- |
| *Version del juego incompatible* | Tienes una versión distinta a la del servidor. Pide el paquete actualizado. |
| *Contrasena incorrecta* | Revisa la contraseña (distingue mayúsculas y minúsculas). |
| *El servidor esta lleno* | Hay 16 jugadores dentro. Espera un momento. |
| *Tiempo de espera agotado* | IP o puerto mal escritos, o el servidor está apagado. |

---

## ⌨️ Controles

| Acción | Tecla |
| :--- | :--- |
| Moverse | `W` `A` `S` `D` |
| Mirar / Apuntar | Ratón |
| Disparar | `Clic Izquierdo` |
| Dash / Impulso | `Espacio` o `Clic Derecho` |
| Salto vertical 3D | `C` o `R` |
| Tabla de puntuaciones | Mantener `TAB` |
| Menú de Ajustes / Pausa | `ESC` |
| Pantalla completa | `F11` o `Alt + Enter` |
| Captura de pantalla HD | `F12` |

---

## ⚡ Arsenal y Hologramas 3D

Todos los objetos y armas flotan en la arena como hologramas 3D identificados con placas flotantes superiores legibles a distancia:

| Categoría | Armas / Ítems | Efecto Especial |
| :--- | :--- | :--- |
| **Estándar** | Pistola, Rifle de Asalto, Escopeta, Subfusil Dual | Balística directa para combate cercano y medio alcance. |
| **Pesadas** | Francotirador de Riel, Lanzamisiles, Minigun | Alto impacto, daño de área y fuego de saturación. |
| **Exóticas 🔥** | **Cañón Tesla** | Ráfagas continuas de arco voltaico de alta velocidad (920 m/s). |
| **Exóticas 🔥** | **Lanza Hojas (Sawblade)** | Discos de plasma que rebotan hasta 3 veces en paredes. |
| **Exóticas 🔥** | **Cañón de Vórtice** | Dispara una singularidad gravitatoria que succiona a los rivales. |
| **Power-Ups** | Botiquín (+40 HP), Escudo (+35), Sobrecarga Speed | Curación inmediata, blindaje y multiplicadores temporales. |

---

## 🔥 Combos de Multi-Kills y Rachas de Bajas

Eliminar enemigos de forma consecutiva (<4.0s) o encadenar bajas sin morir activa fanfarrias sonoras y banners centrales:

- **Multi-Kills**: `DOUBLE KILL` (x2), `TRIPLE KILL` (x3), `QUAD KILL` (x4), `CYBER SLAYER` (x5+).
- **Rachas de Bajas**: `KILLING SPREE` (3), `RAMPAGE` (5), `DOMINATING` (7), `GODLIKE` (10).

---

## 🎨 Personalización de Personaje / Operativo

¡Dile adiós a ser todos iguales! Ahora puedes personalizar completamente la identidad visual de tu operativo antes de entrar a la arena:

Pulsa **`PERSONALIZAR OPERATIVO`** en el menú principal o durante la pausa para abrir el **Estudio de Personalización 3D**:

- **Color de Armadura Primario (10 Opciones)**: Cyan Neón, Rojo Carmesí, Verde Ácido, Amarillo Cyber, Magenta Synthwave, Naranja Eléctrico, Púrpura Sombrío, Blanco Ártico, Negro Midnight, Dorado Apex.
- **Color de Visor / Neón (8 Opciones)**: Azul Neón, Rojo Furia, Amarillo Sol, Verde Matrix, Violeta Neón, Naranja Fuego, Rosa Cyber, Blanco Puro.
- **Estilo de Armadura (4 Clases con siluetas 3D únicas)**:
  - *Vanguard*: Coraza táctica equilibrada y hombreras modulares.
  - *Juggernaut*: Blindaje reforzado pesado, placa pectoral y hombreras dobles masivas.
  - *Cyber Ninja*: Placas aerodinámicas biseladas y aletas dorsales cortantes.
  - *Striker*: Alas de propulsión y toberas de enfriamiento neón.
- **Accesorio de Casco / Cabeza (6 Opciones)**:
  - *Visor Táctico*: Visera de combate reforzada.
  - *Cuernos Oni*: Cuernos cibernéticos con puntas luminosas.
  - *Corona Neón*: Halo holográfico suspendido sobre el casco.
  - *Cyber Mohawk*: Cresta energética vertical de alto impacto.
  - *Antenas Comm*: Doble antena táctica con balizas de comunicación.
  - *Goggles Tri-Eye*: Sensor óptico de visión nocturna con triple lente.
- **Vista Previa 3D Interactiva**: Haz clic y arrastra con el ratón en la ventana 3D para rotar a tu personaje 360° en tiempo real sobre el pedestal cibernético, y usa la rueda del ratón para hacer zoom.
- **Bots IA Únicos**: Los bots ahora también tienen apariencias y colores temáticos distintos entre sí según su nombre.
- **Identificación en Partida**: Los colores de armadura y visor se reflejan en el modelo 3D, en las placas holográficas sobre la cabeza, en la brújula táctica y en la tabla de puntuaciones (`TAB`).

---

## ⚙️ Menú de Ajustes y Opciones

Pulsa **`AJUSTES / OPCIONES`** en el menú o **`ESC`** durante la partida para configurar:
- **Sensibilidad de Ratón**: Ajuste fino del sensor.
- **Campo de Visión (FOV)**: 60° a 110° para mayor visibilidad periférica.
- **Volumen Master y SFX**: Control de mezcla de sintetizadores procedurales.
- **Dificultad de Bots**: `FÁCIL`, `NORMAL`, `DESAFÍO`.
- **Intensidad de Screen Shake**: Activa o suaviza el temblor de impacto.
- *Los ajustes y la personalización se guardan automáticamente en `settings.cfg`.*

---

## 🏆 Cómo se gana

La partida rota de arena automáticamente al llegar a **50 bajas** entre todos los
jugadores. Recoge botiquines, escudos y mejoras repartidos por el
mapa, y vigila la brújula táctica del HUD superior: marca enemigos y puntos cardinales.

¡Buena caza! 🔫
