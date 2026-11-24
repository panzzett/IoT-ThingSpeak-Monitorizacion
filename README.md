# 📡 Monitorización IoT con ThingSpeak

Aplicación web (HTML + JavaScript) que se integra con la **API REST de ThingSpeak** para **enviar, leer y visualizar** las variables de un canal IoT. Muestra la última medición, una tabla histórica y una clasificación automática del estado.

> Trabajo en equipo de la asignatura *Tecnologías Emergentes* (Grado en Ingeniería Informática).

## ⚙️ Funcionalidades

- Configuración del canal: *Channel ID*, *Write API Key* y *Read API Key*.
- Envío de registros al canal mediante peticiones HTTP GET.
- Lectura de los últimos registros en JSON (`feeds.json`).
- Panel con la última medición y estado calculado.
- Histórico de lecturas en tabla.

## ▶️ Uso

1. Crear un canal en [ThingSpeak](https://thingspeak.com/) con los campos necesarios.
2. Abrir `index.html` en el navegador.
3. Introducir el *Channel ID* y las claves API propias. En el código hay marcadores de posición (`TU_API_KEY_n`) en lugar de claves reales.

## 🛠️ Tecnologías

HTML5 · JavaScript (Fetch API) · ThingSpeak · REST · JSON

📄 Detalles en `memoria_tecnica.pdf`.

---
👤 Carlos Gálvez Reguera
