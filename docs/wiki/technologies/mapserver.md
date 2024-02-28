---
title: MapServer
tags: technology, MapServer
---

# MapServer

![MapServer лого](img/mapserver_logo.png)

MapServer (мапсървър) е платформа с отворен код, предназначена за публикуване на пространствени данни и интерактивни картографски приложения в уеб среда. Първоначално разработена през средата на 90-те години в Университета на Минесота, в днешно време се издава под MIT лиценз (лиценз за свободен софтуер) и функционира на всички основни операционни системи (Windows, Linux, Mac OS X).

MapServer е написана на програмния език C и работи с висока скорост. Тя е администрирана в рамките на OSGeo от Комитета за управление на проекта MapServer и е финансирана от разнообразна група организации, отговарящи за актуализации и поддръжка. В основата на проекта стои общност от хора, посветени на отворения код.

## Поддържани стандарти

MapServer поддържа множество стандарти на Open Geospatial Consortium - международна организация, отговаряща за стандарти за геопространствено съдържание, и също така е съвместима с INSPIRE View Service – част от INSPIRE инфраструктурата, целяща да установи лесен и достъпен начин за обмен на пространствена информация в рамките на Европейския съюз.  Долу може да откриете списък с поддържаните стандарти:

-	Web Map Service (WMS) 
-	Web Feature Service (WFS)
-	Web Coverage Service (WCS)
-	Web Map Context (WMC)
-	Filter Encoding (FE)
-	Style Layer Descriptor (SLD)
-	Geography Markup Language (GML)
-	Sensor Observation Service (SOS)
-	Observations and Measurements (OM)

## Приложение

MapServer се използва от частни фирми, изследователски институти и публични администрации за публикуване и споделяне на геопространствени данни. Намира широко приложение в уеб-базирани картографски приложения както от страна на потребителя, така и от страна на сървъра.

## Какво позволява MapServer?

- Възможност за поставяне на етикети на обекти включително предотвратяване на пренасищане 
- Поддържа стандарт за шрифтове TrueType при етикетиране и симвология
- Автоматизиране на елементи на картата (графичен мащаб, легенда, справочна карта)
- Тематично картографиране, базирано на логични/регулярни изрази
- Поддържа рендериране с AGG, Cairo и други драйвери
- SVG симвология
- Multiple Font Support 
- UTF Grid Support – при взаимодействие с обект от картата се извлича и предоставя информация за него
- Създаване на динамични топлинни карти
- Персонализиране на генерирането на клетки на картата 
- Поддържане на растерни заявки
- OGR-базирано генериране на изходни данни от заявки
- Идентификация на обекти чрез атрибути, точки, ограничаваща кутия или геометрия в един или повече слоеве
- Среди за скриптове и разработка: CGI/FastCGI, PHP, Python, Perl, Ruby, Java, .NET
- Междуплатформена поддръжка
- Множество растерни и векторни формати чрез GDAL/OGR
- Поддръжка на множество картни проекции 