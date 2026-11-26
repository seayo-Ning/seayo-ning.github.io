# Boning Wu's Academic Homepage

Personal academic homepage of **Boning Wu (吴博宁)**, M.S. student at the School of Mechanical Engineering, Guangxi University.

🌐 **Live Site**: [https://seayo-ning.github.io](https://seayo-ning.github.io)

---

## 日常维护速查指南

1. **更换个人头像**：
   - 将你的正方形照片命名为 `profile.png`（或 `profile.jpg`），放入 `images/` 目录覆盖原文件（若改了后缀名，同步修改 `_config.yml` 中的 `avatar` 字段）。
2. **添加微信二维码 / Google Scholar / ORCID**：
   - 打开 `_config.yml`，在 `author:` 下填入 `wechat_qr: "images/wechat.jpg"`（图片放入 `images/`）、`googlescholar` 或 `orcid`。
3. **更新个人简介、新闻动态、发表论文、教育与获奖经历**：
   - 打开 `_pages/about.md` 直接修改对应板块内容。
   - 新增论文配图放入 `pub_images/`，BibTeX 条目添加到 `files/papers.bib` 即可支持鼠标悬停预览与一键复制。

Built upon [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) under the MIT License.
