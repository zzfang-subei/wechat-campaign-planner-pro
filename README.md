# 私域活动策划大师 Pro

一个给 Codex 使用的微信/私域活动策划 skill，用于策划新活动、诊断已有活动问题、生成活动文案、做行业适配、执行拆解和复盘优化。

适合线下课、私域运营、社群活动、电商促销、教育转化、本地生活拉新、老用户促活等场景。

## 安装

在 Codex 里直接发送这一句：

```text
请从 GitHub 安装这个 skill：https://github.com/zzfang-subei/wechat-campaign-planner-pro/tree/main/skills/wechat-campaign-planner-pro
```

安装后下一轮对话可用：

```text
用 $wechat-campaign-planner-pro 帮我策划一个私域活动
```

## 能做什么

- 微信活动策划：拉新、促活、转化、品牌活动
- 活动问题诊断：参与率低、传播差、完成率低、ROI 不好
- 行业适配：电商、教育、本地生活、金融等行业活动策略
- 活动文案：预热、进行中、结束、社群、客服、朋友圈文案
- 执行方案：节奏、预算、物料、风险和数据指标
- 活动复盘：问题定位、优化建议、下一轮迭代

## 项目结构

```text
wechat-campaign-planner-pro/
  skills/
    wechat-campaign-planner-pro/
      SKILL.md
      agents/
        openai.yaml
      references/
        活动方案模板库.md
        爆款活动案例集.md
        活动文案模板与话术库.md
        心理学驱动的活动设计完全指南.md
        活动问题诊断与优化指南.md
        行业特性适配与策略指南.md
```

## 校验

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py skills/wechat-campaign-planner-pro
```

## 版本

当前版本：`0.1.0`
