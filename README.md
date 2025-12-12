# MinIOS (web)

Este es un mini "sistema" hecho en HTML/CSS para practicar. Tiene una pantalla de bloqueo y después un escritorio con íconos tipo apps. Cuando haces clic en un ícono, se abre una "ventana" con la app (en realidad es un iframe).

## Qué tiene

*   **Pantalla de bloqueo (`index.html`)**: muestra una hora/fecha y un botón Log In para entrar al escritorio.
*   **Escritorio (`main.html`)**: tiene íconos en el escritorio y en una barra (dock). Cada ícono abre una ventana.

### Apps que ya vienen:
*   Chrome (iframe)
*   Notas (iframe)
*   Calculadora (iframe)
*   Apple Music (iframe)
*   Administrador de archivos (iframe)
*   Productividad (iframe)

## Cómo funciona

En `main.html` cada ícono es un link que apunta a una sección por su `id`, por ejemplo `href="#chromeWindow"`. Esa sección es la ventana (con un header y un iframe adentro).

## Archivos importantes

*   `index.html` = pantalla de bloqueo
*   `main.html` = escritorio y ventanas
*   `style.css` = estilos del lock screen
*   `main.css` = estilos del escritorio/ventanas
*   `Images/` = íconos que se usan en el escritorio/dock
*   `apps/` = páginas HTML que se cargan dentro de las ventanas (iframes)

## Cómo abrirlo

### Opción rápida
1.  Abre `index.html` en tu navegador.
2.  Dale a *Log In* para ir a `main.html`.
3.  Queda listo para usarlo.
