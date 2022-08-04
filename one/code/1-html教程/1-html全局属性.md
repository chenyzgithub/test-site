# html 全局属性

### 常用

* `class` 
    class 全局属性是元素的区分大小写的类的空格分隔列表。类允许 CSS 和 Javascript 通过类选择器或函数（如 DOM 方法 document.getElementsByClassName）选择和访问特定元素。
* `contenteditable`
    contenteditable 全局属性是一个枚举属性，指示元素是否应该由用户编辑。值为 true/false  
* dir 
    dir 全局属性是一个枚举属性，指示元素文本的方向性  ltr/rtl/auto
* hidden
    hidden 全局属性，布尔属性。指示该元素尚未相关或不再相关。例如，它可用于隐藏在登录过程完成之前无法使用的页面元素。浏览器不会渲染具有隐藏属性集的元素。 true/false
* draggable
    draggable 全局属性，可拖动的，枚举属性，指示元素是否可以通过本机浏览器行为或HTML Drag and Drop API进行拖动。 true/false  该属性不能使用空字符串表示 true ，如果不设置该属性，则默认为 auto
* id 
    id 全局属性定义一个标识符 （ID），该标识符在整个文档中必须是唯一的。其目的是在链接（使用片段标识符）、编写脚本或样式（使用 CSS）时标识元素。
    与允许空格分隔值的 class 属性相比，元素只能有一个 ID 值。
    只能使用 ASCII 字母、数字、“_”和“-”，并且 id 属性的值应以字母开头。
* lang 
    lang 全局属性有助于定义元素的语言：编写不可编辑元素的语言，或用户应使用可编辑元素的语言。该属性包含一个“语言标记”
* style
* title
* translate 全局属性，也是枚举属性，用于当页面本地化时，是否翻译。