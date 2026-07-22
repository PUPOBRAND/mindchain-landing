# MindChain — Prototipo jugable

Demo jugable del juego de preguntas sobre Bitcoin, historia del dinero y pensamiento crítico.
Parte del ecosistema **Bitcoin sin humo**.

En vivo: https://jugar-mindchain.vercel.app

## Qué es este repo
Un único archivo estático (`index.html`) con todo embebido: las 120 preguntas del banco,
el logo pill-brain, estilos y lógica de juego. No requiere backend ni build.
Usa además `favicon.png`, `apple-touch-icon.png` y `og-image.png` del repo.

## Contenido
- 120 preguntas en 6 categorías (fundamentos, técnica y cultura, memes, escenarios)
- Rondas de 10 preguntas · curva 4 fáciles / 4 medias / 2 difíciles
- Opciones barajadas en cada pregunta y sin repetir preguntas entre rondas
- Niveles: Precoiner → Orangepilleado → Consciente → Soberano
- Cadena de cápsulas como barra de progreso
- Contador de sats simulado (marcado como demo: no paga)

## Pendientes
- Rediseño propio de las imágenes de los memes (hoy placeholder)
- Backend real (Supabase + Lightning) para pagos en sats
- Bloque de aportes/boost: diseñado y en stand-by

## Contacto
laprimadesatoshi@gmail.com
