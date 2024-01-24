# Клониране на хранилището локално
git clone https://github.com/вашето-потребителско-име/вашето-хранилище.git

# Влизане в директорията на проекта
cd вашето-хранилище

# Създаване на текстов файл и попълване с 10 произволни символа
echo "abcdefghij" > sample.txt

# Добавяне на промените, комитване и push
git add sample.txt
git commit -m "Add sample.txt with 10 characters"
git push origin master

# Създаване на нов клон
git checkout -b нов-клон

# Промяна в текстовия файл
echo "$(date) - change" >> sample.txt

# Добавяне, комитване и push
git add sample.txt
git commit -m "Change in нов-клон branch"
git push origin нов-клон

# Връщане в мастър branch
git checkout master

# Сливане на нов-клон branch
git merge нов-клон

# Отваряне на редактор за разрешаване на конфликтите
# (разрешавайте конфликтите във файла и запазвайте го)
git mergetool

# Добавяне и комитване на разрешението на конфликта
git add sample.txt
git commit -m "Merge branches"

# Push към мастър branch
git push origin master

# Клониране на хранилището
git clone https://github.com/вашето-потребителско-име/вашето-хранилище.git

# Влизане в директорията на проекта
cd вашето-хранилище

# Създаване на текстов файл и попълване с 10 произволни символа
echo "abcdefghij" > sample.txt

# Добавяне на промените, комитване и push
git add sample.txt
git commit -m "Add sample.txt with 10 characters"
git push origin master

# Създаване на нов клон (branch)
git checkout -b нов-клон

# Промяна в текстовия файл
echo "$(date) - change" >> sample.txt

# Добавяне, комитване и push
git add sample.txt
git commit -m "Change in нов-клон branch"
git push origin нов-клон

# Връщане в мастър branch
git checkout master

# Сливане на нов-клон branch
git merge нов-клон

# Разрешаване на конфликти
git mergetool

# Добавяне и комитване на разрешението на конфликта
git add sample.txt
git commit -m "Merge branches"

# Push към мастър branch
git push origin master



