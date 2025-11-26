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

[![](https://mermaid.ink/img/pako:eNqNVdtu4jAQ_ZXIUl8qQAQoC1HVVdWyKlJbrVD3ZeUXEw_B2mQcOc5eWvHvHZsEnJat-kQ8M-f4zM28sFRLYAnr9_scrbI5JNGtEpkRhYgkRGkuKqg4er87VI2Xo1QGUqs0Rvcrjo03uk5TXaONXjgqmUQKLUfUxdoQcWWNwuyr8wBdtlFgWiPHktB_tJF3otoerXVuVaHvdaaQhAkLhDbaqWwuWtGB4-4o4CZXRA4dAVAIlR9J3-mxkMNGow5MAeODftYf5MNRlJDnSuqjJUA_qVJ_z4V9QyEKOBl-IvTNbSWVXdFdWBdrMITTlQ2OFGNA-hpUYckLkQEGBglValQZWKCywiXhJSz8oSuNaKVeWig6-lJBvZSiPe7l_UBlhXEyvTGsJlSim19dgNHOfCAsRRow5nUmzAmdDvJfmZ0rNpBuxZ02Yj9DnfAVVGB-i_fxbeyWcEtUvuZHy7d2ILvNFuscTq3A5yfes52dRQuqS_Vmq9ywO9rLS_BVE279rq443twvF49PC47Xtw_LR08SjNO-SCeBUlWlRrV2SyRdYVNfTpHpQ12Pbfskj07rUkhBi7ovrftss1pBTr3V6N6UdlM5Gw4GMWdRv0_f9Ntk-0HEvsdhQOhtWsqx7a23eq8Lc6lw9HPYxbWsjauDoTeAYzNaAer8AHN7QRF-fT8RcB6yH94Ijp0JCnha4azHMqMkSzYir6DHqAn0uNGZUVsiCrRbKICzhD6lML8oDdwRqBT4U-uCJdbUBDO6zrYHkrqUNMnNy36wGqCRMDdOCUsuplNPwpIX9pcl8WQ2mI7i2XA8jYcXcTzrsX9kHQ7ii9koHo9nky-TyXg-2_XYs792OJhPJ7PRZB5P5uPRiCA9RmWx2jzs_4H8H9HuFSDTT78?type=png)](https://mermaid.live/edit#pako:eNqNVdtu4jAQ_ZXIUl8qQAQoC1HVVdWyKlJbrVD3ZeUXEw_B2mQcOc5eWvHvHZsEnJat-kQ8M-f4zM28sFRLYAnr9_scrbI5JNGtEpkRhYgkRGkuKqg4er87VI2Xo1QGUqs0Rvcrjo03uk5TXaONXjgqmUQKLUfUxdoQcWWNwuyr8wBdtlFgWiPHktB_tJF3otoerXVuVaHvdaaQhAkLhDbaqWwuWtGB4-4o4CZXRA4dAVAIlR9J3-mxkMNGow5MAeODftYf5MNRlJDnSuqjJUA_qVJ_z4V9QyEKOBl-IvTNbSWVXdFdWBdrMITTlQ2OFGNA-hpUYckLkQEGBglValQZWKCywiXhJSz8oSuNaKVeWig6-lJBvZSiPe7l_UBlhXEyvTGsJlSim19dgNHOfCAsRRow5nUmzAmdDvJfmZ0rNpBuxZ02Yj9DnfAVVGB-i_fxbeyWcEtUvuZHy7d2ILvNFuscTq3A5yfes52dRQuqS_Vmq9ywO9rLS_BVE279rq443twvF49PC47Xtw_LR08SjNO-SCeBUlWlRrV2SyRdYVNfTpHpQ12Pbfskj07rUkhBi7ovrftss1pBTr3V6N6UdlM5Gw4GMWdRv0_f9Ntk-0HEvsdhQOhtWsqx7a23eq8Lc6lw9HPYxbWsjauDoTeAYzNaAer8AHN7QRF-fT8RcB6yH94Ijp0JCnha4azHMqMkSzYir6DHqAn0uNGZUVsiCrRbKICzhD6lML8oDdwRqBT4U-uCJdbUBDO6zrYHkrqUNMnNy36wGqCRMDdOCUsuplNPwpIX9pcl8WQ2mI7i2XA8jYcXcTzrsX9kHQ7ii9koHo9nky-TyXg-2_XYs792OJhPJ7PRZB5P5uPRiCA9RmWx2jzs_4H8H9HuFSDTT78)


## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req                     | Detalle                                                                                                                                                                                                                                                                              |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Plato<br>2. CRUD Mesa<br>3. CRUD Mozo                                                                                                                                                                                                                                      |
| CRUD dependiente        | 1. CRUD Pedido {depende de} Mesa y Plato<br>2. CRUD Reserva {depende de} Mesa y Cliente                                                                                                                                                                                         |
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
