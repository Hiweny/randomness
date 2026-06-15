# Randomness

简洁优雅的随机内容展示页面——星空隧道粒子背景 + 抽屉式卡片动画。

**在线访问：** [hiweny.github.io/randomness](https://hiweny.github.io/randomness/)

---

## 页面结构

- **星空粒子背景** — 800 颗粒子，五角星/十字星/光点/闪耀等多种形状，原生 DPR 不限制
- **Randomness 渐变色标题**（靠左，首字母大写）
- **时间段模糊一言**（靠左，轻柔问候，来自山河API）
- **文案 | 图片 分类标签**（文案左、图片右，抽屉式展开卡片列表）
- **卡片折叠展开** — 点击卡片标题拉开，再次点击收起；收起后重新打开会重新请求接口
- **文案卡片展开后自动居中滚动**

---

## 页面内使用的 API

### 图片类（共 6 个）

| 名称 | 接口地址 | 说明 |
|------|----------|------|
| 随机 JK 制服 | `shanhe.kim/api/tu/jk.php` | 山河API，直连 |
| 随机二次元 | `shanhe.kim/api/tu/anime.php` | 山河API，直连 |
| 猫羽雫 | `shanhe.kim/api/tu/mao.php` | 山河API，直连 |
| 随机黑丝 | `v2.xxapi.cn/api/heisi` | 返回JSON含直链 |
| 随机白丝 | `v2.xxapi.cn/api/baisi` | 返回JSON含直链 |
| 随机头像 | `shanhe.kim/api/tu/avatar.php?type=json` | 山河API，头像随机 |

### 文案类（共 11 个）

| 名称 | 接口地址 | 说明 |
|------|----------|------|
| 人生倒计时 | `shanhe.kim/api/za/rsdjs.php?type=json` | 山河API，今年/本周/本月/今天 |
| 星座运势 | `shanhe.kim/api/za/xingzuo.php?msg=` | 山河API，需填星座名 |
| 历史上的今天 | `shanhe.kim/api/za/lishi.php?format=json` | 山河API |
| 随机抽签 | `shanhe.kim/api/za/chouq.php?type=json` | 山河API，含签文 |
| 今日诗词 | `v2.jinrishici.com/one.json` | 直连 |
| Hitokoto 一言 | `v1.hitokoto.cn/?encode=text` | 直连 |
| BugPk 一言 | `api.bugpk.com/api/yiyan` | 走corsproxy代理 |
| 土味情话 | `api.lovelive.tools/api/SweetNothings` | 走corsproxy代理 |
| 舔狗日记 | `shanhe.kim/api/za/tgrj.php?type=json` | 走corsproxy代理 |
| 聚合语录 | `shanhe.kim/api/za/juhe.php?msg=经典语录&type=json` | 山河API |
| 随机色卡 | `shanhe.kim/api/wz/color.php` | 点击变色，不显示色值 |

---

## 配色方案（共 19 套）

### 旧版配色

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

> 土味情话使用 `rose`（独立配色）

### 城市与自然系列（新增 10 套）

| 配色 | 卡片 |
|------|------|
| 隙光 (xiguang) | 人生倒计时 |
| 雪岭望 (xueling) | 星座运势 |
| 暮潮 (muchao) | 历史上的今天 |
| 赤岩远天 (chiyan) | 随机抽签 |
| 海之眼 (haizhiyan) | — |
| 归港 (guigang) | 聚合语录 |
| 碧岩 (biyan) | 随机头像 |
| 樱见 (yingjian) | — |
| 南墙 (nanqiang) | 随机色卡 |
| 暮卫城 (muweicheng) | — |

---

## CORS 代理

页面使用 `https://corsproxy.io/?` 代理 CORS 受限的接口。免费版有限制，如返回错误会被拦截并展示友好提示。

---

## 文件结构

```
randomness/
├── index.html    # 完整页面（手动上传）
└── README.md     # 本文件
```

---

> 持续更新中……