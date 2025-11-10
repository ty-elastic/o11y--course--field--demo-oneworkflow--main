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

- id: flags
  title: Flags
  type: service
  hostname: host-1
  path: /feature
  port: 8080

- id: store
  title: Flags
  type: service
  hostname: host-1
  path: /
  port: 8080

- id: ssyhxjku2bhz
  title: host-1
  type: terminal
  hostname: host-1
  workdir: /workspace/workshop
- id: blah
  title: kubernetes-vm
  type: terminal
  hostname: kubernetes-vm
  workdir: /workspace/workshop
difficulty: basic
timelimit: 600
enhanced_loading: null
---
Demo