# bootstrap_form

![image](https://github.com/edwinmoreno77/bootstrap_form/blob/main/assets/form.png)

# Payment Form Example

Este es un formulario de pago simple que permite a los usuarios seleccionar una región y una ciudad en función de la región seleccionada.
El formulario incluye campos de entrada para el número de tarjeta y CVC, junto con validación del lado del cliente utilizando JavaScript y Bootstrap.

## Descripción

El formulario permite a los usuarios realizar una selección dinámica de ciudad según la región elegida, gracias a un objeto de JavaScript que almacena las ciudades por región.
Además, el formulario cuenta con validación que asegura que los campos sean completados correctamente antes de enviar.

### Características

- **Validación de formulario**: El formulario verifica que los campos sean completados correctamente antes de enviarlo.
- **Selección dinámica de ciudad**: Al seleccionar una región, las ciudades correspondientes a esa región se cargan automáticamente en el selector de ciudad.
- **Estilos de Bootstrap**: El formulario está diseñado utilizando los estilos de Bootstrap para asegurar que se vea bien en diferentes dispositivos.
- **Alertas de error**: Si algún campo obligatorio no está completado, se muestra una alerta indicando que faltan datos.

## Instalación

Para usar este proyecto, simplemente clona el repositorio o descarga los archivos y abre el archivo `index.html` en tu navegador.

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
open index.html
