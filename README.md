# 苍穹外卖 - 智能餐饮O2O平台

基于 Spring Boot 开发的前后端分离餐饮外卖系统，包含商家管理后台与用户微信小程序两端，已接入AI功能实现智能化升级。

## ✨ 项目亮点
- 完整的外卖业务闭环：用户下单、支付、订单流转、商家接单、超时自动取消
- 高并发场景优化：Redis缓存购物车与热门菜品，减轻数据库压力
- 实时交互能力：WebSocket实现来单提醒与用户催单推送
- 智能化升级：集成大模型API，实现AI菜品推荐、评价情感分析与智能客服
- 企业级技术整合：JWT认证、阿里云OSS文件存储、微信支付对接

## 🛠️ 技术栈
- **后端**：Java、Spring Boot、MyBatis、MySQL、Redis、JWT、WebSocket
- **第三方服务**：阿里云OSS、微信登录/支付、大模型API
- **工具**：Maven、Knife4j、Spring Task定时任务

## 🚀 启动步骤
1.  克隆项目到本地
    ```bash
    git clone https://github.com/TrekBunny/sky-take-out.git
