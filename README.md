Проекты:
1) userhome - Находит домашюю папку пользователя по /etc/passwd или специально заданному файлу.
   Usage: ./userhome [-f file] [username]

2) delolder - Удаляет все файлы: которые сущетсвуют более N дней из указанных катологов.
   Usage: ./delolder [-v|-d] N [--] dirs...

Тесты: см. папку tmp1 tmp2, команды:
  ./userhome
  ./delolder -d 365 tmp1 tmp2
