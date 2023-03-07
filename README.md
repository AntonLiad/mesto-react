**Mesto**

### на React

Была прославлена задача сделать замену приложения ins\*\*\* Пользователь может зайти, авторизоваться под своим именем и загрузить свои фотографии и подписать их 💜

Выполнены следующие задачи:

**_1. Контекст текущего пользователя_**
Данные текущего пользователя нужны в разных местах приложения: например, чтобы определить может ли пользователь удалять карточку.
Мы будем использовать контекст, чтобы все компоненты приложения могли получить доступ к этим данным.

1. Создайте стейт currentUser в корневом компоненте
2. Создайте объект контекста и используйте провайдер
3. Используем контекст в Main
4. Используем контекст в Card

**_2. Лайки и удаление карточек_**

1. Добавьте поддержку лайков и дизлайков
2. Добавьте поддержку удаления карточки

**_3. Редактирование профиля_**

1. Рефакторинг: Вынесите компонент EditProfilePopup
2. Добавьте управляемые компоненты
3. Используйте значения по умолчанию из currentUser
4. Сохраняйте данные в API

**_4. Редактирование аватара_**

1. Рефакторинг: Вынесите компонент EditAvatarPopup

**_5. Добавление новой карточки_**

1. Поднимаем стейт cards
2. Рефакторинг
3. Сохраните данные

**_Дополнительные функции_**

1. Сделано закрытие попапа вне поля

**_Дальнешние дорабртки_**

1. Сделать валидацию формы
2. При неверном вводе информации input, блокировать кнопку.
3. При нажатии на урну выводить окно с подтверждением удаления карточки