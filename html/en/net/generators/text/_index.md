---
translation: true
title: HTML Text Input Generator - online tool and C# code
template: /templates/_template-generators-child.md
description: Сreate HTML Text Input for your website. Рreview the text box, copy and use generated HTML and C# code in your project!
url: /net/generators/text/
platformtag: net
generator: HTML Text Input Generator
element: HTML text input
tag: text
---

{{<section banner>}}
---
h1: HTML Text Input Generator
h2: Generate HTML and C# code for an HTML Text Input element and use it in your own website or C# project.
---

{{<section overview>}}
---
h2: HTML Text Input Generator
---

[input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) elements of type *text* create basic single-line text fields.

{{<section plugin>}}

{{< app/html/generator name="text" >}}

<br>
<h2> Attributes </h2>

The checkbox usually contains a `name` and `value` attribute. This name/value pair will be sent to the server when the form is submitted. If the `value` attribute is not specified, then the reported default value is "on".<br>
You can generate an HTML checkbox input tag and checkbox C# code by selecting attributes such as `name`, `checked`, `id`, etc. Each checkbox is associated with a `<label>` element wrapped around the checkbox. Please always include a `<label>` tag for better accessibility!<br><br>

<h2> Create HTML Text Input in C#</h2>

Aspose.HTML for .NET API supports a set of HTML elements that are defined in HTML Standard, along with rules about how the elements can be nested. You can modify the document by appending new elements, removing, or editing the content of existing nodes. If you want to use the HTML editing features in your product or programmatically add a checkbox, see the C# code example below. You can create a checkbox with a few lines of C# code:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Steps to Create Text Input in C#
---

1. Use the [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) method of Document class to create [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) It creates the HTML element specified by tagName.
1. Set values for the [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) and [Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/) attributes.
1. Create the [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) and set required attributes.
1. Copy C# code for the HTML checkbox and use it in your C# project.

{{<section other-generators>}}
---
title: Other Supported HTML Generators
subTitle: "With these HTML Code Generators, all the hard work has already been done for you. All you have to do is copy and paste. Clear, safe and simple!"
---