# Creative Skills Vault

精选优质创意类 AI Agent Skills，让灵感变成作品。

## 分类收藏

### 图像创作 · 照片艺术化

| Skill | 用途 | 收录方式 | 许可 |
| --- | --- | --- | --- |
| [实景拼贴](skills/scenes-gathered-zine-v1-3) | 原始摄影与抽象插画、撕纸材质共同构图 | 完整镜像 | 个人非商业 |
| [影像蒸馏](skills/scene-distillation-zine-v1-3) | 从照片提取场景关系与情绪，重创独立插画 | 完整镜像 | 个人非商业 |
| [Minimal Visual Extract](catalog/image-creation/photo-art/minimal-visual-extract.md) | 上半摄影、下半极简插画的对照海报 | 来源索引 | 未发现明确授权 |

### 更多创意方向

已新增 [9 个候选 Skill 的分类目录与审阅记录](catalog/creative-skills.md)：单色印刷、海报、封面、漫画、信息图、算法艺术、静态视觉、GIF、动态演示。

完整镜像存于 skills/，来源索引与候选评估存于 catalog/。目录分类不改变既有 Skill 的安装路径。候选仅经文本审阅，尚未进行生成效果测试。

## 安装与使用

需要支持 Agent Skills 且具备图片理解、图像生成/编辑能力的环境；安装 Skill 本身不提供生图模型或额度。

使用支持该格式的 Skills CLI：

```bash
npx skills add PAUL-Zf/creative-skills-vault --skill scenes-gathered-zine-v1-3
npx skills add PAUL-Zf/creative-skills-vault --skill scene-distillation-zine-v1-3
```

也可下载仓库，将所需的完整 Skill 文件夹复制到 Agent 的 skills 目录中。不同 Agent 的目录与调用方式以其文档为准。

上传照片后调用，例如：

> 用 $scenes-gathered-zine-v1-3 把这张照片做成拾景纸刊海报，保留人物与海岸线的关系，文字用中文。

> 用 $scene-distillation-zine-v1-3 重新创作这张照片，不保留照片本身，让作品表达“靠近与错过”。

## 来源与迁移范围

- 来源：[Zeejay0/gathered-scenes-zine-skill](https://github.com/Zeejay0/gathered-scenes-zine-skill)
- 固定源版本：[`b9edb836c9dd5c5d80995e89ebcaba34b75fd58f`](https://github.com/Zeejay0/gathered-scenes-zine-skill/tree/b9edb836c9dd5c5d80995e89ebcaba34b75fd58f)
- 本次仅迁入上述两个 v1.3 Skill 的完整目录（SKILL.md 与 agents/openai.yaml），保持原文不变。
- 其他版本、实况照片流程、电影海报 Skill 及上游展示图片不在本次迁移范围。
- 原图与作品案例请查看[上游作品档案](https://github.com/Zeejay0/gathered-scenes-zine-skill/tree/b9edb836c9dd5c5d80995e89ebcaba34b75fd58f/examples)。
- 文件清单及上游 Git blob SHA 见 [SOURCES.md](SOURCES.md)。

## 许可证

各第三方 Skill 保持原作者许可证，不自动适用统一的 MIT 或其他宽松许可证。

当前两个 Skill 使用 **Gathered Scenes Zine Personal Non-Commercial License v1.0**，完整文本分别保存在各 Skill 的 LICENSE 文件中。仅限个人非商业用途；公司、雇主、客户或其他机构用途及商业用途须先获得原作者书面许可。免费分享时须保留许可、版权、署名和来源；修改文件须明确标识。

本仓库仅整理与收录，原作者保留相关权利。安装说明为本仓库新增，尚未进行实际生图效果测试。
