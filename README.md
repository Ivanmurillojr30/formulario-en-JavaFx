# formulario-en-JavaFx

# Diseña el siguiente formulario en JavaFx

# Descripción
Este proyecto es una aplicación JavaFX que demuestra el uso de diversos controles de interfaz de usuario en un formulario. La aplicación organiza los controles en un GridPane para crear una interfaz gráfica de usuario (GUI) intuitiva y estructurada.
 # Ilustracion d elo ejecutado 

![image](https://github.com/Ivanmurillojr30/formulario-en-JavaFx/assets/168851753/0d7c1b3b-08d9-4c7f-8507-a233d3825e6e)

# Estructura del Código

Paquete Principal

package application;

# Importaciones
Se importan las clases necesarias de JavaFX para construir la GUI, como Button, CheckBox, Hyperlink, Label, PasswordField, ProgressBar, ProgressIndicator, RadioButton, Slider, TextArea, TextField, ToggleButton, ToggleGroup, y GridPane.

# Clase Principal
![image](https://github.com/Ivanmurillojr30/formulario-en-JavaFx/assets/168851753/fc86d47c-f586-4e3a-bd73-b133fdc792cb)

# Método start
El método start inicializa el Stage principal y configura los elementos de la interfaz:

Labels: Etiquetas descriptivas para cada control.
Button: Un botón simple.
CheckBox: Una casilla de verificación.
Hyperlink: Un enlace que puede ser clicado.
ToggleButton: Un botón que mantiene su estado (activado/desactivado).
RadioButton: Un botón de radio para selecciones exclusivas.
TextField: Un campo de texto para entrada de usuario.
PasswordField: Un campo de texto para entrada de contraseñas.
TextArea: Un área de texto para entrada de texto más largo.
ProgressIndicator: Un indicador de progreso circular.
ProgressBar: Una barra de progreso.
Slider: Un control deslizante para seleccionar un valor dentro de un rango.
Agrupación de Controles
Se utiliza un ToggleGroup para agrupar los RadioButton, permitiendo selecciones exclusivas.

# Diseño de la Interfaz
Se utiliza un GridPane para organizar los controles en una cuadrícula con espacios entre filas y columnas (Hgap y Vgap), y alineación superior izquierda (Pos.TOP_LEFT).

# Configuración de la Escena
Se crea una Scene con el GridPane y se añaden los estilos desde un archivo CSS (application.css).

# Método main
El método main lanza la aplicación.

![image](https://github.com/Ivanmurillojr30/formulario-en-JavaFx/assets/168851753/abde260f-ab6d-47d6-ba5d-d27a15d0e5b6)

# Ejecución
Para ejecutar la aplicación, compila y ejecuta la clase Main en tu entorno de desarrollo Java favorito.

# Conclusion
Esta aplicación JavaFX muestra cómo utilizar y organizar diversos controles de UI en un formulario utilizando `GridPane`. Proporciona una estructura clara y un diseño intuitivo para una experiencia de usuario mejorada. Ideal para aprender y aplicar conceptos básicos de JavaFX en aplicaciones de escritorio.
