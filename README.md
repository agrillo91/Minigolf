# Club Brisa · Minigolf

Un minigolf de nueve hoyos para navegador, construido con HTML, CSS y JavaScript Canvas sin dependencias.

## Jugar

Abre `index.html` en un navegador moderno. Funciona sin conexión y admite ratón, pantalla táctil y teclado.

- Arrastra desde la bola hacia atrás y suelta para golpear.
- Flechas izquierda/derecha: dirección. Arriba/abajo: potencia. Espacio: golpear.
- Escape: cancelar el arrastre.
- Arena: frena. Agua: devuelve la bola al punto del golpe y suma una penalización.
- Baldosas con flechas: impulso. Barreras móviles: espera la oportunidad.

Completa los nueve hoyos con el menor número de golpes. La mejor puntuación se guarda localmente cuando el navegador permite almacenamiento. Reiniciar un hoyo pone su contador a cero, por lo que la tarjeta es recreativa, sin clasificación competitiva.

## Desarrollo

No requiere instalación, compilación ni servicios externos. `game.js` contiene los niveles, el motor de física de paso fijo y el renderizado. `style.css` contiene la interfaz adaptable. El sonido se sintetiza con Web Audio y está desactivado inicialmente.

La versión inicial no guarda recorridos incompletos. La cámara es fija; cada campo cabe completo en pantalla.
