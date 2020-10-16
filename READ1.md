# 《HTML常用的标签》
## 1.a标签的用法
### 作用：引入超链接
### 包含属性：
* href 的取值有很多，可以是一个网址，绝对路径，相对路径，伪协议等
* target 用于决定该链接在那个网页打开，默认值是_black表示在一个新的页面打开
* download 下载当前网页(通常不用)
* rel=noopener 是为了解决某个bug 
### 例：` <a href="//xiedaimala.com/" target="_black"></a> `
  
## 2.img标签的用法
### 作用：发出get请求，引入图片
### 包含属性：
* alt 当图片异常显示不了时，显示注释文字
* scr 图片路径（相对绝对都可以）
* width,height 设置图片宽度和高度（切记不能同时设置，会导致图片变形）
### 例：` <img src="1.jpg" alt="科比布莱恩特" width="400"> `

## 3.table标签的用法
### 作用：设置表格样式
### 内包含三个标签
* thead 代表表头，通常里面有含有tr（行）和td标签
* tbody 代表表中，通常里面有tr，td标签
* tfoot 代表表尾，通常里面含有tr，td标签
### 例：
```html
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td></td>
            <td></td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td></td>
            <td></td>
        </tr>
    </tfoot>
```
## 4.其他感想
### 总体来说html韩都不是很大，主要是记得偏多，需要长时间的练习记忆，做到孰能生巧，不死记硬背。

