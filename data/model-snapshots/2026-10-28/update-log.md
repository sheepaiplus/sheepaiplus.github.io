# 模型数据更新日志 2026-10-28

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-10-27T23:01:51.210523+00:00
- 上一版本：2026-10-27
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：d0660392e5919347925c2ba0a2407e35269110d8beccc8ba515ed23f54420482
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-10-28.html`

## 数据统计

- 模型数：335
- 有效分组：65
- 厂商数：24
- 调用端点数：182
- 计费类型：audio 2、basic 264、cache 17、image 7、step 45

## 变化摘要

- 新增模型：3
- 移除模型：1
- 字段变化模型：4
- 分组倍率变化：0

## 字段变化分布

- `billing_type`：2
- `cache_creation_1h_ratio`：1
- `cache_creation_5m_ratio`：1
- `enable_groups`：2
- `step_ratios`：1

## 新增模型

gpt-6.1-terra, qwen3.8-omni-flash, qwen3.8-omni-flash-realtime

## 移除模型

gemini-2.5-pro

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
