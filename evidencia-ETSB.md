## Tests exploratorios
### STE01 Bug 1: Errores mostrados despues de intento de envio.
- **Resumen:** Los campos inválidos se indican solo tras intentar enviar el formulario.

- **Expected Result:**  Los errores deben mostrarse a medida que se completa el formulario.

- **Actual Result:** Los errores solo aparecen después de intentar enviar el formulario.

- **Pasos para reproducirlo:**
1. Abrir la página https://with-bugs.practicesoftwaretesting.com/
2. Dirigirse a log in.
3. Ir a la pagina de registro (link en la de log in).
4. Completar los campos.
5. Enviar el formulario.

- **Ambiente:** Windows 11

- **Source URL:** https://with-bugs.practicesoftwaretesting.com/

- **Severity:** baja

- **Priority:** baja

- **Más informacion:**
El formulario no permite caracteres como acentos, lo cual es incorrecto, ya que algunos nombres propios pueden incluirlos.

![bug de contrasena](./caps/testing-exploratorio/1%20errores-contraseña.png)

![bug de tilde](./caps/testing-exploratorio/1%20tilde-invalido.png)

### STE02 Bug 1: Notificación de error
- **Resumen:** Al agregar un producto al carrito exitosamente, la notificación que se muestra es de error.

- **Expected Result:** Que se muestre una notificación de éxito.

- **Actual Result:** Se muestra notificación de error.

- **Pasos para reproducirlo:**
1. Abrir la página https://with-bugs.practicesoftwaretesting.com/
2. Loguearse.
3. En la seccion de herramientas, seleccionar una.
4. Agregar al carrito el item seleccionado.

- **Ambiente:** Windows 11

- **Source URL:** https://with-bugs.practicesoftwaretesting.com/

- **Severity:** media

- **Priority:** media

![bug de notificacion](./caps/testing-exploratorio/2%20notificacion-error.png)

### STE02 Bug 2: Formato incorrecto para incrementar la cantidad de productos

- **Resumen:** Al intentar aumentar la cantidad de productos en el carrito presionando el botón '+', la cantidad no se incrementa.

- **Expected Result:** Al presionar '+', la cantidad debería aumentar.

- **Actual Result:** La cantidad solo se incrementa ingresando un número en un campo de entrada junto al botón '+'.

- **Pasos para reproducirlo:**
1. Abrir la página https://with-bugs.practicesoftwaretesting.com/
2. Loguearse.
3. En la seccion de herramientas, seleccionar una.
4. Intentar aumentar cantidad de elementos.
5. Agregar al carrito el item seleccionado.

- **Ambiente:** Windows 11

- **Source URL:** https://with-bugs.practicesoftwaretesting.com/

- **Severity:** media

- **Priority:** alta

[Video demostrativo](./caps/testing-exploratorio/2%20boton-cantidad.mp4)


## Tests Usabilidad

