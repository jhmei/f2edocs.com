#max-width

##语法

- max-width：&lt;length&gt; | &lt;percentage&gt; | none
- 默认值：none
- 适用于：除非置换内联元素，table-row, table-row-group之外的所有元素
- 继承性：无
- 动画性：当值为&lt;length&gt; | &lt;percentage&gt;时
- 计算值：指定的值


##取值

- none：无最大宽度限制
- &lt;length&gt;：用长度值来定义最大宽度。不允许负值
- &lt;percentage&gt;：用百分比来定义最大宽度。不允许负值


##说明

设置或检索对象的最大宽度。

- 如果max-width属性的值小于min-width属性的值，max-width将会自动以min-width的值作为自己的值。
- IE6尚不支持此属性
- 对应的脚本特性为maxWidth。


##兼容性


<table class="compatible">
<thead>
	<tr>
		<th>Values</th>
		<th>IE</th>
		<th>Firefox</th>
		<th>Chrome</th>
		<th>Safari</th>
		<th>Opera</th>
		<th>iOS Safari</th>
		<th>Android Browser</th>
		<th>Android Chrome</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td rowspan="2"><strong>Basic Support</strong></td>
		<td class="unsupport">6.0</td>
		<td class="support" rowspan="2">2.0+</td>
		<td class="support" rowspan="2">4.0+</td>
		<td class="support" rowspan="2">3.1+</td>
		<td class="support" rowspan="2">4.0+</td>
		<td class="support" rowspan="2">3.2+</td>
		<td class="support" rowspan="2">2.1+</td>
		<td class="support" rowspan="2">18.0+</td>
	</tr>
	<tr>
		<td class="support">7.0+</td>
	</tr>
</tbody>
</table>




##示例

```html

<!DOCTYPE html>
<html lang="zh-cmn-Hans">
<head>
<style>
.test {
	max-width: 200px;
	background: #eee;
}
</style>
</head>
<body>
<div class="test">我的最大宽度为200</div>
</body>
</html>

```
