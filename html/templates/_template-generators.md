---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: html
platformtag: net
feature: generators
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="{{i18n.banner.h1}}"  h2="{{i18n.banner.h2}}" >}}

{{< blocks/products/pf/main-container >}}

{{% blocks/products/pf/agp/content h2="{{i18n.overview.h2}}" %}}

{{i18n.overview}}
<br><br>

<div class="row">
	<div class="col-md-3">
        <h4>Input</h4>				
		<ul>
			<li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/button/" target="_blank">button</a></li>
			<li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/checkbox/" target="_blank">checkbox</a></li>
			<li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/radio/" target="_blank">radio</a></li>
            <li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/color/" target="_blank">color</a></li>
            <li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/date-time/" target="_blank">date-time</a></li>
            <li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/email/" target="_blank">email</a></li>
            <li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/file/" target="_blank">file</a></li>
            <li><a href="https://products.aspose.com/html/{{lang.url-fragment}}net/generators/image-input/" target="_blank">image</a></li>
            <li>number</li>
            <li>password</li>
            <li>range</li>
			<li>range</li>
			<li>search</li>
			<li>submit</li>
			<li>telephone</li>
			<li>text</li>
			<li>textarea</li>
			<li>url</li>					
		</ul>
	</div>
	<div class="col-md-3">		
		<h4>Media</h4>
        <ul>
			<li>audio</li>
			<li>video</li>
			<li>image</li>
        </ul>
	</div>
	<div class="col-md-3">		
		<h4>Text</h4>
        <ul>
			<li>Bi-Directional Override</li>
			<li>strong</li>
			<li>Citation</li>
			<li>code</li>
			<li>Italic</li>
			<li>Highlight</li>
			<li>Quote & Blockquote</li>
			<li>Strikethrough</li>
			<li>Superscript & Subscript</li>
			<li>Underline</li>								
		</ul>
	</div>
    <div class="col-md-3">		
		<h4>Other</h4>
        <ul>
			<li>table</li>
			<li>iframe</li>
			<li>details</li>
			<li>dialog</li>
			<li>hyperlink</li>
			<li>meter</li>
			<li>progress</li>
			<li>list</li>								
		</ul>
	</div>	
</div>

<h2>{{i18n.online-generators.h2}}</h2>

{{i18n.online-generators}}

{{% /blocks/products/pf/agp/content %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}