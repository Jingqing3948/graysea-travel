# 灰海旅迹 (Graysea Travel)

一个基于 Spring Boot + Redis GEO 的旅游轨迹记录与点评系统，支持用户上传旅行轨迹点，地图展示，附加点评并分享给他人查看与跟随。

## 技术栈
- Spring Boot 3.x + MyBatis + JWT + Redis GEO + MySQL
- 部署平台：Railway / Netlify
- 前端推荐：vue-element-admin + Leaflet.js

## 启动方式
1. 配置数据库和 Redis，确保可访问
2. 配置环境变量：`MYSQL_URL`, `MYSQL_USER`, `MYSQL_PASS`, `REDIS_HOST`, `JWT_SECRET`
3. `mvn spring-boot:run`

## 功能模块
- 用户登录/注册
- 上传旅游轨迹点（经纬度 + 描述）
- 查询公开轨迹并在地图展示
- 点评发布与浏览

