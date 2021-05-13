#  <p align=center>`SGSum`</p>

### 简介

**SGSum** (**S**ports **G**ame **Sum**marization) 是一个经过人工清洗的大规模高质量体育赛事摘要数据集。包含7854条体育赛事摘要数据，每条数据包括一场赛事的**在线评论文本**与**新闻文本**。

该数据集仅限学术研究使用。

### 数据集
请使用[讯飞云下载](http://pan.iflytek.com:80/link/96286F5C76F9559149AAFB9BD3B5D705)数据文件（密码XNRE）

共包含三个文件：

* ```train.json```: 训练集
* ```valid.json```: 验证集
* ```test.json```: 测试集


每个json文件的格式如下所示：

```
[
    {
        "_id" : "183",
        "level" : "hard",
        "commentary": [["1'", "都灵球员萨沙·卢基奇一脚直塞球给Juan Iturbe,但是边裁举旗显示后者已经越位.", "0-0"], ["2'", "国际米兰球员加格里亚迪尼大禁区外尝试左脚射门,可惜皮球偏出球门.", "0-0"], ["5'", "国际米兰球员伊卡尔迪大禁区中央右脚射门,被防守球员封堵.给他传球的是坎德雷瓦.", "0-0"],...],
        "news": "开场5分钟，坎德雷瓦中路长传，伊卡尔迪在门前14米处停球射门被封堵..."
    },
    {
        "_id": "288",
        "level": "hard",
        "commentary": [["2'", "利物浦球员杰拉德大禁区外右脚射门,被防守球员封堵.给他传球的是沙辛.", "0-0"], ["2'", "纽卡斯尔球员安尼塔拼抢犯规,对手获得控球权.", "0-0"],...],
        "news": "开场前4分钟，杰拉德两度外围射门均被封堵。第5分钟，苏亚雷斯禁区边缘内转身挑球突破科洛奇尼时被抢断..."
    },
    ...
]
```

### 数据统计
<p align="justify">
  <img src="https://github.com/krystalan/SGSum/blob/main/statistics.png" alt="statistics">
</p>


