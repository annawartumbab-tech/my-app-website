# Sitio web para Google Play — GitHub Pages

## Publicación
1. Crea un repositorio de GitHub o abre el existente.
2. Sube **el contenido de este archivo ZIP** a la raíz del repositorio (index.html, policy/, .nojekyll, README.md).
3. Abre Settings → Pages → Build and deployment → Deploy from a branch.
4. Selecciona `main` y `/(root)` y pulsa Save.
5. Abre la URL publicada y comprueba el enlace a la política de privacidad.

## Direcciones
- Inicio: `https://USUARIO.github.io/REPOSITORIO/`
- Política: `https://USUARIO.github.io/REPOSITORIO/policy`
- Si utilizas el repositorio `USUARIO.github.io`, la dirección será `https://USUARIO.github.io/policy`.

GitHub Pages dirige inicialmente `/policy` a `/policy/` porque sirve `policy/index.html`. La página quita la barra final del navegador con `history.replaceState`. **No se usa `.html` en el enlace público.** El redirect inicial del servidor no puede desactivarse en GitHub Pages.

## Privacidad y Google Play
La política está en español y declara, conforme a lo indicado por el propietario, que no se recogen ni transmiten datos. Comprueba que esto refleje el comportamiento real de la aplicación, sus SDK, servicios de reserva y conexiones de red. Haz que la política también esté disponible dentro de la aplicación, y mantén la sección Data safety de Play Console coherente con los hechos. Si se almacenan o transmiten reservas, identificadores, datos técnicos u otros datos, debes modificar la política y tus declaraciones antes de publicarla.

Paquete: `com.dineely.android.app`  
Contacto: `support@doradorest.com`
