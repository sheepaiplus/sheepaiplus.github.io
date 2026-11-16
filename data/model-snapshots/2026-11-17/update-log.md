# 模型数据更新日志 2026-11-17

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-16T23:03:40.559953+00:00
- 上一版本：2026-11-16
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：fcba38e8a575f0be3d48a7083549c7e3d12b6016a95aef7e2464540ab4bacdac
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-17.html`

## 数据统计

- 模型数：324
- 有效分组：65
- 厂商数：23
- 调用端点数：184
- 计费类型：audio 4、basic 255、cache 18、image 8、step 39

## 变化摘要

- 新增模型：4
- 移除模型：1
- 字段变化模型：12
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：10
- `model_price`：1
- `supported_endpoint_types`：1

## 新增模型

gemini-2.5-pro, hy4-flash, mj_upload, mj_upscale

## 移除模型

wan2.7-image-pro

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
