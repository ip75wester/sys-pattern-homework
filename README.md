# Домашнее задание к занятию "`8.1. Git`" - `Илья Попов`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

Что нужно сделать:

Зарегистрируйте аккаунт на GitHub.
Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
Склонируйте репозиторий, используя https протокол git clone ....
Перейдите в каталог с клоном репозитория.
Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
Выполните команду git status и запомните результат.
Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
Ещё раз выполните команды git diff и git diff --staged.
Теперь можно сделать коммит git commit -m 'First commit'.
Сделайте git push origin master.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/ip75wester/sys-hw/commit/073cde233a0ada0f0a15a57e253a407addc8b388
---

### Задание 2
Что нужно сделать:

Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
Добавьте файл .gitignore в следующий коммит git add....
Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
Сделайте коммит и пуш.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
https://github.com/ip75wester/sys-hw/commit/c42745e46d0e9773995e2c5d114755de7e8ec854
---

### Задание 3

Что нужно сделать:

Создайте новую ветку dev и переключитесь на неё.
Создайте файл test.sh с произвольным содержимым.
Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.
Сделайте коммит и пуш.
В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

### Задание 4

