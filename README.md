# hw9
## Чтобы удалить все пустые строки, я использовала регулярное выражение: \n\r заменила все вхождения на \0 .
![](https://raw.githubusercontent.com/leslyrumyantseva/hw9/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD.png) 
## Чтобы найти всех князей и города, имя и название которых оканчивается на "слав", я использовала регулярное выражение: [А-Я]+(слав) 
## Всего упоминаний о князьях нашла: 592 .
![](https://github.com/leslyrumyantseva/hw9/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD2.png?raw=true)
## Чтобы найти все упоминания Новгорода, я использовала регулярное выражение: Нов.?город.? 
## Всего упоминаний Новгорода нашла: 59 .
![](https://github.com/leslyrumyantseva/hw9/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD3.png?raw=true)
# Бонус
## Чтобы после каждого знака препинания поставить пробел, я использовала регулярное выражение: (?<=[:;,.\]\)])(?=[\[\("А-Яа-я]) и заменила выходные данные на пробел \s .
![](https://github.com/leslyrumyantseva/hw9/blob/5dffa82db720a4e40e29e4c971d89925ede40752/%D1%81%D0%BA%D1%80%D0%B8%D0%BD4.png?raw=true)
