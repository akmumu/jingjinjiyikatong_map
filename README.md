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
            {"label":"明十三陵总神道","j":"116.232006","w":"40.263881"}, //每个景点的经纬度，名称
            {"label":"古长城","j":"115.984126","w":"40.344634"} ////每个景点的经纬度，名称
        ]
    };
```
# 贡献
欢迎大家贡献代码以及添加一卡通上的景点到地图中
# 未得到主人的TODO
- 增加景区等级（5A等）
- 景区日期
- 待添加
