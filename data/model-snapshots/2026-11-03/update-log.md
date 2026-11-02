# 模型数据更新日志 2026-11-03

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-02T22:59:22.306925+00:00
- 上一版本：2026-11-01
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：2948be2c4c384252dcef57f202215f2e09ee9c4744bb326ea6274d8097b31171
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-03.html`

## 数据统计

- 模型数：336
- 有效分组：65
- 厂商数：24
- 调用端点数：184
- 计费类型：audio 4、basic 266、cache 19、image 7、step 40

## 变化摘要

- 新增模型：1
- 移除模型：0
- 字段变化模型：28
- 分组倍率变化：0

## 字段变化分布

- `billing_type`：4
- `cache_ratio`：13
- `completion_ratio`：2
- `enable_groups`：3
- `step_ratios`：17

## 新增模型

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
