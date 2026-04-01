---
layout: topic
title: "Matriz de distâncias e análise da localidade mais próxima"
order: 9
---
- [QGIS - Matriz de distâncias e análise da localidade mais próxima](https://youtu.be/vATTOVOozfQ?si=_37SQL0Egab7gejX)
- [QGIS - Matriz de distâncias euclidianas e análise do ponto central mais próximo](https://youtu.be/mIHzlsoBFL8?si=F4asSl_NRqs-74GK)
- [Rede Belo Horizonte](https://cefetmgbr-my.sharepoint.com/:u:/g/personal/diegocamargo_cefetmg_br/EcBWeOpIRmlLv3_4TsjbN2YBhR0bafPaRP1HC0Rskr5s-g?e=21zJbe)
- [Hospitais Belo Horizonte](https://raw.githubusercontent.com/d-camargo/geo/gh-pages/arquivos/HOSPITAIS.gpkg)
- [Bairros Belo Horizonte - 2014](https://raw.githubusercontent.com/d-camargo/geo/gh-pages/arquivos/BAIRROS_2014_SUPLAN_PBH.gpkg)

Código SQL:
```sql
SELECT origin_id, destination_id, MIN(total_cost) AS shortest_distance, geometry 
FROM input1 
GROUP BY origin_id
```
