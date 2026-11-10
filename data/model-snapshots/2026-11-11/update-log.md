# 模型数据更新日志 2026-11-11

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-10T23:01:09.038860+00:00
- 上一版本：2026-11-10
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：c9253c9774b79b6553e91c7a75d64a0cf803cb4d830d34f88f4e52160dc7e4cf
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-11.html`

## 数据统计

- 模型数：328
- 有效分组：65
- 厂商数：25
- 调用端点数：185
- 计费类型：audio 4、basic 259、cache 19、image 8、step 38

## 变化摘要

- 新增模型：1
- 移除模型：0
- 字段变化模型：16
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：16

## 新增模型

claude-fable-5-2

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
