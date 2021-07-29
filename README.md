<!-- #  <p align=center>`体育赛事摘要`</p> -->

<p align="center">
    <br>
    <img src="./pics/banner.png" width="500"/>
    <br>
</p>

## News
2021/7/29 我们的论文《SGSum：一个面向体育赛事摘要的人工标注数据集》入选CCKS 2021 Oral Paper。

2021/7/2 我们的论文《SGSum：一个面向体育赛事摘要的人工标注数据集》被CCKS 2021录用为资源类（Resource Track）论文。



## SGSum
#### 简介

**SGSum**是一个经过人工清洗的大规模高质量体育赛事摘要数据集。包含7854条体育赛事摘要数据，每条数据包括一场赛事的在线评论文本与新闻文本。

该数据集仅限学术研究使用。

#### 数据集
请使用[讯飞云](http://pan.iflytek.com:80/link/C91C8827872D98DB78E6F25B8E94FCD3)（密码FECv）或[百度网盘](https://pan.baidu.com/s/1rWUTRi3dPdwmXhRD_UjLPQ)（密码p51j）下载数据文件

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
备注："level"字段中的"hard"代表“丰富类”; "medium"对应“中等类”; "easy"对应“简短类”
