# vetis.api #

1С доступ к ГИС Меркурий через Ветис.API http://api.vetrf.ru

Код основан на исходниках:
- https://infostart.ru/public/560823/
- https://infostart.ru/public/171019/
- https://vetrf.ru/vetrf-forum/posts/list/30/6955.page#39151
- https://github.com/mevgenym/1c_vetis.api

## Версии ##
- Ветис.API: 2.0
- 1C: v8.3.10

## Термины ##
- сервис - ГИС Меркурий

## Особенности ##

Код для доступа к Ветис.API:
- не зависит от конфигурации
- расположен в общих модулях, имена соответствуют пространствам имен Ветис.API, имена с суффиксом "_2_0" работают только с версией 2.0, остальные - 1.4
- используется только часть API для оптовой торговли замороженным мясом (не будет производства, живых животных, молока и пр.)

Метаданные и код привязанный к метаданным 1С:
- метаданные ориентированы на работу в качестве самостоятельной конфигурации
- справочники сервиса продублированы в метаданных
- конвертация значений находится в общих модулях (имена соответствуют пространствам имен Ветис.API с суффиксом "Слой1с")
- партионный учет не используется, остатки партий сервиса списываются в ручном режиме выбором в документе ВетисТранспортнаяПартия

## Настройка ##
 ...

## Контакты ##

skype: mevgenym
email: mevgenym@mail.ru
telegram: https://t.me/mevgenym https://t.me/vetismercury

## Лицензия ##

Данное программное обеспечение распространяется на условиях GNU General Public License v3.0.
