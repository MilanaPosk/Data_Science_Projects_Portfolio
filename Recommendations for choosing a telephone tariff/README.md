# Проект по рекомендации тарифов.
В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф.</font><br>
**Описание проекта:** Проанализировать поведение клиентов, оператора мобильной связи «Мегалайн», и предложить пользователям новый тариф.</font><br>
**Цель проекта:** Постройте модель с максимально большим значением accuracy, не менее 0.75.</font><br>
**План исследования:**</font><br>
1. Исследовать данные:
- импортировать библиотеки и методы
- проверить общую информацию по структуру данных и о показателях
2. Разделить исходные данные на выборки:
- разделить обучающую, валидационную и тестовую выборки;
- определить параметры признаков и целевой признака.
3. Исследовать качество разных моделей, меняя гиперпараметры:
- проверить на модели с решающим деревом;
- проверить на модели случайный лес;
- проверить на модели с логистической регрессией;
4. Проверьте качество модели на тестовой выборке:
- выбрать модель с наилучшим accuracy и проверить ее на тестовой выборке.
5. Проверить модель на вменяемость
