# Общие правила

1. В `application.css.sass` и `application.js.coffee` не использовать
`require_tree .` — иначе получится подгрузка всех доступных в проекте стилей и скриптов.
