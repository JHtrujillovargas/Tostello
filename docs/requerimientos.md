# Requerimientos de Tostello

**Versión:** 1.0

## Descripción del negocio

Tostello es una boutique de ropa y artículos de segunda mano. Vende prendas de vestir, zapatos, bolsos, juguetes y otros artículos seleccionados, en buen estado y a precios accesibles, buscando ofrecer una experiencia de compra agradable.

Cada producto es único: existe una sola unidad de cada uno, por lo que cada artículo tiene su propio código, sus propias fotos y la descripción de su estado.

La página web funcionará principalmente como una tienda virtual donde los clientes puedan explorar el catálogo, armar un carrito, hacer pedidos, elegir un método de pago y consultar el estado de su pedido.

## Actores

- Cliente: persona que visita la tienda, explora el catálogo, busca productos por categoría o código, arma un carrito y hace pedidos sin necesidad de crear una cuenta. Puede consultar el estado de su pedido con su código de pedido y su correo.
- Administrador: persona del equipo de Tostello que gestiona la tienda desde un panel protegido con acceso restringido. Crea, edita y marca como vendidos los productos, revisa los pedidos, confirma los pagos y actualiza el estado de cada pedido.

## Historias de usuario (MVP)

| ID | Actor | Historia |
|----|-------|----------|
| HU-01 | Cliente | Como cliente quiero ver el catálogo para conocer qué hay disponible. |
| HU-02 | Cliente | Como cliente quiero ver fotos, descripción, talla, estado y precio para decidir si compro. |
| HU-03 | Cliente | Como cliente quiero filtrar por categoría y buscar por código para encontrar rápido lo que busco. |
| HU-04 | Cliente | Como cliente quiero agregar productos al carrito para comprar varios a la vez. |
| HU-05 | Cliente | Como cliente quiero hacer un pedido con mis datos de envío para recibirlo. |
| HU-06 | Cliente | Como cliente quiero elegir un método de pago para completar mi compra. |
| HU-07 | Cliente | Como cliente quiero consultar el estado de mi pedido para saber cuándo llegará. |
| HU-08 | Administrador | Como administrador quiero crear, editar y marcar como vendidos los productos para mantener el catálogo al día. |
| HU-09 | Administrador | Como administrador quiero ver los pedidos y cambiar su estado para gestionar las ventas. |

## Requerimientos no funcionales

- **Móvil primero:** la página debe verse y funcionar bien en celulares.
- **Rendimiento:** las fotos deben cargar rápido sin perder calidad.
- **Seguridad:** las contraseñas se guardan cifradas y el panel de administración solo es accesible con credenciales.
- **Disponibilidad única:** un producto solo puede ser vendido a un cliente; el sistema debe evitar ventas duplicadas.

## Fuera del MVP (fases posteriores)

- Pasarela de pagos (Wompi, PayU)
- Cuentas de usuario
- Notificaciones automáticas por correo o WhatsApp
- Lista de favoritos

