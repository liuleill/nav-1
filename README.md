## 一个前端的导航项目

### 技术栈：html，css，js，jQuery，hashMap,使用Iconfont库里面的图标，本项目涉及了俩图标都是使用iconfont里面的图标

目的：主要把自己平时使用的几个网站放在一起，方便使用，主要供给自己使用，后面会不断进行维护，迭代

    1.使用hashMap和localStrage，保证用户存储的数据不会丢失

    2.页面初始化的时候会获取locaStrage存贮的x值，并把x转成对象xObject，如果对象存在，则hashMap获取该对象，如果不存在，hashMap获取默认的数组对象

    3.而关闭当前页面的时候，会把当前页面的hashMap值存起来，并转成字符串供下次加载页面使用
