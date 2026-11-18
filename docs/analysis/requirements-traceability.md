# Матрица трассируемости Must MVP

Источники: [реестр требований](requirements_moscow.md), [пакеты работ](../project/work-packages.md), [план разработки](../project/development-plan.md). Включены 57 требований Must из версии реестра от 17.11.2026.

Итерация означает готовность к проверке по плану. Когда для проверки нужно несколько компонентов, указана самая поздняя итерация их готовности. Сквозной прогон всех Must запланирован на итерацию 4. Связи с общими проверками не заменяют задачи реализации.

| Требование | Пакеты | Задачи | Проверки | Итерация |
|---|---|---|---|---|
| Т-01 Действия учебного отдела | WP-01 | 1C-05, 1C-03, 1C-04, 1C-07, 1C-08, 1C-10, 1C-11, 1C-13, 1C-14, 1C-15 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 2 |
| Т-69 Редактирование черновика | WP-01 | 1C-06, 1C-10, 1C-15, 1C-17 | [AT-008](../testing/acceptance-scenarios.md#at-008) | 3 |
| Т-02 Действия администратора расписания | WP-01 | 1C-05, 1C-13, 1C-14, 1C-17 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 3 |
| Т-03 Публичный просмотр без входа | WP-02, WP-03, WP-04 | API-05, DB-04, WEB-05, WEB-06, WEB-08 | [AT-012](../testing/acceptance-scenarios.md#at-012) | 3 |
| Т-04 Штатный вход в 1С | WP-01 | 1C-05 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 1 |
| Т-05 Настройка пользователей и ролей | WP-01 | 1C-05 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 1 |
| Т-06 Ошибка входа | WP-01 | 1C-05 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 1 |
| Т-09 Тестовые пользователи | WP-01, WP-05 | 1C-05, SYS-06 | [AT-001](../testing/acceptance-scenarios.md#at-001) | 4 |
| Т-10 CSV занятий и группы | WP-01 | 1C-08 | [AT-002](../testing/acceptance-scenarios.md#at-002) | 2 |
| Т-11 Дубли занятий | WP-01 | 1C-06, 1C-08 | [AT-002](../testing/acceptance-scenarios.md#at-002) | 2 |
| Т-64 Полная замена черновика импортом | WP-01 | 1C-04, 1C-08, 1C-15, 1C-17 | [AT-002](../testing/acceptance-scenarios.md#at-002) | 3 |
| Т-13 Атомарная проверка CSV | WP-01 | 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-14 Ошибки и итог импорта | WP-01 | 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-15 Начало раньше окончания | WP-01 | 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-16 Границы рабочего дня | WP-01 | 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-17 Ссылки на справочники | WP-01 | 1C-03, 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-18 Один преподаватель и одна аудитория | WP-01 | 1C-01, 1C-06, 1C-08 | [AT-002](../testing/acceptance-scenarios.md#at-002) | 2 |
| Т-19 Обязательная группа | WP-01 | 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-20 Существующие и уникальные группы | WP-01 | 1C-03, 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-65 Настраиваемая сетка пар | WP-01 | 1C-03, 1C-06, 1C-08 | [AT-003](../testing/acceptance-scenarios.md#at-003) | 2 |
| Т-21 Обычные и потоковые занятия | WP-01 | 1C-01, 1C-08 | [AT-002](../testing/acceptance-scenarios.md#at-002) | 2 |
| Т-22 Конфликт аудитории | WP-01 | 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-23 Конфликт преподавателя | WP-01 | 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-24 Конфликт группы | WP-01 | 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-25 Проверка всех групп потока | WP-01 | 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-26 Вместимость аудитории | WP-01 | 1C-08, 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-66 Правило пересечения и стык | WP-01 | 1C-11, 1C-12 | [AT-004](../testing/acceptance-scenarios.md#at-004) | 2 |
| Т-27 Сохранение полей конфликта | WP-01 | 1C-11, 1C-12, 1C-14 | [AT-005](../testing/acceptance-scenarios.md#at-005) | 2 |
| Т-28 Интервалы и состав конфликтов | WP-01 | 1C-11, 1C-12 | [AT-005](../testing/acceptance-scenarios.md#at-005) | 2 |
| Т-29 Проверка всего черновика | WP-01 | 1C-09, 1C-11, 1C-12 | [AT-005](../testing/acceptance-scenarios.md#at-005) | 2 |
| Т-30 Замена результатов проверки | WP-01 | 1C-10, 1C-11, 1C-12 | [AT-005](../testing/acceptance-scenarios.md#at-005) | 2 |
| Т-32 Детали отчёта | WP-01 | 1C-12, 1C-14 | [AT-006](../testing/acceptance-scenarios.md#at-006) | 2 |
| Т-33 Разбивка по датам и преподавателям | WP-01 | 1C-12, 1C-14 | [AT-006](../testing/acceptance-scenarios.md#at-006) | 2 |
| Т-34 Итоги по типам | WP-01 | 1C-12, 1C-14 | [AT-006](../testing/acceptance-scenarios.md#at-006) | 2 |
| Т-35 Доля сочетаний «группа–день» без конфликтов | WP-01 | 1C-12, 1C-14 | [AT-007](../testing/acceptance-scenarios.md#at-007) | 2 |
| Т-36 Фильтры отчёта | WP-01 | 1C-12, 1C-14 | [AT-006](../testing/acceptance-scenarios.md#at-006) | 2 |
| Т-37 Экспорт отчёта в CSV | WP-01 | 1C-14 | [AT-006](../testing/acceptance-scenarios.md#at-006) | 2 |
| Т-39 Передача на согласование | WP-01 | 1C-06, 1C-11, 1C-12, 1C-15, 1C-17 | [AT-010](../testing/acceptance-scenarios.md#at-010) | 3 |
| Т-40 Одобрение и возврат | WP-01 | 1C-15, 1C-16, 1C-17 | [AT-010](../testing/acceptance-scenarios.md#at-010) | 3 |
| Т-62 Состояния и запрет правок | WP-01 | 1C-08, 1C-10, 1C-15, 1C-17, 1C-18 | [AT-010](../testing/acceptance-scenarios.md#at-010) | 3 |
| Т-63 Единственный рабочий документ | WP-01, WP-02, WP-03 | 1C-04, 1C-08, 1C-17, 1C-18, API-04, DB-02, DB-03 | [AT-011](../testing/acceptance-scenarios.md#at-011) | 3 |
| Т-41 Публичное расписание и фильтры | WP-02, WP-03, WP-04 | API-05, DB-04, WEB-05, WEB-06, WEB-08 | [AT-012](../testing/acceptance-scenarios.md#at-012) | 3 |
| Т-42 Черновик и результаты в 1С | WP-01 | 1C-09, 1C-12, 1C-13, 1C-17 | [AT-008](../testing/acceptance-scenarios.md#at-008) | 3 |
| Т-45 Проверка 150+ занятий быстрее 3 секунд | WP-01, WP-05 | 1C-11, 1C-12, SYS-01, SYS-05 | [AT-016](../testing/acceptance-scenarios.md#at-016) | 4 |
| Т-50 Журнал запусков | WP-01 | 1C-11, 1C-12 | [AT-005](../testing/acceptance-scenarios.md#at-005) | 2 |
| Т-54 Синтетический набор 150+ | WP-05 | SYS-01 | [AT-015](../testing/acceptance-scenarios.md#at-015) | 2 |
| Т-56 Логика на платформе 1С | WP-01 | 1C-06, 1C-08, 1C-11, 1C-12, 1C-14 | [AT-015](../testing/acceptance-scenarios.md#at-015) | 2 |
| Т-57 Просмотр на сайте | WP-02, WP-03, WP-04 | API-05, DB-04, WEB-05, WEB-06, WEB-08 | [AT-012](../testing/acceptance-scenarios.md#at-012) | 3 |
| Т-58 Защищённая доставка и повторы | WP-01, WP-02, WP-03, WP-05 | 1C-16, 1C-17, 1C-18, API-02, API-03, API-04, DB-02, DB-03, SYS-03 | [AT-014](../testing/acceptance-scenarios.md#at-014) | 4 |
| Т-59 Публичное API и автономность просмотра | WP-02, WP-03, WP-04 | API-05, DB-04, WEB-08 | [AT-012](../testing/acceptance-scenarios.md#at-012) | 3 |
| Т-70 Недельный календарь 1С | WP-01 | 1C-09, 1C-10, 1C-11 | [AT-008](../testing/acceptance-scenarios.md#at-008) | 2 |
| Т-71 Импорт справочников | WP-01 | 1C-03, 1C-07, 1C-12, 1C-15 | [AT-009](../testing/acceptance-scenarios.md#at-009) | 2 |
| Т-72 Создание и копирование черновика | WP-01 | 1C-04, 1C-17 | [AT-011](../testing/acceptance-scenarios.md#at-011) | 3 |
| Т-73 Снимок согласования | WP-01 | 1C-03, 1C-15, 1C-16, 1C-17 | [AT-011](../testing/acceptance-scenarios.md#at-011) | 3 |
| Т-74 Актуальность результатов | WP-01 | 1C-07, 1C-08, 1C-10, 1C-11, 1C-12, 1C-13 | [AT-008](../testing/acceptance-scenarios.md#at-008) | 2 |
| Т-75 Переход от конфликта к занятиям | WP-01 | 1C-10, 1C-12, 1C-13, 1C-14 | [AT-008](../testing/acceptance-scenarios.md#at-008) | 2 |
| Т-76 Состояния публичного сайта | WP-02, WP-03, WP-04 | API-05, DB-04, WEB-03, WEB-08 | [AT-013](../testing/acceptance-scenarios.md#at-013) | 3 |
