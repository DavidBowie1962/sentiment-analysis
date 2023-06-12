# sentiment-analysis
В данном репозитории представлен проект предсказания доходности с учетом индекса сентимента (настроения) инвесторов в Телеграме и Пульсе

**Проект содержит:**
- I. CATBOOST MODEL.ipynb содержит создание модели для анализа сентимента, а так же тестирование других моделей
- II. TG AND PULSE_SENTIMENT.ipynb (В данном файле происходит обработка сообщений из соцсетей и присваивание сентимента каждому сообщению)
- III. MERGE DATA AND PREDICT RETURN.ipynb (В данном файле происходит объединение данных технических сигналов и сентимента)
- IV and V. Файлы Pulse.py, Telegram.py позволяют парсить данные из соцсетей

**Для работы с проектом рекомендуется**
1. Скачать уже готовую модель catboost. Либо обновить ее, запустив I. CATBOOST MODEL.ipynb.
2. Скачать файлы с данными из соцсетей и технические данные
3. Добавить путь к файлам в TG AND PULSE_SENTIMENT.ipynb, выполнить файл
4. Запустить III. MERGE DATA AND PREDICT RETURN.ipynb и получить результаты
