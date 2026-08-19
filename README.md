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
| Tabla de puntuaciones | Mantener `TAB` |
| Pantalla completa | `F11` o `Alt + Enter` |
| Captura de pantalla | `F12` |
| Volver al menú | `ESC` |

---

## 🏆 Cómo se gana

La partida rota de arena automáticamente al llegar a **50 bajas** entre todos los
jugadores. Recoge botiquines, escudos y mejoras de velocidad repartidos por el
mapa, y vigila el radar del HUD: marca enemigos y objetos cercanos.

¡Buena caza! 🔫
