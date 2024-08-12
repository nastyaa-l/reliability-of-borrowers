# Исследование надёжности заёмщиков

### Опсиание проекта 
На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о
данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.

### Задача: 
На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.

### Инструменты: 
предобработка данных, Python, Pandas

### Ключевые слова: 
обработка данных, дубликаты, пропуски, категоризация, декомпозиция

### Выводы
На первом этапе мы выявили и заполнили мединными значенимяи пропуски. Удалили дубликаты в данных. А также добавили категории уникальных целей взятия кредита и категории по доходу.

На втором этапе оценили зависимость между возвратом кредита и разными показателями и пришли к следующим выводам:
<br> 1) Cемьи, которые не имеют детей чаще вовращают кредиты в срок, чем семьи с двумя детьми.
<br> 2) Cостоящие или состоявшие в браке заемщики реже допускают просрочки.
<br> 3) Люди с более высоким уровнем дохода лучше всего выплачивают кредит в срок.
<br> 4) Лучше всего возвращают кредиты, взятые на недвижимость и свадьбу, хуже - на автомобили и образоввание.
<br>Таким образом, надежный заемщик: человек, состоящий или состоявший в браке, без детей, с высоким доходом и желанием взять кредит на свадьбу или недвижимость. При этом рисковый заемщик: холостой человек и(или) же человек с несколькими детьми, невысоким уровнем дохода и желанием взять кредит на автомобиль или образование.

Анализ данных усложняется неравномерной выборкой, из-за этого снижается его точность. Для более подробного анализа рекомендуется улучшить сбор данных, увеличить количество респондентов в малочисленных группах. 
