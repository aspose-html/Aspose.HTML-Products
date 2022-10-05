---
translation: true
title: HTML Audio 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: HTML Audio 发电机为音频元素创建 HTML 和 C# 代码。您可以生成代码并在您自己的网站或 C# 项目中使用它。
url: /net/generators/audio/
platformtag: net
generator: HTML Audio 发电机
element: HTML audio
tag: audio
---

{{<section banner>}}
---
h1: HTML Audio 发电机
h2: 为 HTML 音频元素生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 音频标签！
---

[audio](https://html.spec.whatwg.org/multipage/media.html#the-audio-element) HTML 元素用于在 HTML 文档中嵌入音乐或任何声音内容。 `<audio>` 元素可以包含一个或多个具有不同音频源的 `<source>` 标签。浏览器将选择它支持的第一个来源。对 `<audio>` 元素的支持因浏览器而异。使用此 HTML Audio 发电机将声音添加到您的网页！

{{<section plugin>}}

{{< app/html/generator name="audio" >}}

<br>
<h2> Attributes </h2>

HTML Audio 发电机中有许多选项可用于生成 HTML 音频标签代码，然后将其复制并粘贴到您自己的网站中。音频元素支持的主要属性是 `controls`、`autoplay`、`loop`、`preload` 和 `src`。

 - 音频 `preload` 属性指定页面加载时应加载的音频文件。
 - `src` 属性指定要嵌入的音频的 URL。但这是可选的。相反，您可以使用音频块中的 `<source>` 元素来指定要嵌入的音频。
 - `autoplay` 布尔属性，如果指定，将自动开始播放。
 - 音频 `controls` 属性指定控件是否应在浏览器中显示。例如，如果您禁用了音频控制并启用了自动播放设置，音频将播放但不会在浏览器中显示。
 - 如果指定了 `loop` 布尔属性，将在到达音频结尾时自动返回起点。
 - `muted` 布尔属性，如果指定，则指示音频是否最初会被静音。它的默认值为假。
<br><br>

<h2> 在 C# 中创建 HTML 音频元素</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<audio>` 元素，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 音频元素的步骤
---

1. 使用 Document 类的 [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) 方法创建音频元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“audio”。
2. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `controls` 和其他需要的属性。
3. 创建一个或多个 `<source>` 元素并为其设置所需的属性。使用带有“源”标签名的 CreateElement() 方法。
4. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将源元素添加到音频元素中。
5. 复制 HTML 音频元素的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---