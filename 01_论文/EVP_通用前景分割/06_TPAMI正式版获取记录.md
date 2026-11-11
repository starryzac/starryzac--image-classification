---
type: access-audit
tags: [图像分类, EVP, TPAMI, 获取记录]
created: 2026-10-29
updated: 2026-10-29
doi: 10.1109/TPAMI.2025.3619490
status: 用户提供期刊PDF已取得并归档；保留此前失败记录
---

# 2025年TPAMI正式版：获取记录

> [!success] 当前状态已更新
> 用户随后自行下载16页IEEE正式PDF并放入Zotero。已通过项目插件归档为附件 `3Z9Z9NPI`，完成 [全文逐段对照](../../PUBLICATION_SCOPE.md)。下文是此前访问失败的历史证据，不代表当前仍缺PDF。

目标为 [00_论文卡](00_%E8%AE%BA%E6%96%87%E5%8D%A1.md) 对应的 **IEEE 11197268**，在线日期2025-10-09，卷期48(2):1762–1777（2026）。本次继续以“仅主文”为范围，没有下载补充材料。

## 已实际核查的访问路径

| 路径 | 2026-10-29核查结果 | 能否提供期刊定稿 |
|---|---|---|
| 用户现有Edge中的[IEEE论文页](https://ieeexplore.ieee.org/document/11197268) | PDF控件明确显示 **“You do not have access to this PDF”**；正文首段后要求登录继续阅读。该页面可直接核对标题、DOI、在线日期与卷期页码。 | 当前浏览器会话不能下载。这里只说明当前会话无权限，不推断学校没有订阅。 |
| [Xi Shen作者主页](https://xishen0220.github.io/) | 论文列在TPAMI 2025下，PDF链接仍为 `https://arxiv.org/pdf/2305.18476`。 | 链接实际为已归档的2023年v1，14页，不能据标题上的2025改称定稿。 |
| [Xiaodong Cun实验室研究目录](https://gvclab.github.io/research/) | 对应条目仍链接arXiv:2305.18476。 | 未找到独立的期刊PDF。 |
| [Chi-Man Pun研究目录](https://cmpun.github.io/research.html) | 有48(2):1762–1777的书目信息，该条没有PDF链接。 | 只有书目证据。 |
| [澳门大学机构仓储](https://repository.um.edu.mo/) | 请求返回403。 | 无法核实内部是否收录，不能据此断言不存在。 |
| [OpenAlex DOI记录](https://api.openalex.org/works/https://doi.org/10.1109/TPAMI.2025.3619490) | 标为green OA，但唯一有PDF地址的仓储位置是arXiv；版本明确为 `submittedVersion`，`is_accepted=false`、`is_published=false`。IEEE出版位置标为非OA且无PDF地址。 | 公开副本仍是预印本。 |
| [Crossref DOI记录](https://api.crossref.org/works/10.1109/TPAMI.2025.3619490) | 期刊版许可链接是IEEE一般许可信息；另一个文件链接标注用途为similarity-checking，未将其当作正常个人全文下载授权。 | 未找到适用于本任务的公开定稿下载入口或全文翻译许可。 |
| Semantic Scholar API | 返回HTTP 429。 | 本次没有取得可用结果，不将失败当作“没有全文”的证据。 |
| Nature Downloader DOI公开源路线 | `downloaded=0`，`status=oa_not_found`；没有PDF落盘。 | 未完成期刊PDF下载。 |

作者项目站的CC BY-SA网站许可不能自动视为外部论文PDF的许可。作者代码仓库中的 `docs/static/pdfs/sample.pdf` 位于被注释的模板海报区域，未当作目标论文下载。

## 此前实际推进（历史）

已打开现有Edge论文页的 **Institutional Sign In → Access Through Your Institution**，尚未选择机构、输入账号或完成登录。当时曾询问学校图书馆/数据库入口；用户随后直接提供了已下载的PDF，因此不再等待该入口；不猜测学校代理域名、不绕过付费访问控制。

[本地插图 / Local figure](../../PUBLICATION_SCOPE.md)

本次并行补齐 [CVPR前作](../EVP_CVPR2023_%E5%89%8D%E4%BD%9C.md) 的官方CVF公开PDF归档。它与TPAMI定稿分开登记，不能用一篇的成功下载覆盖另一篇未完成的状态。

## 此前转换受限的情况（历史，现已解除）

PDF转Markdown在技术上可以做。本项目已具备MarkItDown及PDF解析工具，尚未完成全文输出并非因为缺少转换工具。

当时输入仍是外部链接，且未核实到允许完整复制、翻译该论文的开放许可，所以没有输出完整英文转写或整篇逐段译文。个人学习用途不能改变助手对自行检索版权全文的输出限制。用户作为附件提供拟处理PDF后，可以按文件的实际版本完成转换、逐段对照、公式图表检查及文末术语；详见 [03_全文对照接续说明](03_%E5%85%A8%E6%96%87%E5%AF%B9%E7%85%A7%E6%8E%A5%E7%BB%AD%E8%AF%B4%E6%98%8E.md)。

## 证据位置

- DOI下载尝试：`LOCAL_VAULT\Zotero\inbox\EVP_TPAMI_2025\manifest.json`。
- OpenAlex与Crossref原始记录及API状态：`LOCAL_VAULT\cache\EVP_TPAMI_2025\oa_checks.json`、同目录的 `openalex.json` 与 `crossref.json`。
- 既有作者稿附件、条目与哈希：[00_论文卡](00_%E8%AE%BA%E6%96%87%E5%8D%A1.md)。

下载工具清单中的 `oaAssessment=confirmed_oa` 与下载失败并存；它不能证明期刊定稿开放或允许全文译用。这里以实际PDF地址、版本字段、浏览器权限和文件验证为准。
