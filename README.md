# 谷歌翻译生草机介绍：

:monkey_face::monkey_face::monkey_face:  
***
## 原作者：  
`Bilibili` __@MC着火的冰块__，原视频：[空降至Bilibili](https://space.bilibili.com/551409211 "点击空降")
__（已授权搬运）__
***
## 简介：  
> 最近谷歌翻译在网上火了，因为谷歌翻译是机器翻译，所以如果只是翻译一次，大体还是有九成九的准确度的，但是当使用谷歌翻译选择小语种，然后小语种再翻译到另一个小语种，重复翻译多遍后，内容就会疯狂失真，然后准确度也会随着翻译次数开始偏离原来的真正的意思。  
  
__可如果手动翻译效率极低，于是就有了这款自动翻译机__  
本项目是由`Bilibili` ***@MC着火的冰块***用`Python`制做的谷歌自动翻译机，可以自动翻译内容**几十甚至几百遍**~~*（就是翻译太多变会卡）*~~  
***
## 更新日志：
### 2.0：
- 全新的GUI界面，告别控制台，操作更简单
- 优化算法，由逐条翻译换成整体翻译，大幅提高速度
- 从输入文件路径换成直接输入内容，操作更方便
  
### 2.1：
- 更新一键复制，方便快捷，再也不用选中在复制了！

### 2.2:  
- 更新一键粘贴，输入也变得方便起来
- 更新进度条，再也不用干等了，立马知道进度！
- 翻译使用多线程，窗口再也不会未响应了！
***
## 使用说明：
引用库：`tkinter` `googletrans` `threading` `pyperclip`  
  
### 1.0：  
1. 创建**2**个**文本文档**
2. 在**第一个文本文档**里输入**要翻译的内容**
3. **第二个文本文档留空**
4. **运行程序**
5. 输入**第一个文本文档**的**路径**，*可以是绝对也可以是相对*
6. ***按下Enter***
7. 输入**第二个文本文档**的**路径**，同上，可以是绝对也可以是相对
8. ***按下Enter***
9. 输入**翻译次数**
10. 程序会**加载一会儿**，随后将**翻译结果**放入**第二个文本文档中**
11. **按下Enter**退出
12. 打开**第二个文本文档**就可以看到**翻译结果**了
  
### 2.0：  
1. 运行后会出现窗口，在**上方输入框**中输入**要生草的内容**  
2. 在**中间的输入框**中输入**要翻译的次数**（翻译次数建议**不要超出40**，会卡）  
3. ~~**随后窗口会未响应一会，纯属正常现象！！**~~***（已修复）***  
4. 稍等一会儿在**下方输入框**中会出现**翻译结果**  

*__使用2.0时请勿关闭后方控制台__*
***
## 翻译结果：  
|输入|翻译次数|输出|
|:---|:---:|:---|
|小猪佩奇|30|猪肉页|
|你tm故意找茬是吧|25|您故意发现失败，对吗？|
|我宣布个事，我是个烧饼|15|我宣布的是芝麻蛋糕|
|我是神里绫华的狗|15|我在n中去fs和n，|
|举头望明月，低头思故乡|40|看着混蛋，低下头，想着你的家乡|
