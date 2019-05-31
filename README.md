# Требования к проекту
---

# Содержание

1. [Введение](#intro)  
1.1. [Назначение](#appointment)  
1.2. [Бизнес-требования](#business)  
1.2.1. [Исходные данные](#data)
1.3  [Аналоги](#analog)
2. [Требования пользователя](#requirements)  
2.1. [Программные интерфейсы](#interfaces)  
2.2. [Интерфейс пользователя](#ui)  
2.3. [Характеристики пользователей](#users)  
2.4. [Предположения и зависимости](#dependence)  
3. [Системные требования](#systemreq)  
3.1. [Функциональные требования](#functionalreq)  
3.2. [Нефункциональные требования](#nonfunctionalreq)  
3.2.1. [Атрибуты качества](#qa)  
3.2.2. [Требования к безопасности](#security)  


<a name = "intro"/>

# 1 Введение

<a name = "appointment"/>

## 1.1. Назначение
ISSZ - это десктопное приложение, которое является удобным для беспечиния работ органов по труду, занятости и социальной защите по следующим направлениям:
пенсионное обеспечение;
социальная поддержка населения в виде предоставления детских пособий;
предоставление семейного капитала;
адресная социальная помощь;
учет и распределение технических средств социальной реабилитации;
учет и распределение мест в домах-интернатах;
учет и распределение материальной помощи из средств Фонда социальной защиты населения и на оздоровление;
социальное обслуживание граждан.

<a name = "business"/>

## 1.2. Бизнес требования

Приложение представляет собой окно, предназначенное для просмотра и добавления информации по направлениям социальной защиты. Пользователь может создать базу, хранящую информацию о каждом гражданине или гражданке и назначений.
<a name = "data"/>

### 1.2.1. Исходные данные

Внедрение ISSZ позволит сотрудникам автоматизацию процессов назначения и выплаты пенсий, государственных пособий, адресной социальной помощи, учета льгот и гарантий, социального обслуживания, создание централизованного банка данных социальной защиты.

<a name = "requirements"/>

## 1.3. Аналоги

ГИССЗ- Государственная информацияонная система сициальной защиты.Основным недостатком является то, что система медлительна и труднопонимаема .

<a name = "analog"/>

# 2. Требования пользователя


<a name = "interfaces"/>

## 2.1 Программные интерфейсы

* Приложение должно предоставлять пользователю возможность создания нового дела на гражданина или гражданку .
* Приложение должно предоставлять пользователю возможность создания назначения на пенсионное обеспечение на гражданина или гражданки .
* Приложение должно предоставлять пользователю возможность назначения на социальную поддержку населения в виде предоставления детских пособий.
* Приложение должно предоставлять пользователю возможность назначения на предоставление семейного капитала.
* Приложение должно предоставлять пользователю возможность назначения адресная социальная помощь.
* Приложение должно предоставлять пользователю возможность  учета и распределение технических средств социальной реабилитации.
* Приложение должно предоставлять пользователю возможность учета и распределение мест в домах-интернатах.
* Приложение должно предоставлять пользователю возможность учета и распределение материальной помощи из средств Фонда социальной защиты населения и на оздоровление.
* Приложение должно предоставлять пользователю возможность социального обслуживание граждан .

<a name = "ui"/>

## 2.2. Интерфейс пользователя

Интерфейс пользователя представлен в виде mockup иллюстраций.


| Описание| Иллюстрация|
| :------: | :-------: |
| Основной экран приложения | ![Чат](/Images/chat.png) |
| Экран списка пользователей | ![Пользователи](/Images/userList.png) |
| Экран настроек | ![Настройки](/Images/settings.png) |
| Экран создания группы | ![Группа](/Images/createGroup.png) |
| Экран авторизации/регистрации пользователя | ![Регистрация](/Images/signIn.png) |



<a name = "users"/>

## 2.3. Характеристики пользователей

Разбиения на классы пользователей не предполагается. Все пользователи равны в своих правах и возможностях.


<a name = "dependence"/>

## 2.4. Предположения и зависимости

* Приложение будет некорректно работать на устройстве, версия Windows которого ниже, чем минимальная поддерживаемая версия, для которой осуществлялась разработка приложения.
* Приложение не будет приостанавливать свою работу, а также некорректно её завершать. 
* Приложению требуется постоянный доступ к файлам с записями о гражданах и гражданках.

<a name = "systemreq"/>

# 3. Системные требования

Для запуска данного приложения на персональном компьютере требуется, чтобы было предустановлено следующие программное обеспечение:

Операционная система семейства Windows начиная с Windows XP с пакетом обновления 2;
Платформа .NET Framework 3.0 или выше;


<a name = "functionalreq"/>

## 3.1. Функциональные требования

 --- | ---
Добавление записи  | Приложение должно предоставить пользователю возможность добавления записи  с заданными параметарми, при нажатии на кнопку "Ввод"
Удаление записи  | Приложение должно предоставить возможность удаления определённой записи, при нажатии на клавишу "Удалить"
Изменение записи | Приложение должно предоставить возможность изменения записи, при нажатии на клавишу "Редактировать"
Поиск записи | Приложение должно предоставить возможность поиска определённой записи, при нажатии на клавишу "Найти"
Вывод с определенными параметрами | Приложение должно предоставить возможность вывода с определенными параметрами 
Отмена последней операции | Приложение должно предоставить возможность отмены последней операции

<a name = "nonfunctionalreq"/>

## 3.2. Нефункциональные требования


<a name = "qa"/>

### 3.2.1. Атрибуты качества

Атрибуты, важные для пользователей:
1. Доступность. Приложение должно быть доступно для пользователей круглосуточно.
2. Удобство и простота использования.
3.Загрузка и отображение основного окна программы не должны превышать 5 секунд.  

Атрибуты, важные для разработчиков:

4. Легкость в эксплуатации
5. Тестируемость. Максимальная цикломатическая сложность модуля (количество логических ответвлений в модуле исходного кода) не должна превышать 50.


<a name = "security"/>

### 3.2.2. Требования к безопасности

Надежное функционирование автоматизированной системы должно быть обеспечено выполнением организационно-технических мероприятий, таких как:

- использование лицензионного программного обеспечения;
- организация бесперебойного питания путем использования блоков бесперебойного питания;

