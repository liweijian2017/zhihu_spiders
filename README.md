
项目功能：<br>
  知乎搜索答案的快速爬取，把与输入关键字相关的答案与问题快速爬取到本地并保存，具体效果只要你运行代码之后，打开目录下的data.txt和data2.txt就很清楚了。或者可以参考我的<a href="http://www.cnblogs.com/yonglin/p/7944512.html">博文</a><br><br>
  
使用步骤：<br>
 1.代码下载到本地<br>
 2.打开浏览器，进入知乎，登陆自己的账号,随便搜索一个关键字，然后在返回的结果中随便选择一个问题，进去之后打开浏览器的开发者工具，找到形如 new?r=一串数字 的那个get请求，把请求头中的authorization的值配置到项目中的answer.js的第18行的authorization属性上<br>
 3.命令行进入到项目目录<br>
 4.执行命令 npm install<br>
 5.执行命令 node app<br><br>

文件目录：<br>
  app.js 主程序入口<br>
  allAnswer.js 获得单个问题所有答案<br>
  articleSingle.js 知乎专栏的处理<br>
  questionSingle.js 构造当个页面所有答案的url<br>
  saveArticle.js 保存专栏文章功能<br>
  saveQuestion.js 保存问题和答案功能<br>
  data.txt  保存问题和答案<br>
  data2.txt 保存专栏文章<br>
