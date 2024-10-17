Este examen practico es parte de la materia de Desarrollo de aplicaciones web y móviles en la Universidad Autónoma de Chiapas (UNACH). Su propósito es desarrollar la lógica de programación del BackEnd para gestionar un inventario básico de productos.
Tecnologías utilizadas

•	Bootstrap
•	jQuery(Ajax)
•	PHP
•	MySQL como sistema de gestión de bases de datos.

Funcionalidades
Registrar producto:
Cuando haces clic en "Nuevo Producto", se abre un modal donde llenas el nombre, precio y la cantidad en existencia. Al enviar, se guarda en la base de datos con ayuda de insertar.php y te muestra un mensaje de confirmación.

Editar producto:
Junto al botón de eliminar hay un ícono para editar. Si lo presionas, abre otro modal con los datos del producto ya llenos, para que puedas modificarlos y guardarlos.

Eliminar producto:
Si quieres borrar un producto, solo haz clic en el ícono rojo. Al hacerlo, se llama a eliminar.php y el producto desaparece. Después, se redirige automáticamente al dashboard.

Inicio de sesión:
La app valida que el usuario exista en la base de datos con validar.php. Una vez dentro, aparece tu nombre completo en la barra superior, gracias a una variable de sesión.
