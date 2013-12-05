# alistyle

---

阿里巴巴内部系统样式库

---

## 使用说明


````html
<link type="text/css" rel="stylesheet" media="screen" href="src/bootstrap3.min.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/alistyle.css">
<div class="row clearfix">
	<div class="col-sm-4">
		<h4>Headings &amp; Paragraphs</h4>
		<hr>
		<h1>h1. Heading 1</h1>
		<p class="lead">
			Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus.
		</p>
		<h2>h2. Heading 2</h2>
		<p>
			Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.
		</p>
		<h3>h3. Heading 3</h3>
		<p>
			Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.
		</p>
		<h4>h4. Heading 4</h4>
		<h5>h5. Heading 5</h5>
		<h6>h6. Heading 6</h6>
	</div>
	<div class="col-sm-8">
		<div class="widget-box">
			<div class="widget-header widget-header-flat">
				<h4>Lists</h4>
			</div>
			<div class="widget-body">
				<div class="widget-main">
					<div class="row">
						<div class="col-sm-6">
							<ul>
								<li>Unordered List Item</li>
								<li>
									<small>List Item in small tag</small>
								</li>
								<li>
									<b>List Item in bold tag</b>
								</li>
								<li>
									<i>List Item in italics tag</i>
								</li>
								<li>
									<ul class="list-unstyled">
										<li>
											<i class="icon-caret-right blue"></i>
											Nested List Item
										</li>
										<li>
											<i class="icon-caret-right blue"></i>
											Nested List Item
										</li>
										<li>
											<i class="icon-caret-right blue"></i>
											Nested List Item
										</li>
									</ul>
								</li>
								<li>Unordered List Item which is a longer item and may break into more lines.</li>
								<li>
									<strong>List Item in strong tag</strong>
								</li>
								<li>
									<em>List Item in emphasis tag</em>
								</li>
							</ul>
						</div>
						<div class="col-sm-6">
							<ol>
								<li>Ordered List Item</li>
								<li class="text-primary">.text-primary Ordered List Item</li>
								<li class="text-danger">.text-danger Ordered List Item</li>
								<li class="text-success">
									<b>.text-success</b>
									Ordered List Item
								</li>
								<li class="text-warning">.text-warning Ordered List Item</li>
								<li class="text-muted">.text-muted Ordered List Item</li>
							</ol>
						</div>
					</div>
					<hr>
					<div class="row">
						<div class="col-xs-12">
							<ul class="list-unstyled spaced">
								<li>
									<i class="icon-bell bigger-110 purple"></i>
									List with custom icons and more space
								</li>
								<li>
									<i class="icon-ok bigger-110 green"></i>
									Unordered List Item # 2
								</li>
								<li>
									<i class="icon-remove bigger-110 red"></i>
									Unordered List Item # 3
								</li>
							</ul>
							<ul class="list-unstyled spaced2">
								<li>
									<i class="icon-circle green"></i>
									Even more space
								</li>
								<li class="text-warning bigger-110 orange">
									<i class="icon-warning-sign"></i>
									Unordered List Item # 5
								</li>
								<li class="muted">
									<i class="icon-angle-right bigger-110"></i>
									Unordered List Item # 6
								</li>
								<li>
									<ul class="list-inline">
										<li>
											<i class="icon-share-alt green bigger-110"></i>
											Inline List Item # 1
										</li>
										<li>List Item # 2</li>
										<li>List Item # 3</li>
									</ul>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-sm-6">
		<h3 class="row-fluid header smaller lighter purple">Default Buttons</h3>
		<p>
			<button class="btn">Default </button>
			<button class="btn btn-primary">Primary</button>
			<button class="btn btn-info">Info</button>
			<button class="btn btn-success">Success</button>
		</p>
		<p>
			<button class="btn btn-warning">Warning</button>
			<button class="btn btn-danger">Danger</button>
			<button class="btn btn-inverse">Inverse</button>
			<button class="btn btn-pink">Pink</button>
		</p>
		<p>
			<button class="btn btn-purple">Purple</button>
			<button class="btn btn-yellow">Yellow</button>
			<button class="btn btn-grey">Grey</button>
			<button class="btn btn-light">Light</button>
			<button class="btn btn-white">White</button>
			<button class="btn btn-link">Link</button>
		</p>
	</div>
	<div class="col-sm-6">
		<h3 class="header smaller lighter red">Button Sizing</h3>
		<p>
			<button class="btn btn-minier btn-yellow">Minier</button>
			<button class="btn btn-xs">Mini</button>
			<button class="btn btn-sm btn-primary">Small</button>
			<button class="btn btn-info">Default</button>
			<button class="btn btn-lg btn-success">Large Size</button>
		</p>
		<p>
			<button class="btn btn-warning btn-lg">Large Size</button>
			<button class="btn btn-danger">Default</button>
			<button class="btn btn-sm btn-inverse">Small</button>
			<button class="btn btn-xs btn-pink">Pink</button>
			<button class="btn btn-minier btn-purple">Purple</button>
		</p>
	</div>
</div>
````