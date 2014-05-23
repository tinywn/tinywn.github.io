---
css: about
title: About
layout: page
---

小人物

---

<article class="aboutcon">
<h1 class="t_nav"><span>像“草根”一样，紧贴着地面，低调的存在，冬去春来，枯荣无恙。</span><a href="/" class="n1">网站首页</a><a href="/" class="n2">关于我</a></h1>
<div class="about left">
  <h2>Just about me</h2>
    <ul> 
     <p></p>
    </ul>
	<h2>Contact Me</h2>
	<p>
	{% if site.qq %}
	ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
	{% endif %}
	</P>
	<p>
	微博：[hitcode](http://weibo.com/u/{{ site.weibo }})
	</p>
	<p>
	网站：[{{ site.name }}]({{ site.url }})
	</p>
	<p>
	邮箱：[{{ site.email }}](mailto:{{ site.email }})
	</p>
	<p>
	GitHub : [github.com/{{ site.github }}](http://github.com/{{ site.github }})
	</p>
    <h2>About my blog</h2>
    <p>域  名：www.yangqq.com 创建于2011年01月12日 <a href="/" class="blog_link" target="_blank">注册域名</a></p>
    <p>服务器：阿里云服务器<a href="/" class="blog_link" target="_blank">购买空间</a></p>
    <p>备案号：蜀ICP备11002373号-1</p>
    <p>程  序：PHP 帝国CMS7.0</p>
</div>
<aside class="right">  
    <div class="about_c">
    <p>网名：<span>DanceSmile</span> | 即步非烟</p>
    <p>姓名：杨青 </p>
    <p>生日：1987-10-30</p>
    <p>籍贯：四川省—成都市</p>
    <p>现居：天津市—滨海新区</p>
    <p>职业：网站设计、网站制作</p>
    <p>喜欢的书：《红与黑》《红楼梦》</p>
    <p>喜欢的音乐：《burning》《just one last dance》《相思引》</p>
<a target="_blank" href="http://wp.qq.com/wpa/qunwpa?idkey=d4d4a26952d46d564ee5bf7782743a70d5a8c405f4f9a33a60b0eec380743c64">
<img src="http://pub.idqqimg.com/wpa/images/group.png" alt="杨青个人博客网站" title="杨青个人博客网站"></a>
<a target="_blank" href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&amp;email=HHh9cn95b3F1cHVye1xtbTJ-c3E" ><img src="http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_22.png" alt="杨青个人博客网站"></a>
</div>     
</aside>
</article>

###联系方式：

{% if site.qq %}
ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
{% endif %}

微博：[hitcode](http://weibo.com/u/{{ site.weibo }})

网站：[{{ site.name }}]({{ site.url }})

邮箱：[{{ site.email }}](mailto:{{ site.email }})

GitHub : [github.com/{{ site.github }}](http://github.com/{{ site.github }})
