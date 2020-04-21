# FinNet 

ЗАДАЧА:<br>
Дан граф анонимизированный граф транзакций между юридическими лицами России.<br><br>
В файле vertices.csv информация о юридических лицах<br>
id - id юридического лица <br>
main_okved - основной ОКВЭД юридического лица (https://ru.wikipedia.org/wiki/Общероссийский_классификатор_видов_экономической_деятельности) <br>
region_code - код региона юридического лица <br>
company_type - тип юридического лица <br><br>
В файле edges.csv информация об обороте между юридическими лицами, прошедшем через счета банка Точка <br>
id_1 - id первого юридического лица <br>
Id_2 - id второго юридического лица <br>
value - суммарный оборот между юридическими лицами, к которому применено некоторое линейное преобразование <br>
n_transactions - количество транзакций между юридическими лицами, к которому было применено некоторое линейное преобразование <br>
Обратите внимание на то, что ребра неориентированные!<br><br> 
В файле ids.csv информация о наиболее крупных юридических лицах, для которых требуется восстановить ребра <br>
id - id юридического лица <br>
Справочная информация: <br>
Справочник оквэдов - https://regforum.ru/okved/ <br><br>
Из графа было удалено 100 000 ребер, смежных юридическим лицам из файла ids.csv. Ваша задача - восстановить удаленные ребра и отправить в проверяющую систему файл submission.csv, который содержит 100 000 строк в формате id_1, id_2, где <br>
id_1 - id первого юридического лица <br>
Id_2 - id второго юридического лица <br><br>
Для вашего удобства ссылка на baseline решение [ССЫЛКА] <br><br>
МЕТРИКА: <br>
Метрика по которой будет оцениваться ваше решение <br>
score = intersection(test, prediction) <br><br>
Помните, что по ходу соревнований вам доступен public leaderboard, в котором решение оценивается на 50% отложенной выборки.<br>  
В качестве финального решения загрузите файл submission.csv, который будет оценен на private leaderboard на оставшихся 50% отложенной выборки. Итоговые результаты оцениваются только по private leaderboard. <br>
ТАК ЖЕ ВМЕСТЕ С ФИНАЛЬНОЙ ПОСЫЛКОЙ НЕОБХОДИМО ОТПРАВИТЬ ВОСПРОИЗВОДИМЫЙ КОД С ВАШИМ РЕШЕНИЕМ В ВИДЕ ZIP АРХИВА.  <br><br>
Удачи! 
