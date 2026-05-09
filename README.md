# Исправление UI и механических ошибок работы мифических заклинаний для игры «Pathfinder: Wrath of the Righteous»

Мифические заклинания игры [Pathfinder: Wrath of the Righteous](https://store.steampowered.com/app/1184370/Pathfinder_Wrath_of_the_Righteous__Enhanced_Edition/) содержат множество неточностей и ошибок UI и механики. Данный мод для OMM (Owlcat Modifications Manager) является попыткой устранить эти ошибки и неточности.

Мод поддерживает русскую и английскую версии игры.

## Установка (для Windows)

1. Со страницы релизов скачайте архив с последней версией мода.
2. Перейдите в папку `%localappdata%low\Owlcat Games\Pathfinder Wrath Of The Righteous` (далее — папка игры).
3. Распакуйте из архива папку `Modifications` в папку игры.
4. Если в папке игры нет файла `OwlcatModificationManagerSettings.json`, то извлеките его в папку игры из архива.
5. Если в папке игры уже есть файл `OwlcatModificationManagerSettings.json`, то отредактируйте его: найдите массив `EnabledModifications` (или создайте на верхнем уровне, если его нет) и добавьте в него значение `Nieroo_WotRMythicSpellsFix`.
6. Если мод установлен правильно, то в игре при нажатии `Ctrl+M` в окне OMM можно увидеть название мода

## Список изменений

Ознакомиться со списком внесённых изменений можно в файле [CHANGELOG.md](https://github.com/Nieroo/WotRMythicSpellsFix/blob/main/CHANGELOG.md).
