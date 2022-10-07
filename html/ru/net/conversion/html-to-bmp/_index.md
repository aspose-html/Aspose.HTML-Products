---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в BMP
description: Преобразование HTML в BMP на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер HTML в BMP бесплатно!
url: /net/conversion/html-to-bmp/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать HTML в BMP на C#
h2: Создание BMP из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат BMP онлайн!
---

{{<section overview>}}
---
h2: Преобразование HTML в BMP с помощью C#
---

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Если вам нужно включить файлы HTML в презентацию PowerPoint или отправить их по электронной почте, преобразуйте их в соответствующий формат изображения и используйте по своему усмотрению! С помощью API [Aspose.HTML для .NET](https://products.aspose.com/html/net/) вы можете программно преобразовывать HTML в BMP с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в BMP, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации HTML
---

Проверьте качество преобразования HTML в BMP прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в BMP будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат BMP онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML BMP PDF MD "JPG|JPEG" GIF DOCX XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
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
h2: Как конвертировать HTML в BMP на C#
---

Если вы хотите включить в свой продукт функции преобразования или хотите программно преобразовать HTML в BMP, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с форматом изображения BMP. По умолчанию свойство Format имеет значение PNG.
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter для сохранения HTML в виде файла BMP. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл BMP будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование HTML в BMP в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/#convert-html-to-bmp" target="_blank">Преобразование HTML в BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/#convert-html-to-bmp-in-c-using-imagesaveoptions" target="_blank">Преобразование HTML в BMP с помощью ImageSaveOptions</a>

Файлы BMP представляют собой файлы растровых изображений, которые используются для хранения высококачественных растровых цифровых изображений. Таким образом, иногда может возникнуть необходимость конвертировать HTML в BMP. Пожалуйста, посетите статью документации [Преобразование HTML в BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в BMP. В статье вы найдете информацию о том, как преобразовать HTML в BMP с помощью методов ConvertHTML() и как применить параметры ImageSaveOptions и ICreateStreamProvider.

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