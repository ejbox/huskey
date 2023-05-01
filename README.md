# Про Huskey
Huskey - программа для расшифовки марок сталей, чугунов, бронзы. Планируется возможность построения графика "железо-углерод" по стали.
На данный момент программа поддерживает только марки чугунов. Позже будет добавлена поддержка выше указанных материалов.

huskey-cli - консольное приложение.

huskey-gui - приложение с графическим интерфейсом на tkinter и ttkbootstrap.

## Установка
Для того чтобы запустить huskey-gui необходимо установить pip.
После установки pip выполните команду:
```
pip3 install tkinter
pip3 install ttkbootstrap
(Для Linux/macOS)
```
```
pip install tkinter
pip install ttkbootstrap
(Для Windows)
```
После установки tkinter вы можете запустить программу как любой другой python файл.
Планируется добавление чистого .exe файла под Windows.

### Поддерживаемый функционал
 - [X] Марки чугуна
 - [X] Марки стали
 - [ ] Марки бронзы
 - [ ] Диаграмма 'железо-углерод'
