# Анализ и прогнозирование метрик юнит-экономики мобильного приложения для сканирования документов

Приложение - мобильная утилита для сканирования документов. Модель монетизации подписочная, есть пробный период 7 дней с дальнейшим переходом в оплату 4.99 USD в неделю

## Задачи проекта
1. Необходимо рассчитать текущий LTV юзера, используя когортный анализ (cohorting event - оформление пробного периода, когорта представляет собой кол-во возможных операций).
2. Спрогнозировать, каким будет LTV на полгода.
3. Построить график, который будет отображать кривую фактического LTV на фоне кривой прогнозируемого LTV.
4. Рассчитать ROMI на 4 недели и спрогнозировать его на полгода, если стоимость привлечения платящего пользователя 6 USD

## Описание данных

Каждая строка представляет собой отдельное событие (либо оформление пробной подписки, либо оплата после завершения пробного периода)

- `product_id` - идентификатор оформленной подписки
- `quantity` - количество оформленных подписок
- `is_trial_period` - является ли оформленная подписка пробной
- `purchase_date` - дата оформления подписки
- `user_id` - идентификатор пользователя
