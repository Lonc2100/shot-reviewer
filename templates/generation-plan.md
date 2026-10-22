# 《<项目或剧集名>》视频生成计划 <版本>

```yaml
status: draft
source_path: <导演母版绝对路径>
source_version: <版本或 unknown>
source_sha256: <SHA-256>
shot_review_path: <已通过的 shot-review.md>
shot_review_status: approved
review_scope: <场次或镜号范围>
target_model: <模型名或待模型校准>
duration_basis: <官方能力／平台 schema／用户或项目声明／待模型校准>
generated_at: <ISO 8601>
```

## 单元审核表

| 单元 | 镜号范围 | 规划时长 | 主要内容 | 合并／拆分理由 | 参考图包 |
|---|---|---|---|---|---|
| <V01> | <1-01～1-05> | <如 26 秒；未知写待模型校准> | <连续内容> | <为什么共用或更换参考图包；容量是否容纳> | <环境／角色／道具VFX／锚点简述> |

## 资产缺口

| 缺口 | 影响单元 | 必要性 | 处理建议 |
|---|---|---|---|
| <无则写“无”> | <单元> | <必须／可选> | <复用、补图或待批准> |

## 逐段参考图绑定表

> 这里只决定实际进入模型的图片和语义职责；不预写 LibTV 图片编号。

| 单元 | 图片／ID | 文件路径 | 职责 | 状态 | 选择理由 |
|---|---|---|---|---|---|
| <V01> | <资产名> | <绝对路径> | <identity/environment/relationship_anchor/prop/vfx/first_frame/last_frame/carryover_frame> | <绑定／仅审核／不使用／缺口> | <一句原因> |

## 单元后台详情

### <V01>｜<单元名称>

- 镜号：<镜号列表>
- 叙事任务：<一个主要任务>
- 起始状态：<人物、道具、空间的可见状态>
- 结束状态：<动作结果和下一段可接状态>
- 主要接缝：<动作／视线／声音／物件／反应／遮挡／黑场／结果>
- 连续性风险：<无或具体风险>
- 模型状态：<已核对模型能力／待模型校准>
- 规划时长：<估算值或待模型校准>
- 时长依据：<官方能力／平台 schema／用户或项目声明／待模型校准>
- 参考图包指纹：<环境／机位 + 主要角色 + 道具VFX + 锚点模式 + 生成模式>

#### 参考图选择

| 资产 | 文件／ID | SHA-256 | 职责 | 选择理由 | 状态 |
|---|---|---|---|---|---|
| <资产名> | <路径或ID> | <哈希或unknown> | <identity/environment/relationship_anchor/prop/vfx/first_frame/last_frame/carryover_frame> | <为什么本单元需要> | <approved/candidate/gap> |

#### 下游交接

- 提示词编译注意：<只写语义和动作重点，不编写最终 Prompt>
- LibTV 绑定：未执行；不得预写 `{{Image N}}`。
