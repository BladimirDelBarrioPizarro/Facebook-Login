FACEBOOK LOGIN

    https://developers.facebook.com/
    https://developers.facebook.com/docs/facebook-login/web -> Copiar html
    
    Cambiar {app-id} -> Mis aplicaciones (copiar identificador)

      window.fbAsyncInit = function() {
    FB.init({
      appId      : '{app-id}',
      cookie     : true,                     // Enable cookies to allow the server to access the session.
      xfbml      : true,                     // Parse social plugins on this webpage.
      version    : ''v2.8'           // Use this Graph API version for this call.
    });

    // XAMPP
    Instalación -> https://vitux.com/how-to-install-xampp-on-your-ubuntu-18-04-lts-system/
    1.phpMyAdmin
    2.htdocs (mover la carpeta del proyecto) 
    3. En el navegador localhost/{nombre aplicación}