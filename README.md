# ![project_logo](./images/favicon.png) Научиться учиться

Первая практическая работа в рамках обучения по курсу **"Веб-разработчик плюс"** от [_Яндекс.Практикум_](https://practicum.yandex.ru/).

## Описание проекта
Одностраничный сайт по заданному в двух брифах макету.

Код проекта оптимизирован в соответствии с [_методологией БЭМ_][1] - принципа разделения интерфейса на независимые блоки

```HTML
  <!--наименование классов по принципу Блок__Элемент_Модификатор-->
  <footer class="footer">
    <div class="footer__columns">
      <div class="footer__column footer__column_content_copyright">
        <!--Блок__Элемент_Модификатор_ключ_значение1-->
        ...
      <div class="footer__column footer__column_content_info">
        <!--Блок__Элемент_Модификатор_ключ_значение2-->
        ...
      </div>
    </div>
  </footer>
```

с использованием [_Nested-схемы_][2] организации файловой структуры:

```
  blocks/
    footer/
      __column/
        _content/
          footer__column_content_copyright.css
          footer__column_content_info.css
      __columns/
        footer__columns.css
    footer.css
```

[1]: https://ru.bem.info/methodology/quick-start/

[2]: https://ru.bem.info/methodology/filestructure/#nested

## Технологии

1. **HTML**
   - синтаксис
   - семантика
   - структура HTML-документа
   - связь HTML и CSS
   - флексбокс-верстка

2. **CSS**
   - классы
   - свойства флекс-элементов
   - использование _[normalize.css](./vendor/normalize.css)_

3. **Markdown**<br>
Самостоятельное обучение разметке Markdown

## Инструментарий разработки

* **IDE:** [_Visual Studio Code_](https://code.visualstudio.com/)

* **VCS:** [_Git_](https://git-scm.com/) (*Git Bash*) с хостингом репозитория на [_GitHub.com_](https://github.com/)
<!--
Тип | Название | Версия
--- | --- | :---:
IDE | [Visual Studio Code](https://code.visualstudio.com/) | 1.61
VCS | [Git](https://git-scm.com/) (*Git Bash*) | 2.33
Host | [GitHub.com](https://github.com/) | -
-->
