# randomness

测试和收藏一些免费好玩的 API，供以后做小玩具用。

---

## 山河API (shanhe.kim)

来源：https://api.shanhe.kim/
已收录 138 个接口，大部分免费无需 API Key。

### 🩵 图片类

| 名称 | 接口地址 | 参数 | 状态 |
|------|----------|------|------|
| JK制服图 | `http://shanhe.kim/api/tu/jk.php` | type=json/txt/image（默认image） | ✅ 正常，900+张 |
| 随机二次元动漫图（PC横屏） | `http://shanhe.kim/api/tu/anime.php` | type=json/txt/image | ✅ 正常，1400+张 |
| 猫羽雫图片 | `http://shanhe.kim/api/tu/mao.php` | type=json/txt/image | ✅ 正常 |
| 随机ai绘制图 | `http://shanhe.kim/XX` | 待验证具体路径 | ⏳
| 随机头像图片 | `http://shanhe.kim/XX` | 支持选择类型：动漫/女生/男生/景物 | ⏳
| Bing每日壁纸 | `https://api.shanhe.kim/XX` | 1920x1080横屏 | ⏳
| 随机黑丝图片 | `http://shanhe.kim/XX` | ❌ 已维护（被举报） |
| 随机白丝图片 | `http://shanhe.kim/XX` | ❌ 已维护 |
| 小姐姐随机视频 | `http://shanhe.kim/XX` | ❌ 已维护（1.8k+小姐姐视频） |

### 📝 文字/语录类

| 名称 | 接口地址 | 参数 | 状态 |
|------|----------|------|------|
| 时间段模糊一言 | `http://shanhe.kim/XX` | 无需参数，返回JSON | ⏳
| 舔狗日记 | `http://shanhe.kim/XX` | type=text/json/js | ⏳
| 随机一言 | `http://shanhe.kim/XX` | type=text/json/js | ⏳
| 聚合语录 | `http://shanhe.kim/XX` | 支持20+种类语录 | ⏳
| 网易云热评 | `http://shanhe.kim/XX` | 随机网易云热评 | ⏳
| 网易云热评v2 | `http://shanhe.kim/XX` | 随机网易云热评 | ⏳
| KFC疯狂星期四语录 | `http://shanhe.kim/XX` | 文本返回 | ⏳
| 神回复 | `http://shanhe.kim/XX` | 随机段子 | ⏳
| 挑战古诗词 | `http://shanhe.kim/XX` | 文本返回 | ⏳

### 🎵 音乐/视频解析

| 名称 | 接口地址 | 状态 |
|------|----------|------|
| 网易云音乐解析 | `http://shanhe.kim/XX` | 获取mp3下载链接 | ⏳
| 抖音视频解析 | `http://shanhe.kim/XX` | 去水印 | ⏳
| 快手视频解析 | `http://shanhe.kim/XX` | 去水印 | ⏳
| 皮皮虾视频解析 | `http://shanhe.kim/XX` | 去水印 | ⏳
| 短视频图集解析 | `http://shanhe.kim/XX` | 支持多平台 | ⏳
| 聚合视频解析 | `http://shanhe.kim/XX` | 支持快手/微博/皮皮虾 | ⏳

### 😂 表情包/整活类

| 名称 | 接口地址 | 说明 | 状态 |
|------|----------|------|------|
| 二维码生成 | `http://shanhe.kim/XX` | 输入内容生成二维码 | ⏳
| 小人举牌 | `http://shanhe.kim/XX` | 自定义内容生成举牌图 | ⏳
| 人生倒计时 | `http://shanhe.kim/XX` | 人生倒计时 | ⏳

---

## BugPk API (api.bugpk.com)

来源：https://api.bugpk.com/

| 名称 | 接口地址 | 参数 | 示例 |
|------|----------|------|------|
| 一言 | `https://api.bugpk.com/api/yiyan` | 无需参数 | 返回格式：`英文/&/中文` |
| 抖音解析 | `https://api.bugpk.com/api/douyin?url=` | url=分享链接 | 已用于collection项目 |
| 小红书解析 | `https://api.bugpk.com/api/xhsjx?url=` | url=分享链接 | 已用于collection项目 |
| 短视频聚合 | `https://api.bugpk.com/api/short_videos?url=` | url=分享链接 | 已用于collection项目 |

---

## UomgAPI (api.uomg.com)

来源：https://api.uomg.com/
注意：部分接口可能已失效

| 名称 | 接口地址 | 状态 |
|------|----------|------|
| 名人名言 | `https://api.uomg.com/api/mingyan` | ❌ 失效 |
| 土味情话 | `https://api.uomg.com/api/words` | ❌ 404 |
| 网易云热评 | `https://api.uomg.com/api/comments.163` | ❌ 404 |
| 历史上的今天 | `https://api.uomg.com/api/history` | ❌ 失效 |
| 随机图 | `https://api.uomg.com/api/rand.img1` | ❌ 404 |
| 笑话 | `https://api.uomg.com/api/joke` | ❌ 失效 |

---

## 已验证活着的 API（可直接使用）

| 名称 | 接口地址 | 返回格式 | 说明 |
|------|----------|---------|------|
| JK制服图 | `http://shanhe.kim/api/tu/jk.php?type=json` | JSON | 900+张随机JK制服图 |
| 二次元动漫(PC) | `http://shanhe.kim/api/tu/anime.php?type=json` | JSON | 1400+张横屏二次元 |
| 猫羽雫图片 | `http://shanhe.kim/api/tu/mao.php?type=json` | JSON | 随机猫羽雫 |
| BugPk 一言 | `https://api.bugpk.com/api/yiyan` | 纯文本 | 每日随机一句话 |

---

## 待探索的免费API平台

- **小小API** https://xxapi.cn - 中文，无需注册
- **public-apis** https://github.com/public-apis/public-apis - 全球网友整理的数千免费API
- **无铭便民API** https://jkapi.com - 53个接口
- **聚合数据** https://www.juhe.cn - 760+API，部分免费
- **ALAPI** https://blog.alapi.cn - 100万+开发者使用
