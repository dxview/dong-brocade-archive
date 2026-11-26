# 侗锦库归档 / Dong Brocade Archive

> 抢救性归档：原站「侗族织锦数字博物馆」（侗锦数据库）即将关闭，本仓库为 2026-11-26 对其公开资源的备份，永久保存。
> Rescue archive: the original site "Dong Brocade Digital Museum" (Dong brocade database) is about to close. This repository is a backup of its public resources made on 2026-11-26, preserved permanently.

## 原始出处 / Source

- 网站：http://traditional.design-engine.org/djk/search/
- 站名：侗锦数据库（侗族织锦数字博物馆，NEW CHANNEL）
- 归档日期：2026-11-26
- 原始数据接口：`http://traditional.design-engine.org/djk/search/do`（公开 JSON 接口）
- 详情页：`http://traditional.design-engine.org/djk/fixtures/{id}`

本仓库内容全部来自上述网站的公开页面与公开接口，未做任何修改，仅做整理。图片与附件原托管于七牛云（`dongjinku.fzcloud.design-engine.org`）。

All content in this repository comes from the public pages and public API of the source site above, unmodified except for organization. Images and attachments were originally hosted on Qiniu Cloud (`dongjinku.fzcloud.design-engine.org`).

## 本仓库包含 / What is in this repository

- **71 条织锦资源的完整元数据**（`metadata/fixtures.json`）：编号、名称、作者、采集地、年份、尺寸、介绍文字、分类标签（种类/色彩/构图/功能/格式）、主要图纹、附件文件名、原站详情页链接。
- **11 种图纹的元数据**（`metadata/patterns.json`）：井纹、八角花（百花纹）、几何纹、凤纹、太阳纹、蛇纹、蜘蛛纹、踩歌堂耶罗纹、马纹、鱼纹、龙纹；每种含介绍文字、参考文献与独立的图纹附件名。
- **摘要表**（`metadata/index.csv`）：71 条资源的摘要。
- **「关于侗锦」页说明**：该页内容为 7 张图片（概述/溯源、工艺、色彩、构图、用途、图案、发展），文字版未单独提取，图片见下文。

## 图片与附件文件 / Images and attachments

图片与附件原文件共 **668 个、约 1.7 GB**（480 张图片约 134 MB、82 个附件 zip 约 1.5 GB），已完整下载并保存在归档工作区，**未随本仓库一并推送**，原因：

1. GitHub 连接器的推送接口仅支持 UTF-8 文本文件（单次上限 16 MiB），无法推送图片与 zip 等二进制文件；
2. 附件总体积 1.7 GB，超出 GitHub 建议的仓库 1 GB 上限，单个最大文件 97.4 MB（接近 100 MB 单文件上限）。

如需把图片与附件也放进 GitHub，请在本机用 git 操作：克隆本仓库后，将归档工作区的 `fixtures/`、`patterns/`、`about/` 三个目录复制进来再推送；或将 82 个附件 zip 另建一个仓库/改用 Git LFS。

## 缺失说明 / Missing items

- **43 张图片在归档时已无法下载**：其原链接指向旧七牛域名（`7xkrns.com1.z0.glb.clouddn.com`），返回 404，源站上已失效。涉及 7 条资源（id 004、009、019、023、026、033、034）的部分「素材图」，其余图片均已存入。
- 其余 71 条资源的元数据全部完整；图片与附件除上述 43 张外全部存入。

## 版权 / License

本站资源为侗族传统织锦纹样的数字化记录，仅供学习、研究与非商业设计参考。原始版权归原作者与采集机构所有；如涉及商用，请联系原权利人。
