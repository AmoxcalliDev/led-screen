# Panel LED

Panel LED responsive para cards IoT hecho en un solo archivo HTML.

## Que hace

- Muestra texto en una matriz de LEDs.
- Si el texto cabe, lo centra.
- Si no cabe, activa marquesina de derecha a izquierda.
- Mantiene centrado vertical por filas encendidas para mejor simetria.

## Tecnologias

- HTML + JavaScript (Canvas 2D)
- Tailwind CSS via CDN

## Ejecutar

1. Abre [index.html](index.html) en el navegador.
2. Escribe el mensaje en el input.

## Configuracion actual (en [index.html](index.html))

- `rows = 22`
- `speed = 0.45`
- `alphaThreshold = 95`
- `charSpacing = 2`
- `cols` se calcula de forma dinamica segun el tamano del panel.
