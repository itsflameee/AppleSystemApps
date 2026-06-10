# AppleSystemApps
[ [**RU**](https://github.com/itsflameee/AppleSystemApps/blob/main/README_ru.md) / [EN](https://github.com/itsflameee/AppleSystemApps/blob/main/README.md) ] 

Коллекция оригинальных системных .ipa приложений из iOS 18 с подробным списком совместимости для сайдлоада

## Что это?
В этом репозитории можно найти множество системных приложений, которые были предварительно извлечены из различных прошивок iOS.
Все тесты проводились на указанных в каждом списке устройствах, с указанной прошивкой, используя LiveContainer для сайдлоада всех системных приложений. Ниже будет приведён список приложений в виде таблицы.

## Совместимость
Все приложения из репозитория устанавливаются в LiveContainer, однако не все могут запускаться или функционировать должным образом. Для понимания работоспособности того или иного приложения обратитесь к списку приложений.
В списке приложений совместимость показывается в одноимённом столбце таблицы, ниже представлены варианты совместимости:

* **⭕ Не запускается** - приложение устанавливается в LiveContainer, и отображает метаданные, однако при попытке запустить вызывает краш контейнера.
* **🔴 UI не отрисовывается** - приложение запускается, однако UI не отрисовывается (чёрный или белый статичный экран).
* **🟠 Только неполный UI** - приложение отрисовывает UI с небольшими проблемами, функционал приложения недоступен.
* **🟡 Только UI** - приложение отрисовывает UI должным образом, однако функционал приложения недоступен.
* **🟢 Запускается** - приложение запускается, но ограничено по функционалу.
* **🔵 Работает** - приложение запускается, и функционирует с незначительными проблемами функционала или отрисовки UI.
* **🟣 Идеально** - приложение полностью функционирует.


## Список приложений
### из прошивки iPhone XS (18.7.9)

Эти приложения извлечены из прошивки [iPhone11,2,iPhone11,4,iPhone11,6_18.7.9_22H355_Restore.ipsw](https://ipsw.me/install/iPhone11,2/22H355/), тесты проводились на iPhone 14 Pro Max с iOS 18.6.2

| Иконка | Имя приложения | Имя пакета | Файл | Совместимость | Известные проблемы | Работающие функции | 
| :---: | --- | --- | --- | :-------: | --- | --- |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Phone%20Icon.png?raw=true" width="45" height="45"/> | Phone | com.apple.mobilephone | [MobilePhone.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/MobilePhone.ipa) | **🔵 Работает** | Вкладка "Автоответчик" недоступна, при попытке вызова iOS запросит подтверждение через всплывающее окно | Вызовы, добавление и чтение контактов |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Camera%20Icon.png?raw=true" width="45" height="45"/> | Camera | com.apple.camera | [Camera.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Camera.ipa) | **🟢 Запускается** | Снятые фото/видео не сохраняются в память устройства, использование киноэффекта/режима портрета вызывает вылет | Отображение камеры устройства, переключение объективов, просмотр сохранённых ранее фото/видео, визуальный ProRAW/ProRES, Action Mode |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Settings%20Icon.png?raw=true" width="45" height="45"/> | Settings | com.apple.preferences | [Preferences.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Preferences.ipa) | **⭕ Не запускается** | Приложение вылетает, отрисовав только первые кадры | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Siri%20Icon.png?raw=true" width="45" height="45"/> | Siri | com.apple.siri | [Siri.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Siri.ipa) | **🔴 UI не отрисовывается** | При запуске UI не отображается, однако приложение не вылетает | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Calculator%20Icon.png?raw=true" width="45" height="45"/> | Calculator | com.apple.calculator | [Calculator.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Calculator.ipa) | **🟣 Идеально** | Режим "Математические заметки" отказывается работать, ссылаясь на отсутствие системного приложения заметок | Весь оригинальный функционал кроме "Математических заметок" |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/PosterBoard%20Icon.png?raw=true" width="45" height="45"/> | PosterBoard | com.apple.PosterBoard | [PosterBoard.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/PosterBoard.ipa) | **🟡 Только UI** | Не отображаются системные обои (так как их просто нет в рамках контейнера) | Базовый UI от обычного PosterBoard |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/App%20Store%20Icon.png?raw=true" width="45" height="45"/> | App Store | com.apple.AppStore | [AppStore.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/AppStore.ipa) | **🟡 Только UI** | В связи с отсутствием возможности войти в Apple ID функционал приложения отсутствует | Весь базовый UI |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Apple%20Vision%20Pro%20Icon.png?raw=true" width="45" height="45"/> | Apple Vision Pro | com.apple.visionproapp | [AppleVisionProApp.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/AppleVisionProApp.ipa) | **🔴 UI не отрисовывается** | При запуске UI не отображается, однако приложение не вылетает | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/FaceTime%20Icon.png?raw=true" width="45" height="45"/> | FaceTime | com.apple.facetime | [FaceTime.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/FaceTime.ipa) | **⭕ Не запускается** | Приложение вылетает, не успев отрисовать UI | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Files%20Icon.png?raw=true" width="45" height="45"/> | Files | com.apple.DocumentsApp | [Files.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Files.ipa) | **🟢 Запускается** | Файловая система iOS не отображается ни в каком виде | Сканирование документов, подключение к удалённому серверу |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/FindMy%20Icon.png?raw=true" width="45" height="45"/> | FindMy | com.apple.findmy | [FindMy.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/FindMy.ipa) | **⭕ Не запускается** | Приложение вылетает, не успев отрисовать UI | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Fitness%20Icon.png?raw=true" width="45" height="45"/> | Fitness | com.apple.Fitness | [Fitness.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Fitness.ipa) | **🔴 UI не отрисовывается** | При запуске UI не отображается, однако приложение не вылетает | Ничего |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Health%20Icon.png?raw=true" width="45" height="45"/> | Health | com.apple.Health | [Health.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Health.ipa) | **⭕ Не запускается** | Приложение вылетает, не успев отрисовать UI | При первом запуске запрашивает доступ к данным системного приложения "Здоровье" |
