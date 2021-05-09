# sr_xsd_schemes
XSD схемы для xml фалов в игре SnowRunner.

# Как использовать (VS Code)
Установите [анализатор](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) XML фалов от Red Hat.

Добавьте в начало файла данную строку 
```xml
<?xml-model href="https://verzsut.github.io/sr_xsd_schemes/truck.xsd" type="application/xml" schematypens="http://www.w3.org/2001/XMLSchema"?>
```

Преимущества:
- Автоматитческая валидация.
- Документация при наведении на тег/атрибут.
- Подсказки необходимых тегов.
- Автовставка обязательных значений.
- Подсказки для ограниченных полей.

Минусы:
- Не поддерживаются теги _templates и _parent.
- Не проверяется валидность идентификаторов.
