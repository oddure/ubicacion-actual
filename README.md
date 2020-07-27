# ubicacion-actual
Determinar la ubicación actual con Android Studio(java) y Mapbox.
El proyecto está basado en el ejemplo proporcionado por Mapbox en su pagina oficial
Disponible en https://docs.mapbox.com/android/maps/examples/location-component-basic-pulsing/

El ejemplo mencionado una vez que se ejecuta y detecta que el GPS del móvil está desactivado genera un error
y cierra la aplicación. En éste proyecto se resuelve esé problema y permite que la app se ejecute correctamente.

Observación:
  - Ecribir la Apikey  en : res>values> strings>acces_token
  - El botón "back"  se desactiva una vez que haya empezado a ejecutarse el "progressdialog"  para  evitar
  interrupcines durante la determinacion de la ubicación. 
  - En la primera ejecución tarda más de 5 minutos aproximadamente en determinar la posición (tengaaciencia :) )
