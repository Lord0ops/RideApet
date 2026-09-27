# 🐾🏇 Ride a Pet Hub

Script para el juego de Roblox **Ride a Pet** con su propia interfaz para activar y desactivar cada función.

## Cargar el script

Pega esto en tu executor (cambia `TU_USUARIO` y `TU_REPO` por los de este repositorio):

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/main/RideAPetHub.lua"))()
```

## Controles

| Acción | Cómo |
| --- | --- |
| Mostrar / ocultar UI | `RightControl` (se puede cambiar en **Ajustes**) o el botón flotante 🐾 |
| Mover la ventana | Arrastra la barra superior |
| Minimizar | Botón `–` |
| Cerrar el hub | Botón `✕` o **Ajustes → Cerrar Hub** |

## Funciones

| Pestaña | Contenido |
| --- | --- |
| 🏠 **Panel** | Dinero, huevos en la parcela, próxima eclosión y todas las automatizaciones con su interruptor y estado en vivo. |
| 🥚 **Huevos** | **📖 Menú de huevos** (espera en tu base y recoge los huevos marcados en cuanto aparecen), **⚙️ Ajustes de recogida**, **🌋 Volcanic Egg** (entra y sale del volcán por la puerta), **✨ Auto Mutación Magma**, **🔔 Aviso por Discord** y **👁️ ESP**. |
| 🏡 **Base** | Tu base, **Auto Colocar huevos**, **ESP de huevos colocados** y **Auto Eclosionar**. |
| 🐾 **Mascotas** | **Auto Equipar mejores**, **Auto Cobrar**, **Auto Alimentar** y velocidad de montura. |
| 📈 **Progreso** | **Auto Rebirth**, **Auto Mejorar parcela** y **Auto Reclamar gratis**. |
| 🏃 **Jugador** | Velocidad, salto, volar, noclip, anti-AFK. |
| ⚙️ **Ajustes** | Tecla de la UI, guardado automático, rejoin, cambiar de servidor y cerrar. |

La configuración se guarda sola. Funciona con autoexec.

## Notas

- Algunas funciones dependen del executor (`fireproximityprompt`, `firetouchinterest`, `writefile`, `request`).
- Usar scripts puede violar los Términos de Servicio de Roblox. Úsalo bajo tu propio riesgo.
