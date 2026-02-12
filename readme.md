# Productos y clientes

## Modelos
Client, Product y Order

## Endpoints MVC
- `GET /`: dvuelve una home con todos los clientes, pedidos y productos.

De Client:
- `GET /client`: devuelve todos los clientes
- `POST /client`: inserta un cliente
- `PUT /client/{id}`: actualiza el cliente
- `DELETE /client/{id}`: elimina cliente

De Order:
- `GET /order/create`: devuelve formulario de creación de order que un desplegable con clientes y otro con productos. Debe elegir uno de cada, e insertarlo en la BD
- `POST /order`: llega desde el endpoint anterior y guarda en la bd el pedido seleccionado.

