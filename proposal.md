# Propuesta TP DSW

## Grupo

### Integrantes

- 45198 - Romo, Matías
- 56473 - Heidel, Alan
- 49953 - Fracassi, Santiago

### Repositorios

- [FrontEnd](https://github.com/AlanHeidel/utnfrro-frontend)
- [BackEnd](https://github.com/AlanHeidel/utnfrro-backend)

## Tema

### Descripción

Se trata del sistema para gestionar los pedidos en un bar o restaurante. Los clientes al sentarse en una mesa pueden ingresar y hacer un pedido que será visualizado por un administrador, eventualmente aceptado y posteriormente servido por un mozo. Adicionalmente se permitirá realizar reservas de las mesas por parte de los clientes.

### Modelo

[![](https://mermaid.ink/img/pako:eNqNVNtO4zAQ_ZXIEi-rtmroLY0QKwRdgQQIVTwhv5h4mlqbjCPb2Quo_75jN2kTqNA-JXPmfmbG7yzTEljKhsMhR6dcAWl0o0RuRCkiCVFWCAuWY9B7wTZajlIZyJzSGN2vOTba6CrLdI0ueueoZBopdBxRl6-GAltnFObfvQYo2UaBaUGOFXn_1kbeCrvtmNaFU6W-17lCqkw4IMxoX2aTaU0Cx92xgutCUXToVQClUMUx16eCHBSw0ag7UCfig37TXzTEUVRQFErqI9LxflaVfiqE-xBClHDS_ITph2wV8a4oF9blKxjy09Z1RLIxIAMHtst5KXLADiDBZkZVHQSsE76JUMIqCH0ewIp-ZXUJRnu4ATJRiUxJ0RoUdS7MiQze5USCJ6pb9pvfQLYVt9qI_fR75muwYH6Jz_at7Zb87lAFto7Ij3aVmmBnZ9GKOrEfVtgvlg99cQGhT-F3_fKS4_X93erxecXx6ubh7jEE6Yxu39ZJR6lspVG9-oWVnoosECByfWDiSPR_xtFZXQkp6Cj2ZPjftqs1FDQNjf6A26vgbDwaxZxFwyH907fp9guL_VS6Bl1tMwSO7TQCGrTezLfCMWxO36-N2qh6PnRvHJtlOKq8k2eYVOFGOPvW9TrcGRuw3CjJ0o0oLAwYUUfnTzIjMiOydlsogbOUfqUwPyky7sipEviidclSZ2pyM7rOt4cgdSVpY5rH74AaoEGaa08gS6ezZQjC0nf2h6XD-WiRTM8ns8U4ni_Op-PpgP1l6WwyWs4WcRJPl8l8Mk6S3YC9hbTxKI4JmZwv5kk8T6azyYARB06bh_0jHd7q3T-OtwDh?type=png)](https://mermaid.live/edit#pako:eNqNVNtO4zAQ_ZXIEi-rtmroLY0QKwRdgQQIVTwhv5h4mlqbjCPb2Quo_75jN2kTqNA-JXPmfmbG7yzTEljKhsMhR6dcAWl0o0RuRCkiCVFWCAuWY9B7wTZajlIZyJzSGN2vOTba6CrLdI0ueueoZBopdBxRl6-GAltnFObfvQYo2UaBaUGOFXn_1kbeCrvtmNaFU6W-17lCqkw4IMxoX2aTaU0Cx92xgutCUXToVQClUMUx16eCHBSw0ag7UCfig37TXzTEUVRQFErqI9LxflaVfiqE-xBClHDS_ITph2wV8a4oF9blKxjy09Z1RLIxIAMHtst5KXLADiDBZkZVHQSsE76JUMIqCH0ewIp-ZXUJRnu4ATJRiUxJ0RoUdS7MiQze5USCJ6pb9pvfQLYVt9qI_fR75muwYH6Jz_at7Zb87lAFto7Ij3aVmmBnZ9GKOrEfVtgvlg99cQGhT-F3_fKS4_X93erxecXx6ubh7jEE6Yxu39ZJR6lspVG9-oWVnoosECByfWDiSPR_xtFZXQkp6Cj2ZPjftqs1FDQNjf6A26vgbDwaxZxFwyH907fp9guL_VS6Bl1tMwSO7TQCGrTezLfCMWxO36-N2qh6PnRvHJtlOKq8k2eYVOFGOPvW9TrcGRuw3CjJ0o0oLAwYUUfnTzIjMiOydlsogbOUfqUwPyky7sipEviidclSZ2pyM7rOt4cgdSVpY5rH74AaoEGaa08gS6ezZQjC0nf2h6XD-WiRTM8ns8U4ni_Op-PpgP1l6WwyWs4WcRJPl8l8Mk6S3YC9hbTxKI4JmZwv5kk8T6azyYARB06bh_0jHd7q3T-OtwDh)


<!-- [![](https://mermaid.ink/img/pako:eNqNVE2P2yAQ_SvWHKvY8kfsJL5uValSV1ptt5fKF2omzqgYLIyrdqP89-KPJDabbMsJ3hveY5iBI5SKI-Tg-34hDRmBufeRWKVZzTyOXilYi20hB75ftBNbSE4aS0NKel-eC-nZMfDegyCUBr3jCPaD-ATmHklzxaWqf2gLtkaTrK441ozEW9igwL2Sasmc5uZPyImrpfeIOdZ7LA_M5soMXsGD0hP2QjXekH_GFvUvNte_K_RZUknKlTuzn0i-6_SkFe9K46YyoU4yHNtSU2Pt5Ntba2yZSH2TZJjuz7MXipkbjo_YLhIrmTRfSVjOrVpX97EOKrqK6Xcq80KNup3UnPnfxJYnV68LyXttxRoUYmgFlyHeazjmF6dxcu7rAsIgiArwfN_OP9jJ2GBu1CJkapx_KfX3OsacO23Eh4BoETCUa8YO220SIzu9A4c_3_IUc66G4zGvxz2161lgBZUmDvmeiRZXUKO2r9euYahIAeaAtsMht1PO9M8CCnmymxomvytVQ250Z7dp1VWHi0jXcPs0pq_mEoKSo35QnTSQR2k8aEB-hN-Qx9s0yMIsXm83cbJO19kK_kCeRUGabXdptonDbZhuouy0gtfBNQyyTZhGSRbvdlGSJGG0ApulUfpx_BGHj_H0F_a9hik?type=png)](https://mermaid.live/edit#pako:eNqNVE2P2yAQ_SvWHKvY8kfsJL5uValSV1ptt5fKF2omzqgYLIyrdqP89-KPJDabbMsJ3hveY5iBI5SKI-Tg-34hDRmBufeRWKVZzTyOXilYi20hB75ftBNbSE4aS0NKel-eC-nZMfDegyCUBr3jCPaD-ATmHklzxaWqf2gLtkaTrK441ozEW9igwL2Sasmc5uZPyImrpfeIOdZ7LA_M5soMXsGD0hP2QjXekH_GFvUvNte_K_RZUknKlTuzn0i-6_SkFe9K46YyoU4yHNtSU2Pt5Ntba2yZSH2TZJjuz7MXipkbjo_YLhIrmTRfSVjOrVpX97EOKrqK6Xcq80KNup3UnPnfxJYnV68LyXttxRoUYmgFlyHeazjmF6dxcu7rAsIgiArwfN_OP9jJ2GBu1CJkapx_KfX3OsacO23Eh4BoETCUa8YO220SIzu9A4c_3_IUc66G4zGvxz2161lgBZUmDvmeiRZXUKO2r9euYahIAeaAtsMht1PO9M8CCnmymxomvytVQ250Z7dp1VWHi0jXcPs0pq_mEoKSo35QnTSQR2k8aEB-hN-Qx9s0yMIsXm83cbJO19kK_kCeRUGabXdptonDbZhuouy0gtfBNQyyTZhGSRbvdlGSJGG0ApulUfpx_BGHj_H0F_a9hik) -->

<!-- [![link de la imagen del modelo](https://mermaid.ink/img/pako:eNp9UkFugzAQ_Iq1xwoiHCAQX9NjI1VRT5UvFt4kSGBHxlRtIv5egyFFEY1P652Z9Yy1Nyi0RGAQhiFXtrQVMvJaipMRtSASSVGJBhuuBry_NCPKlSwNFrbUirwduCLuDDjZVSUqi-Tmm90ce0dZSr0IHbBB8yWWZUbLtrDLwj02y6qP8qKfK_V1Dvhiss-BciBh6IoXV3jnTyljAs-Z4nho4PTk3qwnDLZnaF_0hjw6ftQDPqUZOVO2hzfmuf-b9ucFAjiZUgI7iqrBAGo0tejvMPwMB3vGGjkwV0o8irayHLjqnO4i1KfWNTBrWqc0uj2d73PaixQWx225dw0qiWanW2WBZckwA9gNvoHR9Xa1TlK6jZOcJkkaB_DjuildUZpkURTTLM7XeRfAdXg0WmWpa21puqFxnkbZJgCX02qz9zs9rHb3C2pu3Zs?type=png)](https://mermaid.live/edit#pako:eNp9UkFugzAQ_Iq1xwoiHCAQX9NjI1VRT5UvFt4kSGBHxlRtIv5egyFFEY1P652Z9Yy1Nyi0RGAQhiFXtrQVMvJaipMRtSASSVGJBhuuBry_NCPKlSwNFrbUirwduCLuDDjZVSUqi-Tmm90ce0dZSr0IHbBB8yWWZUbLtrDLwj02y6qP8qKfK_V1Dvhiss-BciBh6IoXV3jnTyljAs-Z4nho4PTk3qwnDLZnaF_0hjw6ftQDPqUZOVO2hzfmuf-b9ucFAjiZUgI7iqrBAGo0tejvMPwMB3vGGjkwV0o8irayHLjqnO4i1KfWNTBrWqc0uj2d73PaixQWx225dw0qiWanW2WBZckwA9gNvoHR9Xa1TlK6jZOcJkkaB_DjuildUZpkURTTLM7XeRfAdXg0WmWpa21puqFxnkbZJgCX02qz9zs9rHb3C2pu3Zs) -->

## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req                     | Detalle                                                                                                                                                                                                                                                                              |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Cliente<br>2. CRUD Mesa<br>3. CRUD Mozo                                                                                                                                                                                                                                      |
| CRUD dependiente        | 1. CRUD Pedido {depende de} CRUD Cliente<br>2. CRUD Reserva {depende de} CRUD Mesa y Cliente                                                                                                                                                                                         |
| Listado<br>+<br>detalle | 1. Listado de mesas filtrado por estado, muestra nro de sillas y estado de ocupación => detalle CRUD Mesa<br> 2. Listado de pedidos filtrado por mesa y tipo de producto, muestra estado, nombre y tipo de producto => detalle muestra datos completos de los productos y de la mesa |
| CUU/Epic                | 1. Reservar una mesa del bar<br>2. Realizar un pedido                                                                                                                                                                                                                                |

Adicionales para Aprobación:

| Req      | Detalle                                                                                                                                                       |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CRUD     | 1. CRUD Cliente<br>2. CRUD Mesa<br>3. CRUD Mozo<br>4. CRUD Tipo Producto <br>5. CRUD Producto {depende de} CRUD Pedido                                        |
| CUU/Epic | 1. Reservar una mesa del bar<br>2. Realizar un pedido<br>3. Realizar el pago de uno o más pedidos<br>4. Cancelar reserva (compensa CRUD dependiente faltante) |

### Alcance Adicional Voluntario

| Req      | Detalle                                                                                                                                                                                                    |
| :------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Listados | 1. Pedidos filtrados por Tipo Producto y Cliente, muestra el estado y el nombre de los productos y sus tipos<br>2. Reservas filtradas por fecha muestra datos de la mesa, la fecha y el nombre del cliente |
| CUU/Epic | 1. Solicitar mozo                                                                                                                                                                                          |
