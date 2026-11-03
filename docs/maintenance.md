# Maintaining the collection / 维护方法

## Content model

`data/projects.json` holds bilingual project descriptions, stable numbers, category IDs, official repository URLs, and license source links. The two READMEs expose the same records in readable form. Numbers and `project-XX` anchors are public references; keep them stable.

Five categories organize the collection: animation, scenes, physics, audio, and delivery. They describe a project's main place in the workflow, not all of its capabilities.

## When updating

1. Read the upstream repository, its README, and the actual license/terms file. Check for moves, archived status, component-specific terms, and changed project scope.
2. Update the data and both READMEs in the same PR. Change the checked date only after the records being claimed as checked have actually been reviewed; do not refresh it mechanically.
3. Keep descriptions specific. Avoid unconditional free/commercial claims or presenting the list as a tested integrated software stack.
4. Confirm project counts, category membership, source links, license links, translation parity, and stable navigation. Check local images and preview desktop/narrow layouts.
5. Update the infographic if its names, counts, descriptions, or categories become inaccurate. Original source SVGs live in `assets/`; preserve the creator attribution.
6. Keep raw research, credentials, machine paths, and working audit logs out of this repository.

Original infographic and cover assets are hosted in this repository. Project banner URLs are hotlinked from official upstream GitHub social-preview metadata; their source pages and preview types are recorded in `docs/media-sources.md` and `data/projects.json`. Recheck each upstream image and its click destination when changing banner metadata. The collection's CC BY 4.0 applies to original text and visuals only. Refer to upstream license sources before adding other people's media.

## 中文说明

项目数据、中英文 README 与信息图应保持一致。更新前阅读官方仓库、README 和完整许可，检查迁移、归档及组件许可变化。稳定编号与 `project-XX` 锚点应保留；只有实际核对后才能更新核对日期。

说明应具体，避免无条件免费承诺或把选型清单描述为已经联调的整套软件。发布前核对分类、数量、来源、许可、中英翻译与图片，并检查桌面和窄屏预览。原始研究、凭据和工作日志不进入公开仓库。

项目封面使用官方 GitHub 页面声明的分享图；没有自定义分享图时使用 GitHub 生成的仓库预览卡。修改图片时同步更新数据与来源文档，并检查图片加载和点击目标。上游图片不适用本合集的 CC BY 4.0。
