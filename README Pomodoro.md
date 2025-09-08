# 🍅 Pomodoro Timer

Una aplicación web minimalista y elegante para aplicar la técnica Pomodoro y mejorar tu productividad. Permite personalizar los tiempos de trabajo y descanso, incluye sugerencias para pausas activas y lleva un registro de pomodoros completados.

## ✨ Características

- ⏰ Temporizador configurable (trabajo/descanso)
- 📊 Barra de progreso visual
- 🔔 Sonido de alarma al cambiar de fase
- 💡 Sugerencias aleatorias para descansos activos
- 📱 Diseño responsive (funciona en móviles y desktop)
- 🎨 Interfaz moderna con Tailwind CSS

## 🚀 Cómo usar

1. Establece los minutos de trabajo y descanso
2. Haz clic en "Iniciar" para comenzar
3. Tópate un descanso cuando suene la alarma
4. Usa las sugerencias para aprovechar tus pausas
5. Reinicia cuando necesites empezar de nuevo

## 🛠️ Tecnologías

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript Vanilla

## 📦 Instalación

No requiere instalación. Solo abre el archivo `index.html` en tu navegador.

## 🔧 Personalización

Puedes modificar los tiempos predeterminados editando los valores en los inputs:
```html
<input id="inputWork" type="number" min="1" value="30">
<input id="inputBreak" type="number" min="1" value="5">
