# 模型数据更新日志 2026-11-24

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-23T22:56:52.633809+00:00
- 上一版本：2026-11-23
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：0c36c880c78fb309e5b944b2d1d0fb75f86f2ef1414bcc63421bcfeeb8d2972d
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-24.html`

## 数据统计

- 模型数：319
- 有效分组：65
- 厂商数：22
- 调用端点数：184
- 计费类型：audio 4、basic 249、cache 19、image 8、step 39

## 变化摘要

- 新增模型：4
- 移除模型：7
- 字段变化模型：14
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：14

## 新增模型

gemini-3.8-flash, gemini-4-argon, gemini-4-neon, minimax-h3-z

## 移除模型

grok-build-0.1, grok-imagine-image, grok-imagine-image-2.0, grok-imagine-image-quality, grok-imagine-video, grok-imagine-video-1.5-lite, grok-imagine-video-1.5-preview

## 校验与详细差异

完整字段变化见同目录下的 `changes.json`。

价格锚点：

```json
[
  {
    "name": "claude-opus-5",
    "base_input": 5.0,
    "aws_bedrock_1_input": 4.323564
  },
  {
    "name": "gpt-5.6-sol",
    "stage_1_input": 5.0,
    "stage_2_input": 10.0
  }
]
```

价格为模型广场估算值，最终以 Sheep AI Plus 实际扣费为准。
