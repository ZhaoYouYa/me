---
tags:
  - db
keys:
  - pgsql
  - time-series
---
::: info Introduction

Timescale is a database platform engineered to deliver speed and scale to resource-intensive workloads, which makes it great for things like time series, event, and analytics data. Timescale is built on PostgreSQL, so you have access to the entire PostgreSQL ecosystem, with a user-friendly interface that simplifies database deployment and management.

:::

## timescaledb 的三个特性

### 1. Hypertables

再pgsql 标准表上的扩展，获得时间分片

### 2. Continuous aggregates

加快聚合数据，查询更加方便

### 3. Compression

压缩老数据，可以指定压缩策略

https://docs.timescale.com/tutorials/latest/financial-tick-data/

