# Propuesta TP DSW

## Grupo

### Integrantes

- 56473 - Heidel, Alan
- 49953 - Fracassi, Santiago

### Repositorios

- [FrontEnd](https://github.com/AlanHeidel/utnfrro-frontend)
- [BackEnd](https://github.com/AlanHeidel/utnfrro-backend)

## Tema

### Descripción

Se trata del sistema para gestionar los pedidos en un bar o restaurante. Los clientes al sentarse en una mesa pueden ingresar y hacer un pedido que será visualizado por un administrador, eventualmente aceptado y posteriormente servido por un mozo. Adicionalmente se permitirá realizar reservas de las mesas por parte de los clientes.

### Modelo

[![](https://mermaid.ink/img/pako:eNqNVV1v2jAU_SuRpb1UgAgBClHVqmqRWqmtJtS9TH65xCZYS64jx-m2Vvz3XTsJJIxN5QXfr-Pjc6-dD5ZoIVnMhsMhR6tsJuPgXkFqIIdAyCDJoJQlRx93RtlEOQplZGKVxuBpzbGJBrdJoiu0wQdHJeJAoeWIOt8YAi6tUZjeuIikzbZKmtbJsaDqn9qIByh3R2-VWZXrJ50qJGJgJVUb7Vg2G63J4Lg_EnjW7_o_u3OEQmaZEvro6VS_qkJ_zcCeQEAuz6afST3ZrSCRFO2FVb6Rhup0aTsm5RgpFMkhy65AOaQSOw4hy8SoouORpQV3CE9h5Y0-NYIV-tHKvMcvAVJeQGvW9L6hsmAcTe_sqilL6J-vyqXRzn0ALCDpIGZVCuYMT1fyT5q9LbYy2cGDNlB3vJe-lqU0b31KCpWXuE7etpPCUW98MgXx5tiRllAD1XLqjwFsMnlulD8_uR7ty5dgRYqVJ7fDDa2DvbqSXk9w1-j6muPd0-Pq5XXF8fb--fHFg3QGraZ6tlCostCoNu4yCHfCxB8KUn1Q_NjQT-LopCpAAF24Wim33J804ggV0O8vOOcEeiTeoF5TcyBT7x7K2TSNicxaZK_XmmzXMffqtB3gbDwahZwFwyGt6b-emm5CN9pw49hOi_f6qEtzEnD0k92va1GbUK-GXhWOzbB2qi4OZe6mUYZ_ED6RcNFFP7w6HHuT18FpibMBS40SLN5CVsoBI7VzcDbzPeDM7mQuOYtpKcD8oGPgnooKwO9a5yy2pqIyo6t0dwCpCkEXpnnZD14jaZTMnWPC4jCaLT0Kiz_YLxYPo8VouRxP5tHlcjEJ55cU_U3u6WI0m0RRNJnN57MoCqf7AXv3G4cjSlrOp2EUXo6n48ViMWAkjNXmuf4G-U_R_g_UKVCo?type=png)](https://mermaid.live/edit#pako:eNqNVV1v2jAU_SuRpb1UgAgBClHVqmqRWqmtJtS9TH65xCZYS64jx-m2Vvz3XTsJJIxN5QXfr-Pjc6-dD5ZoIVnMhsMhR6tsJuPgXkFqIIdAyCDJoJQlRx93RtlEOQplZGKVxuBpzbGJBrdJoiu0wQdHJeJAoeWIOt8YAi6tUZjeuIikzbZKmtbJsaDqn9qIByh3R2-VWZXrJ50qJGJgJVUb7Vg2G63J4Lg_EnjW7_o_u3OEQmaZEvro6VS_qkJ_zcCeQEAuz6afST3ZrSCRFO2FVb6Rhup0aTsm5RgpFMkhy65AOaQSOw4hy8SoouORpQV3CE9h5Y0-NYIV-tHKvMcvAVJeQGvW9L6hsmAcTe_sqilL6J-vyqXRzn0ALCDpIGZVCuYMT1fyT5q9LbYy2cGDNlB3vJe-lqU0b31KCpWXuE7etpPCUW98MgXx5tiRllAD1XLqjwFsMnlulD8_uR7ty5dgRYqVJ7fDDa2DvbqSXk9w1-j6muPd0-Pq5XXF8fb--fHFg3QGraZ6tlCostCoNu4yCHfCxB8KUn1Q_NjQT-LopCpAAF24Wim33J804ggV0O8vOOcEeiTeoF5TcyBT7x7K2TSNicxaZK_XmmzXMffqtB3gbDwahZwFwyGt6b-emm5CN9pw49hOi_f6qEtzEnD0k92va1GbUK-GXhWOzbB2qi4OZe6mUYZ_ED6RcNFFP7w6HHuT18FpibMBS40SLN5CVsoBI7VzcDbzPeDM7mQuOYtpKcD8oGPgnooKwO9a5yy2pqIyo6t0dwCpCkEXpnnZD14jaZTMnWPC4jCaLT0Kiz_YLxYPo8VouRxP5tHlcjEJ55cU_U3u6WI0m0RRNJnN57MoCqf7AXv3G4cjSlrOp2EUXo6n48ViMWAkjNXmuf4G-U_R_g_UKVCo)


## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req                     | Detalle                                                                                                                                                                                                                                                                              |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Plato<br>2. CRUD Mesa<br>3. CRUD Mozo                                                                                                                                                                                                                                      |
| CRUD dependiente        | 1. CRUD Pedido {depende de} Mesa y Plato<br>2. CRUD Reserva {depende de} Mesa y Account                                                                                                                                                                                         |
| Listado<br>+<br>detalle | 1. Platos: Listado filtrado por nombre y tipo, mostrando precio de venta/costo y margen de ganancia (CRUD Plato).<br> 2. Pedidos: Listado filtrado por nro. de mesa, mostrando estado, platos, mozo y total (Pedidos) |
| CUU/Epic                | 1. Reservar una mesa del bar<br>2. Realizar un pedido                                                                                                                                                                                                                                |

Adicionales para Aprobación:

| Req      | Detalle                                                                                                                                                       |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CRUD     | 1. CRUD Plato<br>2. CRUD Mesa<br>3. CRUD Mozo<br>4. CRUD Tipo Producto <br>5. CRUD Pedido {depende de} Mesa y Plato<br>6. CRUD Reserva {depende de} Mesa y Cliente                                       |
| CUU/Epic | 1. Reservar una mesa del bar<br>2. Realizar un pedido<br>3. Realizar el pago de uno o más pedidos<br>4. Cancelar reserva (compensa CRUD dependiente faltante) |

### Alcance Adicional Voluntario

| Req      | Detalle                                                                                                                                                                                                    |
| :------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Listados | 1. Pedidos filtrados por Tipo Producto y Cliente, muestra el estado y el nombre de los productos y sus tipos<br>2. Reservas filtradas por fecha muestra datos de la mesa, la fecha y el nombre del cliente |
| CUU/Epic | 1. Solicitar mozo                                                                                                                                                                                          |
