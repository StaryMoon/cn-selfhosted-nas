# 自托管服务与 NAS 工具

> 整理自托管入口、Docker 管理、相册、影音、网盘、密码库、Git 服务和监控工具。

<p align="left">
  <a href="https://github.com/StaryMoon/cn-selfhosted-nas"><img alt="stars" src="https://img.shields.io/github/stars/StaryMoon/cn-selfhosted-nas?style=flat&label=stars"></a>
  <img alt="category" src="https://img.shields.io/badge/%E8%87%AA%E6%89%98%E7%AE%A1%20%20%2F%20%20NAS-curated-blue">
  <img alt="language" src="https://img.shields.io/badge/language-中文-brightgreen">
</p>

![preview](assets/preview.png)

<sub>图片来源：公开入口预览图，[https://github.com/awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)，截取/整理日期：2026-07-02。</sub>

## 定位

本仓库是一份面向中文用户的主题索引，重点整理常用、稳定、值得优先了解的工具入口，并补充适用场景、选型建议和风险边界。目标不是追求数量，而是降低第一次检索和筛选的成本。

- **主题**：自托管 / NAS
- **适合人群**：想搭家庭服务器、NAS、个人云和内网服务的人
- **首批重点**：awesome-selfhosted / Docker / CasaOS / Immich / Jellyfin
- **为什么值得整理**：自托管和 NAS 是高收藏属性主题，适合从入门到项目清单持续更新。

## 使用方式

1. 先看 [精选资源](#精选资源)，按自己的场景挑 2-3 个入口试用。
2. 再看 [选型建议](#选型建议)，避免一上来把同类工具全装一遍。
3. 如果用于课程、论文、开源项目或生产环境，务必看 [风险提醒](#风险提醒)。

## 收录口径

先收最容易落地且有长期维护的自托管服务，默认 Docker Compose 友好。

优先收录：

- 官方文档、官网、活跃 GitHub 仓库；
- 免费可试用或开源项目；
- 中文用户高频搜索、收藏、复用的工具；
- 入口稳定、说明清楚、维护状态可判断的资源。

暂不收录：

- 破解软件、灰色下载、账号代认证、返利推广；
- 长期不可访问或入口频繁变化的镜像；
- 只有营销话术、没有清晰文档的产品；
- 与本主题关系很弱的泛泛工具。

## 精选资源

| 名称 | 适合场景 | 入口 |
| --- | --- | --- |
| awesome-selfhosted | 自托管项目大列表。 | [访问](https://github.com/awesome-selfhosted/awesome-selfhosted) |
| Docker | 容器基础设施。 | [访问](https://www.docker.com/) |
| CasaOS | 家庭云系统。 | [访问](https://casaos.io/) |
| Immich | 自托管相册。 | [访问](https://github.com/immich-app/immich) |
| Jellyfin | 自托管媒体服务器。 | [访问](https://jellyfin.org/) |
| Nextcloud | 个人云盘和协作平台。 | [访问](https://nextcloud.com/) |
| Vaultwarden | 轻量 Bitwarden 兼容服务。 | [访问](https://github.com/dani-garcia/vaultwarden) |
| Uptime Kuma | 自托管监控面板。 | [访问](https://github.com/louislam/uptime-kuma) |
| SiteWatcher | 自托管网站监控，检查可用性、响应时间以及证书和域名到期时间。 | [访问](https://github.com/NikKurkov/sitewatcher) |
| Portainer | Docker 管理面板。 | [访问](https://www.portainer.io/) |
| Nginx Proxy Manager | 反向代理和证书管理。 | [访问](https://nginxproxymanager.com/) |
| Homepage | 自托管服务导航页。 | [访问](https://gethomepage.dev/) |
| Home Assistant | 智能家居中枢。 | [访问](https://www.home-assistant.io/) |
| Gitea | 轻量自托管 Git 服务。 | [访问](https://about.gitea.com/) |

## 选型建议

- 先用 Docker Compose 管理服务。
- 所有外网暴露服务都要有 HTTPS 和强密码。
- 先搭备份，再搭相册和网盘。

## 风险提醒

- 避免将管理面板直接暴露到公网。
- 家庭 NAS 的核心风险是缺少可靠备份，而不是部署失败。

## 维护说明

- 本仓库会优先更新失效链接、官方入口变更和明显过时的描述。
- 新增资源请尽量给出官网、GitHub 仓库、文档页或可验证的公开说明。
- 推荐新资源时，请说明具体场景和选择理由，避免只写泛泛评价。

## 数据文件

结构化数据见 [`data/links.json`](data/links.json)，可用于脚本生成网页、表格或个人导航页。

## Contributing

欢迎提交 PR 修正链接、补充官方文档、更新截图或改进中文说明。请保持描述短、准、可验证。

## License

MIT。第三方商标、截图、网页内容和产品名称归各自权利方所有，本仓库只做索引和学习整理。
