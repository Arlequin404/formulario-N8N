# Formulario de Registro de Intereses

Este proyecto es un formulario web moderno y responsivo diseñado para capturar información de contacto e intereses de los usuarios. Está integrado con un webhook de n8n para procesar los datos enviados.

## 🚀 Características

-   **Diseño Premium:** Interfaz limpia y moderna utilizando Tailwind CSS con efectos de hover y transiciones suaves.
-   **Validación de Datos:** Asegura que el usuario complete todos los campos obligatorios y seleccione al menos una área de interés.
-   **Estado de Carga:** Incluye un indicador visual (spinner) mientras se procesa el envío de datos.
-   **Notificaciones en Tiempo Real:** Feedback visual mediante mensajes de éxito o error tras el envío.
-   **Integración con Webhook:** Envío de datos en formato JSON a un endpoint de automatización (n8n).

## 🛠️ Tecnologías Utilizadas

-   **HTML5:** Estructura semántica del formulario.
-   **Tailwind CSS:** Estilizado rápido y responsivo mediante clases de utilidad.
-   **JavaScript (Vanilla):** Lógica de validación, manejo del DOM y peticiones asíncronas (Fetch API).
-   **CSS Personalizado:** Animaciones para el cargador y efectos de sombra.

## 📋 Campos del Formulario

1.  **Nombre Completo:** Campo de texto obligatorio.
2.  **Teléfono:** Campo numérico/teléfono obligatorio.
3.  **Edad:** Campo numérico con validación de rango (1-120).
4.  **Áreas de Interés:** Checkboxes (Programación, Automatización, Negocio).
5.  **Correo Electrónico:** Validación de formato de email.

## ⚙️ Configuración

El formulario envía los datos a la siguiente URL de webhook:
`https://n8n-73qy.onrender.com/webhook-test/formulario`

Para cambiar el destino de los datos, simplemente modifica la constante `webhookUrl` en la sección `<script>` del archivo `index.html`.

## 💻 Cómo Usar

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` en cualquier navegador web moderno.
3.  Completa los campos y presiona "Enviar Registro".

---
Desarrollado con ❤️ para la gestión eficiente de datos.
