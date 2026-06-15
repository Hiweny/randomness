# Randomness

简洁优雅的随机内容展示页面——星空隧道粒子背景 + 抽屉式卡片动画。

**在线访问：** [hiweny.github.io/randomness](https://hiweny.github.io/randomness/)

---

## 页面结构

- **星空粒子背景** — 800 颗粒子，包含五角星、十字星、光点、闪耀等多种形状，原生 DPR 不限制
- **Randomness 渐变色标题**（靠左，首字母大写）
- **时间段模糊一言**（靠左，轻柔问候，来自山河API）
- **图片/文案 分类标签**（点击切换，抽屉式展开卡片列表）
- **卡片折叠展开** — 点击卡片标题拉开，再次点击收起；收起后重新打开会重新请求接口

---

## 页面内使用的 API

### 图片类

| 名称 | 接口地址 | 说明 |
|------|----------|------|
| 随机 JK 制服 | `https://shanhe.kim/api/tu/jk.php` | 直连，直接返回图片 |
| 随机二次元 | `https://shanhe.kim/api/tu/anime.php` | 直连，直接返回图片 |
| 猫羽雫 | `https://shanhe.kim/api/tu/mao.php` | 直连，直接返回图片 |
| 随机黑丝 | `https://v2.xxapi.cn/api/heisi` | 返回 JSON，内含图片直链 |
| 随机白丝 | `https://v2.xxapi.cn/api/baisi` | 返回 JSON，内含图片直链 |

### 文案类

| 名称 | 接口地址 | 说明 |
|------|----------|------|
| 时间段模糊一言 | `https://shanhe.kim/api/za/time.php` | 页面加载时显示在主标题下方 |
| 舔狗日记 | `https://shanhe.kim/api/za/tgrj.php?type=json` | 走 corsproxy.io 代理 |
| 土味情话 | `https://api.lovelive.tools/api/SweetNothings` | 走 corsproxy.io 代理 |
| BugPk 一言 | `https://api.bugpk.com/api/yiyan` | 走 corsproxy.io 代理 |
| Hitokoto 一言 | `https://v1.hitokoto.cn/?encode=text` | 直连 |
| 今日诗词 | `https://v2.jinrishici.com/one.json` | 直连，含作者出处 |

---

## 配色方案

页面内置 9 套配色方案（卡片 header 渐变），按卡片区分：

| 配色 | 卡片 |
|------|------|
| 月下海 (moon) | JK制服 |
| 天黑以前 (dusk) | 二次元 |
| 雪国夜 (snow) | 猫羽雫 |
| 渡月 (du) | 黑丝 |
| 弦月渡 (cres) | 白丝 |
| 夜航灯 (lamp) | 舔狗日记 |
| 暮云深 (cloud) | BugPk 一言 |
| 夜航星 (star) | Hitokoto 一言 |
| 夜航船 (night) | 今日诗词 |

> 注：土味情话使用 `rose` 配色（独立于以上命名）。

---

## CORS 代理

页面使用 `https://corsproxy.io/?` 代理 CORS 受限的接口（舔狗日记、土味情话、BugPk一言）。该代理免费版有限制，如返回错误页面内容会被拦截并展示友好提示。

---

## 文件结构

```
randomness/
├── index.html    # 完整页面
└── README.md     # 本文件
```

---

> 持续更新中……
