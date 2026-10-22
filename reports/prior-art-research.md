# 参考研究 · 2026-10-22

本次实际查看本地 shot-reviewer、character-asset-cleanup、fish-wanwusheng 入口及 Skill 使用地图。
shot-reviewer 复用既有源稿权威、分阶段审核、参考图职责分离和静态卡模板；不改成新导演系统。
character-asset-cleanup 只参考“批准图是身份权威”的职责，不引入三路图像重建；fish-wanwusheng 面向特定模型且有自己的来源要求，不复制其文案或执行依赖。

外部检索：character design reference sheet SKILL.md；storyboard shot review SKILL.md。
- https://github.com/fal-ai-community/skills/blob/main/skills/character-design/SKILL.md ：身份锚点与画风分离可作概念参照；其 genmedia 与模型路由不适合本包无平台依赖的默认提示词交付，不复制源代码。
- https://github.com/Saeyeon-developer/character-design-sheet ：横向全身多视图、表情及细节图并非本次固定2:3上脸下身模板；不替换用户版式。仓库标明Apache-2.0，未复制其内容。
- https://github.com/EyrieCommander/codex-video-vision/blob/main/skills/storyboard-review/SKILL.md ：搜索结果说明其检查实际成片与分镜符合度，属于后期补充能力；页面直接读取失败，不声称完整审计。

未运行SkillsMP/skills.sh双目录研究；不宣称覆盖全部技能、流行度排名或质量优于他人。外部维护状态、许可证及运行安全未全面审计；候选未安装或运行。
