# Анализ рынка компьютерных игр
`Gamedev`  `Маркетинг-аналитика`
### Данные 
Исторические данные из открытых источников о продажах игр, оценках пользователей и экспертов, жанрах и платформах.

### Задача   
Выявить закономерности, определяющие характеристики потенциально прибыльной игры, чтобы спланировать рекламные кампании на 2017 год.

### Навыки и инструменты
`Python`  · `EDA` ·  `Statistics` ·  `Pandas` · `Scipy` · `Seaborn` ·  `Matplotlib`

---

### Результаты исследовательского анализа данных

**Потенциально прибыльные платформы:**  
`PS4` и `XOne` (у второй продажи почти в двое меньше относительно первой). 
Обе находятся в стадии роста с 2013 года, то есть рост прогнозируется и в 2017 году  
(Средняя продолжительность игровой платформ составляет 11 лет: 4 года роста + 5 лет пик популярности)

**Потенциально прибыльные жанры:**  
`Shooter` - популярный с самыми высокими объёмами продаж жанр   
`Action` - самый популярный жанр (доля ~34%)   
`Sport` - популярный с высокими продажами жанр

**Оценка критиков:**  
Высокие продажи более 1 млн копий имеют игры с высокими оценками критиков - не менее 50 единиц.

**Составлен портрет пользователя каждого региона**  

Портреты пользователе из Северной Америки и Европы похожи и соответствуют общим описанным выше тенденциям, а портрет пользователя из Японии сильно отличается.

Если рекламная кампания направлена на регионы Сев.Америка и Европа, наиболее прибыльными будет игра:

- platform: `PS4`, `XOne` и затухающая `X360`
- genre: `Action` и `Shooter`, `Sport`
- rating: `M` "Для взроослых"
  
Если на японский рынок:
- platform: `3DS`, `PS3`, `PSV`
- genre: `Role-Playing`, `Shooter`
- rating: `T` "Для продростков".
