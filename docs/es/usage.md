# Manual de usuario
## 1 Primeros pasos
Visita [Bing](https://bing.com/search?q=pagetual) y desplázate hacia abajo, la siguiente página se unirá automáticamente.

## 2 Divisor de página
Al pasar las páginas, habrá barras espaciadoras entre ellas. El icono de Tai Chi a la izquierda de la barra espaciadora es para volver al principio de la página, y el icono a la derecha es para ir al final de la página. La palabra "Page" en el medio es el enlace de la siguiente página.
### 2.1 Experiencia inmersiva sin interrupciones
La barra divisoria de página se puede configurar para que se oculte en la página de configuración. Se pueden lograr experiencias inmersivas ocultando los divisores y añadiendo barras laterales.
### 2.2 Número de página personalizado
Si hay un `pageNum` establecido en la regla actual. Puedes hacer clic en el número después de `Page` para introducir un número de página y saltar a esa página.
### 2.3 Detener paginación
Hacer clic en la barra divisoria de página puede detener la paginación.

## 3 Menú de comandos
Haz clic en el icono de Tampermonkey y verás tres opciones bajo "Pagetual".
### 3.1 Configurar
Haz clic para ir a la página de configuración, donde se encuentran todas las configuraciones personales y la personalización de reglas.
### 3.2 Deshabilitar en el sitio
Haz clic para deshabilitar Pagetual en el sitio web actual.
### 3.3 Forzar unión
Haz clic aquí si la regla inteligente es incorrecta. El script activará el modo de empalme forzado, todo el contenido de la página siguiente se empalmará al pie de página si eliges `join full body`, de lo contrario, Pagetual cargará contenido dinámico en un iframe y los devolverá.
### 3.4 Actualizar reglas en línea
Haz clic para actualizar los elementos de reglas que has importado en línea, y Pagetual actualizará automáticamente las reglas en línea cada dos días por defecto.

## 4 Ajustes de Personalidad
Después de ir a la página de configuración, puede realizar ajustes personales, como el valor transparente del divisor, escribir historial, abrir una nueva página de pestaña y hacer doble clic para ocultar el divisor, etc.

Puede importar enlaces de reglas escritos por otras personas, o simplemente puede personalizar las reglas en el cuadro de entrada usted mismo. Las reglas del enlace admiten la clasificación y la actualización en caliente. Haga clic en las flechas hacia arriba y hacia abajo delante del enlace para ordenar, y haga clic en la hora de actualización para actualizar las reglas.
### 4.1 Escribir historial
Después de activar esta opción, Pagetual escribirá la URL de la página siguiente en el registro del historial cada vez que se pase la página, de modo que cuando haga clic en el enlace y regrese a la página anterior, volverá al número de página que navegó la última vez.
### 4.2 Abrir una nueva pestaña
Después de habilitar esta opción, todos los enlaces unidos a la página actual se abrirán en nuevas pestañas.
### 4.3 Precargar la página siguiente para acelerar la navegación
Después de abrir, al leer la página actual, Pagetual precargará todas las imágenes de la página siguiente con antelación.

## 5 [Reglas personalizadas](/rule.md)
![Reglas personalizadas](https://s3.bmp.ovh/imgs/2024/01/10/fa4f00c3e9f77878.gif)
### 5.1 Captura visual
Después de hacer clic en `Edit rule for current` (Editar regla para la actual), aparecerá un cuadro azul en la página actual siguiendo el ratón. En este momento, haz clic en el elemento correspondiente para capturar el contenido que deseas unir y convertirlo en el código del selector.
### 5.2 Ajustar el selector
Después de seleccionar el contenido del cuerpo, pasa el ratón sobre el código del selector para expandir todo el texto, puedes hacer clic para cambiar al nodo padre. Cuando introduces manualmente un selector en el cuadro de entrada, verifica el elemento correspondiente del selector haciendo clic en el botón de verificación `√`.
### 5.3 Empezar a editar
Cuando estés listo, simplemente haz clic en el icono del lápiz para saltar a la página de configuración y empezar a editar la regla.
### 5.4 Tu primera regla personalizada
Por ejemplo
```json
   {
     "name":"beauty", // nombre de la regla
     "url":"^https://www\\.beautyxxx\.com/", // regularidad de coincidencia correspondiente a la URL de la página
     "pageElement":"p>img" // El elemento que quieres insertar en la siguiente página
   }
```
Se pueden añadir otros elementos según sea necesario, como "selector para el botón de la página siguiente", "método de captura de elementos", "intervalo de tiempo de cambio de página", etc.
### 5.5 Mover la ventana del menú
Arrastra y suelta el título del menú para mover la ventana del menú.
### 5.6 Pausar el rastreo visual
Haz clic en el icono de Tai Chi en el lado izquierdo de la barra de título del menú para pausar el rastreo visual.
### 5.7 Edición rápida
Haz clic en el icono 🔽 a continuación para abrir la función de edición rápida, verifica y copia el selector a través del cuadro de entrada del selector de arriba, pégalo en el atributo correspondiente y haz clic en el icono de guardar al finalizar.
