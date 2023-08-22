# Propuesta TP DSW

## Grupo
### Integrantes
* 49879--Aloi--Vicente
* 49939--Bochatay--Mauricio
* 50179--Mariani--Valentino
* 49878--Pizzicotti--Sebastian

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
 Diseñar y desarrollar una página web interactiva para la compra y venta de celulares, que permita a los clientes explorar un catálogo de productos, realizar compras y gestionar sus pedidos. Además, el sitio debe contar con un panel de administración seguro y fácil de usar, donde el administrador puede agregar, modificar y eliminar productos, gestionar inventario, supervisar transacciones y realizar otras tareas administrativas necesarias para el funcionamiento óptimo del sitio.

### Modelo
Presentamos el siguiente DER, que cumple con las reglas de negocio propuestas.
![imagen del modelo]('https://drive.google.com/file/d/11AA0wYvpriZMYcnujtVh3KU1ldogZcWR/view?usp=sharing');

## Alcance Funcional 
Reglas de Negocio:
- Un producto se identifica con una id, que se asignara automaticamente por el sistema.
- De un producto se tiene id,modelo,marca,stock,color y descripcion.
- Un usuario se identifica por su dni, tambien se tiene nombre, apellido, email y password para validar su ingreso.
- Un cliente es un usuario que solo podra realizar compras u busquedas sobre el producto que busca, tendra registrada una tarjeta de credito o debito.
- Un administrador tendrá un conteo de cantidad de publicaciones que realizó.
- Ambos(clientes y administradores) serán un usuario pero con diferentes funcionalidades.
- Una venta puede tener un envio el cual dependerá de la misma, tiene un idEnvio,
  costoBasePorKm y un domiciolio.
- De un domicilio se registrará codPostal, calle y nro. En base a eso se calculará el costo total del envio.

Requerimientos:

- Validar usuario / administrador
- Registrar, Actualizar y Borrar productos 
- Registrar, Actualizar y Borrar Clientes
- Registrar Ventas 
- Informar ventas en un periodo de tiempo determinado.
- Mostrar Listado de administradores y la cantidad de publicaciones.
- Mostrar listado de clientes hasta el momento.
- Mostrar Productos en stock.




