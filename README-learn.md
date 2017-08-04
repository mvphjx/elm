

vue2 + vuex + vue-router + webpack + ES6/7 + fetch + sass + flex + svg


##Vuex 是什么
Vuex 是一个专为 Vue.js 应用程序开发的状态管理模式。
它采用集中式存储管理应用的所有组件的状态，并以相应的规则保证状态以一种可预测的方式发生变化。

使用一个全局单例模式管理需要同步的数据
（PS 简单应用一个简单的 global event bus 就足够）



##vue-router 
路由，单页面实现。内部跳转，实现局部刷新



##webpack 
打包工具，按照src/store/index.js 的配置，实现css js 文件合并 压缩等操作。

##ES6/7 
新的语法
import
export default


##fetch
用来替代ajax
```
  fetch('http://offline-news-api.herokuapp.com/stories')
      .then(function (response) {
        if (response.status >= 400) {
          throw new Error("Bad response from server");
        }
        return response.json();
      })
      .then(function (stories) {
        console.log(stories);
        });
 ``` 

##sass
很自然地，有人就开始为CSS加入编程元素，这被叫做"CSS预处理器"（css preprocessor）。
它的基本思想是，用一种专门的编程语言，进行网页样式设计，然后再编译成正常的CSS文件。
 ``` 
<style lang="scss"></style>
 ``` 
##flex
Flex 布局


##svg
SVG 意为可缩放矢量图形（Scalable Vector Graphics）。
SVG 使用 XML 格式定义图像。
````
<?xml version="1.0" standalone="no"?>

<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" 
"http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">

<svg width="100%" height="100%" version="1.1"
xmlns="http://www.w3.org/2000/svg">

<circle cx="100" cy="50" r="40" stroke="black"
stroke-width="2" fill="red"/>

</svg>
````

## devtools extension
vue官方提供的调试工具




