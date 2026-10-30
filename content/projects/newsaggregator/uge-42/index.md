---
title: "Uge 42: Sammensætning af mange ting"
date: 2026-10-18
description: "vedvarende opdatering"
series: ["NewsAggregator"]
series_order: 8
draft: false
---

## Hvad lavede jeg
- SyncService oppe at køre med multi treading.
- Valgte kun at bruge en god API frem for en god og flere 'dårlige'
- Ændrede mit design af min DB fra ManyToMany mellem Article og Topic til OneToMany fra Topic

## Udfordringer
- Havde en del problemmer med nogle af de andre api's jeg havde og forskellen mellem deres JSON output, hvilket gave en del problemmer med mine DB queries

## Næste uge
-