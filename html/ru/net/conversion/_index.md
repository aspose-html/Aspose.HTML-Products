---
translation: true
template: /templates/_template-conversion.md
title: Преобразование HTML, XHTML, Markdown, MHTML, EPUB и SVG с помощью C#
url: /net/conversion/
description: Конветрируйте HTML в XHTML, PDF, DOCX, XPS, Markdown, MHTML и изображения с помощью нескольких строк кода C#. Проверьте онлайн-конвертер HTML бесплатно!
---

{{<section banner>}}
---
h1: Конвертировать HTML на C#
h2: Преобразование HTML в XHTML, MHTML, Markdown, PDF, XPS, DOCX и изображения, включая BMP, JPG, PNG, TIFF, для создания кроссплатформенных приложений .NET.
---

{{<section overview>}}
---
h2: Как конвертировать HTML с помощью C#
---

 Язык гипертекстовой разметки HTML — это язык Интернета. В настоящее время большая часть информации представлена ​​на веб-сайтах в виде веб-страниц. Таким образом, преобразование этой информации на основе HTML в другие форматы, такие как PDF, XPS, Microsoft® Word, Markdown и форматы изображений, является распространенным сценарием. [.NET HTML API](https://products.aspose.com/html/net/) упрощает процесс преобразования для разработчиков.<br><br>
Любое преобразование, которое вы хотите выполнить, включает в себя загрузку HTML-документа и его сохранение в поддерживаемом формате. Это могут быть разные сценарии, но это можно сделать с помощью нескольких обязательных шагов:

 - Загрузите документ HTML в объект Document с помощью одного из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
 - Создайте объект «Параметры сохранения».
 - Вызовите один из методов [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) и передайте ему необходимые параметры.


{{<section demos>}}
---
h2: Онлайн Конвертер HTML
---

Вы можете конвертировать HTML с помощью Aspose.HTML для .NET API в режиме реального времени. В следующем примере C# показано, как преобразовать HTML-документ. Пожалуйста, загрузите файл из локальной файловой системы, выберите выходной формат и запустите конвертер. Вы сразу получите результат. Вы можете попробовать бесплатные онлайн-конвертеры <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank">здесь</a>.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PDF DOCX MD BMP "JPG|JPEG" PNG GIF TIFF XPS>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("input.{{input lower}}");
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
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");
{{< /app/html/converter>}}

{{<section documentation>}}
---
h2: Статьи документации о конвертации HTML файлов
article1: Конвертировать HTML в PDF
article2: Преобразование HTML в XPS
article3: Преобразование HTML в DOCX
article4: Конвертировать HTML в MHTML
article5: Конвертировать HTML в Markdown
article6: Преобразование HTML в BMP
article7: Конвертировать HTML в PNG
article8: Конвертировать HTML в JPG
article9: Преобразование HTML в TIFF
---

Главной изюминкой Aspose.HTML .NET API является функция преобразования. Преобразование между форматами требуется по разным причинам: для работы в привычном, удобном формате или для использования преимуществ разных форматов для конкретных задач. Пространство имен [Aspose.Html.Converters](https://apireference.aspose.com/html/net/aspose.html.converters) реализует простой доступ к методам преобразования. Он обеспечивает широкий спектр преобразований HTML в популярные форматы, такие как PDF, XPS, DOCX, JPEG, PNG, BMP, TIFF, GIF, MHTML и MD. Пожалуйста, посетите главу документации [Преобразование между форматами,](https://docs.aspose.com/html/net/converting-between-formats/) чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API.

{{<section installing>}}
---
h2: Установка библиотеки Aspose.HTML для .NET
---

Эта библиотека поддерживает синтаксический анализ HTML5, CSS3, SVG и HTML Canvas для создания объектной модели документа (DOM) на основе стандарта WHATWG DOM. Вы можете использовать несколько способов установки библиотеки Aspose.HTML для .NET в вашей системе:</br>

1. Использование графического интерфейса диспетчера пакетов NuGet.
2. Использование консоли диспетчера пакетов.
3. Установка Aspose.HTML для .NET через MSI.</br>

Дополнительные сведения об установке библиотеки C# вы найдете в [документации Aspose.HTML.](https://docs.aspose.com/html/net/getting-started/installation/)

{{<section other-conversions>}}
---
h2: Другие поддерживаемые Конвертеры
---

Вы также можете конвертировать файлы HTML, XHTML, MHTML, EPUB, Markdown и SVG во многие другие форматы файлов, включая некоторые из перечисленных ниже: