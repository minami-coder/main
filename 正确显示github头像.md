## github头像无法显示

可能是ip变动或其他原因，github的头像可能无法正常显示。

### 方法
更改位于C:\Windows\System32\drivers\etc目录下的host文件，添加以下IP语句：
    
    199.232.68.133 .githubusercontent.com
    
### 可维护性
该ip地址可能发生变动，请通过相应工具查询对应ip。

首先，在无法显示的元素上右键以新页面打开，复制该网址，然后通过域名反查ip获得其最新ip地址，更改host中的ip地址即可。

该网站可以用来反查IP：
https://www.ipaddress.com/
