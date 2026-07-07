# UML de Casos de Uso con Diagramas Mermaid

## Proyecto

**CafeEDEC Express**

---

# Introducción

En este documento se presentan los diagramas UML elaborados con Mermaid para representar gráficamente las principales funcionalidades del sistema CafeEDEC Express. Estos diagramas muestran la interacción entre los actores y las funciones principales del sistema.

---

# Diagrama 1. Casos de Uso

```mermaid
graph LR

Estudiante((Estudiante))
Personal((Personal Cafetería))
Administrador((Administrador))

Menu((Consultar menú))
Carrito((Agregar al carrito))
Pedido((Realizar pedido))
Pago((Pagar pedido))
Estado((Consultar estado))
Preparar((Preparar pedido))
Admin((Administrar menú))

Estudiante --> Menu
Estudiante --> Carrito
Estudiante --> Pedido
Estudiante --> Pago
Estudiante --> Estado

Personal --> Preparar

Administrador --> Admin
```

---

# Descripción

Este diagrama representa las acciones principales que cada actor puede realizar dentro del sistema.

- El estudiante consulta el menú y realiza pedidos.
- El personal prepara los pedidos.
- El administrador administra el menú.

---

# Diagrama 2. Flujo del Pedido

```mermaid
flowchart TD

A[Consultar Menú]
B[Seleccionar Productos]
C[Agregar al Carrito]
D[Confirmar Pedido]
E[Realizar Pago]
F[Pedido Registrado]
G[Preparación]
H[Pedido Listo]
I[Entrega]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
```

---

# Descripción

El estudiante inicia consultando el menú, selecciona sus productos y confirma el pedido. Después de realizar el pago, el pedido es preparado por el personal hasta quedar listo para su entrega.

---

# Diagrama 3. Flujo del Administrador

```mermaid
flowchart TD

A[Iniciar Sesión]
B[Panel Administrativo]
C[Agregar Producto]
D[Editar Producto]
E[Eliminar Producto]
F[Guardar Cambios]

A --> B

B --> C
B --> D
B --> E

C --> F
D --> F
E --> F
```

---

# Descripción

Este diagrama representa las actividades del administrador para mantener actualizado el menú del sistema.

---

# Actores del Sistema

| Actor | Descripción |
|--------|-------------|
| Estudiante | Consulta el menú, realiza pedidos y consulta el estado del pedido. |
| Personal de Cafetería | Recibe los pedidos y actualiza su estado durante la preparación. |
| Administrador | Gestiona el menú y administra los productos disponibles. |

---

# Beneficios de utilizar UML

- Facilita la comprensión del sistema.
- Permite identificar las funciones principales.
- Mejora la comunicación entre los integrantes del proyecto.
- Sirve como apoyo durante el desarrollo del software.

---

# Conclusión

Los diagramas UML permiten representar de manera gráfica el funcionamiento general de CafeEDEC Express. Gracias a Mermaid, estos diagramas pueden visualizarse directamente desde Visual Studio Code o GitHub, facilitando la documentación y el mantenimiento del proyecto.
