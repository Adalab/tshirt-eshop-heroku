
# ¿Cómo desplegar este repo en Heroku?

Estos son los pasos a seguir para publicar este servidor en un servidor de producción de [Heroku](heroku.com).

1. Registrarse en heroku.com:
   1. Confirmar email.
   1. Acerptar terminos del servicio.
1. Crear una aplicación:
   1. Al pulsar en **Create new app**, hay que elegir:
      1. Nombre de la aplicación. No puede existir otro igual, ni si quiera que lo haya usado otra usuaria.
      1. Choose a region: Europe.
   1. En la pestaña deploy, hay que elegir:
      1. Deployment method.
      1. GitHub. Connect to GitHub > Hacer login.
      1. Elegir repo **tshirt-eshop-heroku**.
      1. Pulsa en Conectar.
      1. En el apartado Automatic deploys pulsar en Enabled automatic deploys:
         - Con esto hacemos que cada vez que se suba algo a master se despliegue automáticamente la nueva versión del servidor.
      1. Forzamos un despliegue pulsando Deploy branch en el apartado Manual deploy:
         - Con esto hacemos un despliegue manual, el primero.
1. Para ver la aplicación pulsar en Open app.
1. Mostrar pestaña Activity
1. Mostrar botón More > View logs