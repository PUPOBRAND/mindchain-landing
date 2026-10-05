# MindChain — Prototipo jugable

Demo jugable del juego de preguntas sobre Bitcoin, historia del dinero y pensamiento crítico.
Parte del ecosistema **Bitcoin sin humo**.

En vivo: https://jugar-mindchain.vercel.app

## Qué es este repo
Un único archivo estático (`index.html`) con todo embebido: el banco de preguntas,
el logo pill-brain, estilos y lógica de juego. No requiere backend ni build.
Usa además `favicon.png`, `apple-touch-icon.png` y `og-image.png` del repo.

## Contenido
- 166 preguntas en el banco, 146 activas, en 7 categorías: Bitcoin Básico, Historia & Satoshi, Economía Honesta, Conciencia & Filosofía, Inflación & Bancos, Libertad & Futuro, Seguridad & Custodia
- Modos: ronda al azar (`/`), pregunta del día (`/?hoy=1`) y rondas temáticas (`/?set=seguridad`, `/?set=criterio`, `/?set=circular`)
- Rondas de 10 preguntas · curva 4 fáciles / 4 medias / 2 difíciles
- Opciones barajadas en cada pregunta y sin repetir preguntas entre rondas
- Niveles: Precoiner → Orangepilleado → Consciente → Soberano
- Cadena de cápsulas como barra de progreso
- Contador de sats simulado (marcado como demo: no paga)

## Pendientes
- Arte propio para los memes que siguen dormidos (7 ya tienen arte y están activos)
- Backend real (Supabase + Lightning) para pagos en sats
- Bloque de aportes: activo solo con `/?boost=1`

## Contacto
laprimadesatoshi@gmail.com
