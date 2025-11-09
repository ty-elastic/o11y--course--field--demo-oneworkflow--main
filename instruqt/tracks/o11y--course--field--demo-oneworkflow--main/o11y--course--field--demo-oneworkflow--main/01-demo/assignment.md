---
slug: demo
id: izlqqkzxglpx
type: challenge
title: Getting Started
tabs:
- id: u2nmw20sfz6j
  title: Elasticsearch
  type: service
  hostname: kubernetes-vm
  path: /app/apm/service-map
  port: 30001
difficulty: basic
timelimit: 600
enhanced_loading: null
tabs:
- id: jeu1estyxf1z
  title: Elasticsearch
  type: service
  hostname: kubernetes-vm
  path: /app/discover#/?_g=(filters:!(),query:(language:kuery,query:''),refreshInterval:(pause:!t,value:60000),time:(from:now-1h,to:now))&_a=(breakdownField:log.level,columns:!(),dataSource:(type:esql),filters:!(),hideChart:!f,interval:auto,query:(esql:'FROM%20logs-*'),sort:!(!('@timestamp',desc)))
  port: 30001
- id: lyqrwsofywhh
  title: Terminal
  type: terminal
  hostname: host-1
  workdir: /workspace/workshop
