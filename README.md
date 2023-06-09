# Домашнее задание к занятию "6.1. Виртуализация и облачные решения: AWS, GCP, Яндекс.Облако, Openstack "

**

### Задание 1. 

**Ответьте на вопрос в свободной форме.**

Чем частное облако отличается от общедоступного, публичного и гибридного?

Основное отличие - уровни доступа. Частное облако доступно только определенным аутентифицированным пользователям. Для всех остальных оно закрыто, в отличие от публичного, которое открыто для всех пользователей. Общедоступное или общественное облако распределяется между несколькими организациями, связанными определенными интересами. Это могут быть научные, военные или иные организации. Гибридные облака могут строиться на основе частного и публичного или общественного облака. 

---

### Задание 2 

Что обозначают: IaaS, PaaS, SaaS, CaaS, DRaaS, BaaS, DBaaS, MaaS, DaaS, NaaS, STaaS? Напишите примеры их использования.

*Приведите ответ в свободной форме.*

- IaaS - инфраструктура как услуга. По сути это схема, при которой различные компоненты облачной инфраструктуры вроде серверов, хранилищ данных, операционных систем и сетевых ресурсов предоставляются в качестве подключаемой услуги;

- PaaS - платформа как услуга. Здесь предоставляются определенные инструменты, например: система управления базами данных, среда машинного обучения или обработки big data, промышленный IoT. Их нужно настроить под потребности, но не надо строить с нуля; 

- SaaS - ПО как услуга. Это одна из форм облачных вычислений, при которой пользователям предоставляется готовое прикладное программное обеспечение, полностью обслуживаемое провайдером. К примеру, сервисы электронной почты yandex.ru, google.ru, mail.ru, или настроенная в облаке программа 1С, или обланая CRM;

- CaaS - коммуникация как услуга. Решение ИТ-аутсорсинга для корпоративной связи, арендованной у одного провайдера. В неё входит сервис интернет-телефонии, мессенджеры, интерфейсы совместной работы или синхронизации изменений в рабочих документах, видеоконференции;

- DRaaS - аварийное восстановление ИТ-систем как услуга. Оно заключается в создании копии физических или виртуальных серверов третьей стороной, чтобы минимизировать потери бизнеса, вызванные отказом инфраструктуры в случае техногенной катастрофы или стихийного бедствия;

- BaaS (mBaas) - бэкэнд как услуга. Используется для того, чтобы быстро построить необходимый бэкенд и платформу для обработки данных, поступающих из мобильных приложений. BaaS-платформами пользуется множество разработчиков игр, социальных и корпоративных приложений. Кроме этого, аббревиатуру BaaS можно расшифровать следующим образом - бэкап как услуга. Многие компании нуждаются в резервном копировании большого объема данных. Проще всего хранить бэкапы в облаке — так они не занимают места на жестком диске и всегда доступны при необходимости восстановления. Периодичность создания резервных копий может быть любой. И еще один вариант это "банк как услуга". По сути это инновационная B2B-услуга сдачи банками в аренду своей инфраструктуры. Используется организациями, которып желают проводить платежные транзакции внутри своей инфраструктуры (ERP-системы, web, application), но не имеют возможности организовать собственный банк или приобрести существующий;

- DBaaS - база данных как услуга. Это любая СУБД, предоставляемая по подписке как облачный сервис в рамках платформенной модели обслуживания;

- MaaS - мониторинг как услуга. Она важна для большого количества компаний, которым необходимо следить за своим оборудованием и программным обеспечением постоянно. Выступая обслуживаемым в облаке программным обеспечением для мониторинга, она позволяет снизить расходы на установку и поддержку системы мониторинга. Заказчик получает продвинутые возможности для отслеживания событий в собственной инфраструктуре;

- DaaS - рабочий стол как услуга. Здесь сервисом является не определенное программное обеспечение, а рабочее место, которое готово к использованию и снабжено всеми необходимыми средствами;

- NaaS - сеть как услуга. Принцип работы NaaS основан на эксплуатации сервисов транспортных соединений, или, проще говоря, на продаже сетевых услуг клиентам, не желающим строить собственную сетевую инфраструктуру. Сервис может включать функционал, обеспечивающий организацию WAN-соединений, подключений к ЦОД, в том числе организацию пропускной полосы по требованию, обеспечение безопасности и другое;

- STaaS - хранение как услуга. Сервис может быть полезен кому угодно, начиная от корпоративного сектора, заканчивая обывателем, у которого попросту заканчивается свободное место на жестком диске. Сервис STaaS дает возможность сохранять данные на внешнем носителе в облаке хостинг-провайдера, который на стороне пользователя выглядит как дополнительный логический диск или папка;

---

### Задание 3 

Напишите, какой вид сервиса предоставляется пользователю, когда:

1. Управляет всеми процессами провайдер;
2. Вы управляете приложением и данными, остальным управляет провайдер; 
3. Вы управляете операционной системой, средой исполнения, данными, приложениями, остальными управляет провайдер;
4. Вы управляете сетью, хранилищами, серверами, виртуализацией, операционной системой, средой исполнения, данными, приложениями;

*Приведите ответ в свободной форме.*

1. SaaS; 
2. PaaS;
3. IaaS;
4. Collocation или реальная IT-инфраструктура предприятия;

---

 ### Задание 4 

Вы работаете ИТ-специалистом в своей компании. Перед вами встал вопрос: покупать физический сервер или арендовать облачный сервис от [Yandex Cloud](https://cloud.yandex.ru).
 
Выполните действия и приложите скриншоты по каждому этапу:

1. Создать платёжный аккаунт:
  - зайти в консоль;
  - выбрать меню биллинг; 
  - зарегистрировать аккаунт.
2. После регистрации выбрать меню в консоли Computer cloud. 
3. Приступить к созданию виртуальной машины. 


 *Приложите скриншоты.*

<a href="https://ibb.co/TBg3K5k"><img src="https://i.ibb.co/C5HGJFz/6-1-1.png" alt="6-1-1" border="0"></a>
<img src="https://i.ibb.co/DVQpkCx/1.png" alt="1" width="707" height="248" data-is360="0" data-load="full">


Ответьте на следующие вопросы:

1. Какие ОС можно выбрать?
2. Какие параметры сервера можно выбрать?
3. Какие компоненты мониторинга можно создать?
4. Какие системы безопасности предусмотрены?
5. Как меняется цена от выбранных характеристик? Приведите пример самой дорогой конфигурации и самой дешевой. 

*Приведите ответы в свободной форме.*

1. Семейсто Linux:
<img src="https://i.ibb.co/JmJXjSY/6-1-2.png" alt="6-1-2" width="777" height="250" data-is360="0" data-load="full">

2. Процессор, Оперативная память, Дисковые накопители, Сетевые настройки:
<img src="https://i.ibb.co/vHFp5Fr/6-1-3.png" alt="6-1-3" width="883" height="892" data-is360="0" data-load="full">

3. В Мониторинге можно выбрать "Сервисные дашборды"
<img src="https://i.ibb.co/r0zNJyw/6-1-4.png" alt="6-1-4" width="1149" height="476" data-is360="0" data-load="full">

4. Защита от DDOS-атак, оплачиваемая за каждый очищенный гигабайт. Кроме этого, на Cloud.Market в разделе безопасность можно выбрать антивирусные продукты, межсетевые экраны и vpn-серверы;

5. Цена изменяется в пределах от 729 р. до 1 602 000 р. за vm/мес.
