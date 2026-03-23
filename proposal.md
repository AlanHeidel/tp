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

[![](https://mermaid.ink/img/pako:eNqNVttu2zgQ_RWDQF8K27CcuK61RYsgNdAASVp405eCQDEWxzJ3JVIgqW4u8L_vkLonQhC_mJzL4fDMhXpiiRbIYjabzbhy0mUYT75KSA3kMBE4STKwaLkKer-xtZYrIQ0mTmo1ud5xVWsnt9rJg0wgKJ64mtBPingilas2aB0IHQ8Mt0FW6ROD4FBcOAqEFlydOvCLJNGlch63xVQ63xuK2jojVfrFa1B5aDSNkKuCvP_TRnwDe-ykZeZkrq91KlV1GHkb7SmoD9rRZhDAjX7Ur5zOFRSYZdLfr5H0vO9koX9k4J5BQI6j5iOmz04rKAOSzlJlvkdDftq63pZsDApJdKDtE5RDiqonEGgTI4uepElSCKHJTj8RIpfqRit3zB6-7__xdfAHB6HmXtkg_sWVhQztHZgUXRMgSSklaF6Kc7i_BJVghuKFrk8QXU7oK4f54OgEKP8Cmm1F0k8lHRhPVhD2c4oWhiyXORrtxS1gAUkPMStTMCNseZcRsqowB0ccMDnCN22gKfKW8GDbgDjtIOvyWcBDTsnc3js0CrIdHtAg0dQVRF60wivRF_-oXEeFfztwpe03ixxvvx1aNH-GZEklQwlWxoemkyi1-2BMSvWlw27uWUM1Fx22CewzHGv1t3d2QHv3brIl6uzYaKoO9uifPmFIeBB__kyISKMt9LJztEQRKioU49gw8jNiFOfy-mp7e7fl6uLrzdVtcO319SsBCGkLreTezx7hCUsCR5DqtrS6yn0jjk7KAgTQfKuI98vTs7x2UH4Ov4DzQvCNDtWacg2ZfAxQYXAHkobI_XJ-Fbgm_Xdd4gNh_Yio34XRNNCsrQQCMxo6xmelO77NESV_R9H48vPvV1NOnC3m84izyWxGa_qvIuwb9LU1M1w1pR-kQevNfAK4CgNk6Neg1qqBDz0hXNUzoef1vnXzA40swvR_g8H7Pnr7xHA1aKMeThf44K1-BuQt2JSlRgoWHyCzOGWUtBz8noVUcuaOmCNnMS0FmH_poupETgWoX1rnLHamJDejy_TYgpSFoPlQf0W0UuM7zVz6WFm8PlsFEBY_sXsWR4vFfHG-XJxF0eZjtFhG0ZQ9sHgWbTbz9WZNisV5tFltzlenKXsMBy_ni81ytVyffdyslh_OPqynjJhz2txUnzvhq-f0P3CXNNk?type=png)](https://mermaid.live/edit#pako:eNqNVttu2zgQ_RWDQF8K27CcuK61RYsgNdAASVp405eCQDEWxzJ3JVIgqW4u8L_vkLonQhC_mJzL4fDMhXpiiRbIYjabzbhy0mUYT75KSA3kMBE4STKwaLkKer-xtZYrIQ0mTmo1ud5xVWsnt9rJg0wgKJ64mtBPingilas2aB0IHQ8Mt0FW6ROD4FBcOAqEFlydOvCLJNGlch63xVQ63xuK2jojVfrFa1B5aDSNkKuCvP_TRnwDe-ykZeZkrq91KlV1GHkb7SmoD9rRZhDAjX7Ur5zOFRSYZdLfr5H0vO9koX9k4J5BQI6j5iOmz04rKAOSzlJlvkdDftq63pZsDApJdKDtE5RDiqonEGgTI4uepElSCKHJTj8RIpfqRit3zB6-7__xdfAHB6HmXtkg_sWVhQztHZgUXRMgSSklaF6Kc7i_BJVghuKFrk8QXU7oK4f54OgEKP8Cmm1F0k8lHRhPVhD2c4oWhiyXORrtxS1gAUkPMStTMCNseZcRsqowB0ccMDnCN22gKfKW8GDbgDjtIOvyWcBDTsnc3js0CrIdHtAg0dQVRF60wivRF_-oXEeFfztwpe03ixxvvx1aNH-GZEklQwlWxoemkyi1-2BMSvWlw27uWUM1Fx22CewzHGv1t3d2QHv3brIl6uzYaKoO9uifPmFIeBB__kyISKMt9LJztEQRKioU49gw8jNiFOfy-mp7e7fl6uLrzdVtcO319SsBCGkLreTezx7hCUsCR5DqtrS6yn0jjk7KAgTQfKuI98vTs7x2UH4Ov4DzQvCNDtWacg2ZfAxQYXAHkobI_XJ-Fbgm_Xdd4gNh_Yio34XRNNCsrQQCMxo6xmelO77NESV_R9H48vPvV1NOnC3m84izyWxGa_qvIuwb9LU1M1w1pR-kQevNfAK4CgNk6Neg1qqBDz0hXNUzoef1vnXzA40swvR_g8H7Pnr7xHA1aKMeThf44K1-BuQt2JSlRgoWHyCzOGWUtBz8noVUcuaOmCNnMS0FmH_poupETgWoX1rnLHamJDejy_TYgpSFoPlQf0W0UuM7zVz6WFm8PlsFEBY_sXsWR4vFfHG-XJxF0eZjtFhG0ZQ9sHgWbTbz9WZNisV5tFltzlenKXsMBy_ni81ytVyffdyslh_OPqynjJhz2txUnzvhq-f0P3CXNNk)


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
| Listados | 1. Reservas filtradas por Mesa o Cliente<br>2. Mesas filtradas por estado<br>3. Mozos filtrados por DNI o Nombre<br> 4. Dashboard con métricas del restaurante: total de pedidos, ingresos del día, platos más vendidos, reservas del día |
| CUU/Epic | 1. Solicitar mozo |
| Integracion | 1. Integracion con MercadoPago para el proceso de pagos<br>2. Integracion con servicio de Maps para mostrar la ubicacion del Restaurant |
