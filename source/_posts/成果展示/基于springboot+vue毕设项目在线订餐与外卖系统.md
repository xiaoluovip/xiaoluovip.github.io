---
title: 基于SpringBoot+Vue的在线订餐与外卖管理系统
date: 2026-3-2 10:00:00
tags: 毕设项目
description: 基于Spring Boot 3.x + Vue 3.x的前后端分离架构,实现用户、商家、骑手、管理员四端协同的在线订餐与外卖管理系统,支持实时配送跟踪、订单管理、数据统计等核心功能
---

# 📌 项目简介

基于 Spring Boot 3.x 和 Vue 3.x 构建的在线订餐与外卖管理系统,采用前后端分离架构设计。系统面向中小型餐饮商家,提供轻量化的外卖运营管理解决方案。前端使用 Vue3 + Element Plus 构建响应式用户界面,后端基于 Spring Boot + MyBatis Plus 实现业务逻辑,配合 Redis 缓存与 WebSocket 实时通信,为用户提供便捷的点餐体验,为商家提供高效的运营管理工具。

系统涵盖用户端、商家端、骑手端和管理员端四大核心模块,实现了在线点餐、菜品管理、订单处理、实时配送、数据统计等全流程功能,接口平均响应时间≤1秒,支持100并发用户访问。

---

# 🎬 演示地址

**[本地部署演示](#)**

---

# 📸 成果展示

## 🎬 视频演示



---

## 🖼️ 图片展示

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="/img/works/takeout/01.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/02.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/03.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/04.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/05.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
    </tr>
    <tr>
      <td align="center"><img src="/img/works/takeout/06.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/07.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/08.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/09.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
      <td align="center"><img src="/img/works/takeout/10.png" width="200" style="border-radius:8px;transition:transform 0.3s ease,box-shadow 0.3s ease;" onmouseover="this.style.transform='scale(1.05)';this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)'" onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'"></td>
    </tr>
  </table>
</div>

---

# ✨ 功能展示

## 🔧 技术架构

| 层级 | 技术选型 |
|------|---------|
| **后端框架** | Spring Boot 3.x + MyBatis Plus 3.x |
| **前端框架** | Vue 3.x + Element Plus + Vite 5.x |
| **数据库** | MySQL 8.0 + Redis 7.0 |
| **安全认证** | Spring Security + JWT |
| **实时通信** | WebSocket |
| **接口文档** | Swagger / Knife4j |
| **构建工具** | Maven + Vite |
| **部署方案** | Docker + Linux 服务器 |

---

## 🛒 用户端功能

| 功能 | 说明 |
|------|------|
| ✨ 注册登录 | 支持手机号/用户名注册,密码BCrypt加密存储 |
| 🍜 商家浏览 | 按区域、分类、销量、评分筛选商家 |
| 📦 购物车管理 | 添加商品、修改数量、计算总价 |
| 📝 订单管理 | 创建订单、选择地址、支付、跟踪订单状态 |
| 📍 配送跟踪 | 实时查看配送进度与骑手位置 |
| 👤 个人中心 | 管理收货地址、历史订单、收藏菜品 |

---

## 🏪 商家端功能

| 功能 | 说明 |
|------|------|
| 📋 注册审核 | 提交营业执照,等待管理员审核 |
| 🍲 菜品管理 | 新增、编辑、删除菜品,上架/下架操作 |
| 📊 订单处理 | 查看新订单、接单/拒单、制作管理 |
| 📈 数据统计 | 查看订单量、销售额、菜品销量排行 |
| 💬 评价管理 | 查看用户评价、回复评价 |

---

## 🚴 骑手端功能

| 功能 | 说明 |
|------|------|
| 🎫 注册审核 | 实名认证,等待管理员审核 |
| 📦 订单接收 | 查看待接订单、接单/拒单操作 |
| 🛵 配送管理 | 更新配送状态、查看配送路线 |
| 💰 收入统计 | 查看配送订单数、收入金额 |

---

## 👨‍💼 管理员端功能

| 功能 | 说明 |
|------|------|
| 👥 用户管理 | 查看用户列表、禁用/启用账号 |
| 🏢 商家审核 | 审核商家资质、管理商家账号 |
| 🚴 骑手审核 | 审核骑手资质、管理骑手账号 |
| ⚙️ 系统配置 | 配置配送费、起送金额等参数 |
| 📊 数据统计 | 查看平台整体运营数据 |

---

## 🔐 安全与性能

| 特性 | 说明 |
|------|------|
| 🔒 JWT身份认证 | 无状态认证机制 |
| 🔐 密码加密 | BCrypt算法加密存储 |
| 🛡️ 权限控制 | 基于角色的权限管理(RBAC) |
| ⚡ Redis缓存 | 缓存热点数据,提升查询速度 |
| 🔄 分布式锁 | Redis实现订单并发控制 |
| 📡 实时通信 | WebSocket推送订单状态 |
| ⏱️ 性能优化 | 接口平均响应时间≤1秒,支持100并发 |

---

## 💾 核心数据表

系统采用MySQL 8.0存储核心业务数据,遵循第三范式设计,主要数据表包括:

| 表名 | 说明 |
|------|------|
| `user` | 用户表 - 存储用户基本信息 |
| `merchant` | 商家表 - 存储店铺信息与资质 |
| `rider` | 骑手表 - 存储骑手实名信息 |
| `dish` | 菜品表 - 存储菜品详细信息 |
| `orders` | 订单表 - 存储订单核心信息 |
| `delivery` | 配送表 - 存储配送状态信息 |
| `order_detail` | 订单明细表 - 存储订单商品明细 |
| `user_address` | 地址表 - 存储用户收货地址 |
| `dish_category` | 分类表 - 存储菜品分类信息 |

---

<div align="center">
  <p style="color:#888;font-size:14px;margin-top:30px;">
    使用 Spring Boot + Vue 3 + MySQL 构建 🍕
  </p>
</div>
