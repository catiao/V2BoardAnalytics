# V2Board Analytics 开源功能介绍 及 部署教程

---
<div align="center">

![V2Board Analytics01](https://github.com/catiao/V2BoardAnalytics/raw/main/png/V2Board%20Analytics01.jpg)

![V2Board Analytics01](https://github.com/catiao/V2BoardAnalytics/raw/main/png/V2Board%20Analytics02.jpg)

![V2Board Analytics01](https://github.com/catiao/V2BoardAnalytics/raw/main/png/V2Board%20Analytics03.jpg)

![V2Board Analytics01](https://github.com/catiao/V2BoardAnalytics/raw/main/png/V2Board%20Analytics04.jpg)

</div>

---

**V2Board Analytics** 是一款专为机场主设计的专业运营数据分析平台，帮助机场主全面掌握业务运营状况，提升管理和决策效率。主要功能包括：

- **运营数据分析**  
  实时监控关键运营指标，支持多维度数据解读，助力机场业务优化。

- **新用户充值率**  
  精准统计新用户的充值行为，评估用户转化效果。

- **客单价分析**  
  监控用户平均消费金额，帮助制定合理的定价策略。

- **网站访问量与注册率**  
  统计网站流量及注册转化情况，洞察用户访问行为。

- **每日流水监控**  
  实时展示每日收入状况，支持快速响应市场变化。

- **趋势曲线图**  
  包含最近13天和最近一年业务数据曲线，直观反映业务发展趋势。

- **本月运营概览**  
  汇总当月关键指标，提供全面的业务表现概览。

- **每月成本计算**  
  自动计算月度运营成本，辅助财务管理与预算控制。

V2Board Analytics 以数据驱动机场业务增长，助力机场主实现科学决策与持续优化。

---



## 部署教程

请按照以下步骤完成 V2Board Analytics 的部署：

1. 在 V2Board 面板的 `public/` 目录下创建一个自定义文件目录，建议目录名使用随机16位以上的字符串以保证安全性。例如：public/yourrandomstring12345678/

2. 将 `V2BoardAnalyticsapi.php` 和 `index.html` 两个文件上传到 public/yourrandomstring12345678/目录中。

3. 编辑 `V2BoardAnalyticsapi.php` 文件，填写以下配置信息：

```html
// 数据库地址
$servername = "127.0.0.1";
// 数据库用户
$username = "user";
// 数据库密码
$password = "admin";
// 数据库名
$dbname = "dbname";
```


4. 通过浏览器访问：http://你的V2Board域名/yourrandomstring12345678/ 即可打开 V2Board Analytics 数据分析面板。

---


如果你在部署过程中遇到任何问题，欢迎提交 [issue](https://github.com/catiao/V2BoardAnalytics/issues) 或联系维护者协助解决。

 [Telegram频道](https://t.me/V2BoardAnalytics) 


 ---

 ## 更新记录
 
**V1.0.1** 
- 更新本月概览，新增本月流水、注册&充值率、订单&客单价
