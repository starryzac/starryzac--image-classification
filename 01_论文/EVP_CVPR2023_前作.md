---
type: paper
tags: [图像分类, EVP, 前作, 文献关系]
created: 2026-10-29
updated: 2026-11-10
title: Explicit Visual Prompting for Low-Level Structure Segmentations
authors: [Weihuang Liu, Xi Shen, Chi-Man Pun, Xiaodong Cun]
year: 2023
doi: 10.1109/CVPR52729.2023.01862
arxiv_id: 2303.10883
zotero_item_key: XP73YZ24
zotero_attachment_key: 8E8F8Z2B
pdf_version: CVF官方开放版，与接受稿除水印外相同
pdf_pages: 12
pdf_sha256: 0a0916b981c003b2c8e33a1fa1aa5f3d93073c5c3b001ad86db89e855f2c3da4
pdf_copy_path: ""
status: CVF主文PDF已通过Zotero归档；全文转写和逐段译文未完成
---

# EVP的CVPR 2023前作

独立原文副本：[直接打开会议论文 PDF](../PUBLICATION_SCOPE.md)。副本与 Zotero 受管原件的 SHA-256 一致，2026-11-10 核验。

发表于CVPR 2023，页码19434–19445。[CVF正式论文页面](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_Explicit_Visual_Prompting_for_Low-Level_Structure_Segmentations_CVPR_2023_paper.html) · [作者项目页](https://nifangbaage.github.io/Explicit-Visual-Prompt/)。

[通用前景分割论文](EVP_%E9%80%9A%E7%94%A8%E5%89%8D%E6%99%AF%E5%88%86%E5%89%B2/00_%E8%AE%BA%E6%96%87%E5%8D%A1.md)是其扩展工作；关系依据为作者仓库扩展版公告及扩展预印本引言，详见 [02_版本与来源核验](EVP_%E9%80%9A%E7%94%A8%E5%89%8D%E6%99%AF%E5%88%86%E5%89%B2/02_%E7%89%88%E6%9C%AC%E4%B8%8E%E6%9D%A5%E6%BA%90%E6%A0%B8%E9%AA%8C.md)。这里建立一个实际论文节点，便于Obsidian图谱显示前作与扩展的连接。

阅读代码时先认识 [视觉提示](../02_%E6%9C%AF%E8%AF%AD/%E8%A7%86%E8%A7%89%E6%8F%90%E7%A4%BA.md)、[傅里叶变换与高频](../02_%E6%9C%AF%E8%AF%AD/%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2%E4%B8%8E%E9%AB%98%E9%A2%91.md) 和 [冻结与微调](../02_%E6%9C%AF%E8%AF%AD/%E5%86%BB%E7%BB%93%E4%B8%8E%E5%BE%AE%E8%B0%83.md)；具体实现路线见 [03_从论文想法到代码入口](../04_%E6%95%99%E5%AD%A6/EVP%E5%85%A5%E9%97%A8/03_%E4%BB%8E%E8%AE%BA%E6%96%87%E6%83%B3%E6%B3%95%E5%88%B0%E4%BB%A3%E7%A0%81%E5%85%A5%E5%8F%A3.md)。本页登记来源、归档与关系，不声称已经完成前作全文精读或实验复现。

## 已取得的主文与版本

2026-10-29从 [CVF官方主文PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Explicit_Visual_Prompting_for_Low-Level_Structure_Segmentations_CVPR_2023_paper.pdf) 下载了12页文件，页码19434–19445，大小5,001,888字节。首页说明这是Computer Vision Foundation提供的开放版本，除水印外与接受稿相同；IEEE最终会议录版本另在IEEE Xplore。因此本页将附件标为**CVF官方开放版**，不冒称本次另行取得IEEE最终排版版。

本次只收集主文，未下载补充材料。标题、作者、页数与页码已核对；未执行全文MD转写或整篇逐段翻译。

## Zotero归档与附件核验

| 项目 | 已读回结果 |
|---|---|
| 项目API | `http://127.0.0.1:23120`，已由项目入口核对profile及data路径 |
| 集合 | `图像分类`，key `KUTSQ6LT` |
| 文献条目 | 在Zotero选择前作（溯源地址：`zotero://select/library/items/XP73YZ24`），key `XP73YZ24` |
| PDF附件 | [用Zotero打开前作PDF](../PUBLICATION_SCOPE.md)，key `8E8F8Z2B` |
| SHA-256 | `0a0916b981c003b2c8e33a1fa1aa5f3d93073c5c3b001ad86db89e855f2c3da4` |

[打开本项目受管PDF](../PUBLICATION_SCOPE.md)。

实际路径为 `LOCAL_VAULT\Zotero\data\storage\8E8F8Z2B\Liu 等 - 2023 - Explicit Visual Prompting for Low-Level Structure Segmentations.pdf`。已读回附件URL并核实文件存在、真实PDF头、12页及哈希与下载文件一致。归档通过已安装Zotero插件的HTTP帮助程序完成，未直接写数据库。

机器可读证据：[EVP_CVPR2023_zotero_archive.json](../PUBLICATION_SCOPE.md)。下载清单在项目 `Zotero/inbox/EVP_CVPR2023/manifest.json`；专用导入脚本为 `tools/archive_evp_cvpr.py`。

完整原文MD和逐段中英对照仍未交付。处理用户提供的PDF后的交付口径可参照 [03_全文对照接续说明](EVP_%E9%80%9A%E7%94%A8%E5%89%8D%E6%99%AF%E5%88%86%E5%89%B2/03_%E5%85%A8%E6%96%87%E5%AF%B9%E7%85%A7%E6%8E%A5%E7%BB%AD%E8%AF%B4%E6%98%8E.md)，但必须为本前作建立独立文件，不能与期刊扩展版混在一起。
