# Документация

Игра "guess" - игра, в которой пользователь пытается отгадать слово по буквам

Функция *play* - основной игровой цикл. 
+ Программа выбирает случайное слово из файла со словами функцией *get_rand_word*
+ она дает 6 попыток на ошибки, 
+ после каждой попытки отрисовывается поле игры функцией *print_game*, 
+ также функция проверяет, все ли правильно введено функцией *get_letter*

Функция *get_rand_word* открывает файл со словами и выбирает оттуда случайное слово.

Функция *print_game* отрисовывает весь процесс игры на экране: 
![text](https://github.com/ildarishe/devman_2/blob/main/guess.gif?raw=true)

Функция *get_letter* позволяет вводить только допустимые буквы и не повторяться при вводе.
![](https://github.com/ildarishe/devman_2/blob/main/guess1.gif?raw=true)
