## 简介

这个项目是18年高中写的，是我第一次接触后端开发，因为喜欢网页开发，但静态网页始终不如人意，于是就开始探究后端。

而这方面的探索得益于我校高教课 金峰 老师，每次探讨这个页面的时候都非常高兴。
## 技术栈
Django、sqlite3、jquery、bootstrap、ckeditor

### 项目功能

- 登录(账号后台导入)
- 后台引入富文本编辑器
- 答题积分机制
  - 正确加分
  - 错误扣分
  - 每天只能计分一次
- 收藏夹
- 错题记录
- 支持单选多选(6个选项)文字题
- 支持书本-单元-小节逻辑分层
- 统计做题数量，班级排名，正确率等信息

### 安装

新建虚拟环境安装 `All_bundle.text` 文件里面的依赖,内容如下

```
asn1crypto==0.24.0
cffi==1.11.5
cryptography==2.3.1
Django==2.1.1
django-ckeditor==5.6.1
django-js-asset==1.1.0
idna==2.7
Pillow==5.2.0
pycparser==2.18
PyMySQL==0.9.2
pytz==2018.5
six==1.11.0
```

**账号：**

90500160123	123456

admin	admin

### 登录

![image-20220407083131625]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407083131625.png)

### 首页

![image-20220407083525183]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407083525183.png)

### 题目记录分类

![image-20220407083619989]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407083619989.png)

点击题目可以跳转到对应的题目页面

### 答题界面

![image-20220407083724754]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407083724754.png)

### 答题卡

![image-20220407083748135]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407083748135.png)

### 后台管理

![image-20220407084010543]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407084010543.png)

### 题目编辑

![image-20220407084036942]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407084036942.png)

### 选项设置

![image-20220407084103708]( https://ev20.oss-cn-hangzhou.aliyuncs.com/GiteeImage/image-20220407084103708.png)
