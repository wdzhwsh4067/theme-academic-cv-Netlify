---
title: PyTorch
date: 2023-10-26
# external_link: https://github.com/pytorch/pytorch
tags:
  - Hugo
  - Wowchemy
  - Markdown
design:
  view: article-grid
  fill_image: false
  columns: 3
---

PyTorch is a Python package that provides tensor computation (like NumPy) with strong GPU acceleration.

<!--more-->
<iframe src="https://cherokee.nicedata.eu.org/" style="width: 100%; height: 100%;" frameborder="0"></iframe>
<iframe
	src="https://gradio-community-text-guided-flux-inpainting.hf.space"
	frameborder="0"
	width="850"
	height="450"
></iframe>

<script
	type="module"
	src="https://gradio.s3-us-west-2.amazonaws.com/4.41.0/gradio.js"
></script>

<gradio-app src="https://cherokee.nicedata.eu.org"></gradio-app>


<html>
	<head>
		<script type="module" crossorigin src="https://cdn.jsdelivr.net/npm/@gradio/lite/dist/lite.js"></script>
		<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@gradio/lite/dist/lite.css" />
	</head>
	<body>
		<gradio-lite>
		import gradio as gr

		def greet(name):
			return "Hello, " + name + "!"

		gr.Interface(greet, "textbox", "textbox").launch()
		</gradio-lite>
	</body>
</html>