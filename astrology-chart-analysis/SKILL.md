---
name: astrology-chart-analysis
description: "专业西方古典占星星盘分析技能。以Hellenistic和Medieval传统为理论框架，提供本命盘解读、行运推运预测、合盘关系分析等全面服务。Use when user asks to: (1) analyze a natal/birth chart, (2) interpret planetary placements, aspects, or dignities, (3) predict timing with profections, firdaria, solar arc, transits, zodiacal releasing, (4) analyze relationship compatibility (synastry/composite), (5) read a chart screenshot or planetary data, (6) explain classical astrology concepts like sect, reception, lots, or any chart-related astrology questions."
---

# 西方古典占星星盘分析

## 分析流程

1. **接收输入**：用户提供星盘截图或行星度数列表
2. **识别盘型**：判断分析类型（本命盘 / 行运 / 合盘 / 预测）
3. **执行分析**：按对应流程进行解读
4. **分层输出**：先给简明总结，再提供专业详析

## 输入处理

### 星盘截图

从截图中提取：
- 上升星座及度数
- 各行星所在星座及度数
- 宫位分布（注意宫位制）
- 可见的相位线

如信息不完整，列出已识别的内容并询问缺失部分。

### 行星数据列表

用户可能以文字形式提供，如：
```
太阳 狮子座 15°, 月亮 双鱼座 22°, 上升 天蝎座 8°...
```

直接使用提供的数据进行分析。

## 分析类型与流程

### 本命盘分析

详见 [references/natal-chart.md](references/natal-chart.md)

分析步骤：
1. 教派判断（日间/夜间盘）→ 确定吉凶星倾向
2. 上升与盘主星 → 命主基调
3. 太阳、月亮状态 → 核心能量
4. 各行星尊贵度评估 → 参考 [references/dignities-reception.md](references/dignities-reception.md)
5. 宫主星网络 → 人生领域联结
6. 相位格局 → 关键互动
7. 福点与精神点 → 物质/精神指向
8. 特殊格局识别（群星、T三角、围困、燃烧等）

### 预测分析

详见 [references/predictive-techniques.md](references/predictive-techniques.md)

根据用户需求选择技法：
- **年度运势** → 小限法 + 行运 + 太阳回归盘
- **人生阶段** → 法达星限 + 黄道释放
- **具体事件时间** → 日弧推运 + 行运 + 小限交叉验证
- **内在转变** → 次限推运（推运月亮周期）
- **综合预测** → 多重技法叠加确认

### 合盘分析

详见 [references/synastry-composite.md](references/synastry-composite.md)

需要两人的本命盘数据。分析步骤：
1. 各自关系模式评估（7宫主、金星、月亮）
2. 轴点互动
3. 发光体与内行星相位
4. 宫位覆盖
5. 互容与接纳关系
6. 整体评估

## 输出格式

### 分层输出结构

**第一层：总结（所有用户可读）**

```
## 星盘概览
[2-3句话概括核心特质/运势，使用日常语言]

## 关键发现
- 要点1
- 要点2
- 要点3
```

**第二层：详细分析（占星爱好者/专业人士）**

```
## 详细分析

### 教派与盘主星
[专业术语 + 解释]

### 行星状态
[逐一分析各行星尊贵度、宫位、相位]

### 宫主星网络
[各宫主星的落宫关系]

### 相位格局
[重要相位及其意涵]

### [预测/合盘特定部分]
[根据分析类型展开]
```

### 术语处理

首次出现专业术语时附加简短解释：
- 正确：「入庙（行星在自己主宰的星座，力量最强）」
- 之后可直接使用术语

## 核心原则

- 使用整宫制（Whole Sign Houses）为默认宫位制
- 仅使用传统七星主宰体系，外行星不赋予主宰权
- 教派（Sect）是判断吉凶的首要依据
- 预测需多重技法交叉验证，避免单一技法下结论
- 解读需平衡——既指出挑战，也指出应对资源
- 如用户提供的数据使用其他宫位制（如Placidus），说明差异后仍以整宫制为主要分析框架
