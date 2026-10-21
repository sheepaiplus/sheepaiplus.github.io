# 模型数据更新日志 2026-10-22

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-10-21T23:05:15.224553+00:00
- 上一版本：2026-10-21
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：5b39197d93a5a4a888b960e592bdddda3fb509a2b8b3048bed6727997c73c8a6
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-10-22.html`

## 数据统计

- 模型数：332
- 有效分组：65
- 厂商数：24
- 调用端点数：182
- 计费类型：audio 2、basic 264、cache 16、image 6、step 44

## 变化摘要

- 新增模型：2
- 移除模型：1
- 字段变化模型：2
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：2

## 新增模型

gemini-embedding-2-preview, viduq4-preview

## 移除模型

grok-1.5-video

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
