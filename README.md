更新时间：2021年3月10日20:58:46

当天选了好多主题，然后发现不会弄，然后选择了matery主题

不过这几天觉得Butterfly主题也不错，可能会搭建一个新的博客

## 1月29日

2021年1月29日开始搭建博客，因为时间问题基本都是在晚上修复bug和更改一些设置

bug：未配置username和useremail 具体操作忘记了待补充

## 1月30日	

修改了网站名称和网站图标等

## 1月31日

同时进行了两个网站(gitee和github)的部署和网站汉化(一开始是自己汉化到最后发现站点目录下的语言选择错误，一开始教程zn-CN主题中文语言包是zh-CN)

## 2月01日

修改了友情链接样式，并对电影目录修改[教程](https://blog.csdn.net/qq_41496127/article/details/108852514?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161426921916780262582191%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=161426921916780262582191&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~baidu_landing_v2~default-1-108852514.pc_v1_rank_blog_v1&utm_term=matery%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5),然后电影修改后一直报错

## 2月02日

继续修改电影ejs，直到最后那friends.ejs替换后重新修改才完成

## 2月03日-2月07日

忘记了，不更新了

## 2月08日

对博客滚动条背景等一系列做了改动[教程](https://blog.csdn.net/cungudafa/article/details/106278206?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522161279666616780255242975%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fall.%252522%25257D&request_id=161279666616780255242975&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~hot_rank-8-106278206.first_rank_v2_pc_rank_v29&utm_term=matery)跳转评论因为bug就没有采用，添加了背景科技线条[教程](https://blog.csdn.net/weixin_33888907/article/details/93354304?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522161279624716780264036896%252522%25252C%252522scm%252522%25253A%25252220140713.130102334..%252522%25257D&request_id=161279624716780264036896&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~baidu_landing_v2~default-1-93354304.first_rank_v2_pc_rank_v29&utm_term=hexo%25E5%258A%25A8%25E6%2580%2581%25E7%25BA%25BF%25E6%259D%25A1)

## 2月09日

添加了live2D（看板娘）[教程](https://blog.csdn.net/u011054333/article/details/82718910?ops_request_misc=%25257B%252522request%25255Fid%252522%25253A%252522161288583216780255291737%252522%25252C%252522scm%252522%25253A%25252220140713.130102334.pc%25255Fall.%252522%25257D&request_id=161288583216780255291737&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~rank_v29-2-82718910.first_rank_v2_pc_rank_v29&utm_term=%25E5%258D%259A%25E5%25AE%25A2live2d%25E4%25BD%258D%25E7%25BD%25AE)

## 2月10日

调整了网页返回顶部按钮

## 2月11日

添加了评论系统valine，并对其美化

## 2月12日

修改了原有主题的相册参照[[过客～励む](https://yafine-blog.cn/)]的[教程](https://yafine-blog.cn/posts/3b98.html)同时为自己在gitee搭建了图床，但忘记上传图片有大小导致上传失败，还有设置正确导致无法上传（图片标出来的）![image-20210224235446805](C:\Users\xjuzhi\AppData\Roaming\Typora\typora-user-images\image-20210224235446805.png)

但是因为没学过json的语言，导致错误

```json
[
    {
      "name": "2020",
      "cover": "images/p0.png",
      "description": "我的图床",
      "photos": [
        "images/node-1.png",
        "images/node-2.png",
        "images/node-3.png",
        "images/node-4.png",
        "images/node-5.png",
        "images/node-6.png",
        "images/node-7.png",
        "images/node-8.png",
        "images/logo.png",
        "images/logo1.png",
        "images/node-11.png",
        "images/node-12.png",
        "images/01.gif",
        "images/02.gif",
        "images/03.gif",
        "images/04.gif"
      ]
    }
]
```

注意最后一行并不会用；结尾

```json
"images/错误方法.gif";
```



而是直接结尾

```json
"images/正确方法.gif"
```



然后对博客打算采用cdn加速，设置完后发现cdn和gitee图床没啥却别，于是放弃了在github的cdn加速



## 2月13日

完善了音乐页面参考的LuckyMe的博客，基于[LuckyMe博客](http://luckyzmj.cn/)公开源码的音乐页面源码~~只改了一丢丢源码，就搬过来了~~来完善音乐界面，然后找artitalk，修复了artitalk，一开始照着[cungudafa](https://cungudafa.blog.csdn.net/)代码写的然后提示版本低，[hexo（matery）添加实时发布说说页面（Artitalk）](https://cungudafa.blog.csdn.net/article/details/106208556)直接删了重改后来照着博主[留幸愉](https://blog.csdn.net/Edviv)[Hexo系列matery主题踩坑优化记录](https://blog.csdn.net/Edviv/article/details/110632433)抄的css部分

```css
<%- partial('_partial/bg-cover') %>

<style ype="text/css">

#pubShuo {

  margin-right: 5px;
}

#operare_artitalk .shuoshuo_input_log {
    outline-style: none;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 6px;
    padding: 8px 16px;
    font-size: 12px;
    background-color: transparent;

    color: #0bb7fbd6;
    width: 70%;
    height: 28px;
    margin-left: 10px;
}

#artitalk_main {

  margin-top: 5px ;
  margin-left: 5%;
  margin-right: 5%;

}

#lazy{
  margin-top: 40px;
}

</style>


<script src="<%- theme.jsDelivr.url %><%- url_for(theme.libs.js.artitalk) %>"></script>

<article id="articles11" class="container  chip-container">
  <div class="row ">

      <div class=" card">
        <div class="card-content" >
          <div class="tag-title center-align">
                <i class="fas fa-pen-alt"></i> 说说
           </div>
          <div id="artitalk_main"></div>
        </div>  
      </div>

  </div>
</article>
<script>
```



后面的直接复制的matery主题下的_widget/artitalk.ejs的代码

```javascript
<script type="text/javascript" src="//cdn.jsdelivr.net/npm/artitalk"></script>
<div id="artitalk_main"></div>
<script>
    new Artitalk({
        appId: '<%- theme.artitalk.appId %>',
        appKey: '<%- theme.artitalk.appKey %>',
    })
</script>
```



## 2月14日

弄了一晚上首页视频，发现弄不了b站的链接,然后找b站的视频源代码找不到然后就放弃了，打算直接写网页，因为由于我本人纯小白一点不会那种我找到首页视频上的css文件，然后复制粘贴到网页中index.md中，然后添加b站链接，嵌入式的那个链接，然后发现直接叠在推荐文章一起，又弄了半天就放弃了，然后打算下载b站视频直接添加，然后发现，添加后也没发播放本地，然后我又将视频上传github和gitee用mp4的url，结果也没用，于是心态爆炸直接不弄了

## 2月15日

准备添加追番功能，插件(hexo-bilibili-bangumi)都装完了准备测试页面时点击在看会跳转空白链接和番剧页面和文章页面没区别，然后一直找没找到就睡觉了

## 2月16日

第二天，还是不好用，找到作者的github看了半天没说明，然后打算删除数据了，然后把整个_data下的文件全删了，于是我关了这个追番插件，然后花了时间又修复了电影图书页面顺带把bug反馈给了作者

## 2月17日

今天下午看到hexo-bilibili-bangumi的作者发的邮件，bug修复完了升级到1.5.2了，然后我去到github仓库看了一下，顺带瞟见了插件仿照了douban插件，然后晚上准备弄书单界面，发现douban插件要用hexo版本<4.2.0否则有bug跳转空白页面，然后我就想起了追番插件了。我也没打算降版本所以就不用追番插件了，然后在留言板添加了一言，照着两位大佬抄的，明天补（2月18日补）

然后又看到大佬的界面想要源码

## 2月18日

2021年2月18日00:32:06，备忘录刚好码完

#### 2.18晚上

晚上我本来想给网页弄个深色模式，但是弄完之后看了看好丑然后就删了

然后我找到博主[itsnekodeng学习技术博客](https://blog.csdn.net/weixin_42529972)的文章[关于给hexo文章分类页面按钮仿书本样式美化](https://blog.csdn.net/weixin_42529972/article/details/109411974)然后修改了我的分类页面

## 2月19日

添加深夜模式，但嫌有点bug所以删了

## 2月19日~22日

修复页面白条，我太难了

我从回收站找到以前备份博客的文件替换了layout，白条就没了，然后进行了对比发现

```css
    <script>
        if (localStorage.getItem('dark') === '1') {
        document.body.classList.add('dark');
        }
        else if (new Date().getHours() >= 22 || new Date().getHours() < 7) {
        document.body.classList.add('dark');
        } 
        else if (matchMedia('(prefers-color-scheme: dark)').matches) {
        document.body.classList.add('dark');
        }
    </script>
    <a onclick="switchNightMode()" id="sma">
        <i class="fa fa-moon-o" id="nightMode" aria-hidden="true"></i>
    </a>
```

老文件没有这几行代码，这里的bug是由于深夜按钮导致的，奥利给心情多大号

## 2月23日

备份博客

[备份教程](https://blog.csdn.net/muzihuaner/article/details/113880440?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161408141116780265413464%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=161408141116780265413464&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-113880440.first_rank_v2_pc_rank_v29&utm_term=hexo%E5%A4%87%E4%BB%BD)大佬写的

css要在layout.ejs中引入

加入了标签美化，灯笼不会弄于是我不弄了

## 2月24日

添加博客增加随笔页面（并对页面仿信纸作业纸样式修饰），[教程](https://blog.csdn.net/weixin_42529972/article/details/109469448)直接抄代码，其中essay.ejs

```ejs
 <%- partial('_widget/essay-cloud') %>
```



但是博主忘了引用的essay-cloud.ejs文件内容，于是我开始从博主博客入手，开始扒代码，花了一个小时将代码全部拔下来了

打算写书单

扒了[nekodeng](https://nekodeng.gitee.io/books/)书单的代码

出现了bug

```ejs
<main class="content">
    <div class="container">
        <div class="card"> 
            <div class="card-content">
                <div class="tag-title center-align">
                    <div class="miaoshus">
                        <div class="title center-align">“ 书单 没有比阅读更有益的事了，如果有，就两本~ ”</div>
                        “ 盛夏之夜，随手举起放在桌旁的地球仪，指着伦敦说：这里有个举世闻名的格林威治天文台，世界时间就从这里开始。时间？时间在哪儿？ ”
                    </div>
```

期中第三行的

```ejs
<div class="card"> 
```

导致天气插件在添加的书本上方遮挡住书本

目前书单页面差评论区

今日闭

## 2月25日

基本完成打算对剩下的进行慢慢补充

## 2月26日

发现bug页脚消失，一分钟后找到bug透明度问题
