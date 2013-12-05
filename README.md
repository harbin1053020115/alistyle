# alistyle

---

阿里巴巴内部系统样式库

---

## 使用说明


````html
<!--基于aliceui-->
<link media="all" href="https://a.alipayobjects.com/??alice/base/1.0.1/base.css,alice/button/1.1.1/button.css,alice/grid/1.0.0/grid.css" rel="stylesheet">
<link type="text/css" rel="stylesheet" media="screen" href="src/alistyle.css">
<div class="ali-modal">
	<div class="ali-modal-header">
		<button class="ali-modal-close" title="关闭本框">×</button>
		<h3>您确定要删除此记录吗？</h3>
	</div>
	<div class="ali-modal-content">
		<div class="ali-modal-message">
			<p>删除后，您可在回收站还原，或永久删除。</p>
		</div>
		<div class="ali-modal-operation">
			<div class="ali-modal-btn">
				<a class="ui-button ui-button-swhite">取消</a>
			</div>
			<div class="ali-modal-btn">
				<a class="ui-button ui-button-sorange">确定</a>
			</div>
		</div>
	</div>
</div>
````