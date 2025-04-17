# Sommerfeld-Bot
sommerfeld bot is a simple bot for discord with support Python and Json.

## 📁 Estructura del paquete

Sommerfeld/
├── Sommerfeld.exe               
├── token.txt  
│
├── commands/               
│   ├── comandos.json            
│   ├── redescreator.json         
│   └── hola.py                   
│
├── datos/                        
│   └── requirements.txt 
│
├── LEEME, SON LOS COMANDOS.txt   # Archivo de texto con los comandos disponibles.


---

## ⚙️ ¿Cómo usar?

1. Abre el archivo `token.txt` y pega tu token de bot de Discord. (puedes conseguirlo en el Discord Developer Portal)
2. Ejecuta el archivo `Sommerfeld.exe`.
3. El bot estará listo en tu servidor con los comandos habilitados.

---

## 🧩 Tipos de comandos

- **Comandos JSON (`!comando`)**  
  Personalizables sin modificar el código. Solo crea un archivo `.json` en la carpeta `commands`.

- **Comandos Python (`&comando`)**  
  Escribe código Python en archivos `.py` dentro de `commands/`. También soportan `enabled`.

---

## 📚 Ejemplos

### JSON (`commands/redescreator.json`)
```json
{
  "command": "redescreator",
  "description": "Muestra los enlaces del creador del bot.",
  "enabled": true,
  "response": "Este bot fue creado por **Sommer**.\\n[Repositorio de Sommer](https://github.com/Sommervt)"
}
```

### Estructura de Python:
command = "hola"
enabled = True

async def run(message):
    await message.channel.send(f"¡Hola {message.author.name}! Soy un comando en Python.")

## ¿Quieres el código fuente?
Esta versión solo incluye el ejecutable y archivos esenciales.
Si deseas el código fuente completo con documentación técnica, deberás Esperar la versión de desarrollador. Incluye notas del autor y soporte extendido. 

## --Autor:
Sommerfeld -- ig:<a href="https://www.instagram.com/nothing_.ez?igsh=MW5nOG9rejBmd3Z3dA==" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
</a>
 
