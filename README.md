# Prototipo Sistema-de-pedidos
Prototipo de interfaz (HTML, CSS y Bootstrap) de una tienda online para un negocio de sándwiches y completos, cuyo único canal de pedidos hoy es el WhatsApp personal del dueño, lo que genera saturación de mensajes, falta de registro centralizado y de trazabilidad de los pedidos.

La solución permite al cliente ver un catálogo de productos personalizables, generar su pedido con datos de contacto, elegir retiro en local o despacho a domicilio, seleccionar su medio de pago y recibir notificaciones por WhatsApp sobre el estado del pedido. Además incluye un panel de gestión para el cajero y los dueños, que centraliza los pedidos de todos los canales, asigna despachos a repartidores externos y restringe el acceso a los datos de los clientes solo a personal autorizado.

El repositorio contiene **solo la interfaz** (prototipo); no incluye backend ni base de datos.

## Integrantes

| Nombre completo | Usuario de GitHub |       Rama        |
| Diego Quispe    |    `@Dfvg898`     | `feature/dquispe` |
| Leonel Humire   |   `@manzana728`   | `feature/lhumire` |
| Alonso Molina   |     `@vlonzz`     | `feature/amolina` |

## Framework de estilos

Bootstrap 5 , más archivos CSS propios por gestor.

## Gestores e historias de usuario

El proyecto tiene 30 historias de usuario (HU) agrupadas en 8 gestores. El reparto es de 10 HU por integrante.

| Gestor                                | HU incluidas                             | N° de HU | Responsable   | Rama              |
|---------------------------------------|------------------------------------------|----------|---------------|-------------------|
| Gestor de Pedidos (panel interno)     | HU-13, HU-14, HU-15, HU-16, HU-26, HU-29 | 6        | Diego Quispe  | `feature/dquispe` |
| Gestor de Catálogo                    | HU-01, HU-02, HU-03, HU-04               | 4        | Diego Quispe  | `feature/dquispe` |
| Gestor de Pagos y Comprobantes        | HU-09, HU-10, HU-23, HU-24, HU-25        | 5        | Leonel Humire | `feature/lhumire` |
| Gestor de Historial y Reportes        | HU-22, HU-30                             | 2        | Leonel Humire | `feature/lhumire` |
| Gestor de Delivery                    | HU-17, HU-18, HU-19                      | 3        | Leonel Humire | `feature/lhumire` |
| Gestor de Datos del Cliente y Entrega | HU-05, HU-06, HU-07, HU-08               | 4        | Alonso Molina | `feature/amolina` |
| Gestor de Notificaciones              | HU-11, HU-12, HU-27, HU-28               | 4        | Alonso Molina | `feature/amolina` |
| Gestor de Acceso y Seguridad          | HU-20, HU-21                             | 2        | Alonso Molina | `feature/amolina` |
| **Total**                             |  **30**                                                                          |