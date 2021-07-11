## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/LaNx3R/try121420/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

<head>
<meta charset="UTF-8">
<title>Insert title here</title>
<script type="text/javascript">
var result_1;
//加法
function add() {
var a = getFirstNumber();
var b = getTwiceNumber();
var re = Number(a) + Number(b);
sendResult(re);
}
//減法
function subtract() {
var a = getFirstNumber();
var b = getTwiceNumber();
var re = a - b;
sendResult(re);
}
//乘法
function ride() {
var a = getFirstNumber();
var b = getTwiceNumber();
var re = a * b;
sendResult(re);
}
//除法
function devide() {
var a = getFirstNumber();
var b = getTwiceNumber();
var re = a / b;
sendResult(re);
}
//給p標簽傳值
function sendResult(result_1) {
var num = document.getElementById("result")
num.innerHTML = result_1;
}
//獲取第一位數字
function getFirstNumber() {
var firstNumber = document.getElementById("first").value;
return firstNumber;
}
//獲取第二位數字
function getTwiceNumber() {
var twiceNumber = document.getElementById("twice").value;
return twiceNumber;
}
</script>
</head>
<body>
<p>簡單計算器:</p>
<table border="1" style="position: center;">
<tr>
<td>第一個數：</td>
<td><input type="text" id="first" /></td>
</tr>
<tr>
<td>第二個數：</td>
<td><input type="text" id="twice" /></td>
</tr>
<tr>
<td colspan="2">&nbsp;
<button style="width: inherit" onclick="add()">+</button> &nbsp;
<button style="width: inherit" onclick="subtract()">-</button>
&nbsp;
<button style="width: inherit" onclick="ride()">*</button> &nbsp;
<button style="width: inherit" onclick="devide()">/</button>
</td>
</tr>
<tr>
<td colspan="2" rowspan="2">
<p id="result"></p>
</td>
</tr>
</table>

</body>

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LaNx3R/try121420/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

