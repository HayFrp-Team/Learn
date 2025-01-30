---
prev:
  text: 'HayFrp OPENAPI使用文档'
  link: '/api-doc'
next: false
---

# Error Code

## 1xxxx Backend Error

### 10xxx Data Centre

- 10001 数据中心内部网络出错
- 10002 数据中心公网v6出错
- 10003 数据中心v6转v4CF代理出错
- 10014 数据中心网关错误

- 10011 数据中心数据库繁忙
- 10012 数据中心出口繁忙
- 10013 数据中心雷池错误

### 11xxx Business Core

- 11001 业务核心BE丢失与DB的连接
- 11002 业务核心出口出错

- 11011 业务核心DB繁忙
- 11012 业务核心BE繁忙

- 11020 业务核心总出口掉线
- 11021 业务核心代理出口1掉线
- 11022 业务核心代理出口2掉线
- 11023 业务核心代理出口3掉线

### 12xxx Communication Hub

- 12001 通讯中枢公网掉线
- 12002 通讯中枢繁忙

## 2xxxx Connection Error

### 20xxx Internal Connection

- 20001 BC失去与DC的连接
- 20002 BC失去与CH的连接
- 20003 DC失去与BC的连接
- 20004 DC失去与CH的连接
- 20005 CH失去与BC的连接

### 21xxx User-Agent Lost

- 21001 用户无法请求DC
- 21002 用户无法请求BC

### 22xxx 3rd-Party Lost

- 22001 BC失去与SMTP服务器的连接
- 22002 BC失去与微信公众平台的连接
- 22003 BC失去与Cloudflare的连接

- 22101 DC失去与SMTP服务器的连接
- 22102 DC失去与Cloudflare的连接

## 3xxxx Product Error


### 30xxx GoFRP

> For solution, See [Usage](/usage#常见错误).

- 30001 隧道已被禁用
- 30002 隧道不存在
- 30003 节点没有上线权限
- 30004 未找到节点
- 30005 i/o timeout
- 30006 没有找到用户
- 30007 连接被拒绝
- 30008 配置文件错误
- 30009 无法连接到服务器
- 30010 认证失败
- 30011 隧道已存在
- 30012 隧道类型不支持
- 30013 隧道节点不可用
- 30014 隧道协议不支持
