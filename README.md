# tuchuang

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


## token获取方式

https://github.com/settings/tokens


CDN使用方式 `https://cdn.jsdelivr.net/gh/user/repo@version/file`

```
https://cdn.jsdelivr.net/gh/hoochanlon/img@main/up/p5r_test.jpg
```

## picgo配置



> [!NOTE]  
> pico vscode，不能直接复制粘贴一步上传到位。因为不是直接调用桌面端现有程序，相当于是一个独立的程序。



## typora






[^1]: https://docs.github.com/zh/repositories/working-with-files/managing-large-files/about-large-files-on-github
[^2]: https://squoosh.app
[^3]: https://cdn.jsdelivr.net
[^4]: https://picgo.github.io/PicGo-Doc/zh/guide/getting-started.html

