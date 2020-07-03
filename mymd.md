# 我爱你
## 就是爱着你
**`markdown`**  
~~dab~~     
*斜体*    
***粗斜体***   
![](C:\Users\apple\Pictures\IMG_0027(20200506-154912).JPG "照片")  
[**百度链接**](https://www.baidu.com/)    

[*打开照片所在位置*](C:\Users\apple\Pictures\IMG_0027(20200506-154912).JPG)

### 分隔线
---
### 引用 
>离别了若想心安 先别要每夜重翻旧案    
望着更好的地方 为下段爱恋吸收阳光       

* 李
* 松
* 州
### 表格
| 左对齐 | 居中  | 右对齐 |
| :--- |:-----------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

### 代码段
```python
def init(input = ""):
	print("hello world")
```

### diff
```diff
+爱你   
-不爱你
```
:blush:
上标：X<sub>2</sub>，下标：O<sup>2</sup>
#### GFM task list

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2
---
#### 特殊符号 HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

[========]
#### 反斜杠 Escape

\*literal asterisks\*
### 科学公式 TeX(KaTeX)

$$E=mc^2$$

行内的公式$$E=mc^2$$行内的公式，行内的$$E=mc^2$$公式。

$$x > y$$

$$\(\sqrt{3x-1}+(1+x)^2\)$$

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

### 分页符 Page break

> Print Test: Ctrl + P


### 绘制流程图 Flowchart

```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```
[========]

### 绘制序列图 Sequence Diagram

```seq
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```
### End