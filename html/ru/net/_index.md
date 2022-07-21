---
translation: true
template: /templates/_template-net.md
title: C# HTML Parser — .NET API для обработки файлов HTML
weight: 20
url: /net/
description: C# .NET API для чтения, записи, изменения, редактирования, объединения и преобразования HTML, XHTML, MHTML, EPUB, Markdown и SVG.
---

{{<section banner>}}
---
h1: C# API для анализа файлов HTML
h2: Создавайте, редактируйте, извлекайте данные, объединяйте и конвертируйте HTML-страницы в PDF, DOCX, XPS, изображения и другие форматы.
---

{{<section overview>}}
---
item1: <a href="https://docs.aspose.com/html/net/working-with-documents/creating-a-document/" target="_blank">Создавайте или загружайте HTML-документы</a> из файл, URL, строка или поток.
item2: <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Конвертируйте документы</a> между популярными форматами.
item3: <a href="https://docs.aspose.com/html/net/message-handlers/" target="_blank">Создавайте собственные обработчики сообщений</a> для выполнения определенной задачи.
item4: <a href="https://docs.aspose.com/html/net/how-to-articles/how-to-use-xpath/" target="_blank">Навигация по HTML-документам</a> с помощью запроса XPath или CSS-селектора.
item5: <a href="https://docs.aspose.com/html/net/working-with-documents/editing-a-document/" target="_blank">Редактируйте файлы HTML</a>, вставляя новые узлы, удаляйте или редактируйте содержимое существующих узлов.
item6: <a href="https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/" target="_blank">Визуализация документов</a> с высоким качеством,
item7: и более.
---

Aspose.HTML для .NET — это расширенный API-интерфейс обработки HTML для выполнения широкого спектра задач управления и манипулирования в кросс-платформенных приложениях. API предназначен для создания, изменения, извлечения данных, преобразования и рендеринга HTML-документов без какого-либо внешнего программного обеспечения. Кроме того, он поддерживает популярные форматы файлов, такие как EPUB, MHTML, XML, SVG и Markdown, а также рендеринг в форматы файлов PDF, DOCX, XPS и изображений. Aspose.HTML для .NET полностью написан на C# и может использоваться для создания любого типа 32-разрядного или 64-разрядного приложения .NET, включая ASP.NET, WCF, WinForms и .NET Core.<br><br>

Кроме того, объектная модель HTML-документа интегрирована со встроенными форматами и спецификациями, такими как CSS, HTML Canvas, SVG, XPath и JavaScript, которые расширяют возможности манипулирования и качество рендеринга. Вы можете увидеть полный список функций Aspose.HTML в нашей <a href="https://docs.aspose.com/html/net/getting-started/" target="_blank">документации</a>. Использование библиотеки C# Aspose.HTML в вашем проекте позволяет выполнять следующие задачи:


{{<section glance>}}
---
h3: С одного взгляда
description: Обзор Aspose.HTML для .NET API.
---

{{<section platform>}}
---
h3: Независимость от платформы
description: Aspose.HTML для .NET поддерживает .NET framework и .NET Standard.
---

{{<section formats>}}
---
h3: Поддерживаемые форматы файлов
description: Aspose.HTML для .NET [поддерживаемые форматы](https://docs.aspose.com/html/net/supported-file-formats/) перечислены ниже.
---

{{<section feature>}}
---
title: Расширенные функции .NET HTML API
feature1: Создание HTML-страниц с нуля
feature2: Загрузить существующий HTML из файла, потока или URL
feature3: Реализовать спецификации W3C
feature4: Внедрение шаблонов с помощью слияния шаблонов
feature5: Заполните шаблон различными источниками данных
feature6: Рендеринг HTML Canvas 2D в PDF
feature7: Добавить, заменить или удалить узлы
feature8: Извлечение данных из HTML-документов
feature9: Загрузка форматов файлов EPUB и MHTML
feature10: Рендеринг HTML в форматы растровых изображений
feature11: Отображение нескольких документов одновременно
feature12: <a href="/html/{{lang.url-fragment}}net/conversion/md-to-html">Реализация конвертера Markdown в HTML</a>
feature13: Применение верхнего и нижнего колонтитула во время преобразования HTML в PDF
feature14: Навигация по HTML с помощью XPath Query или CSS Selector
feature15: <a href="/html/{{lang.url-fragment}}net/conversion/">Широкий диапазон преобразований между форматами</a>
---

{{<section converter>}}
---
h2: Конвертация HTML в другие форматы на C#
h3: Преобразование HTML в PDF — С#
---
   
C# API позволяет всего несколькими строками кода реализовать преобразование HTML в PDF, HTML в изображение, HTML в XHTML и т.д. Процесс преобразования прост и надежен, что делает Aspose.HTML для .NET API идеальным выбором.

{{<section "code" i18n-exclude>}}
     
using Aspose.HTML;
using Aspose.HTML.Saving;
using Aspose.HTML.Converters;
...
    
    // Load an HTML file to be converted
    using var document = new HTMLDocument("input.html")
    
    // Create an instance of the PdfSaveOptions class
    var pdfSaveOptions = new PdfSaveOptions();    
    
    // Convert HTML to PDF
    Converter.ConvertHTML(document, pdfSaveOptions, "output.pdf");
    

{{<section online-converters>}}

Вы можете проверить в работе онлайн Конвертер HTML <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank"> перейдя по ссылке.</a>

{{<section other-converters>}}

Вы также можете конвертировать HTML, XHTML, MHTML, Markdown, EPUB или SVG во многие другие форматы файлов, включая некоторые из перечисленных ниже:

{{<section edit-html>}}
---
h2: Редактирование HTML-документов
---

Aspose.HTML для .NET позволяет создавать и редактировать HTML-документы с использованием объектной модели документа (DOM). DOM — это программный интерфейс для HTML-документов, который представляет документ (в виде узлов и объектов) в виде дерева узлов, где каждый узел представляет часть документа. Aspose.HTML для .NET API позволяет вам подключаться к странице и изменять структуру, стиль и содержимое документа. Вы можете изменить документ, вставив новые узлы и удалив или отредактировав содержимое существующих узлов. <br><br>
.NET HTML API помогает разработчикам читать, изменять, перемещаться и редактировать документы (X)HTML. Некоторые функции редактирования файлов, которые может выполнять Aspose.HTML для .NET API, следующие:<br><br>
    
 - перемещаться по документам HTML с помощью различных методов, таких как обход элементов, обход документа, запросы XPath и запросы селектора CSS,<br>
 - удалить и заменить узлы HTML,<br>
 - извлекать и редактировать CSS из HTML, <br>
 - настроить песочницу для документов и многое другое.

{{<section markdown>}}
---
h2: Поддержка Markdown
h3: Преобразование HTML в Markdown — C#
h3-md: Преобразование Markdown в HTML — C#
---

Markdown — это язык разметки с синтаксисом форматирования простого текста. Markdown часто используется в качестве формата для документации и файлов readme, поскольку он позволяет писать в удобном для чтения и написания стиле. Aspose.HTML предоставляет мощный и гибкий конвертер Markdown, который может конвертировать в обоих направлениях из Markdown в HTML и из HTML в Markdown. Более того, API-интерфейс преобразователя имеет набор предопределенных правил, поэтому вы можете конвертировать HTML в Markdown, используя аутентичный синтаксис Markdown, модификацию GitLab Flavored Markdown или даже настраивать правила для своих нужд.

{{<section markdown-reverse>}}

Обратное преобразование так просто! Используя библиотеку классов Aspose.HTML в своем приложении C#, вы можете легко преобразовать Markdown в HTML-файл всего одной строкой кода!

{{<section "code-markdown1" i18n-exclude>}}
     
using Aspose.Html;
using Aspose.HTML.Saving;
...
    
	// Load an HTML file
	using var document = new HTMLDocument("document.html");

	// Convert HTML to Markdown using a set of features supported by GitLab Flavored Markdown
	document.Save("output.md", MarkdownSaveOptions.Git);

{{<section "code-markdown2" i18n-exclude>}}
     
using Aspose.Html.Converters;
...	

	// Convert Markdown to HTML
	Converter.ConvertMarkdown("document.md", "output.html");

{{<section markdown-online>}}

Вы можете попробовать онлайн Конвертер Markdown <a href="https://products.aspose.app/html/conversion/md" rel="opener noopener noreferrer" target="_blank"> здесь.</a> Конвертируйте Markdown в PDF, XPS, DOCX, JPG, PNG, BMP, TIFF, GIF и MHTML. Загружайте, преобразовывайте свои документы и получайте результаты за несколько секунд. Вам не нужно никакого дополнительного программного обеспечения.

{{<section epub-mhtml>}}
---
h2: Электронные книги и веб-архивы
h3-epub: Преобразование EPUB в PDF — C#
h3-mhtml: Преобразование MHTML в PDF — C#
---

Aspose.HTML для .NET может загружать файлы EPUB и MHTML для выполнения различных операций, включая преобразование в форматы с фиксированным макетом и растровые изображения.


{{<section "code-epub" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...
    
	// Open an existing EPUB file for reading
     using var stream = File.OpenRead("input.epub");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertEPUB method to convert EPUB to PDF
     Converter.ConvertEPUB(stream, options, "output.pdf"); 	 

{{<section "code-mhtml" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...   
	
	 // Open an existing MHTML file for reading
     using var stream = File.OpenRead("input.mht");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertMHTML method to convert MHTML to PDF
     Converter.ConvertMHTML(stream, options, output.pdf); 

{{<section epub-mhtml-online>}}

Вы можете попробовать онлайн <a href="https://products.aspose.app/html/conversion/mhtml" rel="opener noopener noreferrer" target="_blank">конвертер MHTML</a> и онлайн<a href= "https://products.aspose.app/html/conversion/epub" rel="opener noopener noreferrer" target="_blank"> Конвертер EPUB.</a> Наши браузерные инструменты конвертации работают на всех платформах, включая Windows , Linux, Mac OS, Android и iOS. Конвертеры совместимы со всеми ПК, смартфонами и планшетами.

{{<section web-scraping>}}
---
h2: Веб-скрейпинг
h3: Простое извлечение веб-данных — C#
---	
	
Веб-скрапинг -  извлечение веб-данных или веб-сканирование, представляет собой метод извлечения данных с веб-сайта. Aspose.HTML не поддерживает встроенный модуль Web Scraping. Однако, используя Aspose.HTML API, который полностью основан на спецификации W3C и поддерживает запросы XPath и CSS Selector, вы можете легко проверить содержимое любого HTML-документа и создать собственное решение для веб-скрейпинга.

{{<section "code-web-scraping" i18n-exclude>}}
     
using Aspose.Html;
...

    // Create an instance of the HTML document with a website as a parameter
    using var document = new Aspose.Html.HTMLDocument("https://en.wikipedia.org/wiki/Aspose_API");

    // Get all anchor-elements
    var elements = document.QuerySelectorAll("a");

    // Dump the anchor-element data to the console
    elements.Cast&lt;HTMLAnchorElement&gt;().ToList().ForEach(x =&gt;
        {
            System.Console.WriteLine("[Href]: " + x.Href);
            System.Console.WriteLine("[Content]: " + x.TextContent);
        });

{{<section online-web-scraping>}}

Aspose.HTML предлагает бесплатные онлайн-приложения <a href="https://products.aspose.app/html/data-scrapers" rel="opener noopener noreferrer" target="_blank">Data Scrapers</a>, способ получения данных с веб-сайтов. Наши приложения безопасны, работают на любой платформе и не требуют установки программного обеспечения. Парсеры данных можно использовать для извлечения изображений, получения ключевых слов с веб-страницы и т. д. Они просты и понятны в использовании, но при этом действенны и надежны.

{{<section learning>}}
---
tabTitle: Образовательные ресурсы
name1: Документация
name2: Исходный код
name3: Ссылки на API
name4: Учебные видео
---

{{<section support>}}
---
tabTitle: Поддержка продукта
name1: Бесплатная поддержка
name2: Платная поддержка
name3: Блог
name4: Примечания к выпуску
---

{{<section why>}}
---
tabTitle: Почему Aspose.HTML для .NET?
name1: Список клиентов
name2: Истории успеха
description: "Aspose.HTML предлагает отдельные API-интерфейсы обработки HTML для других популярных сред разработки, перечисленных ниже:"
---