
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

# INVESTIGACIóN:
CRUD es el acrónimo de Create (Crear), Read (Leer), Update (Actualizar) y Delete (Borrar). Este concepto se utiliza para describir las cuatro operaciones básicas que pueden realizarse en la mayoría de las bases de datos y sistemas de gestión de información.

Con el tiempo, el concepto de CRUD se ha convertido en una práctica común en el diseño y desarrollo de aplicaciones de software, especialmente en aquellas que utilizan bases de datos relacionales como MySQL, Oracle, PostgreSQL, entre otras. La implementación de operaciones CRUD simplifica el proceso de desarrollo y mantenimiento del software, ya que las y los desarrolladores pueden centrarse en implementar la lógica de negocios de la aplicación en lugar de tener que preocuparse por las tareas básicas que ya describimos.

## VENTAJAS
1. Facilita la creación y gestión de datos.
2. Proporciona una estructura coherente y fácil de entender para su manipulación.
3. Ayuda a minimizar los errores y garantiza la integridad de los datos.
4. Proporciona una base sólida para el desarrollo de aplicaciones.

## DESVENTAJAS
1. Puede ser demasiado simplista para aplicaciones complejas.
2. En ocasiones, es menos eficiente para aplicaciones de alta velocidad o de gran escala.
3. A veces, requiere una gran cantidad de código y configuración para implementarlo completamente.

las operaciones CRUD son fundamentales en una amplia variedad de aplicaciones y sistemas, ya que permiten a los usuarios interactuar con los datos de manera efectiva y gestionarlos según sea necesario; por ejemplo.

### Aplicación de gestión de estudiantes:

- **Crear:** Agregar un nuevo estudiante con su nombre, número de identificación, carrera, etc.
- **Leer:** Mostrar la lista de todos los estudiantes matriculados junto con su información.
- **Actualizar:** Modificar la información de un estudiante, como cambiar su dirección o actualizar su número de teléfono.
- **Borrar:** Eliminar un estudiante que se ha graduado o ya no está activo en la institución.

### Aplicación de gestión de inventario de una tienda:

- **Crear:** Agregar un nuevo producto al inventario con su nombre, descripción, precio y cantidad disponible.
- **Leer:** Mostrar la lista de todos los productos disponibles en la tienda junto con sus detalles.
- **Actualizar:** Cambiar la cantidad disponible de un producto debido a ventas o reposiciones de inventario.
- **Borrar:** Eliminar un producto que ya no se vende o está descontinuado.

### Aplicación de redes sociales:

- **Crear:** Publicar un nuevo mensaje o estado en el perfil de un usuario.
- **Leer:** Mostrar el feed de noticias con las publicaciones más recientes de los amigos o seguidos.
- **Actualizar:** Editar un mensaje o estado existente para corregir errores o actualizar la información.
- **Borrar:** Eliminar un mensaje o estado que ya no sea relevante o que se considere inapropiado.

## Sistemas Y Programas que usan CRUD

1. **Front End**: 
 El front end de una aplicación es la parte que interactúa directamente con el usuario y proporciona una interfaz gráfica para que este pueda interactuar con la aplicación. En el contexto del CRUD, el front end se encarga de mostrar los formularios y la información de los registros, permitir la búsqueda y selección de registros

2. **Back end**: 
   El back end de una aplicación es la parte que se encarga de procesar las solicitudes del usuario, interactuar con la base o el sistema de almacenamiento de datos y realizar las operaciones CRUD. En el contexto del CRUD, el back end se encarga de recibir las solicitudes del front end, validar los datos, realizar las operaciones CRUD correspondientes y devolver los resultados al front end.

3. **UI / UX**: 
   El uso del CRUD se enfoca en la presentación y la interacción del usuario con la información almacenada en la base de datos o el sistema de almacenamiento de datos.
