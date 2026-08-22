# Output template

## 容量审核

- 原时间段：
- 可用时长：
- 台词估时：
- 动作与反应估时：
- 判断：fits / tight / overloaded
- 拆分：

## 剧情功能

- 表层事件：
- 隐藏冲突：
- 情绪推进：
- 本场结尾状态：

## 海外市场与本地化

- 目标地区/受众：
- 平台/画幅/分级：
- 语言/口音/字幕：
- 类型承诺与开场钩子：
- 保留的故事内核：
- 需要本地化的文化机制：
- 暂定假设与风险：

## 角色与声音

For each character: identity, appearance, wardrobe, position, objective, subtext, voice identity, delivery state, line-level facial-performance map, body language, mouth-state, and continuity locks.

## 场景与连续性

Specify geography, time, physical light sources, color, materials, props, ambience, eyelines, 180-degree line, entrances, exits, and immutable layout details.

## 片段地图

| 片段 | 原时间线 | 生成时长 | 叙事任务 | 首帧状态 | 尾帧状态 |
|---|---:|---:|---|---|---|

## 片段提示词

For every clip:

### 分镜时间轴

| 镜头 | 本地时间 | 景别/机位/焦段 | 画面/肢体/逐句面部表演 | 对白/口型 | 转场 |
|---|---:|---|---|---|---|

### Seedance 2.0导演版

Write the prompt in Chinese with exact local time ranges and explicit hard-cut timestamps. Preserve supplied English dialogue verbatim. Bind each line to one speaker and state who must not move their mouth. Specify generated dialogue, ambience, Foley, prop sounds, and motivated effects. End with an explicit ban on subtitles, captions, title cards, watermarks, and screen overlays.

### 皮皮虾短剧平台精简执行版

Retain subject, action, cut points, camera, verbatim English dialogue, voice, generated ambience and Foley, reference assignments, preservation constraints, no-subtitle/no-overlay requirement, and ending state. Remove duplicated adjectives. Do not invent platform-specific fields that the user has not supplied.

### 节点命名

Use stable names such as `05A-01_偏殿建立大全景`, `05A-02_赵渊审问`, and `05A-03_赵景珩反应`.

## 修改说明

| 类别 | 原设计 | 修改后 | 原因 | 制作影响 | 剧情影响 |
|---|---|---|---|---|---|

## 高质量验收

Rate story, localization, casting/identity, performance, lip-sync/voice, continuity, anatomy/physics, composition/edit, material realism, and sound as `pass`, `revise`, or `regenerate`. List fixes in priority order.

## 连续生成交接

State which generated clip or actual final frame must be returned before the next continuation prompt becomes final.
