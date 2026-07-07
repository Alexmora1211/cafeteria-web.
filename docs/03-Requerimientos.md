# Requerimientos Funcionales y Criterios de Aceptación

## Proyecto

**CafeEDEC Express**

---

# Introducción

Este documento describe los requerimientos funcionales y no funcionales del sistema CafeEDEC Express. Estos requerimientos definen las funciones que deberá cumplir la aplicación para satisfacer las necesidades de los estudiantes, el personal de cafetería y el administrador.

---

# Requerimientos Funcionales

## RF-01 Consultar Menú

### Descripción

El sistema deberá permitir que los estudiantes consulten el menú disponible del día.

### Criterios de aceptación

- Mostrar nombre del producto.
- Mostrar imagen.
- Mostrar precio.
- Mostrar disponibilidad.
- El menú deberá actualizarse diariamente.

---

## RF-02 Buscar Productos

### Descripción

El estudiante podrá buscar productos mediante un cuadro de búsqueda.

### Criterios de aceptación

- Buscar por nombre.
- Mostrar resultados relacionados.
- Si no existen resultados, mostrar un mensaje.

---

## RF-03 Agregar Productos al Carrito

### Descripción

El estudiante podrá agregar uno o varios productos al carrito de compras.

### Criterios de aceptación

- Agregar diferentes productos.
- Modificar cantidades.
- Calcular automáticamente el total.

---

## RF-04 Eliminar Productos del Carrito

### Descripción

El estudiante podrá eliminar productos antes de confirmar el pedido.

### Criterios de aceptación

- Eliminar cualquier producto.
- Actualizar el total automáticamente.

---

## RF-05 Confirmar Pedido

### Descripción

El sistema permitirá registrar el pedido del estudiante.

### Criterios de aceptación

- Generar un número de pedido.
- Registrar la fecha y hora.
- Guardar el pedido en la base de datos.
- Mostrar mensaje de confirmación.

---

## RF-06 Consultar Estado del Pedido

### Descripción

El estudiante podrá visualizar el estado actual de su pedido.

### Criterios de aceptación

Los estados disponibles serán:

- Pendiente.
- En preparación.
- Listo.
- Entregado.

---

## RF-07 Pago del Pedido

### Descripción

El estudiante podrá realizar el pago desde la aplicación.

### Criterios de aceptación

- Seleccionar método de pago.
- Registrar el pago.
- Generar comprobante.

---

## RF-08 Administración del Menú

### Descripción

El administrador podrá administrar los productos disponibles.

### Criterios de aceptación

- Agregar productos.
- Editar productos.
- Eliminar productos.
- Actualizar precios.

---

## RF-09 Administración de Pedidos

### Descripción

El personal de cafetería podrá consultar los pedidos recibidos.

### Criterios de aceptación

- Visualizar pedidos.
- Cambiar estado del pedido.
- Confirmar entrega.

---

# Requerimientos No Funcionales

## RNF-01 Usabilidad

La interfaz deberá ser sencilla e intuitiva para cualquier usuario.

---

## RNF-02 Rendimiento

Las páginas deberán cargar en un tiempo menor a 3 segundos con una conexión estable.

---

## RNF-03 Compatibilidad

El sistema deberá funcionar correctamente en:

- Google Chrome.
- Microsoft Edge.
- Mozilla Firefox.

Además, deberá ser compatible con computadoras, tablets y teléfonos móviles.

---

## RNF-04 Seguridad

La información de los pedidos deberá almacenarse de forma segura y únicamente el administrador tendrá acceso a las funciones administrativas.

---

## RNF-05 Disponibilidad

El sistema deberá estar disponible durante el horario de servicio de la cafetería.

---

## RNF-06 Mantenibilidad

El sistema deberá permitir futuras actualizaciones del menú y nuevas funcionalidades sin afectar el funcionamiento general.

---

# Resumen de Requerimientos

| Código | Requerimiento |
|---------|---------------|
| RF-01 | Consultar menú |
| RF-02 | Buscar productos |
| RF-03 | Agregar productos al carrito |
| RF-04 | Eliminar productos del carrito |
| RF-05 | Confirmar pedido |
| RF-06 | Consultar estado del pedido |
| RF-07 | Pago del pedido |
| RF-08 | Administración del menú |
| RF-09 | Administración de pedidos |

---

# Conclusión

Los requerimientos funcionales y no funcionales establecen las características que deberá cumplir CafeEDEC Express para ofrecer una solución eficiente, segura y fácil de utilizar. Estos servirán como base para el desarrollo, las pruebas y la validación del sistema.
