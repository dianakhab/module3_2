[module_3_2.txt](https://github.com/user-attachments/files/16644884/module_3_2.txt)# module3_2
[Uploading modudef 
send_email(message, recipient, sender = "university.help@gmail.com"):
    valid_domains = ('.com', '.ru', '.net')
    if ("@" not in sender or not sender.endswith(valid_domains)) or \
            ("@" not in recipient or not recipient.endswith(valid_domains)):
        print(f"Невозможно отправить письмо с адреса {sender} на адрес {recipient}")
        return
    if message == recipient:
        print("Нельзя отправить письмо самому себе!")
        return
    if sender == "university.help@gmail.com":
        print(f"Письмо успешно отправлено с адреса {sender} на адрес {recipient}")
    else:
        print(f"НЕСТАНДАРТНЫЙ ОТПРАВИТЕЛЬ! Письмо отправлено с адреса {sender} на адреc {recipient}.")

send_email('Это сообщение для проверки связи', 'vasyok1337@gmail.com')
send_email('Вы видите это сообщение как лучший студент курса!', 'urban.fan@mail.ru', sender='urban.info@gmail.com')
send_email('Пожалуйста, исправьте задание', 'urban.student@mail.ru', sender='urban.teacher@mail.uk')
send_email('Напоминаю самому себе о вебинаре', 'urban.teacher@mail.ru', sender='urban.teacher@mail.ru')
le_3_2.txt…]()
