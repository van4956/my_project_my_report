# НЕДЕЛЬНАЯ СТАТИСТИКА


В данном проекте я предоставляю доступ к динамическому отчету по моей статистике.  
В нем я отбображаю наибоелее важные на мой взгляд аспекты человеческой жизни, такие как:  
*Сон*, *Питание*, *Активность.*  

 - ***Сон*** - очень важный, мало изученый жизненый процесс. 30% всей жизни мы спим. Во время сна происходят важные востановительные процессы, формируется память. Метрики для сна собираю с помощию фитнес браслета Xiaomi Mi Band 4. Раз в неделю переношу агрегированные данные в Google Sheets.  
 - ***Питание.*** Мы то, что мы едим. Диета - это культура питания. По моему важно понимать, и осознанно относиться к тому что, и как мы едим. Данные по питанию собираю с помощью мобильного приложения Счетчик Каллорий. Раз в неделю переношу агрегированные данные в Google Sheets. Так же раз в неделю провожу взвешивание на умных весах Xiaomi Mi Body Composition 2, в строго определенное время, утром в понедельник до завтрака, что позволяет минимизировать влеяние аномалий и случайных отклонений. Все полученные показатели так же вношу в Google Sheets.  
 - ***Активность.***  Для  поддержания общего тонуса рекомендуется заниматься спортом, или иными видами активности. Я выбрал бег. Регулярный медленный бег, в средней пульсовой зоне, 3-4 раза в неделю. Показатели считываю при помощи нагрудного пульсометра Garmin HRM-Dual и фитнес браслета Xiaomi Mi Band 4. Раз в неделю переношу агрегированные данные в Google Sheets.
   
---  
  
В проекте используются программы `Google Sheets`, `Google Date Studio`.  
Все исходные данные собираются в таблицах Google Sheets, стандартизируются и готовятся к дальнейшему процессу визуализации.  
Отчет создается в Google Date Studio, и состоит из трех страниц: СОН, ПИТАНИЕ, БЕГ.  
<BR>  
 
1. Страница отчета - СОН.  
 Ключевым показателем считаю время начала сна, время пробуждения. Очень важно что бы время отбоя и пробуждения было постоянным. Регулярность и постоянство интервалов важнее продолжительности, поэтому эти показатели идут первыми.  
 Продолжительность медленного сна, именно во время него происходят самые важные процессы востановления организма, обработка, отбор и перенос важной информации из краткосрочной памяти в долгосрочную. Корреляция оценки сна со временем медленого и быстрого сна, и дневной активности показывает прямую зависимость между медленным сном/оценкой сна и обратную зависимость быстрого сна/общей оценкой сна.  
 Так же используются показатели продолжительность быстрого сна, общее время сна, дневная активность, количестов шагов, общая оценка сна. 
  
2. Страница отчета - ПИТАНИЕ.  
 Питание 
  
3. Страница отчета - БЕГ.  
 Бег 
 
<BR>  
---
  
Ссылка на таблицы:  
https://docs.google.com/spreadsheets/d/1On-vrOyN0avxJ4QdWPiVbKVIU16TntCrXoQpxnr4_fk/edit?usp=sharing

Ссылка на динамический отчет:  
https://datastudio.google.com/reporting/0e6923dc-1256-496b-b760-2a73da3682be
