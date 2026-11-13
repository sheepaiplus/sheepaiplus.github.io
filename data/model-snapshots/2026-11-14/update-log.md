# 模型数据更新日志 2026-11-14

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-13T22:59:38.252839+00:00
- 上一版本：2026-11-13
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：e94530e9e5a6058c3206da841ca039f02b6056199a96d313c2aa547fea576419
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-14.html`

## 数据统计

- 模型数：321
- 有效分组：65
- 厂商数：23
- 调用端点数：184
- 计费类型：audio 4、basic 253、cache 18、image 8、step 38

## 变化摘要

- 新增模型：1
- 移除模型：2
- 字段变化模型：15
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：14
- `supported_endpoint_types`：1

## 新增模型

gemini-4-hydrogen

## 移除模型

mj_upload, mj_upscale

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
