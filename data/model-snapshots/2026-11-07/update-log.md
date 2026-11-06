# 模型数据更新日志 2026-11-07

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-06T22:56:15.290207+00:00
- 上一版本：2026-11-06
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：906d3639a4574066c07ab98f2263df5714cc63e5d6689331988aca1764f105bb
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-07.html`

## 数据统计

- 模型数：331
- 有效分组：65
- 厂商数：25
- 调用端点数：185
- 计费类型：audio 4、basic 262、cache 18、image 8、step 39

## 变化摘要

- 新增模型：3
- 移除模型：16
- 字段变化模型：53
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：53

## 新增模型

gemini-flash-latest, gemini-flash-lite-latest, gemini-pro-latest

## 移除模型

flux-1.1-pro, flux.1-kontext-pro, gpt-4, gpt-4o-audio-preview-2024-12-17, gpt-4o-mini-transcribe, gpt-4o-transcribe, gpt-5.1-codex-mini, gpt-5.2-codex, gpt-audio-2025-08-28, gpt-image-1-mini, o3-pro, tts-1, tts-1-1106, tts-1-hd, tts-1-hd-1106, whisper-1

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
