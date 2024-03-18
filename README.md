# Камень я дам

## Функциональные требования 
Функциональные требования к системе:
Система – магазин по продаже камней, название «Камень я дам». Требования составлены на основе анализа заинтересованных сторон и бизнес-процессов. Общее требование – быть коммерчески выгодным магазином по продаже камней.  
Задача системы – автоматизировать следующие процессы:  
1. Покупка товара. С помощью онлайн-заказа, пользователь может совершать покупку товара. Технические требования к пользовательскому интерфейсу:  
Просмотр каталога товара  
Возможность просмотра всех свойств товара  
Возможность онлайн-оплаты покупок  
Просмотр корзины покупок  
Просмотр истории покупок  
Персонализированные рекомендации на основе предыдущих покупок и покупок пользователей с похожим поведением  
2. Приём и обработка заказов. Система должна взаимодействовать с логистической службой и отправлять ей всю необходимую для осуществления доставки информацию, такую как:  
Название товара  
Количество товара 
Точный адрес доставки – город и пункт выдачи  
Дополнительную информацию об условиях доставки товара  
3. Закупка товара. Система должна взаимодействовать с логистической службой, чтобы определять количество недостающего товара и автоматически закупать его. Логистическая служба должна отправлять информацию о количестве каждого вида товара на складе, на основе чего система в полуавтоматическом режиме с помощью интерфейса закупок и ответственного за закупки должна осуществлять запрос в логистическую службу на закупку товара.  
4. Доставка товара. Система должна взаимодействовать с ресурсами логистической службы: получать информацию о статусе доставки товара для того, чтобы сообщать её покупателю.  
5. Возврат товара: Если пользователя не устроил товар, то система должна обрабатывать его возврат - делать соответствующие записи в базы данных, сопровождать возврат средств; согласно описанию соответствующего бизнес-процесса.
## Метрики качества
За основу взят стандарт ISO/IEC 9126  
1. Эффективность:  
    - Сайт должен обслуживать без видимых замедлений около 150 тысяч пользователей ежемесячно и около 500 заказов. (При нормальной конверсии в 0.3-0.4% от общего количества посетителей)  
2. Удобство:  
    - Интерфейс сайта не должен отталкивать покупателей  
    - Время обучения пользованием внутреннего интерфейса системы для работников не должно превышать 2 часов  
3. Функциональность:  
    - Система должна соответствовать выше изложенным функциональным требованиям и выполнять все эти операции  
    - Система должна быть интероперабельной для всех внешних систем, к которым она должна быть подключена  
    - Безопасность – система должна соответствовать стандарту ISO/IEC 27001  
4. Ремонтопригодность:  
    - Система должна быть пригодна для обновления и изменения ПО по требованию заинтересованных сторон  
5. Переносимость:  
    - Система не должна быть привязана к специфичным технологиям хостинга, оплаты и разработки ПО, для того чтобы имелась возможность без особых усилий заменить как оборудование, на котором работает система, так и команду   поддержки ПО и оборудования.  


## Ссылка на макет
https://www.figma.com/file/fNnfCoxTaYQVdUub9OFBx2/Untitled?type=design&node-id=0%3A1&mode=design&t=L9bdKk4Me7nEnzDA-1

## Критика макета
https://docs.google.com/document/d/12VWFEz1BASJv5BKvC6Taj1sMLB4cnxp7r6hYHnpmu9g/edit?usp=sharing

## Ссылка на модели и диаграммы 
https://drive.google.com/file/d/1qti0p4eiksP_n_B6XOT3IIjgxSQeeDNo/view?usp=sharing_eip_se_dm&ts=65c63363 


## Бизнес процессы:
### Список обозначений: 
![symbols](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Условные_обозначения.PNG)

### Процессы:
![bpsecond](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Возврат_товара.PNG)
![bpthird](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Доставка_товара.PNG)
![bpfourth](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Закупка_товара.PNG)
![bpfifth](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Иневентаризация.PNG)
![bpsixth](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Онлайн_заказ_товара.PNG)
![bpseventh](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Оплата_товара.PNG)
![bpeightth](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Получение_и_хранение_товара.PNG)
![bpninth](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Прием_и_обработка_заказа.PNG)


## Контекстная диаграмма
Информация о взаимодействиях системы: https://docs.google.com/document/d/1LyJ6ZyQQuPcwKKIbPfOoMwiVOB9JGCCt3p7kMRVc148/edit?usp=sharing
![bpkd](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/blob/master/Reports/BuisnessProcess/Контекстная_диаграмма.PNG)

## Заинтересованные лица

![-O0CPcpX3EE](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/155570357/0df9b8ad-07af-46c6-a12c-5a6160b5e2be)

![7-q-6E5FSM4](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/155570357/9a211576-959c-4bd2-8f5d-d5995f448b79)

![O_r8VkRCJss](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/113982481/791287d8-2a9c-4351-bd49-0c1608482a40)
![1-z0V5HT1I8](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/113982481/aefc298f-b4b7-49e2-bdbe-4bb54896087c)
![9ONZY9KavR0](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/113982481/5e09692b-a87b-4e37-bae5-f9bce663d91c)
![qhf5fl0IJgk](https://github.com/Kirill-Bokov/I-ll-give-you-the-stone/assets/113982481/1bf5386a-d6c0-4613-8d05-eda5b008ca54)
