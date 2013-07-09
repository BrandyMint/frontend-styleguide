## Управляем frontend-компонентами и зависимостями

Twitter Bower :: http://bower.io

Настройки — в .bowerrc

Список пакетов — в bower.json

Установленные компоненты:

```
bower list
```

Установить компоненты из bower.json:

```
bower install
```

Поиск по bower-репозиториям:

```
bower search
```

Требуется подключение компонентов в application, как и раньше. Если файлы не подгружаются, то надо поискать их в vendor/assets/components/ и прописать пути в application.
