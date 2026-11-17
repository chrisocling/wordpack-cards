# Wordpack · 拆词记

英语单词抽卡与拼写练习网站。

- 固定 3,837 个词条，按词频加权抽取。
- 每 60 秒最多开一包，每包最多 5 个不同单词；已学过的词退出候选池。
- 新词默认进入“正在学”，每次移入“已学过”都需正确拼写。
- 学习进度与倒计时保存在访客自己的浏览器中。

此仓库保存已构建的网站文件，通过 GitHub Pages 从 main 分支根目录部署。无需安装依赖。

## 来源与许可

- card-pack-opening 卡包动画：© 2026 chrisocling，MIT，见 CARD-PACK-LICENSE.txt。
- 词典：skywind3000/ECDICT，MIT，见 ECDICT-LICENSE.txt。
- 词频：Hermit Dave / FrequencyWords、OpenSubtitles 2018，数据内容及派生词库采用 CC BY-SA 4.0，见 CC-BY-SA-4.0.txt。
- 固定版本、筛选规则和数据归属见 source.json。

应用由 Qoder CLI 开发，需求、数据准备与验收由 Codex 辅助；当前网站托管于 GitHub Pages。
