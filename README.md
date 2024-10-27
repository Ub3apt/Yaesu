CHIRP имеет существенный недостаток - для программирования Yaesu FT70  шаблон позволяет вводить строчные буквы в названии, Комментарии на русском языке.
Это приводит к зависанию процесса загрузки и стиранию программы в станции.

 CHIRP читает  образы прошивок FT-70D ADMS-10 EXP файлы *.ft70d игнорируя Комментарии к каналам.
Поэтому предпочтительнее  для Yaesu FT-70D  пользоваться фирменным программатором ADMS-10 EXP.
Комментарии FT-70D ADMS-10 EXP также сохраняет в фирменный файл образа. 
С CHIRP есть разница в формате *.CSV  что делает их несовметимыми ,
однако выгрузка в них гораздо удобнее для чтения так как таблица Банков Памяти в нем выбедена в отдельную таблицу.

Вывод на печать в фирменном ADMS-10 EXP неудобен. Он полностью печатает всю таблицу банков памяти. Это 20 страниц! Невозможно сделать выборку нужных банков. CHIRP гораздо удобнее. Лучьше всего делать экспорт в *.CSV для последующей обработки, создания документации в Libre Office Calc. 
CHIRP  позволяет экпортировать и импортировать таблицы каналов в Yaesu FT-817 из FT70D. Необходимо учитывать 10-кратную разницу объёма памяти.
ADMS-10  видимимо не может правильно импортировать собственные записи с полем "коментарий" из файла FT-70D Untitled1.csv 
 работает в японской кодировке Windows-932. Любая неточность приводит к ошибке импорта. 
Используя Libre Office Calc удаётся вставить строки каналов,  копируя  и вставляя всю строку листа Calc из файла-донора в новый файл и импортировать его в ADMS-10.

