# -SEO-GEO-SKILL-
为刚开始使用ai搭建外贸网站提供技能上的思路和解决方案
[b2b-website-builder-skill.zip](https://github.com/user-attachments/files/34468031/b2b-website-builder-skill.zip)
[README.md](https://github.com/user-attachments/files/34468046/README.md)
# B2B 外贸网站全栈搭建与运营 Skill 技能说明书
技能包完整文件结构清单
b2b-website-builder-skill/
│
├── SKILL.md                          # 核心执行规范（Agent 驱动大脑与 SOP）
├── README.md                         # 技能完整使用说明书与目录索引
│
├── templates/                        # 生产级代码模板库（即拷即用）
│   ├── nginx_hybrid.conf             # 动静分离（静态主站 + /news/ 博客）Nginx 配置模板
│   ├── disable_canonical.php         # 解决 WP 子目录重定向死循环的 Must-Use 插件
│   ├── contact_form.html             # 集成 Honeypot 蜜罐与 AJAX 异步提交的前端外贸表单
│   ├── submit_lead.php               # MySQL 数据优先落盘 + 阿里云 SMTP 即时发信后端
│   ├── robots.txt                    # 适配主流搜索引擎与 AI 爬虫（GPTBot/ClaudeBot）的标准规则
│   └── schema_jsonld_template.html   # B2B 独立站核心 JSON-LD（Organization/Product/FAQ）代码
│
└── scripts/                          # 自动化运维与监控工具
    ├── bt_push.py                    # 本地项目代码一键打包并推送到服务器宝塔/Web目录脚本
    └── health_check_cron.sh          # Linux Crontab 定时探活与 502 自动重启脚本

    三、技能核心能力与提效场景
后续您在任何时候需要搭建外贸独立站、工业品出海站或企业官网时，只需对我说“参考建站技能包做个网站”，Agent 将自动遵循以下标准化流程高效执行：

架构快速选型与一键避坑：
自动应用“极速静态主站 + /news/ 动态 WordPress 博客”的动静分离混合架构；
自动部署 disable_canonical.php，彻底绝缘 WordPress 在子目录运行时的 ERR_TOO_MANY_REDIRECTS 死循环故障。
企业级零漏单询盘系统（开箱即用）：
蜜罐反爬虫机制：前端自动埋设隐藏 Honeypot 字段，静默拦截 99% 的黑产垃圾抓取广告；
双保险闭环：询盘优先写入 MySQL 数据表（wp_kx_leads），随后通过企业邮箱 SMTP 465 端口即时推送到主收件箱，彻底告别丢单。
老外阅读习惯与高转化动线（Buyer UX）：
默认执行 F 型阅读动线，以客观参数密度（纯度、产能、认证）替代空洞形容词；
强制采用 HTML 参数对比表格，拒绝全图切片，技术中心（TDS/MSDS/COA）一站式集成。
Google SEO + GEO（生成式 AI 引擎）双驱合规：
全面开放对 GPTBot、ClaudeBot、PerplexityBot 的爬取授权；
自动植入包含 CAS、规格、FAQ 的 Schema.org JSON-LD 结构化数据，确保站点被主流大模型优先采信为行业权威数据源。
