---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в MHTML
description: Преобразование HTML в MHTML на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер HTML в MHTML бесплатно!
url: /net/conversion/html-to-mhtml/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: MHTML
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP XHTML MD
---

{{<section banner>}}
---
h1: Преобразование HTML в MHTML через C#
h2: Создание MHTML из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат MHTML с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование HTML в MHTML с помощью C#
---

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Преимущество сохранения HTML как MHTML заключается в том, что все элементы веб-страницы сохраняются в одном файле. MHTML содержит базовый HTML-документ и встроенные в него изображения, мультимедиа и другие ресурсы. С помощью API [Aspose.HTML для .NET](https://products.aspose.com/html/net/) вы можете программно преобразовать HTML в MHTML с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в MHTML, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования HTML в MHTML прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в MHTML будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат MHTML онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML MHTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG >}}
using Aspose.Html;
using Aspose.Html.Converters;
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
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Шаги по преобразованию HTML в MHTML в C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в MHTML, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:
1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [MHTMLSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/mhtmlsaveoptions).
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить HTML как файл MHTML. Вам необходимо передать HTMLDocument, MHTMLSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл MHTML будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование HTML в MHTML в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#html-to-mhtml-by-a-single-line-of-code " target="_blank">Преобразование HTML в MHTML с помощью одной строки кода</a>
  - Цель <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-in-c-using-mhtmlsaveoptions" ="_blank">Преобразование HTML в MHTML с помощью MHTMLSaveOptions</a>

MHTML объединяет обычный HTML с внешними ресурсами, такими как изображения, анимация, аудио и т. д., в один файл с расширением .mht. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать HTML в формат MHTML. Пожалуйста, посетите статью документации [Преобразование HTML в MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в MHTML. В статье вы найдете информацию о том, как преобразовать HTML в MHTML с помощью методов ConvertHTML() и как применить параметры MHTMLSaveOptions и ICreateStreamProvider.

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