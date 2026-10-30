# JUNKERS-CAR-WASH (repo duplicado / borrador)

## Para qué sirve
Solo contiene una **pantalla de acceso con PIN de 4 dígitos** para un sistema de Junkers Car Wash. No tiene el resto del sistema.

## Para qué empresa
JUNKERS CAR WASH (lavadero de autos).

## Cómo está armado (archivos principales)
- `index.html` — única página (≈150 líneas): teclado de PIN que, al acertar, manda a `dashboard.html`.
- Esa página pide archivos que **NO existen** en el repo: `css/style.css`, `assets/logo.png`, `js/firebase-config.js`, `js/auth.js` y `dashboard.html`. Por eso, publicada, no funciona.
- Un solo commit ("Add files via upload", 31/07/2026). Sin versiones.

## Dónde se guardan los datos
En ninguna parte desde este repo: carga Firebase (versión 9) pero la configuración estaba en `js/firebase-config.js`, que no se subió.

## Cómo se publica
GitHub Pages activo en https://jmenachocntx.github.io/JUNKERS-CAR-WASH/ (sin dominio propio, no hay `CNAME`). Muestra la pantalla de PIN, pero no puede iniciar sesión.

## Cuidados importantes
- **Este repo es un DUPLICADO viejo.** El sistema real y completo del lavadero está en `Sistema-NUMMEROS-Junkers-CARWASH` (usa Firebase proyecto `sistema-contax-junkers-carwash`). Hacer los cambios allá, no aquí.
- Recomendación: desactivar GitHub Pages y archivar este repo, para que nadie entre a una página rota.
- El repositorio es PÚBLICO: si alguna vez se suben los archivos que faltan, no incluir claves ni PIN.
