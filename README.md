<h1 align="center" paddin> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>

<p align="center">Лабораторная работа №6 "CSS" </p>

<p align="right">Выполнил: Рогаль Сергей Александрович</p>
<p align="right">Проверил: Соболев Е. И.</p>

<p align="center">г. Южно-Сахалинск <br> 2023 год</p>

<h2 align="center">Введение</h2>
<p align="justify">CSS (Cascading Style Sheets) — формальный язык описания внешнего вида документа, написанного с использованием языка разметки. CSS используется для определения стилей (правил) оформления документов — включая дизайн, вёрстку и вариации макета для различных устройств и размеров экрана. 
</p>

<h2 align="center">Цели и задачи</h2>
<palign="justify">Цели: выполнить задания, создать заголовки, абзацы, страницы по образцу, стилизовать страницы</p>
<palign="justify">Задачи: применить технологии HTML и CSS.</p>

<h2>Решение задач</h2>
<pre>
  <style>
  html {
  font-size: 150%;
}
/* №1 */
div p{
	color:red;
}
/* №2 */
div h2
{
	color:green;
}
/* №3 */
#test p{
	color:orange;
}
/* №4 */
#test h2{
	color:blue;
}
/* №5 */
.bbb{
	color:violet;
}
/* №6 */
#test .bbb {
	color:red;
}
/* №7 */
.bbb p{
	text-align:center;
}
/* №8 */
.bbb h2{
	text-align:center;
}
/* №9 */
#test .bbb p {
	color:red;
}
/* №10 */
.bbb, .xxx {
	color:red;
}

/* №11 */
#test .bbb p, #test .xxx h2 {
	color:red;
}
/* №12 */
#test .bbb p, #test .xxx p {
	color:red;
}
/* №13 */
.fff {
	color:red;
}
/* №14 */
.fff>p {
	color:red;
}
/* №15 */
.fff p {
	color:red;
}
/* №16 */
.fff>.bbb {
	color:red;
}
/* №17 */
.fff>.bbb h2 {
	color:red;
}
/* №18 */
#test a:link, #test a:visited {
	color:red;
	text-decoration: none;
}
#test a:hover {
	color:blue;
	text-decoration:underline;
}
/* №19 */
a.www:link, a.www:visited {
	color:blue;
	text-decoration:underline;
}
a.www:hover {
	text-decoration: none;
}
/* №20 */
#test a.www:link {
	color:pink;
	text-decoration: none;
}
#test a.www:hover {
	color:blue;
	text-decoration:underline;
}
#test a.www:visited {
	color:red;
	text-decoration:line-through;
}
/* №21 */
.eee a.www:link {
	color:pink;
	text-decoration: none;
}
.eee a.www:hover {
	color:blue;
	text-decoration:underline;
}
.eee a.www:visited {
	color:red;
	text-decoration:line-through;
}
</style>
</pre>
<p>№22</p>
<pre>
<style>
#one{
	text-decoration: underline;
}
#two{
	text-decoration: line-through;
}
#three{
	text-decoration: overline;
}
</style>
</pre>
<p>№23</p>
<pre>
<style>
div{
	height:300px;
	width:300px;
	border: solid red 2px;
}
</style>
</pre>
<p>№24</p>
<pre>
<style>
div{
	height:300px;
	width:700px;
	border: solid blue 2px;
}
</style>
</pre>
<p>№25</p>
<pre>
<style>
div{
	height:400px;
	width:400px;
	border: solid blue 2px;
	border-radius: 5px 20px 5px 20px; 
}
</style>
</pre>
<p>№26</p>
<pre>
<style>
div{
	height:400px;
	width:400px;
	border: solid red 2px;
	border-radius: 50%;
}
</style>
</pre>
<p>№27</p>
<pre>
<style>

#one {
	color:green;
}
#two {
	color:red;
}
#three {
	color:black;
	text-decoration:none;
}
</style>
</pre>
