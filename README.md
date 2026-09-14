# Jwan AI Skills

Jwan 的可复用 AI Skill 总目录。每个 Skill 都是一个独立的 Markdown 工作流，包含名称、触发条件、执行规则、输出要求和质量检查。

## Skill catalog

| Skill | 用途 | 独立仓库 |
| --- | --- | --- |
| `jwan-circular-cutout-story-poster` | 圆形照片切片故事海报 | [GitHub](https://github.com/gongjuan96-crypto/jwan-circular-cutout-story-poster) |
| `jwan-photo-poem-poster` | 照片与插画配对、下方诗意文案 | [GitHub](https://github.com/gongjuan96-crypto/jwan-photo-poem-poster) |
| `jwan-wibi-frame` | 照片与复古漫画头像拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-wibi-frame) |
| `jwan-marker-child-diptych` | 儿童照片与马克笔插画拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-marker-child-diptych) |
| `jwan-minimal-pet-doodle` | 宠物照片与极简涂鸦拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-minimal-pet-doodle) |
| `documentary-color-collage-poster` | 黑白纪实照片与半透明色彩线稿 | [GitHub](https://github.com/gongjuan96-crypto/documentary-color-collage-poster) |
| `jwan-dark-red-black-cel-shaded` | 暗红黑赛璐璐头像拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-dark-red-black-cel-shaded) |
| `jwan-fisheye-city-cover` | 鱼眼城市封面拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-fisheye-city-cover) |
| `jwan-alt-manga-avatar` | 照片与漫画头像拼接 | [GitHub](https://github.com/gongjuan96-crypto/jwan-alt-manga-avatar) |
| `jwan-electric-blue-poster` | 电蓝半调肖像海报 | [GitHub](https://github.com/gongjuan96-crypto/jwan-electric-blue-poster) |
| `jwan-tech-food-launch-poster` | 食物科技发布会海报 | [GitHub](https://github.com/gongjuan96-crypto/jwan-tech-food-launch-poster) |
| `jwan-ink-overrun-editorial-poster` | 黑色水墨越界编辑海报 | [GitHub](https://github.com/gongjuan96-crypto/jwan-ink-overrun-editorial-poster) |
| `jwan-culture-fragment-poster-engine` | 文化碎片编辑海报 | [GitHub](https://github.com/gongjuan96-crypto/jwan-culture-fragment-poster-engine) |

## Install

每个目录中的 `SKILL.md` 都可以单独复制到支持 Agent Skills 的智能体中。也可以打开上表中的独立仓库，下载对应文件和 `examples/` 案例目录。

### 通用安装

1. 进入 `skills/<skill-name>/`。
2. 复制 `SKILL.md` 全文。
3. 粘贴到智能体的 Skill、系统提示词、角色设定或工作流规则区域。
4. 将对应独立仓库中的案例图作为视觉参考资料上传。
5. 用 `$skill-name` 或自然语言描述任务进行调用。

### Codex / Claude Code

将完整 Skill 文件夹放入对应工具的 Skills 目录，并确保入口路径为：

```text
<skills-directory>/<skill-name>/SKILL.md
```

### 豆包及不支持 Skill 文件夹的平台

新建一个智能体，把 `SKILL.md` 粘贴到角色设定或系统提示词；每个智能体建议只安装一个 Skill，避免不同视觉规则互相冲突。

## Repository convention

每个独立仓库保持以下结构：

```text
SKILL.md
README.md
LICENSE
examples/
```

案例图是公开展示素材，不包含用户原始照片文件。

## Maintainer

Created and maintained by Jwan (`gongjuan96-crypto`).

## License

The Jwan-authored catalog and bundled Skill files are released under the MIT License. Individual repositories may include additional attribution requirements for adapted source material; check each repository's README and LICENSE.
