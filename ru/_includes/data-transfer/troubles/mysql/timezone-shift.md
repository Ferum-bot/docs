### Сдвиг времени в типе данных DATETIME при трансфере в {{ CH }}

Сдвиг времени наблюдается, так как эндпоинт-источник применяет часовой пояс UTC+0 для данных с типом `DATETIME`. Подробнее см. в разделе [{#T}](../../../../data-transfer/operations/endpoint/source/mysql.md#known-limitations).

**Решение:** Примените нужный часовой пояс на уровне приемника вручную.
