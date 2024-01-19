# 论文排版格式
> 前提：**严格** 按照投稿期刊、会议或学位论文的 **模板**

**排版 = 逻辑**

**宗旨：美观、层次清晰**

**强烈建议使用Latex**

## Latex
- 整体代码结构要**清晰明了**
- 每个 章节、段落、图表、公式 都要有简短的`\label`
  - 如 `\label{sec:intro}`, `\label{ssec:cnn}`, 
  - `\label{fig:pipeline}`, `\label{tab:comp}`, `\label{eq:comp}`
- 每个章节，可以考虑使用单独的`tex`文档。
- 每个`\section`标题`前后`，增加几行间隔，方便看出整体结构。
- 正文中，段落之间空一行，不要使用`\\`
- 独行的公式，使用`equation`环境，不要使用`$$x$$`，且使用编号
- 建议参考[《一份不太简短的 LATEX2ε 介绍》](lshort-zh-cn.pdf)
  - 源文件：[lshort-zh-cn@github](https://github.com/CTeX-org/lshort-zh-cn)


## 英文
- 标题不需要 "Research on"
  - 标题单词首字母大写，参考一般英文论文标题。
- 简洁，不要长句子，不要各种从句。 **主谓宾** 就可以。
- 注意 **单复数、时态、标点后的空格**
- 参考已发表的论文，特别是主题一样的论文，不要自己“造”
- 只用简单的词，不要乱“拽”。 任何词都可以在有道等字典里，看看`英英释义`，了解原本的用法和含义。
  - 中文释义参考意义不大，因为中文容易混淆。
- 建议参考[《风格的要素》](EoS_4thEd.pdf)

### 画图
- **视觉元素 反映 逻辑关系**
  - 颜色不超过3种，最多再加一个黑色
  - 颜色不要太艳/刺眼，ppt里默认推荐的颜色就很好
  - 同一个模块，采用同一个色系，深浅区分
  - **配不配？** 一个模块的面积大小，要匹配其重要性。
    - 箭头不宜太长
  - 圆角矩形的圆角不宜过大
- 学位论文：图尽量不要有大面积的背景填充色，打印出来会很难看
- **在PPT中画图**，然后存为图片（如果是Word模板）或pdf（如果是latex）
- 图中如果有文字，确保**图中的文字与正文文字大小相近**
- 不要从网上截图，涉及抄袭，而且打印不清晰
- 中文论文：如果图中文字是英文，自己改为中文

## 表格
- 建议使用 `\toprule`, `\midrule`, `\bottomrule` 作为横线，不要使用 `\hline`
- 建议采用**三线表**，不用太多竖线或横线，不然太乱了
- 表格中的量化指标等，**整数和小数位一般不超过4位**
  - 比如：`0.1234`, `1.234`, `12.34`



## 章节安排
- 学位论文：每一章的首页另起一页
- 章节标题：简洁、不要太长;
- 段落：
  - **不要过长(超过1/3页面，不要过短(少于5行)**
  - **除章节结尾处外，不要有大段空白；**
  - **若章节结尾如果只有少量几行，尽量缩进到前一页；**
  - **每一段的最后一行：不要少于5个字**

## 其他
- 英文缩写：**首次出现** 形式为：`中文全拼(英文全拼, 英文缩写)`,
  - 例如:`人脸识别(Face Recognition, FR)`
  - 这里的逗号、括号是`半角`。
- 中文文档，正文中的标点符号为`全角` (中文逗号、括号、句号、冒号等)

----------
以下主要针对Word。
----------

## 排版
- 标题：编号样式
- 字体大小：各级标题、正文要有区分
- 字体样式：
  - 中文文档中，英文字体一般要求是 `Times New Roman` 字体。
  - 可以`全选`，然后`选择字体`。
- 行间距：
  - 一般为固定值20磅；
  - 有公式、图、表的地方，根据情况调节，一般为1.25倍间距;
- 段落缩进形式：一般为首行缩进 2 字符；

## 参考文献
- Word：以编号形式，如 [1]
- 如果模版没有要求，则字体为五号
- Word：在正文中进行交叉引用，引用内容为编号
- 中文论文中，参考文献为`上标`形式
- 参考文献的序号，一般与文中引用顺序一致，除非没有要求

## 公式
- Word：采用mathtype输入或用自带的公式编辑器；WPS可以采用自带公式编辑器输入
- 公式字体大小与论文相同
- 在Word中，图像在正文中为`嵌入`格式，不要是`浮动`。**不要在word中画图!**
