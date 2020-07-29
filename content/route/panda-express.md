---
title: Panda Express
title_zh: 熊貓快綫
route_sign: [P]
branch_line: false
stations:
  - station_code: [P1]
    name: Panda Museum
    name_zh: 熊貓博物館
    first_station: true
  - station_code: [P2]
    name: Cavemouth
    name_zh: 洞口
    transfer:
      - route_sign: [G]
  - station_code: [P3]
    name: Mugen
    name_zh: 無限
    transfer:
      - route_sign: [B,V,W,D]
  - station_code: [P4]
    name: Under the Falls
    name_zh: 瀑布下
    transfer:
      - route_sign: [R,W]
  - station_code: [P5]
    name: City Farm
    name_zh: 城市農場
    transfer:
      - route_sign: [G,B]
  - station_code: [P6]
    name: Oasis Point
    name_zh: 綠洲角
    transfer:
      - route_sign: [W]
    last_station: true
custom_style: table{margin:0 auto}.station-code-bg-first{background-image:url(/img/bg/pandaexpress.png);background-repeat:no-repeat;background-size:7px 50%;background-position:51px bottom}.station-code-bg{background-image:url(/img/bg/pandaexpress.png);background-repeat:no-repeat;background-size:7px 101%;background-position:51px}.station-code-bg-last{background-image:url(/img/bg/pandaexpress.png);background-repeat:no-repeat;background-size:7px 50%;background-position:51px top}
weight: 9
---