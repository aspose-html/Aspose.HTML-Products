---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в XHTML
description: Преобразование HTML в XHTML на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер HTML в XHTML бесплатно!
url: /net/conversion/html-to-xhtml/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: XHTML
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать HTML в XHTML на C#
h2: Сгенерируйте XHTML из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат XHTML онлайн!
---

{{<section overview>}}
---
h2: Преобразование HTML в XHTML с помощью C#
---

XHTML был разработан, чтобы быть более структурированным, менее скриптовым и универсальным, с использованием всех существующих возможностей XML и большей независимостью от устройств. Чтобы преобразовать HTML в XHTML, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Вы можете программно преобразовывать HTML в XHTML с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в XHTML, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Как преобразовать HTML в XHTML в C#
---

В следующем примере C# показано, как преобразовать HTML-документ. Существуют различные случаи преобразования HTML в XHTML, такие как чтение с URL-адреса/веб-страницы, сгенерированного редактором WYSISYG HTML или из сохраненного файла. Мы описываем исходный код для чтения HTML из файла и последующего преобразования HTML в XHTML с помощью метода Save().

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML XHTML MHTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG>}}
using Aspose.Html;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
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
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF' 'PDF' 'MHTML' 'MD' 'XPS' 'DOCX'}}
    Aspose.Html.Converters.Converter.ConvertHTML(document, options, "output.{{output lower}}"); 
{{/if_output}}
{{#if_output 'XHTML'}} 
    document.Save("output.xhtml", new HTMLSaveOptions() { DocumentType = HTMLSaveOptions.XHTML}); 
{{/if_output}}     
{{< /app/html/converter>}} 

{{<section steps>}}
---
h2: Шаги по преобразованию HTML в XHTML в C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в XHTML, см. приведенный выше пример кода C# или изучите главу «Документация». Пожалуйста, выполните следующие обязательные действия:

1. Загрузите HTML-документ в объект Document с помощью конструктора [HTMLDocument(`string`)](https://apireference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Вызовите метод [Сохранить(`string`, `HTMLSaveOptions`)](https://apireference.aspose.com/html/net/aspose.html/htmldocument/save/).
1. Передайте путь к выходному файлу с расширением XHTML.
1. Файл XHTML будет сохранен по указанному пути.


{{<section documentation>}}
---
h2: Преобразование HTML в документации
---

Преобразование между форматами требуется по разным причинам: для работы в привычном, удобном формате или для использования преимуществ разных форматов для конкретных задач. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать HTML в другие популярные форматы. Пожалуйста, посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об Aspose.HTML для .NET API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

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
title: Другие поддерживаемые преобразования HTML
subTitle: "Вы также можете конвертировать HTML во многие другие форматы файлов:"
---