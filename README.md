# Маяк

Сообщества, личные сообщения, голос, видео и трансляции. Официальные установщики и обновления клиента.

## Скачать alpha.87

- [Windows — установщик NSIS, x64](https://github.com/MerryGrim/mayak-releases/releases/download/v0.1.0-alpha.87/Mayak-Setup-0.1.0-alpha.87-x64.exe)
- [Debian / Ubuntu — x64](https://github.com/MerryGrim/mayak-releases/releases/download/v0.1.0-alpha.87/Mayak-0.1.0-alpha.87-amd64.deb)
- [Linux — архив, x64](https://github.com/MerryGrim/mayak-releases/releases/download/v0.1.0-alpha.87/Mayak-0.1.0-alpha.87-linux-x64.tar.gz)
- [Arch Linux — x86_64](https://github.com/MerryGrim/mayak-releases/releases/download/v0.1.0-alpha.87/Mayak-0.1.0-alpha.87-archlinux-x86_64.pkg.tar.zst)
- [Рецепт и инструкция Arch](https://github.com/MerryGrim/mayak-releases/releases/download/v0.1.0-alpha.87/Mayak-0.1.0-alpha.87-archlinux-packaging.zip)

[Описание выпуска](https://github.com/MerryGrim/mayak-releases/releases/tag/v0.1.0-alpha.87) · [Предыдущий выпуск alpha.86](https://github.com/MerryGrim/mayak-releases/releases/tag/v0.1.0-alpha.86)

## Обновления

Откройте **Настройки → Приложение → О приложении** или пункт **О приложении** в меню пользователя. Здесь доступны установленная версия, проверка, скачивание с прогрессом и отменой, установка и настройки канала выпусков. Версия веб-интерфейса показана отдельно.

Обычная установка NSIS снова запускает Маяк после завершения. Обновление передаётся родительскому загрузчику, чтобы установщик продолжал работать после закрытия старого клиента. При ошибке запуска клиент остаётся открыт и показывает причину.

Для первого перехода с alpha.84 или более старого клиента скачайте установщик и установите его вручную в прежний каталог, предварительно закрыв Маяк. Для Inno alpha.85 также нужен ручной переход на NSIS. Ctrl+R обновляет только веб-интерфейс. В старых версиях кнопка в разделе «О приложении» открывает отдельные настройки клиента.

Манифест обновления подписан Ed25519; клиент проверяет подпись, размер и SHA-256 скачанного пакета. Установка начинается по нажатию и блокируется во время разговора. Подпись обновлений не заменяет проверку EXE защитой Windows.

Полная установка alpha.87 с повторным запуском на рабочем профиле и проверка на физическом Arch пока не выполнены.
