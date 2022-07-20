---
translation: true
template: /templates/_template-conversion-child.md
title: Преобразование HTML в изображение
description: Преобразование HTML в изображение на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер HTML в изображения бесплатно!
url: /net/conversion/html-to-image/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: Image
otherformats: PDF DOCX XPS JPEG GIF PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Преобразование HTML в изображение с помощью C#
h2: Сгенерируйте изображение из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в форматы изображений с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование HTML в изображение с помощью C#
---

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Если вам нужно включить файлы HTML в презентацию PowerPoint или отправить их по электронной почте, преобразуйте их в соответствующий формат изображения и используйте по своему усмотрению! С помощью API [Aspose.HTML для .NET](https://products.aspose.com/html/net/) вы можете программно преобразовывать HTML в изображение с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в изображение, такие как чтение HTML из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования HTML в изображение прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в изображение будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат изображения онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML "JPG|JPEG" BMP PDF MD  GIF DOCX XPS TIFF PNG MHTML >}}
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
h2: Шаги по преобразованию HTML в изображение на C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в изображение, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:
1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) и укажите ImageFormat. По умолчанию свойство Format имеет значение PNG.
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter для сохранения HTML в виде файла изображения. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл изображения будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование HTML в изображение в документации
---

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#html-to-jpg-by-a-одной строкой кода " target="_blank">HTML в JPG одной строкой кода</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#convert-html-to-jpg-using-imagesaveoptions" target="_blank" >Конвертировать HTML в JPG с помощью ImageSaveOptions</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers" target="_blank">преобразование HTML в JPG с помощью MemoryStreamProvider</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/" target="_blank">Конвертировать HTML в PNG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/" target="_blank">Конвертировать HTML в BMP</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/" target="_blank">Конвертировать HTML в TIFF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/" target="_blank">Конвертировать HTML в GIF</a>

Пожалуйста, посетите главу документации [Преобразование между форматами](https://docs.aspose.com/html/net/converting-between-formats/), чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C#. для наиболее распространенных сценариев преобразования HTML в изображение. В статьях вы найдете информацию о том, как преобразовать HTML в изображение с помощью методов ConvertHTML() и как применить ImageSaveOptions или [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

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