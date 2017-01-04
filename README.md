### x-base64
js代码进行base64的编码与解码

# npm
- 安装

    `npm install x-base64 --save`
- 使用

    ```JavaScript
    var base = require('x-base64');
    var str = 'base64';
    var encode = base.encode(str); 
    console.log(encode);
    var decode = base.decode(encode);  
    console.log(decode);
    ```

# html页面
- 安装

    下载`x-base64.js`文件并用<script>标签在页面中引入
- 使用

    ```JavaScript
    var str = 'base64';
    var encode = Base64.encode(str); 
    console.log(encode);
    var decode = Base64.decode(encode);  
    console.log(decode);
    ```

    