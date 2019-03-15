# jingjinjiyikatong_map
京津冀旅游一卡通地图导览

# 预览图
![](https://raw.githubusercontent.com/akmumu/jingjinjiyikatong_map/master/demo.png)
# demo示例
http://www.akmumu.com/map.html
# 如何使用
直接配置config中的内容即可
```
    var config = {
        "center": {"j": "116.276079", "w": "40.16096"}, //中心点的经纬度
        "attractions": [ //
            //海淀
            {"label":"鹫峰(3A)-4日闭园","location":"116.111358,40.071585","status":"black"},
            {"label":"阳台山(2A)","location":"116.112194,40.07365","status":"done"},
            {"label":"中国京西皮影非遗园","location":"116.224348,40.143285"},
            {"label":"大钟寺古钟博物馆(3A)","location":"116.344546,39.973724"},
            //丰台
            {"label":"世界公园","location":"116.297135,39.819814","status":"attention"},
            //延庆
            {"label":"古长城","location":"115.984126,40.344634"},
            {"label":"梦幻长城球幕影院(5A)","location":"116.015981,40.363695"},
            {"label":"古崖居风景名胜区(3A)","location":"115.781963,40.469104"},
            {"label":"长城铁花(A)","location":"115.993567,40.429756","status":"done"},
            //昌平
            {"label":"燕子湖风景区","location":"116.213614,40.297034"},
            {"label":"明十三陵总神道(5A)","location":"116.232006,40.263881","status":"done"},
            {"label":"居庸关长城(4A)","location":"116.082341,40.293508","status":"done"},
            {"label":"北京后花园","location":"116.104689,40.133128"},
            {"label":"静之湖森林公园(3A)","location":"116.450002,40.252247"},
        ]
    };
```
# 贡献
欢迎大家贡献代码以及添加一卡通上的景点到地图中
# 未得到主人的TODO
- 增加景区等级（5A等）
- 景区日期
- 是否需要预约的显示
- 待添加
