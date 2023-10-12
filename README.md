Области хранения данных: - база данных на json-server - BFF - REDUX Store

    Сущности приложения:
    - пользовательЖ БД (список пользователей), BFF (сессия текущего), Store (отображение в браузере)
    - роль пользователя: БД (список ролей), BFF (сессия пользователя с ролью), Store (использование на клиенте)
    - статьяЖ БД (список статей), Store (отображение в браузере)
    - комментарийЖ БД (список комментариев), Store (отображение в браузере)

    Таблица БД:

    - пользователи - users: id / login / password / registered_at / role_id
    - роли - roles: id / name
    - статьи - posts: id / title / image_url / content / published_at
    - комментарии - comments: id / author_id / post_id content
