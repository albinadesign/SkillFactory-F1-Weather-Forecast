# SkillFactory-F1-Weather-Forecast

нужно создать простейший сервис просмотра информации о погоде.

При создании сервиса нужно соблюсти следующие условия:
Необходимо использовать фреймворк React и адаптивный дизайн, чтобы страница открывалась на любом consumer-grade устройстве.
Пользователь должен либо иметь возможность выбрать из списка город, для которого ему нужен прогноз погоды.
Пользователь должен иметь возможность посмотреть данные на следующие временные промежутки:
«сейчас» (на день);
«ближайшие пять дней» (по дням на пять суток).
Данные должны запрашиваться через One Call API OpenWeather.

Загрузить проект:

1) окрываем новый проект в IDE

2) в терминале git clone https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast.git

3) cd SkillFactory-F1-Weather-Forecast

4) npm i

Запустить: npm start



При запуске проекта открывается окно, где можно ввести любой город на английском
<img width="1632" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/2b439ad4-af84-4d4b-9029-e0890ffa21a5">

При нажатии кнопки enter выдается погода на 1 день
<img width="1655" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/c718a804-9eda-402a-aec6-043a99c1fbe5">

При этом фон меняется в зависимости от температуры (для 15 гр и выше - оранжевые оттенки)
<img width="1659" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/9ca37ddc-040b-4769-814c-2efc6e5ee05b">

Также на странице появляется кнопка выбора погоды на 5 дней. Если на нее нажать:
<img width="1668" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/e166f75e-315d-46eb-801f-61b7134492f1">

Теперь на странице видна кнопка выбора погоды на 1 день - то есть можно переключаться между режимами. 

Дизайн адаптивный: при уменьшении экрана меняется расположение плашек с прогнозом погоды по дням:
<img width="1395" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/577fc3c3-ccf1-4e13-913a-00bca17afa5f">

<img width="668" alt="image" src="https://github.com/albinadesign/SkillFactory-F1-Weather-Forecast/assets/117900508/1e71bae1-58c5-4662-934a-a6586f9b98fe">






