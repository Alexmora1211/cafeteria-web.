# Especificación de Diseño de Software (SDD)

## Proyecto

**CafeEDEC Express**

---

# 1. Introducción

## 1.1 Propósito

El presente documento tiene como finalidad describir el diseño del sistema **CafeEDEC Express**, una aplicación web desarrollada para mejorar el proceso de compra en la cafetería del Campus EDEC.

La plataforma permitirá a los estudiantes consultar el menú, realizar pedidos desde cualquier dispositivo y recoger su comida sin necesidad de hacer largas filas.

---

## 1.2 Alcance

El sistema permitirá:

- Consultar el menú del día.
- Visualizar imágenes y precios.
- Agregar productos al carrito.
- Confirmar pedidos.
- Consultar el estado del pedido.
- Administrar el menú.
- Administrar pedidos.

El proyecto está dirigido principalmente a estudiantes, personal de cafetería y administradores.

---

# 2. Descripción General

CafeEDEC Express busca reducir el tiempo de espera dentro de la cafetería mediante una plataforma sencilla y fácil de utilizar.

Los estudiantes podrán realizar pedidos antes de llegar a la cafetería, mientras que el personal tendrá acceso a una lista organizada de pedidos para agilizar la preparación.

---

# 3. Objetivos

## Objetivo General

Desarrollar una aplicación web que permita realizar pedidos en línea para disminuir las filas dentro de la cafetería.

## Objetivos Específicos

- Reducir tiempos de espera.
- Mejorar la experiencia del estudiante.
- Facilitar la administración del menú.
- Mantener un registro de pedidos.
- Permitir consultar el estado del pedido.

---

# 4. Actores del Sistema

## Estudiante

Puede:

- Consultar menú.
- Agregar productos al carrito.
- Confirmar pedidos.
- Consultar estado.
- Realizar pago.

---

## Personal de Cafetería

Puede:

- Consultar pedidos.
- Cambiar el estado del pedido.
- Confirmar entrega.

---

## Administrador

Puede:

- Agregar productos.
- Editar productos.
- Eliminar productos.
- Actualizar precios.
- Administrar usuarios.

---

# 5. Arquitectura del Sistema

El sistema estará compuesto por tres partes principales.

## Cliente

Interfaz donde interactúan los usuarios.

Tecnologías:

- HTML5
- CSS3
- JavaScript

---

## Servidor

Encargado del procesamiento de la información.

Tecnologías propuestas:

- Node.js o PHP

---

## Base de Datos

Almacenará la información del sistema.

- Productos
- Pedidos
- Usuarios
- Historial de compras

Motor sugerido:

- MySQL

---

# 6. Reglas de Negocio

RN-01  
Solo podrán realizar pedidos los productos disponibles.

RN-02  
Cada pedido tendrá un identificador único.

RN-03  
El menú deberá actualizarse diariamente.

RN-04  
Solo el administrador podrá modificar el menú.

RN-05  
El personal únicamente podrá cambiar el estado del pedido.

RN-06  
Todo pedido deberá quedar registrado.

RN-07  
El estudiante podrá consultar el estado de su pedido en cualquier momento.

---

# 7. Requerimientos Generales

El sistema deberá ser:

- Fácil de utilizar.
- Compatible con computadoras.
- Compatible con dispositivos móviles.
- Seguro para el manejo de información.
- Rápido durante la navegación.

---

# 8. Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- Visual Studio Code
- GitHub
- Markdown
- Mermaid

---

# 9. Beneficios Esperados

- Disminuir las filas en la cafetería.
- Ahorrar tiempo a los estudiantes.
- Mejorar la organización del personal.
- Facilitar la consulta del menú.
- Optimizar el proceso de compra.

---

# 10. Conclusión

CafeEDEC Express representa una solución tecnológica para mejorar el servicio de la cafetería del Campus EDEC. Mediante una aplicación web sencilla y accesible, se busca reducir tiempos de espera y brindar una mejor experiencia tanto a estudiantes como al personal encargado del servicio.
