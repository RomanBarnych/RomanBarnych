# Proyecto documentación para el administrador de red
**![](https://lh6.googleusercontent.com/sI8fxry9KqcZCxIcwAraCf5PBGDX2I1-JqrhGaopgWMbGoXyunc4a36YxnJRsRQhiMkqzC_pn5jghpvfyoB8ImmRQm4k0cUAEiA8scd_-KcHdhPKwPC1uBbGmNeR_djQDoetDroB)**
## Lista de compra
|Presupuesto ordenadores|Precio unitario €|Nº unidades                        |
|----------------|-------------------------------|-----------------------------|
|**[Portátil](https://www.pccomponentes.com/asus-e410ma-ek018ts-intel-celeron-n4020-4gb-64gb-emmc-14)**|**248,99€**           |10          |
|**[Torre con tarjeta red integrada](https://www.pccomponentes.com/pccom-basic-elite-pro-intel-core-i5-10400-8gb-1tb-240ssd)**      |**433,63€**           |1         |
|**[Adaptador USB rj45](https://www.amazon.es/Adaptador-Ethernet-BENFEI-Compatible-port%C3%A1til/dp/B08KWC7D78/ref=sr_1_2_sspa?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=adaptador+rj45&qid=1637062041&sr=8-2-spons&psc=1&smid=AVXBDLJMD7W0C&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzUDMzNjVWMFlLWVIwJmVuY3J5cHRlZElkPUEwMzAxMTkyMkdCV0E0NFRIQzVURSZlbmNyeXB0ZWRBZElkPUEwMTMxMjU2MVROT05RNk4yRUhDWSZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=)**  |**12,99€**|10

## Lista de la compra para la red Ethernet
![enter image description here](https://www.upload.ee/image/13728247/Screenshot_1092.png)


## Comando de terminal
```bash

ls -lah

cd directorio

```
## Mapa fisico
┌──┬────────────────────────────────────────────────────┐
│  └─────┼┼┼┼───────┼┼┼─────────┼┼┼────────┼┼┼─────────┼│
│        └┼─┘       └─┤         └┼┘        └─┤         ││
│  R2P1T11│    R2P1T10│  R2P1T9  │    R2P1T8 │         ││
│  ┼    ┌─┴─┐       ┌─┴──┐     ┌─┴─┐     ┌───┤         ││
│       │   │       │    │     │   │     │   │         ││
│       └───┘       └────┘     └───┘     └───┘  ┌───┐ ┌┼│
│                                               │   ├─┴┼│
│                                          R2P1T7───┘  ││
│                                                    ┌─┼│
│                                              ┌───┬┬┴─┼│
│                                       R2P1T6 │   ├┘  ││
│                                              └───┘   ││
│                                      ┌───┐         ┌─┼│
│                            R2P1T5    │   ├─────────┴─┼│
│                                      └───┘           ││
│                                             ┌────┐   ││
│                                   R2P1T4    │    ├─┬─┼│
│                                             ├───┬┘ └─┼│
│                                           ┌─┴───┤    ││
│                                  R2P1T3   │     │    ││
│                                           └─────┴─┬──┼│
│                                                   └──┼│
│                                             ┌───┐    ││
│                                  R2P1T2     │   │   ┌┼│
│                                             │   ├───┴┼│
│                                             └───┘    ││
│                                   ┌───────┐        ┌─┼│
│                           R2P1T1  │       ├────────┴─┼│   ┌────────┐
├─────────                          │       │          ││   │        │
│                                   └───────┘  ┌───────┴┤   │Rack1   │
│                                              │        ├───┤        │
│                                              │  Rack2 │   │        │
│                                              │        │   └────────┘
│            ┌────────────────────┐            │        │
└────────────┴────────────────────┴────────────┴────────┘



## Mapa logico
[Clic aqui](https://drive.google.com/file/d/1YI0Xckyza3mmpr7VSqgZL5U4n3IaKd3w/view)
