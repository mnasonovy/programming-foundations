# Установка Git на Windows

---

Git — это распределённая система контроля версий, которая используется
для управления исходным кодом, командной работы и хранения проектов.
Она лежит в основе таких платформ, как GitHub, GitLab и Bitbucket.

В этом гайде мы установим **Git for Windows** и настроим рекомендуемые параметры.

---

## 1. Переход на официальный сайт

Откройте официальный сайт Git:

👉 https://git-scm.com

На главной странице нажмите кнопку **Install for Windows**.

![img.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img.png)
---

## 2. Загрузка установщика

После перехода на страницу установки для Windows:

- Нажмите ссылку для загрузки **Git for Windows (x64)**
- Дождитесь завершения загрузки
- Запустите скачанный `.exe` файл

![img_1.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_1.png)
---

## 3. Запуск установщика

После запуска установщика:

- Ознакомьтесь с лицензией **GNU General Public License**
- Нажмите **Next**

(Ничего менять здесь не нужно)

![img_2.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_2.png)
---

## 4. Выбор компонентов

На этапе **Select Components** рекомендуется оставить настройки по умолчанию:

✔ Windows Explorer integration  
✔ Open Git Bash here  
✔ Open Git GUI here  
✔ Git LFS (Large File Support)  
✔ Associate `.git*` files  
✔ Associate `.sh` files  
✔ Add a Git Bash profile to Windows Terminal  
✔ Scalar

Нажмите **Next**.

![img_3.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_3.png)
---

## 5. Выбор редактора по умолчанию

На шаге **Choosing the default editor used by Git**:

Рекомендуемый вариант:
- **Use Vim as Git's default editor** (оставляем как есть)

> ⚠️ Редактор используется редко (например, при merge-конфликтах).
> В дальнейшем можно поменять его на VS Code или любой другой.

Нажмите **Next**.

![img_4.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_4.png)
---

## 6. Имя начальной ветки

На шаге **Adjusting the name of the initial branch**:

Рекомендуемый вариант:
- **Let Git decide** (по умолчанию)

> В современных проектах чаще используется `main`,
> но GitHub автоматически приведёт всё к нужному формату.

Нажмите **Next**.

![img_5.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_5.png)
---

## 7. Настройка PATH

На шаге **Adjusting your PATH environment** выберите:

✅ **Git from the command line and also from 3rd-party software (Recommended)**

Это позволит:
- использовать Git в Git Bash
- использовать Git в PowerShell / CMD
- работать с Git из Visual Studio

Нажмите **Next**.

![img_6.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_6.png)
---

## 8. Выбор SSH-клиента

На шаге **Choosing the SSH executable**:

Рекомендуемый вариант:
- **Use bundled OpenSSH**

Нажмите **Next**.

![img_7.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_7.png)
---

## 9. HTTPS backend

На шаге **Choosing HTTPS transport backend**:

Рекомендуемый вариант:
- **Use the native Windows Secure Channel library**

Это обеспечивает корректную работу с сертификатами Windows.

Нажмите **Next**.

![img_8.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_8.png)
---

## 10. Настройка переводов строк

На шаге **Configuring the line ending conversions**:

Рекомендуемый вариант:
- **Checkout Windows-style, commit Unix-style line endings**

Это стандарт для Windows и кроссплатформенных проектов.

Нажмите **Next**.

![img_9.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_9.png)
---

## 11. Терминал для Git Bash

На шаге **Configuring the terminal emulator**:

Рекомендуемый вариант:
- **Use MinTTY (the default terminal of MSYS2)**

Нажмите **Next**.

![img_10.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_10.png)
---

## 12. Поведение `git pull`

На шаге **Choose the default behavior of `git pull`**:

Рекомендуемый вариант:
- **Fast-forward or merge**

Это наиболее безопасный и понятный вариант для новичков.

Нажмите **Next**.

![img_11.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_11.png)
---

## 13. Credential Helper

На шаге **Choose a credential helper**:

Рекомендуемый вариант:
- **Git Credential Manager**

Он отвечает за безопасное хранение логинов и токенов GitHub.

Нажмите **Next**.

![img_12.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_12.png)
---

## 14. Дополнительные опции

На шаге **Configuring extra options**:

Рекомендуется:  
✔ Enable file system caching  
✖ Enable symbolic links (можно оставить выключенным)

Нажмите **Install**.

![img_13.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_13.png)
---

## 15. Завершение установки

Дождитесь окончания установки.

На финальном экране:
- можно снять галочку **View Release Notes**
- нажмите **Finish**

![img_14.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_14.png)
🎉 Git успешно установлен.

---

## 16. Проверка установки (рекомендуется)

Откройте **Git Bash** и выполните команду:

```
git --version
```

![img_15.png](../Скриншоты/git%20%26%20github/Установка%20Git%20на%20Windows/img_15.png)
