# API-VK-POSTMAN
Отправка комментария к фото вконтакте через постман.

Задача: С помощью API VK и Postman отправить комментарий к фото в VK.(https://vk.com/album189704458_0?z=photo189704458_303057922%2Falbum189704458_0%2Frev)

Шаги:
# 💻1.Нужно создать приложение в ВК.
  1. Перешел по ссылке https://dev.vk.com/ru/mini-apps/management/creating-new-apps?ref=old_admin_panel
  2.  Созданть приложение  тип Standalone-приложение(лучший способ в нашем случае)
  3.  Нужно отдельно сохранить ID приложения (для удобства)

 # 📩2. Получение access токена.
  1. Собрал URL  https://oauth.vk.com/authorize?client_id="ID приложения"&display=page&scope=photos,wall,offline&response_type=token&v=5.199
  2. Подставим наш ID приложения.
  3. В методе "scope=photos,wall,offline" подставим нужные доступы документация [здесь](https://id.vk.com/about/business/go/docs/ru/vkid/latest/vk-id/connection/work-with-user-info/scopes).
  4. Посмотреть актуальную версию API VK(здесь https://dev.vk.com/ru/reference/versions)
   

