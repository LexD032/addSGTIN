# addSGTIN
Программа предназначена для подбора в чек SGTIN  ЛС из прайс-листа ПО Касса Инфоаптека

для того что бы программа работала, на одном из дисков(c: d: e:)
должна быть папка c программой инфоаптека склад  в папке IApteka

Скопироватьфайлы. Оба файла должны быть в одной папке (любой)
запускается exe файл На экране появляется окно с одной кнопкой. 

Как работает
1. Открываем прайс - список товаров с ценами на кассе. Находим 
   нужный товар. Копируем в буфер обмена SGTIN из списка остатков.
2. Переключаемся на окно программы. Нажимаем на кнопку.
   в ответ сообщает "нашла и поместила в буфер обмена"
4. Переключаемся снова в кассовую программу и вставляем из буфера данные в поле Штрихкод 
   нажимаем "ентер" - товар подбирается в чек

П.С - тут только рабочие файлы. Для тех, кто пожелает проект есть  на соседней ветке https://github.com/LexD032/InfoApteka_Find_FullCode
