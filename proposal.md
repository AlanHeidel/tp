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

[![](https://mermaid.ink/img/pako:eNqNVVtrGzsQ_iuLoC_FNr42qSktoTU0kJTi5rwcBGW8Gm_E2R0tkjanTfB_70i7a2tTt8Qv1nya-TT3fRK5USjWYjweS_Lal7jOPmkoLFSQKczyEhw6SfE-CK67laS0xdxrQ9nNVlJ3m13luWnIZ0-StFpnmrwkMtXOMrHzVlPxIdwgP7bXaHtQUs3W_xurPoO7P6FN6XVlbkyhiR0Dj2xtTfCye2jLgqTDyYFb82j-8rokqLEstTInJLG-07X5WoJ_RgEVnlU_o_rstZqTpPktaqodWrYzzici61hUmtOBLk1QBQVSAih0udV1gqDzEIKILmyiMHSNaZW59lgN_MuBM6-gF1v3_iHtwQY3I5hmEx0M42sqtCbAR8Ia8oSxbAqwZ_wMJn90c_DEHvN7-GwstBVPQo26PYk3HspTJmv4WXEaNz88WoJyi3u0SHlSiqo-gtcqhb-2pmfBbx5849I21erK954lgWzRoX0YJkuTjsVvlfd9D0syu6jMl_ThxN3H2VH1gQ4bFHYlnhuyl89UZHv1Kttw6tyzuQ3jFGjfvcNYaQgD_v69pI8315svdxtJV59ur79EkmQEWlfPGirtakN6F8ZUhQjzGBQU5tgLp1Z7IY_JmxoU8CpoMxWOh2eFOFFl_PuNLoDA6-sB2jMXB0r9GKmCzHOSYzlkTvvvr8Q1srtUfO96cgC2gqbvtTU8-861gMJSP3BzqvT5IPXV2rI3oV_CNu7rL8V0MplJkY3HfOb_1sNUIb3tMiOp79WIxtugFgogKU780K5n7a4GNrxtJXVDnFi9PpqFDcQacVG-QOF1yn7cxpIGfZ_w9I6LkSisVmK9h9LhSHBJKgiyiIWSwt9jhVKs-ajA_sdh0IGNaqB_janE2tuGzaxpivsjSVMrHtfui3dEeYMotB-DJ2I9W01XkUWsn8QPli8nbxeMLZbz-fziYrW8HImfDE8nF9PZfLlcXC4vV9PZ6s1hJB7jw7PJYrF8u5hdLGbz-XL6ZiQ4Ld7Y2_bLHD_Qh18PgLdS?type=png)](https://mermaid.live/edit#pako:eNqNVVtrGzsQ_iuLoC_FNr42qSktoTU0kJTi5rwcBGW8Gm_E2R0tkjanTfB_70i7a2tTt8Qv1nya-TT3fRK5USjWYjweS_Lal7jOPmkoLFSQKczyEhw6SfE-CK67laS0xdxrQ9nNVlJ3m13luWnIZ0-StFpnmrwkMtXOMrHzVlPxIdwgP7bXaHtQUs3W_xurPoO7P6FN6XVlbkyhiR0Dj2xtTfCye2jLgqTDyYFb82j-8rokqLEstTInJLG-07X5WoJ_RgEVnlU_o_rstZqTpPktaqodWrYzzici61hUmtOBLk1QBQVSAih0udV1gqDzEIKILmyiMHSNaZW59lgN_MuBM6-gF1v3_iHtwQY3I5hmEx0M42sqtCbAR8Ia8oSxbAqwZ_wMJn90c_DEHvN7-GwstBVPQo26PYk3HspTJmv4WXEaNz88WoJyi3u0SHlSiqo-gtcqhb-2pmfBbx5849I21erK954lgWzRoX0YJkuTjsVvlfd9D0syu6jMl_ThxN3H2VH1gQ4bFHYlnhuyl89UZHv1Kttw6tyzuQ3jFGjfvcNYaQgD_v69pI8315svdxtJV59ur79EkmQEWlfPGirtakN6F8ZUhQjzGBQU5tgLp1Z7IY_JmxoU8CpoMxWOh2eFOFFl_PuNLoDA6-sB2jMXB0r9GKmCzHOSYzlkTvvvr8Q1srtUfO96cgC2gqbvtTU8-861gMJSP3BzqvT5IPXV2rI3oV_CNu7rL8V0MplJkY3HfOb_1sNUIb3tMiOp79WIxtugFgogKU780K5n7a4GNrxtJXVDnFi9PpqFDcQacVG-QOF1yn7cxpIGfZ_w9I6LkSisVmK9h9LhSHBJKgiyiIWSwt9jhVKs-ajA_sdh0IGNaqB_janE2tuGzaxpivsjSVMrHtfui3dEeYMotB-DJ2I9W01XkUWsn8QPli8nbxeMLZbz-fziYrW8HImfDE8nF9PZfLlcXC4vV9PZ6s1hJB7jw7PJYrF8u5hdLGbz-XL6ZiQ4Ld7Y2_bLHD_Qh18PgLdS)


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
