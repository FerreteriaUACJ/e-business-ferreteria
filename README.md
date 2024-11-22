# E-Business Ferretería
## Descripción
E-Business Ferretería es una plataforma diseñada para gestionar una tienda ferretera en línea, ofreciendo funcionalidades como registro de usuarios, catálogo de productos, carrito de compras, procesamiento de pagos, y gestión de inventario para administradores. El proyecto tiene como objetivo mejorar la experiencia de compra de los clientes y optimizar la administración de la tienda.
## Características
- **Registro y autenticación de usuarios:** Permite a los clientes crear cuentas y acceder al sistema.
- **Catálogo de productos:** Visualización de una lista completa de productos con detalles como precios y calificaciones.
- **Carrito de compras:** Agregar, modificar y eliminar productos antes de completar la compra.
- **Procesamiento de pagos:** Integración con pasarelas de pago seguras.
- **Gestión de inventario:** Funcionalidades específicas para que los administradores agreguen, editen y reciban alertas sobre el stock de productos.
- **Historial de compras:** Visualización de las compras realizadas con opción de descarga de comprobantes.
## Requisitos del Sistema
- **Backend:** Node.js con Express (o el framework que estés utilizando).
- **Frontend:** React.js (o el framework correspondiente).
- **Base de datos:** MySQL (o la base de datos configurada).
- **Dependencias principales:** 
  - Axios
  - Sequelize
  - JSON Web Tokens (JWT) para autenticación.
Introducción
En la actualidad, la digitalización de negocios es fundamental para incrementar su alcance, optimizar procesos internos y mejorar la experiencia del cliente. Una ferretería tradicional enfrenta desafíos en la gestión de inventarios, ventas y atención al cliente, especialmente en un mercado donde las compras en línea son cada vez más demandadas. Este proyecto tiene como objetivo diseñar e implementar un sistema de e-business para una ferretería, facilitando la interacción con los clientes y automatizando procesos esenciales como la gestión de productos, pagos y pedidos.
El propósito de este proyecto es desarrollar un sistema de información que permita a la ferretería ofrecer sus productos en línea, gestionando su inventario y permitiendo a los usuarios finales realizar compras de manera fácil, rápida y segura. Adicionalmente, se busca optimizar las operaciones administrativas, mejorar la satisfacción del cliente y aumentar las ventas al abrir un nuevo canal de distribución.
Información General del Proyecto
Nombre del Proyecto: e-business-ferretería
Descripción: Proyecto de desarrollo de un e-business para una ferretería con gestión de inventario y compras en línea.
. Épicas y Historias de Usuario
Épica 1: Registro y Autenticación de Usuarios
Como usuario, quiero poder registrarme en el sistema
Criterios de aceptación:
•	- Debo poder ingresar mi nombre, correo electrónico y una contraseña para crear una cuenta.
•	- Recibir un mensaje de confirmación cuando el registro sea exitoso.
Como usuario, quiero iniciar sesión en mi cuenta
Criterios de aceptación:
•	- Debo poder ingresar mi correo electrónico y contraseña para acceder al sistema.
•	- Mostrar un mensaje de error si las credenciales son incorrectas.
Como usuario, quiero poder restablecer mi contraseña si la olvido
Criterios de aceptación:
•	- Puedo solicitar un enlace de recuperación mediante mi correo electrónico.
•	- Recibir un correo con instrucciones para restablecer mi contraseña.
Épica 2: Catálogo de Productos
Como usuario, quiero poder ver una lista de productos disponibles en el catálogo
Criterios de aceptación:
•	- Los productos deben mostrar nombre, descripción, precio y disponibilidad.
Como usuario, quiero buscar productos por nombre o categoría
Criterios de aceptación:
•	- Puedo ingresar un término de búsqueda o seleccionar una categoría para filtrar los resultados.
Como usuario, quiero ver los detalles de un producto específico
Criterios de aceptación:
•	- Debo poder seleccionar un producto y visualizar su descripción, precio, y disponibilidad.
Épica 3: Carrito de Compras
Como usuario, quiero poder agregar productos al carrito de compras
Criterios de aceptación:
•	- Puedo seleccionar un producto y añadirlo al carrito con una cantidad específica.
Como usuario, quiero ver un resumen de los productos en mi carrito
Criterios de aceptación:
•	- Deben mostrarse los nombres, cantidades, precios y total acumulado.
Como usuario, quiero poder modificar o eliminar productos del carrito
Criterios de aceptación:
•	- Puedo cambiar la cantidad de un producto o eliminarlo completamente del carrito.
Épica 4: Sistema de Pagos
Como usuario, quiero realizar un pago seguro para completar mi compra
Criterios de aceptación:
•	- El sistema debe solicitar los datos de mi tarjeta o método de pago.
•	- Recibir una confirmación cuando el pago sea exitoso.
Como usuario, quiero elegir entre diferentes métodos de pago
Criterios de aceptación:
•	- Deben estar disponibles al menos dos métodos de pago (tarjeta de crédito/débito y PayPal).
Épica 5: Gestión de Inventario (Administrador)
Como administrador, quiero poder agregar nuevos productos al inventario
Criterios de aceptación:
•	- Debo poder registrar el nombre, descripción, precio, y cantidad inicial de un producto.
Como administrador, quiero editar los detalles de un producto existente
Criterios de aceptación:
•	- Debo poder modificar el nombre, precio, descripción o cantidad disponible.
Como administrador, quiero recibir alertas cuando el stock de un producto sea bajo
Criterios de aceptación:
•	- El sistema debe notificarme si el inventario de un producto cae por debajo de una cantidad mínima definida.
Épica 6: Notificaciones
Como usuario, quiero recibir una confirmación de mi pedido después de realizar una compra
Criterios de aceptación:
•	- El sistema debe enviarme un correo con el resumen de mi pedido y el número de referencia.
Como usuario, quiero recibir notificaciones del estado de mi pedido
Criterios de aceptación:
•	- El sistema debe informarme sobre el envío y entrega del pedido.
Épica 7: Historial de Compras
Como usuario, quiero poder ver un historial de todas mis compras anteriores
Criterios de aceptación:
•	- Debe mostrarse la lista de pedidos con la fecha, productos comprados y el total pagado.
Como usuario, quiero poder descargar un comprobante de mi compra
Criterios de aceptación:
•	- Debo tener la opción de descargar un recibo en formato PDF.
Épica 8: Opiniones y Calificaciones
Como usuario, quiero poder dejar una calificación y comentario sobre un producto que compré
Criterios de aceptación:
•	- Solo puedo dejar comentarios sobre productos que he comprado.
Como usuario, quiero ver las calificaciones y comentarios de otros usuarios sobre los productos
Criterios de aceptación:
•	- Los comentarios deben mostrar el nombre del usuario, la calificación y el texto.
Objetivo del sistema
Desarrollar un e-business para una ferretería que permita la venta en línea de productos, gestionando el inventario y facilitando el proceso de compra y pago, mediante la integración de tecnologías modernas y herramientas de gestión de proyectos.
Objetivos Específicos
1.	Implementar un sistema de registro y autenticación para usuarios y administradores.
2.	Diseñar un catálogo de productos interactivo con descripciones, precios y disponibilidad.
3.	Integrar un carrito de compras funcional que permita la selección y modificación de productos antes del pago.
4.	Desarrollar un sistema de pagos en línea seguro, compatible con tarjetas de crédito/débito y otras plataformas de pago.
5.	Proporcionar al administrador herramientas para la gestión del inventario y notificaciones de bajo stock.
6.	Incluir funcionalidades de notificaciones, historial de compras y opiniones de usuarios para enriquecer la experiencia del cliente.
Alcance del Proyecto
Este sistema se enfocará en:
•	Proveer una plataforma en línea para la venta de productos ferreteros.
•	Optimizar la administración de inventario, mostrando productos disponibles en tiempo real.
•	Ofrecer una experiencia de usuario intuitiva tanto para clientes como para el administrador del sistema.
•	Asegurar la protección de datos y transacciones mediante protocolos de seguridad modernos.


Requerimientos funcionales
Requerimientos Funcionales: Aquellos que describen lo que el sistema debe hacer.
•	Registro y autenticación de usuarios.
•	Visualización del catálogo de productos.
•	Gestión del carrito de compras.
•	Sistema de pagos en línea.
•	Gestión de inventario.
•	Envío de notificaciones.
•	Historial de compras.
•	Opiniones y calificaciones.
 
Requerimientos no funcionales
Requerimientos No Funcionales: Restricciones o condiciones bajo las que el sistema debe operar.
•	Seguridad en el registro y manejo de datos de usuario.
•	Respuesta rápida de la aplicación (menor a 2 segundos).
•	Escalabilidad para soportar 1000 usuarios simultáneamente.
•	Compatibilidad con navegadores modernos y dispositivos móviles.
