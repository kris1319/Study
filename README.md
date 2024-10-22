# Purposes and Current Progress

Здесь находятся текущие планы и цели, а также прогресс по их выполнению.
Схема моей отчетности тут будет следующей:

1. Каждое воскресенье я составляю план на следующую неделю. В него входят:
  
  * цель/задача
  * краткое описание, алгоритм действий
  * жесткий дедлайн
  
2. По мере выполнения в течение недели и в заданные дедлайны я делаю коммит с мини-отчетом.
3. В конце каждой недели подвожу итог о проделанной работе. 

Репозиторий создан как для отчетности научному руководителю о ходе работы, так и в значительной доле для самоконтроля.

## 06.03 - 12.03

Статьи из директории articles делятся на две категории: обработка сигнала ЭЭГ и применение машинного обучения (иногда и глубинного обучения) для задач классификации. На текущий момент все статьи прочитаны и осмысленны, в процессе написания два отчета, а также работа с данными ЭЭГ и опробование разных методов обработки сигналов. Поэтому план таков:

- [x] Подробное описание методов предобработки сигналов и получения признаков (наиболее распространенные, описанные в статьях, методы используемые в соревнованиях). Дедлайн (тк документ в процесе написания): вторник 07.03.
- [x] Структурированный анализ прочитанных статей: основные идеи, задачи, алгоритмы. Собственные выводы. 08.03.
- [ ] Поработать с матлабом и датасетами ЭЭГ (https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html).
- [ ] Запрогать алгоритмы из первого пункта и выложить ноутбук. 10.03.
- [ ] Сформулировать потенциальные области и задачи исследования.
________________________________________________________________________________________________________________________
Пора сделать выводы по прошедшей неделе (к тому же, сроки прошли два дня назад).
Итоги состоят из двух блоков: прогресс по задачам и наблюдения о самом процессе работы.

### Прогресс по задачам
* Нашла и изучила отличные статьи со структурированными знаниями об основных методах обработки ЭЭГ и извлечения признаков. Здесь сразу несколько пунктов:
  - понятие фильтров, преобразование Фурье, Лапласа и тд
  - PCA/ICA, их разница и приложения 
  - Common Spatial Patterns
  - xDAWN
  - составила структурированный обзор (лежит в reports)
* Получила более полное представление по разным типам BCI, почти сложился собственный взгляд на то, что я хотела бы делать дальше по курсовой.
* Почитала еще парочку статей про разные фишки с ЭЭГ, но все они используют стандартные алгоритмы, которые охватывает первый пункт.
* Гляжу на данные, ищу датасеты, пишу код (который надо причесать и выложить).

### Замечания к процессу работы
* Пыталась писать отчеты в техе, выходит долго и бесполезно. Так, потратила много времени на часть 1 пункта из предыдущего параграфа, хотя материал усваивается в разы быстрее с заметкам на листике. Больше так пока не буду, только уже какие-то более формальные документы.
* Статьи мне удобней всего читать параллельно с составлением заметок: какие-то факты, итоги гугления и тд. 
* С тайм-менеджментом пока не очень хорошо, но я с этим постепенно справляюсь. В рабочий процесс уже втянулась, каждый день что-то делаю по научке.
* Решила, что даже если жесткий тайм-лайн не соблюдается, то все равно он помогает поддерживать темп работы.
________________________________________________________________________________________________________________________

## 15.03 - 19.03
- [ ] Поработать с матлабом и датасетами ЭЭГ (https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html).
  - [ ] Запрогать алгоритмы из первого пункта и выложить ноутбук.
- [ ] Сформулировать потенциальные области и задачи исследования.
