### 蹲蹲机（胖乖生活版）
你是否有过在宿舍洗衣服，却要和同学们一起去竞争洗衣机洗衣服的经历。经常抢不到洗衣机，总是在那里一遍又一遍的跑楼梯，那我告诉你，现在可以在寝室就得到楼下洗衣机的使用情况，而且你还可以设置一个提醒事项，当洗衣机出现空闲的时候，你将会收到提醒。
#### 使用方式
1. 安装相关依赖
2. 使用 `python main.py` 运行。
3. 按照提示使用。

#### 注意事项
在新版本中，胖乖生活使用了阿里云盾等防火墙软件，会导致无法登录，可以先抓包请求，得到 `token` 后使用自定义配置。配置步骤如下。
1. 在user文件夹下新建json文件，格式如下
```json
{
    "phone": "你的手机号",
    "token": "你的token",
    "delay": 60 // 表示轮询间隔时间，单位为秒
}
```
2. 再启动程序，选择使用。
