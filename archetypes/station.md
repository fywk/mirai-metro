---
title: {{ replace .Name "-" " " | title }} station
station_code: []
station_name_en: {{ replace .Name "-" " " | title }}
station_name_zh: 
route_sign: []
adjacent_stations:
  - route_sign: []
    preceding:
      - station: 
        towards: 
    following:
      - station: 
        towards: 
alternate_station_name_en: 
alternate_station_name_zh: 
district_en: 
district_zh: 
jumbotron_style: 
address: [{{ replace .Name "-" " " | title }}, City of Mirai, United Cities]
coordinate:
  - route_sign: []
    xyz: [0,0,0]
nearby_attraction: []
connecting_station: false
popular: false
date: {{ .Date }}
---

