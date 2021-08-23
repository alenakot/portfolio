# Проект "Изучение закономерностей, определяющих успешность игр"

**Цель:** Есть исторические данные о продажах игр на различных платформах. На основании этих данных надо сделать предположение о том, что будет в 2016-2017 годах.

**Описание данных**

- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

**Используемые библиотеки**

pandas 
matplotli
seaborn
numpy
scipy

**Выводы**

Выявлены параметры, определяющие успешность игры в разных регионах мира. Проведена предобработка данных, анализ. Выбран актуальный
период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовала критерий Стьюдента для независимых выборок.