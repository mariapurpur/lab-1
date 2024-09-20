## Лабораторная работа 1
### Выполнила Суханова Мария (467635, K3160)

Я начала выполнение работы с ознакомления с работой терминала на Linux Mint по инструкции, указанной в изначальном файле readme.

1. Создала новый файл с именем `script.bash`

![scr1](https://github.com/user-attachments/assets/e9533bed-c6e4-4813-95d3-d160fd3cfbed)

2. Открыла созданный файл `script.bash` для редактирования при помощи команды `xed`.

![scr2](https://github.com/user-attachments/assets/bd9f11ac-58fc-4002-bc7e-41a0aa60fc8a)

3. Впишисала предоставленный в лабораторной работе скрипт.

![scr3](https://github.com/user-attachments/assets/acf335ff-f257-46c3-b5e8-3257e2d2ac41)

4. Сохранила и закрыла текстовый редактор, а затем запустила bash-скрипт через терминал. Получился вывод "Welcome to IMTO University".

![scr4](https://github.com/user-attachments/assets/4a400cc3-5dff-4a57-b0a2-11e5cf1ba3fa)

## Выполнение задачи 1

Условия задачи следующие:

*Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде*

```bash
bash script.bash Vasya Pupkin
```

*Вывод был*

`Welcome, Vasya Pupkin`

*Hint: Скрипт должен работать для любых имен, даже если это Benedict Timothy Carlton Cumberbatch.*

Для решения этой задачи понадобится составить код так, чтобы "Welcome, " оставалось статичным при любом вводе, а введённое имя отображалось сразу после, каким бы оно ни было. Для исполнения этого я сделала следующее:

1. 
