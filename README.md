# Input - мини гайд


# Ur_text = переменная, в которую сохраняется то, что ввёл пользователь
# input() — команда для ввода текста от пользователя
# Внутри input("...") указывается приглашение (текст, который видит пользователь при вводе)

Ur_text = input("Напишите сюда что-либо: ")

# print — команда для вывода информации в терминал
# f перед кавычками означает, что внутри строки можно вставлять переменные через {имя_переменной}
# В данном случае {Ur_text} — то, что ввёл пользователь
# "," в print разделяет элементы, автоматически добавляя пробел между ними

print(f"{Ur_text}", "— Ваш текст")

