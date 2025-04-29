# 🤖 YesNo App

**YesNo App** es una aplicación desarrollada en Flutter que responde a tus preguntas con un **"Sí" o "No"**, acompañando la respuesta con una imagen divertida tomada desde internet.

---

## ❓ ¿Cómo funciona?

1. El usuario escribe una pregunta en la app (por ejemplo: *¿Debería salir hoy?*).
2. Al enviar la pregunta, la app consulta una API y responde con:
    - Un **"Yes"** o **"No"** aleatorio.
    - Una imagen que acompaña visualmente la respuesta.
3. Las respuestas se muestran en una lista estilo chat, para que puedas ver el historial.

---

## 🎯 Objetivo del proyecto

Esta aplicación fue creada para aplicar y consolidar conocimientos de Flutter, trabajando con:

- Entrada de texto y control del teclado
- Peticiones HTTP y carga de imágenes desde internet
- Gestión de widgets y diseño responsive
- Manejo de listas dinámicas tipo chat
- Aplicación de estilos personalizados con `ThemeData`

---

## 🧱 Tecnologías y widgets utilizados

- `TextEditingController`, `FocusNode`
- `ThemeData`, `Container`, `SizedBox`, `Expanded`, `Padding`, `ListView`
- `Image.network`, `ClipRRect` (bordes redondeados)
- Widgets personalizados (`CustomWidgets`)

---

## 🛠️ Cómo usarla

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/yes_no_app.git
   cd yes_no_app

2. Instala las dependencias:
    ```bash
   flutter pub get
3. Ejecuta la app:
   ```
   flutter run


