1. **В данном проекте мы применяем модели машинного обучения для того, чтобы промышленное предприятие работало более эффективно. Полученая модель должна предсказывать коэффициент восстановления золота из руды. То есть модель должна помогать оптимизировать производство, уменьшая при этом убытки.**
----------------------------------------
2. **ОПИСАНИЕ ДАННЫХ:** 
Технологический процесс:
- Rougher feed — исходное сырье
- Rougher additions (или reagent additions) — флотационные реагенты: Xanthate, Sulphate, Depressant
  - Xanthate — ксантогенат (промотер, или активатор флотации);
  - Sulphate — сульфат (на данном производстве сульфид натрия);
  - Depressant — депрессант (силикат натрия).
- Rougher process (англ. «грубый процесс») — флотация
- Rougher tails — отвальные хвосты
- Float banks — флотационная установка
- Cleaner process — очистка
- Rougher Au — черновой концентрат золота
- Final Au — финальный концентрат золота
Параметры этапов:
- air amount — объём воздуха
- fluid levels — уровень жидкости
- feed size — размер гранул сырья
- feed rate — скорость подачи
----------------------------------------
3. **ОСНОВНЫЕ ПУНКТЫ И ЦЕЛИ ИССЛЕДОВАНИЯ:**
- Предобработать данные, и провести анализ данных;
- Построить и обучить модель.
----------------------------------------
4. **ИСПОЛЬЗУЕМЫЕ БИБЛИОТЕКИ:**
- *pandas;*
