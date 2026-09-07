# Creative Skills

图像与视频创作 Skills 合集。仓库只维护索引和上游引用，不存放第三方仓库内容；安装和使用时请以各上游项目的最新文档与许可证为准。

## 图像创作 Skills

| Skill | 用途 | 上游项目 | 授权 |
| --- | --- | --- | --- |
| Minimal Zine Poster | 极简纸感编辑海报、留白、实验性文字和视觉锚点 | [LiamGvchi/gc-minimal-zine-poster](https://github.com/LiamGvchi/gc-minimal-zine-poster) | MIT |
| Photo Abstract Editorial | 保留原照片，并生成同源抽象记忆面板与诗意标题 | [ZzzLc0405/photo-abstract-editorial](https://github.com/ZzzLc0405/photo-abstract-editorial) | 个人、教育、研究和非商业用途 |
| Scenes Gathered Zine v1.3 | 照片锚点、来源抽象插画、强调色和手撕纸边界 | [Zeejay0/gathered-scenes-zine-skill](https://github.com/Zeejay0/gathered-scenes-zine-skill) | 个人非商业授权 |
| Culture Fragment Poster Engine | 文化素材索引、视觉基因提取、文化海报和品牌 KV | [dacnay816y62-hub/culture-fragment-poster-engine](https://github.com/dacnay816y62-hub/culture-fragment-poster-engine) | 上游未发现许可证，使用前确认 |
| Create Photo Flipbook UI | 照片书、zine、作品集和响应式 3D 翻页网页 | [HaichaoLihc/create-photo-flipbook-ui](https://github.com/HaichaoLihc/create-photo-flipbook-ui) | MIT；内置 page-flip 另有第三方许可 |
| Paper Signal | 主体保持、适应性构图、编辑视觉、系列生成和位图 QA | [jiahuiqu17/paper-signal](https://github.com/jiahuiqu17/paper-signal) | MIT |
| Zine Poster Skill | minimal、scenes、editorial 三种 zine / photo-editorial 工作流 | [jas0nh/zine-poster-skill](https://github.com/jas0nh/zine-poster-skill) | MIT；请同时阅读 NOTICE |
| Poster Generator Skill | 从文字内容生成 20 种风格的设计级海报 | [howardz27/poster-generator-skill](https://github.com/howardz27/poster-generator-skill) | MIT |
| Baoyu XHS Images | 将文章拆成 1–10 张社交媒体图片卡片 | [JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) | 以源仓库许可证为准 |

## 展示效果

以下图片使用上游仓库中的公开示例，通过远程链接展示；本仓库不保存这些图片。

| Skill | 上游展示效果 | 示例来源 |
| --- | --- | --- |
| Minimal Zine Poster | <img src="https://raw.githubusercontent.com/LiamGvchi/gc-minimal-zine-poster/main/examples/night-door.jpeg" alt="Minimal Zine Poster example" width="180"> | [night-door.jpeg](https://github.com/LiamGvchi/gc-minimal-zine-poster/blob/main/examples/night-door.jpeg) |
| Photo Abstract Editorial | <img src="https://raw.githubusercontent.com/ZzzLc0405/photo-abstract-editorial/main/assets/examples/case-10.jpg" alt="Photo Abstract Editorial example" width="180"> | [case-10.jpg](https://github.com/ZzzLc0405/photo-abstract-editorial/blob/main/assets/examples/case-10.jpg) |
| Scenes Gathered Zine v1.3 | <img src="https://raw.githubusercontent.com/Zeejay0/gathered-scenes-zine-skill/main/examples/real-scene-collage/01-where-stone-meets-sky/result.jpg" alt="Scenes Gathered Zine example" width="180"> | [result.jpg](https://github.com/Zeejay0/gathered-scenes-zine-skill/blob/main/examples/real-scene-collage/01-where-stone-meets-sky/result.jpg) |
| Culture Fragment Poster Engine | <img src="https://raw.githubusercontent.com/dacnay816y62-hub/culture-fragment-poster-engine/main/8dc29d5b4ddb67499a005d4d0c14661.png" alt="Culture Fragment Poster Engine example" width="180"> | [8dc29d5b…png](https://github.com/dacnay816y62-hub/culture-fragment-poster-engine/blob/main/8dc29d5b4ddb67499a005d4d0c14661.png) |
| Create Photo Flipbook UI | <img src="https://raw.githubusercontent.com/HaichaoLihc/create-photo-flipbook-ui/main/docs/images/death-valley-flipbook.jpg" alt="Create Photo Flipbook UI example" width="180"> | [death-valley-flipbook.jpg](https://github.com/HaichaoLihc/create-photo-flipbook-ui/blob/main/docs/images/death-valley-flipbook.jpg) |
| Paper Signal | <img src="https://raw.githubusercontent.com/jiahuiqu17/paper-signal/main/assets/gallery/01-study-old-town-after-rain.webp" alt="Paper Signal example" width="180"> | [gallery](https://github.com/jiahuiqu17/paper-signal/tree/main/assets/gallery) |
| Zine Poster Skill | <img src="https://raw.githubusercontent.com/jas0nh/zine-poster-skill/main/assets/samples/zine-channel-guide.png" alt="Zine Poster Skill example" width="180"> | [zine-channel-guide.png](https://github.com/jas0nh/zine-poster-skill/blob/main/assets/samples/zine-channel-guide.png) |
| Poster Generator Skill | <img src="https://raw.githubusercontent.com/howardz27/poster-generator-skill/main/examples/poster-grid-en.jpg" alt="Poster Generator Skill example" width="180"> | [poster-grid-en.jpg](https://github.com/howardz27/poster-generator-skill/blob/main/examples/poster-grid-en.jpg) |
| Baoyu XHS Images | 暂无单独稳定样图，查看上游 README 中的样式、布局和生成说明 | [官方 README](https://github.com/JimLiu/baoyu-skills#baoyu-xhs-images) |

## 安装方式

### 方式一：Skills CLI

适用于支持社区 Skills 安装器的宿主。推荐先安装完整项目，再按提示选择具体 Skill：

```bash
npx skills add jiahuiqu17/paper-signal --agent codex
npx skills add jas0nh/zine-poster-skill --agent codex
npx skills add howardz27/poster-generator-skill --agent codex
npx skills add JimLiu/baoyu-skills --agent codex
```

### 方式二：Git 克隆

适用于 Codex 或其他支持本地 Skill 目录的宿主。克隆后把包含 `SKILL.md` 的 Skill 目录复制到宿主的 Skill 目录；Codex 常用目录为 `~/.agents/skills/`。

```bash
git clone https://github.com/LiamGvchi/gc-minimal-zine-poster.git
git clone https://github.com/ZzzLc0405/photo-abstract-editorial.git
git clone https://github.com/Zeejay0/gathered-scenes-zine-skill.git
git clone https://github.com/dacnay816y62-hub/culture-fragment-poster-engine.git
git clone https://github.com/HaichaoLihc/create-photo-flipbook-ui.git
git clone https://github.com/jiahuiqu17/paper-signal.git
git clone https://github.com/jas0nh/zine-poster-skill.git
git clone https://github.com/howardz27/poster-generator-skill.git
git clone https://github.com/JimLiu/baoyu-skills.git
```

### 方式三：单 Skill 安装

当上游仓库包含多个 Skill 时，只复制目标目录，避免把整个合集加载进宿主：

```bash
mkdir -p ~/.agents/skills
cp -R gathered-scenes-zine-skill/skills/scenes-gathered-zine-v1-3 ~/.agents/skills/
cp -R create-photo-flipbook-ui/skills/create-photo-flipbook-ui ~/.agents/skills/
cp -R paper-signal/skills/paper-signal-art-director ~/.agents/skills/
cp -R paper-signal/skills/paper-signal-series ~/.agents/skills/
cp -R baoyu-skills/skills/baoyu-xhs-images ~/.agents/skills/
```

对于根目录直接包含 `SKILL.md` 的项目，直接复制项目目录即可：

```bash
cp -R gc-minimal-zine-poster ~/.agents/skills/
cp -R photo-abstract-editorial ~/.agents/skills/
cp -R culture-fragment-poster-engine ~/.agents/skills/
cp -R zine-poster-skill ~/.agents/skills/zine
cp -R poster-generator-skill ~/.agents/skills/poster-generator
```

安装完成后，新开一个任务或刷新宿主的 Skill 列表。是否能直接生成图片，取决于宿主提供的图像生成和图像查看能力。

## 说明

- `scenes-gathered-zine-v1-3` 位于 `gathered-scenes-zine-skill` 的 `skills/` 子目录。
- `paper-signal` 和 `baoyu-skills` 都是多 Skill 仓库，本合集只列出与图像创作直接相关的入口。
- `culture-fragment-poster-engine` 和部分个人授权项目不应默认用于商业项目。
- 后续新增视频创作 Skills 时，在本 README 增加上游链接、用途、入口和授权说明，不复制上游内容。
