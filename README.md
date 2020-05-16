# 南京大学大学生创新训练项目---基于知识图谱的经典文本理解
本仓库中存放了创新项目的框架代码打包后的文本阅读器及相关示例文件，使用说明如下：

1. 文本阅读器的可执行程序位于目录`KGNLP`下，文件名为`main.exe`
2. 文本阅读器运行方法：
   1. 完整下载目录`KGNLP`，请不要改动任何该目录下的文件、目录
   2. 点击目录`KGNLP`下的文件`main.exe`即可运行，请确保在联网环境下运行
   3. 成功运行将弹出一个图形化窗口，分为左右两部分视图区域。左侧为可输入文本框，右侧为文本解析结果。
   4. 可以直接在文本框中输入待解析文本，也可以通过工具栏的“文件-打开”选项打开待解析文本，注：打开文本大小不宜过大，最好在1-2M左右。过大文本导致的bug有待修复。
   5. 文本输入停止后，阅读器将自动开始文本分析，完成相关实体知识的查询并将知识呈现在视图右侧区域。该过程有可能会占用较长时间(正常情况下不会超过5min)，请耐心等待，若长时间无反应可尝试重新运行程序。知识展示结果设定最多为30个实体，所以当文本内容较长，实体较多时会采用特定方式选择top30的实体。
   6. 该阅读器是初期代码框架，可能会存在一些bug，请谅解。我们后期会继续完善。
3. 本仓库中的TXT文件为可供解析使用的示例文本，有：`《三国演义》第一话部分.txt`；`《西游记》第一话.txt`；`《作为意志与表象的世界》第一章.txt`
4. 文件`文本理解实例.pdf`展示了示例文本在阅读器下的解析结果，并作出了相关说明

