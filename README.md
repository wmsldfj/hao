一出一抽bgm在线观看一出一抽bgm120在线听

4.list属性：

   list属性用于设置输入域的datalist元素，为list属性设置datalist的id属性值，可以将datalist元素与input元素相关联：

   list属性适应于以下类型的input元素：text、search、url、telephone、email、date、 pickers、number、range和color；   

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>6.2.1</title>
</head>
<body>
<input type="url" list="url_list" name="myUrl" />
<datalist id="url_list">
  <option label="Microsoft" value="http://www.microsoft.com" />
  <option label="Google" value="http://www.google.com" />
  <option label="百度" value="http://www.baidu.com" />
</datalist>
</body>
</html>

5.multiple属性

   multiple属性用于设置input元素是否可以有多个值。该属性只适用于email和file类型的input元素。如果给email类型的input元素设置multiple属性，那么在输入框中可以输入多个email地址，多个email地址之间用逗号隔开。

如果给file类型的input元素设置multiple属性，那么在打开的选择文件对话框中就可以选择对个文件

E-mail：<input type="email" name="myEmail" multiple />
File：<input type="file" name="myFile" multiple />

6.pattern正则表达式

    正则表达式由一系列字符和数字组成，用于匹配某个句法规则。该属性适应于text、search、url、telephone、email和password类型的input元素
