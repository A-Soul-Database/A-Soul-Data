# A-Soul-Data A-Soul 直播数据
[Asdb 运行结构请移步](https://github.com/peterpei1186861238/A-Soul-Database)
## 文件结构
```
main.json --- 记录月份或年份的直播归档
srt/ --- 处理好的字幕文件
schedule/ --- 日程表
danmaku/ --- 字幕文件
timeline/ --- 评论区和其他地方的时间轴
Index.json --- 索引BV号位置
search.json --- 包含字幕和其他文件信息
```

<details>
<summary>场景一览表</summary>
Under Construction
</details>

<details>
<summary>服饰一览表</summary>
Under Construction
</details>

<details>
<summary>index.json 模板</summary>

```json
{
	"date": "12-11",
	"time": "20:00",
	"liveRoom": "D",
	"bv": "BV1Ka411k7rM",
	"title": "【A-SOUL一周年】2021.12.11 周年特别直播！",
	"scene": ["LegendWorld"],
	"type": ["song", "chat", "dance", "game"],
	"staff": ["A", "B", "C", "D", "E"],
	"clip": 3,
	"items": [{
		"name": "game",
		"item": [
			["入梦", "1-18:01"],
			["同行", "1-61:37"],
			["赴约", "2-22:39"],
			["乘风", "3-03:15"],
			["追光", "3-21:04"]
		]
	}, {
		"name": "song",
		"item": [
			["沧海一声笑", "1-28:37", ["A"]],
			["刀马旦", "1-37:54", ["C"]],
			["传说的世界", "2-19:12", ["A", "B", "C", "D", "E"]],
			["在水一方", "2-29:02", ["C", "E"]],
			["藏", "2-35:35", ["A", "B", "D"]],
			["流光记", "3-08:11", ["E"]],
			["苏幕遮", "3-09:10", ["B"]],
			"......"
		]
	}, {
		"name": "dance",
		"item": [
			["leavan polkka", "1-07:23", ["A", "B", "C", "D", "E"]],
			["我们身处当下", "1-08:17", ["A", "B", "C", "D", "E"]],
			["ふわふわ時間", "1-09:48", ["A", "B", "C", "D", "E"]],
			"......."
		]
	}],
	"skin": {
		"A": ["LegendWorld", "group", "year"],
		"B": ["LegendWorld", "group", "year"],
		"C": ["LegendWorld", "group", "year", "official"],
		"D": ["LegendWorld", "group", "year"],
		"E": ["LegendWorld", "group", "year"]
	},
	"platform": "B",
	"tags": ["00:01 还记得与她们的初遇吗？","....."]
}
```
</details>

