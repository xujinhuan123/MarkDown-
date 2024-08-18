# MarkDown-
本人初期学习markdown的笔记


start time:2024.8.01
# <center><font face="仿宋" color=red>markdown学习笔记</font></center>
## <center><font face="楷体" color=red>须尽欢 </font></center>
***
## **需要的插件**
markdown all in one 
markdown preview enhanced
Paste Image
***
1. **标题** 
   #一级标题
   ##二级标题
   ...
   一共有六级标题
***
2. **引用**
   >这是内容
   >>可以嵌套
***
3. **列表**
   1. 无序列表
   + 列表1
   - 列表2
   * 列表3
   2. 有序列表
   3. 嵌套
   4. todolist
     - [ ] 待办
     - [x] 已完成
     **注意语法是- [ ] 每一个符号中间都有一个空格**
***
4. **表格**
   | 表头1（左对齐） | 表头2（居中对齐） | 表头3（右对齐） |
   | :- | :-: | -: |
   | a | b | c |

    **同样是每个符号中间都有一个空格 控制对齐的时候这样记忆：一共有n(随意几个、至少两个)符号位置，：在左边就是左对齐，左右都有：就是居中对齐**
***
5. **段落**
    + 理论上来说换行需要在需要换行的地方加两个空格/中间空一行，但是实际操作中，只需要在需要换行的地方直接回车即可
    + 分割线 大于等于三个* 分割线的位置也有讲究，位置不对会导致其它代码运行不对，最好对齐分割，发现代码运行不对可以自己尝试调整位置
    **或者说上下级关系比较严格，不止是这个符号，下一级内容代码位置就是要放在上一级内容代码之后**
    ***
    + 字体
      | 字体 | 代码 |
      | :-: | :-: |
      | *斜体* | * * |
      | ==高亮== | == == |
      | **粗体** | ** ** |
      | ***粗斜体*** | *** *** |
      | ~~删除线~~ | ~~ ~~ |
      |<u>下划线</u>|`<u> </u>`|
    + 脚注  
       请大家多多[^1]指教
***
6. **代码**
   `one line code`
   ```
   一段代码
   这是一段代码
   hello world
   ```
***
7. **链接**
   + [百度](https://www.baidu.com)
   + [百度](https://www.baidu.com "百度一下")
   + [百度]：baidu.com
   + 点击查看[百度的链接](https://www.baidu.com)
***
8. **图片**
  - 使用图床保存图片
   [路过图床]：imgse.com
   **测试用例 md图片数据从图床中取得**
   [![pkXU1qU.png](https://s21.ax1x.com/2024/08/01/pkXU1qU.png)](https://imgse.com/i/pkXU1qU)
   - 使用vscode插件paste img 拖入图片/f复制图片形成**如果要给别人发送md源文件查看使用这个方法别人看不到本地的图片，要使用上面的方法上传到图床中，本地文件缺失就是以下效果 所以想要发送别人md笔记的时候最好打包发送，把paste img 贴进来的图片一起发送过去，保持相对路径不变（不确定自己试试）**
    ![alt text](<屏幕截图 2024-07-08 154456.png>)
    ![alt text](image.png)
***
9. **其它**
    - 公式
      采用latex语法直接加入
    - 使用html更改图片大小
    比如
    更改前：
    <a href="https://imgse.com/i/pkXU1qU"><img src="https://s21.ax1x.com/2024/08/01/pkXU1qU.png" alt="pkXU1qU.png" border="0" /></a>
    更改后：(==主要更改了宽和高(width and height)的数值大小，设置了居中==)
    <center><a href="https://imgse.com/i/pkXU1qU"><img src="https://s21.ax1x.com/2024/08/01/pkXU1qU.png" alt="pkXU1qU.png" border="0" width=80% height=60% /></a></center>
***
- 另存为PDF文档
 open in browser 在浏览器里存为PDF 浏览器里没保存的 按ctrl+P 打印功能自带保存

[^1]:下面写了上面才会正常显示脚注
## <font color=red>**<font color=red>注意</font>**：似乎以上方式保存会丢失高亮信息</font>
