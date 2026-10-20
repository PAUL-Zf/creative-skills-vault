# 创意 Skills 候选目录

核查日期：2026-10-20。以下 9 项仅收录来源与评估，没有镜像或安装其文件。

筛选依据：直接阅读上游 SKILL.md，检查输入输出、工作流和依赖描述，并查看 GitHub 许可信息；Anthropic 三项另核查了各自目录的 LICENSE.txt。优先级是文本审阅判断，不是实测评分。尚未测试安装、生成质量、运行安全或不同 Agent 的兼容性；不以 Stars 或更新时间单独认定质量。

| 分类 | Skill / 来源 | 主要用途 | 推荐理由及限制 | 许可 | 优先级 |
| --- | --- | --- | --- | --- | --- |
| 图像创作 / 单色印刷 | [mono-color](https://github.com/yanliudesign/mono-color-skill/blob/main/SKILL.md) | 将主题或参考照片转成单色/双色编辑印刷视觉 | 色彩与排版规则具体，含输出配方；默认输出路径需适配本机 | MIT | 优先 |
| 图像创作 / 海报 | [poster-generator](https://github.com/howardz27/poster-generator-skill/blob/main/SKILL.md) | 按内容选择海报构图与风格 | 有20类风格与可选渲染后端；需完整 references 目录及生图工具 | MIT | 备选 |
| 内容创作 / 漫画 | [baoyu-comic](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-comic/SKILL.md) | 将知识、教程或人物故事改编为漫画 | 分镜与风格流程完整；需生图能力和相关参考文件，跨页一致性需验证 | MIT | 优先 |
| 信息设计 / 信息图 | [baoyu-infographic](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-infographic/SKILL.md) | 将复杂内容组织成信息图 | 明确区分信息布局与视觉风格；生成的数据、文字仍需校对 | MIT | 优先 |
| 图像创作 / 文章封面 | [baoyu-cover-image](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-cover-image/SKILL.md) | 按主题、色板、表现方式、文字与情绪创作封面 | 支持多种比例且后端选择明确；需要配套文件与生图环境 | MIT | 优先 |
| 生成艺术 / 算法艺术 | [algorithmic-art](https://github.com/anthropics/skills/blob/main/skills/algorithmic-art/SKILL.md) | 使用 p5.js 创作可调参数的生成艺术 | 有种子与参数探索流程、查看器模板；默认 CDN 依赖需留意离线环境 | Apache-2.0（该 Skill 目录） | 优先 |
| 视觉设计 / 静态艺术 | [canvas-design](https://github.com/anthropics/skills/blob/main/skills/canvas-design/SKILL.md) | 以设计理念创作 PNG/PDF 视觉作品 | 设计过程清楚，附字体等资源；须保留资源各自许可并适配路径 | Apache-2.0（该 Skill 目录） | 优先 |
| 动态创作 / GIF | [slack-gif-creator](https://github.com/anthropics/skills/blob/main/skills/slack-gif-creator/SKILL.md) | 生成适合聊天使用的动画 GIF | 含 GIF 构建工具、尺寸与帧率约束；需要完整 core 工具目录和 Python 环境 | Apache-2.0（该 Skill 目录） | 优先 |
| 交互创作 / 动态演示 | [frontend-slides](https://github.com/zarazhangrui/frontend-slides/blob/main/SKILL.md) | 制作有动画效果的 HTML 演示文稿 | 有风格预览与固定画布规范；须携带模板、脚本与参考文件，转换 PPT 另有依赖 | MIT | 优先 |

## 建议收藏顺序

先尝试 mono-color（与照片纸刊相近但有独立视觉语言）、baoyu-comic（叙事扩展）、algorithmic-art（用代码创作）、frontend-slides（动态表达）。其余按实际场景补充。

## 获取原则

优先从作者仓库获取完整 Skill 目录，不能只复制 SKILL.md 而遗漏脚本、模板、字体、references 或资源许可。宿主已有生图能力时应按实际工具接口适配；Skill 不提供模型账号、额度或 API 密钥。

MIT 条目依据核查时 GitHub 的仓库级许可元数据；后续实际迁移仍须核对完整许可及第三方资源例外。Anthropic 条目依据各 Skill 自带 Apache-2.0 许可，不能由此推断其仓库内所有内容采用同一许可。
