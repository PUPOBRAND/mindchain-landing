# MindChain — Prototipo jugable

Demo jugable del juego de preguntas sobre Bitcoin, historia del dinero y pensamiento crítico.
Parte del ecosistema **Bitcoin sin humo**.

## Qué es este repo
Un único archivo estático (`index.html`) con todo embebido: las 120 preguntas del banco,
el logo pill-brain, estilos y lógica de juego. No requiere backend ni build.

## Deploy
Vercel detecta el `index.html` automáticamente. Sin configuración adicional.

## Contenido del prototipo
- 120 preguntas (4 tandas: base, técnica/cultura, memes, escenarios)
- Rondas de 10 preguntas con curva 4 fáciles / 4 medias / 2 difíciles
- Opciones barajadas en cada pregunta (anti-patrón)
- Sin repetición de preguntas entre rondas de la misma sesión
- Niveles: Precoiner → Orangepilleado → Consciente → Soberano
- Cadena de cápsulas como barra de progreso
- Contador de sats simulado (marcado como demo, no paga)

## Pendientes conocidos
- Rediseño propio de las imágenes de memes (hoy placeholder; los originales son de terceros)
- Bloque de aportes/boost retirado y guardado en stand-by
- Backend real (Supabase + Lightning) para la versión que paga sats

## Contacto
pupovision@gmail.com
