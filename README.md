# 图床

> [!CAUTION]  
> 图床的repo名称不要与站点项目存放资源的路径相同，以避免因图床repo发布gh-pages造成网页资源路径冲突。

## 说明

该repo做为自用图床存储。

1. GitHub存储限制[^1]最多可以存5G左右
2. 一般电脑截图1-2M，Mac差不多翻倍，手机照片甚至十兆几十兆不等，所以需要 squoosh[^2] 进行图片压缩
3. 国内GitHub的链接很慢，所以上传的照片需要用到jsdelivr cdn[^3]保证加载速度。
4. 使用picgo[^4]方便将上述操作一气呵成。

以下是我的常用图床：

* https://tu.zbhz.org
* https://image.aibochinese.com
* https://imgchr.com
* https://sm.ms
* https://meee.com.tw
* https://img.scdn.io (单张图片连续60天未访问则自动清理)



## picgo配置

> [!IMPORTANT]  
> pico vscode不能像typora那样复制粘贴就直接上传到GitHub，vscode版相当于是一个独立的程序。
软件设置同picgo vscode版，token获取方式：https://github.com/settings/tokens

![](https://cdn.jsdelivr.net/gh/hoochanlon/tuchuang@main//up/86cd19f218e1b64528db53c1f8acbd5e.png)

> [!TIP]
> picgo时间戳重命名失败注意关闭插件内置的重命名功能。

![](https://cdn.jsdelivr.net/gh/hoochanlon/tuchuang@main//up/20251014210329971.png)

## typora

![](https://cdn.jsdelivr.net/gh/hoochanlon/tuchuang@main//up/d4eaabbc7788fd9ee1e78c67cbea3b87.png)

## map

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0,
        "name": "湖南郴州资兴"
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [113.200, 25.950],
            [113.200, 25.600],
            [113.700, 25.600],
            [113.700, 25.950],
            [113.200, 25.950]
          ]
        ]
      }
    }
  ]
}

```

[^1]: https://docs.github.com/zh/repositories/working-with-files/managing-large-files/about-large-files-on-github
[^2]: https://squoosh.app
[^3]: https://cdn.jsdelivr.net
[^4]: https://picgo.github.io/PicGo-Doc/zh/guide/getting-started.html

