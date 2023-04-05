## 1 javascript是什么
   + 1. javascript是一种运行在客户端（浏览器）的变成语言，实现人机交互的效果
   + 2. javascript的组成有什么
     + ECMAScript:
        规定了js的基础语法核心知识
        + 比如：变量，分支语句，循环语句，对象等等
     + Web APIs:
        + DOM: 操作文档，比如对页面元素进行移动，大小，添加删除等操作
        + BOM：操作浏览器，比如页面弹窗，检测窗口宽度，存储数据到浏览器等等

#### javascript的作用
    + 1. 网页特效（监听用户的一些行为，让网页做出对应的反馈）
    + 2. 表单验证（针对表单数据的合法性判断）
    + 3. 数据交互（获取后台数据，渲染到前端）
    + 4. 服务端变成（node.js）

##### javascript 权威网站： https://developer.mozilla.org/zh-CN/
#### 一个简单的点击那个按钮 哪个按钮变色的小实例
![鼠标点击按钮变色](../images/%E9%BC%A0%E6%A0%87%E7%82%B9%E5%87%BB%E6%8C%89%E9%92%AE%E5%8F%98%E8%89%B2.png)

### 2  JavaScript 书写位置
    1. 内部JS： 与CSS一样，区别在于：script标签一定要写在 **< /body >** 的上方,html文档的后面
![弹出警示框](../images/alert%E5%BC%B9%E5%87%BA%E8%AD%A6%E7%A4%BA%E6%A1%86.png)   
![注意事项](../images/%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.png)

    2.外部JS： 使用script标签引入,标签内部不可以写内容
![引入外部JS文件](../images/%E5%A4%96%E9%83%A8JS%E6%96%87%E4%BB%B6.png)

    3. 标签内部js： <button onclick="alert('逗你玩。。。。')"></button>
![内部js](../images/%E5%86%85%E9%83%A8js.png)

### 3  javascript 输入输出语法
    目标：能够写出常见javascript输入输出语法
##### 什么是语法：计算机规定的语法规则
 + 输出语法：
    + 语法1 ： ![](../images/%E8%BE%93%E5%87%BA%E8%AF%AD%E6%B3%95.png)
    + 作用：向body内输出内容
    + 注意：如果输出内容写的是标签，也会被解析为网页元素
    + 语法2 ： ![](../images/%E9%A1%B5%E9%9D%A2%E5%BC%B9%E5%87%BA%E8%AD%A6%E5%91%8A%E5%AF%B9%E8%AF%9D%E6%A1%86.png)
    + 作用：页面弹出警告对话框
    + 语法3 ： ![](../images/%E6%8E%A7%E5%88%B6%E5%8F%B0%E6%89%93%E5%8D%B0%E8%BE%93%E5%87%BA.png)
    + 作用：控制台输出语法，程序员调试使用

+ 输入语法:
    + 语法 : ![](../images/%E8%BE%93%E5%85%A5%E8%AF%AD%E6%B3%95prompt.png)

+ javascript代码执行顺序：
    + 按照html文档流顺序执行代码
    + alter()和prompt() 他们会跳过页面渲染先被执行


