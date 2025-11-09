---
slug: demo
id: zzp0nxfxmxry
type: challenge
title: Getting Started
tabs:
- id: xdbcqb6naygo
  title: Elasticsearch
  type: service
  hostname: kubernetes-vm
  path: /app/discover#/?_g=(filters:!(),query:(language:kuery,query:''),refreshInterval:(pause:!t,value:60000),time:(from:now-1h,to:now))&_a=(breakdownField:log.level,columns:!(),dataSource:(type:esql),filters:!(),hideChart:!f,interval:auto,query:(esql:'FROM%20logs-*'),sort:!(!('@timestamp',desc)))
  port: 30001
- id: ssyhxjku2bhz
  title: Terminal
  type: terminal
  hostname: host-1
  workdir: /workspace/workshop
difficulty: basic
timelimit: 600
enhanced_loading: null
---
Demo