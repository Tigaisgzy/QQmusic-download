# 有很多地方可以优化，大家就去自己优化吧。我懒得搞了哈哈

## QQ音乐下载工具

   1. 先去网页版登录，从cookie中获取qm_keyst
   （有效期为一天，说是一天，但是测试下来好像能用挺久的）
   （必须是绿钻的，非绿钻的下不了vip音乐）
   qq登录的话uin就是qq号，微信登录的话就是cookie中的wxuin

   2. 将qm_keyst与uin写入，uin即为QQ号

      ![img.png](QQ音乐V0.1/img/img2.png)

   3. 启动mian.py，输入歌曲名即可下载

      ![img_1.png](QQ音乐V0.1/img/img_1.png)

   4. 当前下载的是默认搜索到的第一首歌曲，如果要选择的话，将搜索结果那部分修改即可，网页版限制搜索结果最多10条。

## 网易云音乐下载工具

   1. 先去网页版登录，从cookie中获取MUSIC_U和__csrf

   ![img_2.png](网易云音乐/img/img_2.png)

   2. 启动main.py，输入歌曲名获取搜索结果，这个搜索结果默认30条，可以根据需求修改。

   ![img.png](网易云音乐/img/img.png)

   3. 选择歌曲，输入歌曲id即可下载。

   ![img.png](网易云音乐/img/img3.png)

