# 首页维护规范

首页是用户完成 AI 服务接入的路线图，不是全部内容的集合。产品总规范见 [`product-architecture-v3.md`](product-architecture-v3.md)。

## 区块顺序

```text
Hero
01 Sheep AI Plus
02 模型广场
03 快速开始
04 最新公告
```

不得为了新增内容随意改变核心用户路径。教程与公告的完整内容进入各自页面，首页只放解释、推荐和入口。

## 数据来源

| 内容 | 维护位置 |
|---|---|
| 品牌与全局链接 | `data/site.json` |
| 快速开始路线 | `data/tutorial-*.json` |
| 最新三条公告 | `data/announcements.json` |
| Hero 与区块说明文案 | `index.html` |

修改 JSON 后执行：

```bash
python3 scripts/build-site-data.py
python3 scripts/validate-site.py
```

## 快速开始入口

首页只链接到工具集合：

```text
guide/index.html?tool=<tool-id>
```

不要从首页直接跳到 CC Switch 生成器；生成器属于快速开始中的辅助与进阶入口。

## 视觉与交互

- 延续现有 CSS 变量和浅/深主题；
- 保持标题层级、焦点样式和 375px 移动端可用；
- 外链使用 `target="_blank" rel="noopener"`；
- 避免重复玻璃卡片和无业务意义的装饰；
- 修改后检查横向溢出、导航滚动和 reduced-motion。
