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

[![](https://mermaid.ink/img/pako:eNqNVu2K2zoQfRUj6J-ShCRtbmK3tCzbQBd2e0u6_VMEZWJNHLW2ZCS5dz_Iu9-RbCfybigbCPGcmTkazZfzyHItkGVsPB5z5aQrMUs-SSgMVJAITPISLFqugt4LttNyJaTB3EmtkusNV502uchz3SiXPHIlRZZI5bhSutoaIrbOSFV89Bqkw3YSTQ9yVZP3f9qIz2D3J7Qpnaz0tS6kosDAIXkb7aPsDtqQwNXhFMCNftB_OZ0rqLEspdAnJPK-lbX-WoJ7QgEVnjU_Y_rktJqSJOks1VRbNOSnrYtEsjEoJKUDbZygCgpUESDQ5kbWEYLWgb9ECGEdhEFoF6KS6kYrty_v_93-8qX6g4NQK6_sGd9xZaFEewumQNcHSCiVBM1zuIK7S1A5liie6eIE0eWEvnJYDY7OgeovoBfbJH1X0oHxyQpgXFO0MMxyU6HRHj4S1pBHjGVTgDmTLe9yJlltmIMjdpjv4bM20PZdlPBg25M47aA81bOG-4qKub5zaBSUG9yhQUrTqSGq-gheiRj-2rqeBb85cI2Nh0WKC9dHFl1kgxbNn2GypJKhBVvjXT9JVNptMCal-nji7u_ZUfUXHY4JbEs8N-ovn-zA9upVsqbU2Sfbww-1p33_HkOlwa-ZDx-4ury-Wn-5XXN18enm6ksgiQaxDfWso5C21kpu_bIQ_oZ5uBQU-tgLp1Z7IY_OmxoE0EJqM-UfD08KcaJK6POMzoPgJxPaZyoOlPIhUHk5DyM2ZI7776_ENVK4qvjZ9eQAbAWpftZG0waytgUElrQlaCPFx3upr9aGovH94t8Jff05m04mM86S8Zie6beNMDaItV1muOp7NaBB6818AbgKEz_061k71cCHdj5X3RBHXq-Pbn4DkUVY1y8weB2zH98JXA36PuLpA2cjVhgpWLaD0uKIUUkq8DILheLM7bFCzjJ6FGB-0zXUgZxqUD-0rljmTENuRjfF_kjS1ILGtXvvHlHaILSYL30kLEuni0DCskd2x7LxfJIulqt08Q99529ny3TE7gmerWaTZbqczxbTN-kqTafLw4g9hIPnk2k6X8yXb1arabpczVZvR4wS47S5af8hhD8Kh_8ByZnrXQ?type=png)](https://mermaid.live/edit#pako:eNqNVu2K2zoQfRUj6J-ShCRtbmK3tCzbQBd2e0u6_VMEZWJNHLW2ZCS5dz_Iu9-RbCfybigbCPGcmTkazZfzyHItkGVsPB5z5aQrMUs-SSgMVJAITPISLFqugt4LttNyJaTB3EmtkusNV502uchz3SiXPHIlRZZI5bhSutoaIrbOSFV89Bqkw3YSTQ9yVZP3f9qIz2D3J7Qpnaz0tS6kosDAIXkb7aPsDtqQwNXhFMCNftB_OZ0rqLEspdAnJPK-lbX-WoJ7QgEVnjU_Y_rktJqSJOks1VRbNOSnrYtEsjEoJKUDbZygCgpUESDQ5kbWEYLWgb9ECGEdhEFoF6KS6kYrty_v_93-8qX6g4NQK6_sGd9xZaFEewumQNcHSCiVBM1zuIK7S1A5liie6eIE0eWEvnJYDY7OgeovoBfbJH1X0oHxyQpgXFO0MMxyU6HRHj4S1pBHjGVTgDmTLe9yJlltmIMjdpjv4bM20PZdlPBg25M47aA81bOG-4qKub5zaBSUG9yhQUrTqSGq-gheiRj-2rqeBb85cI2Nh0WKC9dHFl1kgxbNn2GypJKhBVvjXT9JVNptMCal-nji7u_ZUfUXHY4JbEs8N-ovn-zA9upVsqbU2Sfbww-1p33_HkOlwa-ZDx-4ury-Wn-5XXN18enm6ksgiQaxDfWso5C21kpu_bIQ_oZ5uBQU-tgLp1Z7IY_OmxoE0EJqM-UfD08KcaJK6POMzoPgJxPaZyoOlPIhUHk5DyM2ZI7776_ENVK4qvjZ9eQAbAWpftZG0waytgUElrQlaCPFx3upr9aGovH94t8Jff05m04mM86S8Zie6beNMDaItV1muOp7NaBB6818AbgKEz_061k71cCHdj5X3RBHXq-Pbn4DkUVY1y8weB2zH98JXA36PuLpA2cjVhgpWLaD0uKIUUkq8DILheLM7bFCzjJ6FGB-0zXUgZxqUD-0rljmTENuRjfF_kjS1ILGtXvvHlHaILSYL30kLEuni0DCskd2x7LxfJIulqt08Q99529ny3TE7gmerWaTZbqczxbTN-kqTafLw4g9hIPnk2k6X8yXb1arabpczVZvR4wS47S5af8hhD8Kh_8ByZnrXQ)


## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req                     | Detalle                                                                                                                                                                                                                                                                              |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Plato<br>2. CRUD Mesa<br>3. CRUD Mozo                                                                                                                                                                                                                                      |
| CRUD dependiente        | 1. CRUD Pedido {depende de} Mesa y Plato<br>2. CRUD Reserva {depende de} Mesa y Account                                                                                                                                                                                         |
| Listado<br>+<br>detalle | 1. Platos: Listado filtrado por nombre y tipo, mostrando precio de venta/costo y margen de ganancia (CRUD Plato).<br> 2. Pedidos: Listado filtrado por nro. de mesa, mostrando estado, platos, mozo y total (Pedidos) |
| CUU/Epic                | 1. Gestion de reservas<br>2. Gestion de pedidos                                                                                                                                                                                                                                |

Adicionales para Aprobación:

| Req      | Detalle                                                                                                                                                       |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CRUD     | 1. CRUD Plato<br>2. CRUD Mesa<br>3. CRUD Mozo<br>4. CRUD Tipo Producto <br>5. CRUD Pedido {depende de} Mesa y Plato<br>6. CRUD Reserva {depende de} Mesa y Cliente                                       |
| CUU/Epic | 1. Gestion de reservas<br>2. Gestion de pedidos<br>3. Realizar el pago de uno o más pedidos |

### Alcance Adicional Voluntario

| Req      | Detalle                                                                                                                                                                                                    |
| :------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Listados | 1. Reservas filtradas por Mesa o Cliente<br>2. Mesas filtradas por estado<br>3. Mozos filtrados por DNI o Nombre |
| CUU/Epic | 1. Solicitar mozo |
| Integracion | 1. Integracion con MercadoPago para el proceso de pagos<br>2. Integracion con servicio de Maps para mostrar la ubicacion del Restaurant |
