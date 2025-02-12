---
title: "Как добавить параметр в датасет"
description: "Следуя данной инструкции, вы сможете добавить параметр в датасет."
---

# Добавление параметра в датасет

{% note info %}

Параметры, добавленные на уровне датасета, доступны во всех чартах, созданных над этим датасетом.

{% endnote %}

Чтобы добавить в датасет [параметр](../../concepts/parameters.md):


{% include [datalens-workbooks-collections-select-note](../../../_includes/datalens/operations/datalens-workbooks-collections-select-note.md) %}


1. На панели слева нажмите ![image](../../../_assets/datalens/datasets.svg) **Датасеты** и выберите нужный датасет. Если у вас нет датасета, [создайте его](create.md).
1. В верхней части экрана переключитесь на вкладку **Параметры**.
1. Нажмите кнопку **Добавить**.
1. В окне **Добавление параметра** введите:

   * **Название**. Задает название параметра.
   * **Тип**. Определяет тип данных параметра: **Дата**, **Дата и время**, **Дробное число**, **Логический**, **Строка** или **Целое число**.
   * **Значение по умолчанию**. Заполняется обязательно. Используется в случаях, когда значение параметра не определено на дашборде, в URL чарта или в настройках самого чарта.

1. Нажмите кнопку **Добавить**.

Также вы можете создать параметры [на уровне чарта](../chart/add-parameter-chart.md).
