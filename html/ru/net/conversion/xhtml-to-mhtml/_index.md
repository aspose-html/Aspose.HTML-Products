---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в MHTML
description: Преобразование XHTML в MHTML на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в MHTML бесплатно!
url: /net/conversion/xhtml-to-mhtml/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: MHTML
otherformats: PDF XPS DOCX GIF JPEG PNG TIFF BMP HTML MD
---

{{<section banner>}}
---
h1: Конвертировать XHTML в MHTML через C#
h2: Создайте MHTML из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте формат XHTML в MHTML онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в MHTML с помощью C#
---

Преимущество сохранения (X)HTML как MHTML заключается в том, что все элементы веб-страницы сохраняются в одном файле. MHTML содержит базовый (X)HTML-документ и встроенные в него изображения, мультимедиа и другие ресурсы. С помощью API [Aspose.HTML для .NET](https://products.aspose.com/html/net/) вы можете программно конвертировать XHTML в MHTML с полным контролем над параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в формате MHTML. Мощный C# API позволяет быстро и качественно конвертировать XHTML в MHTML!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в MHTML прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в MHTML будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат MHTML онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML MHTML BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MD >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Действия по преобразованию XHTML в MHTML в C#
---

Если вы хотите программно преобразовать XHTML в MHTML, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML в MHTML требует некоторых обязательных шагов:
1. Загрузите файл XHTML, используя один из конструкторов HTMLDocument() класса [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument).
1. Создайте новый объект [MHTMLSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/mhtmlsaveoptions).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить XHTML как файл MHTML.
1. Файл MHTML будет сохранен по указанному пути.


{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

MHTML объединяет обычный (X)HTML с внешними ресурсами, такими как изображения, анимация, аудио и т. д., в один файл с расширением .mht. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

{{<section online-converters>}}
---
h2: Бесплатные онлайн-конвертеры
---

{{<section get-started>}}
---
h2: Как установить библиотеку Aspose.HTML для .NET
---

{{<section other-conversions>}}
---
title: Другие поддерживаемые преобразования XHTML
subTitle: "Вы также можете конвертировать XHTML во многие другие форматы файлов:"
---