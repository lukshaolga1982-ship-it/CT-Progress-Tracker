<<<<<<< HEAD
# CT Progress Tracker

Готовый трекер для GitHub Pages и Firebase Firestore.

## Перед публикацией

1. В Firebase Authentication включите Email/Password.
2. В разделе Users создайте пользователя `lukshaolga982@gmail.com`.
3. Скопируйте содержимое `firestore.rules` во вкладку Firestore Database → Rules и нажмите Publish.
4. Загрузите `index.html`, `style.css` и `app.js` в корень репозитория GitHub.
5. В Settings → Pages выберите Deploy from a branch, `main`, `/ (root)`.
6. В Firebase Authentication → Settings → Authorized domains добавьте домен вида `имя.github.io`.

Пароль преподавателя нигде в файлах не хранится.
=======
# CT Progress Tracker

Готовый трекер для GitHub Pages и Firebase Firestore.

## Перед публикацией

1. В Firebase Authentication включите Email/Password.
2. В разделе Users создайте пользователя `lukshaolga982@gmail.com`.
3. Скопируйте обновлённое содержимое `firestore.rules` во вкладку Firestore Database → Rules и нажмите Publish. Оно разрешает всем просмотр, но редактирование — только вашему email.
4. Загрузите `index.html`, `style.css` и `app.js` в корень репозитория GitHub.
5. В Settings → Pages выберите Deploy from a branch, `main`, `/ (root)`.
6. В Firebase Authentication → Settings → Authorized domains добавьте домен вида `имя.github.io`.

Пароль преподавателя нигде в файлах не хранится.

Посетители открывают сайт сразу в режиме просмотра. Кнопка «Войти как преподаватель» включает редактирование только после входа владельца.

Если в базе уже есть только часть подготовленных учеников, нажмите «Добавить недостающих». Сайт создаст только отсутствующие профили и сохранит имеющиеся результаты.
>>>>>>> d164b0d (Add public view and student avatars)
