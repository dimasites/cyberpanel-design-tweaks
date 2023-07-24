# CyberPanel настройки внешнего вида (Design Tweaks)

Из коробки панель свёрстана так, что на русском языке многое разъезжается или выглядит криво. Настало время исправить это за пару кликов и один копипаст!

## Последняя версия всех твиков - в CSS файле:
→ **css/all-tweaks.css**: https://github.com/dimasites/cyberpanel-design-tweaks/blob/dimasites-patch-1/css/all-tweaks.css

Выглядеть будет вот так:
![image](https://github.com/dimasites/cyberpanel-design-tweaks/assets/5102558/328de663-1d91-4fd4-b9da-a6f15edd4ccd)
(сравните с таким же экраном из коробки и всё станет ясно)

Если коротко, что сделано: выключенн показ (просто скрыты через CSS) платные функции, ссылки на ютуб-каналы и т.п. чтобы панель выглядела немного больше похожей на готовый рабочий продукт (чем она и является), а не на тестовый проект энтузиастов-экспериментаторов.

### Как использовать
Просто добавить через админку [CSS-код из этого файла](https://github.com/dimasites/cyberpanel-design-tweaks/blob/dimasites-patch-1/css/all-tweaks.css) в меню Design, и он инкапсулируется в эту же самую админку:

![photo_2023-07-24_21-36-57](https://github.com/dimasites/cyberpanel-design-tweaks/assets/5102558/3d7615b6-e09d-451f-9e7f-e98d48acaf7e)

### Как отключить
Чтобы отключить, код просто надо стереть код в меню Design или закомментировать

### Часто задаваемые вопросы
Вопрос: А где логотип CyberPanel?
Ответ: Нн был из коробки растровый (.png вместо .svg), тёк пикселями и это меня раздражало, вот я его и скрыл. Кому надо - можете вернуть, просто отключив соответствующую секцию в CSS.

### Поддержка и участие
Ставьте звёзды, делайте форки, скриншоты кривой вёрстки и кидайте issue - я планирую поддерживать код в актуальном состоянии. и в результате "починить вёрстку" панели под русский язык (и другие языки, в которых фразы длиннее, чем английские) насколько это возможно. А может, это всё перерастет в "тему" для CyberPanel или PR в основную верстку... Давайте сделаем любимую панель более юзабельной, имхо - оно того стоит!
