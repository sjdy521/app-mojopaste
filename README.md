### 输入文本内容然后点击左下角的[粘帖]按钮, 将地址栏出现的新地址分享给小伙伴.

### 你也可以在命令行环境下使用:

#### 上传文本   

`cat something.txt|curl https://paste.perfi.wang -F txt=@-`

#### 上传图片，自动识别扩展名

`cat something.jpg|curl https://paste.perfi.wang -F img=@-`

#### 上传图片，手动指定扩展名

`cat something.png|curl https://paste.perfi.wang -F img=@- -F suffix=.png`
