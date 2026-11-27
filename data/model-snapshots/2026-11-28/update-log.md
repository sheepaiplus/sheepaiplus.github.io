# 模型数据更新日志 2026-11-28

> 维护者记录：保存数据来源、校验信息和归档位置，不作为面向用户的公告。

## 版本与来源

- 生成时间（UTC）：2026-11-27T22:58:08.201309+00:00
- 上一版本：2026-11-27
- 数据源：https://sheepaiplus.top/api/pricing
- 源文件：pricing.json
- 原始响应：raw.json.gz
- 原始数据 SHA-256：6aa4f3763473eca643fcc6c1f70e65e550f61cfd88c0792565a276d5c6d10d38
- 清洗快照：`cleaned.json`
- 机器差异：`changes.json`
- 用户公告：`announcements/models-update-2026-11-28.html`

## 数据统计

- 模型数：318
- 有效分组：65
- 厂商数：22
- 调用端点数：186
- 计费类型：audio 4、basic 249、cache 19、image 8、step 38

## 变化摘要

- 新增模型：1
- 移除模型：3
- 字段变化模型：7
- 分组倍率变化：0

## 字段变化分布

- `enable_groups`：7

## 新增模型

mj_fast_variation

## 移除模型

glm-4-flash, glm-4.5, glm-4.5-air

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
