# HTMLに関する知識
## web

- Structure -> html
  - vs code !
- Presentation -> css
- Behavior -> js

## tag

- 分类：双标签，单标签
- 关系：包含与被包含，并列
- basics：

```html
<html>
  <head>
    <title>title</title>
  </head>
  <body>
    body
  </body>
</html>
```

### title

```html
<h1>h1</h1>
<h2>h2</h2>
<h3>h3</h3>
<h4>h4</h4>
<h5>h5</h5>
<h6>h6</h6>
```

 <h1>h1</h1>
 <h2>h2</h2>
 <h3>h3</h3>
 <h4>h4</h4>
 <h5>h5</h5>
 <h6>h6</h6>

### p & br

```html
<p>paragragh</br>new line</p>
<p>new paragragh</p>
```

<p>paragragh</br>new line</p>
<p>new paragragh</p>

### format: strong em

```html
<strong>strong</strong>
<b>strong</b>
<em>em</em>
<i>em</i>
<del>del</del>
<s>del</s>
<ins>ins</ins>
<u>ins</u>
```

<strong>strong</strong>
<b>strong</b>
<em>em</em>
<i>em</i>
<del>del</del>
<s>del</s>
<ins>ins</ins>
<u>ins</u>

### layout: div span

```html
<div>div takes one line</div>
123
<div>div takes one line</div>
123
<span>span</span>
<span>span</span>
<span>span</span>
```

<div>div takes one line</div>123
<div>div takes one line</div>123
<span>span</span>
<span>span</span>
<span>span</span>

### image

```html
<image
  src="./pic.jpeg"
  alt="kika drew this"
  title="did kika really draw this?"
  width="500"
  height="400"
  border="30"
/>
```

<image
  src="./pic.jpeg"
  alt="kika drew this"
  title="did kika really draw this?"
  width="500"
  height="400"
	border="30"
/>

### a

```html
<a href="http://www.qq.com" target="blank">tencent</a> <a href="pic.jpeg.zip">zip exe download</a>
```

<a href="http://www.qq.com" target="blank">tencent</a></br>
<a href="pic.jpeg.zip" >zip,exe download</a>

### comment

```html
<!-- this is a comment -->
&nbsp; &lt; &copy; &amp; &reg; &deg; &plusmn; &times; &divide; &sup2; &sup3; &yen;
```

<!-- this is a comment -->

&nbsp;
&lt;
&gt;
&copy;
&amp;
&reg;
&deg;
&plusmn;
&times;
&divide;
&sup2;
&sup3;
&yen;

## form

```html
<table align="center" boder="1" cellpadding="20" cellmargin="0" width="200" height="100">
  <thead>
    <tr>
      <th>Name</th>
      <th colspan="2">Age&gender</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Lee</td>
      <td>27</td>
      <td>Female</td>
    </tr>
    <tr>
      <td>20</td>
      <td>Male</td>
    </tr>
  </tbody>
</table>
```

<table align="center" boder="1" cellpadding="20" cellmargin="0" width="200" height="100">
	<thead>
		<tr><th>Name</th><th colspan=2>Age&gender</th></tr>
	</thead>
	<tbody>
		<tr><td rowspan=2>Lee</td><td>27</td><td>Female</td></tr>
		<tr><td>20</td><td>Male</td></tr>
	</tbody>
</table>

### list

```html
<ul>
  <li>list 1</li>
  <li>list 2</li>
  <li>list 3</li>
</ul>
```

<ul>
	<li>list 1</li>
	<li>list 2</li>
	<li>list 3</li>
</ul>

```html
<ol>
  <li>list 1</li>
  <li>list 2</li>
  <li>list 3</li>
</ol>
```

<ol>
	<li>list 1</li>
	<li>list 2</li>
	<li>list 3</li>
</ol>

```html
<dl>
  <dt>list 1</dt>
  <dd>list 2</dd>
  <dd>list 3</dd>
  <dt>list 1</dt>
  <dd>list 2</dd>
  <dd>list 3</dd>
</dl>
```

<dl>
	<dt>list 1</dt>
	<dd>list 2</dd>
	<dd>list 3</dd>
	<dt>list 1</dt>
	<dd>list 2</dd>
	<dd>list 3</dd>
</dl>

### form

```html
<form action="url" method="POST" name="name1">
  <label for="username">username</label>
  <input type="text" name="username" maxlength="4" id="username" />
  <label for="password">password</label>
  <input type="password" name="password" id="password" />
  <input type="radio" name="gender" checked />
  <input type="radio" name="gender" />
  <input type="checkbox" name="hobby" checked />
  <input type="checkbox" name="hobby" checked />
  <input type="checkbox" name="hobby" />
  <label for="username">select one</label>
  <select>
    <option>A</option>
    <option>B</option>
    <option selected>C</option>
  </select>
  <input type="button" value="send code" />
  <input type="file" />
  <input type="hidden" />
  <input type="image" />
  <textarea rows="3" cols="150"></textarea>
  <input type="submit" value="OK" />
  <input type="reset" value="RESET" />
</form>
```

<form action="url" method="POST" name="name1">
	<label for="username">username</label>
	<input type="text" name="username" maxlength=4 id="username" />
	<label for="password">password</label>
	<input type="password" name="password" id="password"/>
	<input type="radio" name="gender" checked />
	<input type="radio" name="gender" />
	<input type="checkbox" name="hobby" checked />
	<input type="checkbox" name="hobby"checked />
	<input type="checkbox" name="hobby" />
	<label for="username">select one</label>
	<select> 
		<option>A</option>
		<option>B</option>
		<option selected>C</option>
	</select>
	<input type="button" value="send code" />
	<input type="file" />
	<input type="hidden" />
	<input type="image" />
	<textarea rows=3 cols=150 ></textarea>
	<input type="submit" value="OK" />
	<input type="reset" value="RESET" />
</form>
