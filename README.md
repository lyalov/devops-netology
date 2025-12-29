Домашнее задание по лекции "Системы контроля версий"
Ялова Л.В.



![alt text](https://github.com/lyalov/devops-netology/blob/main/git_status_1.png)
![alt text](https://github.com/lyalov/devops-netology/blob/main/git_status_2.png)
![alt text](https://github.com/lyalov/devops-netology/blob/main/git_add.png)
![alt text](https://github.com/lyalov/devops-netology/blob/main/git_diff.png)
![alt text](https://github.com/lyalov/devops-netology/blob/main/git_diff_staged.png)



В файле .gitignore обычно указываются шаблоны имён файлов и директорий, которые Git должен игнорировать — то есть не отслеживать и не включать в коммиты. Ниже приведено описание типичных категорий файлов, которые будут проигнорированы благодаря содержимому .gitignore 



Благодаря файлу .gitignore в каталоге terraform/ будут игнорироваться:

Вся папка .terraform и всё её содержимое (например, .terraform/plugins/, .terraform/lock.hcl).
Все файлы, имя которых заканчивается на .tfstate (например, state.tfstate, prod.tfstate).
Все файлы, имя которых заканчивается на .tfstate.backup (например, state.tfstate.backup).
Все файлы, имя которых заканчивается на .tfvars (например, secrets.tfvars, prod.tfvars).
Все файлы, имя которых заканчивается на _override.tf или _override.tf.json (например, main_override.tf).
Все файлы, имя которых заканчивается на .tfvars.json или .tfplan (например, config.tfvars.json, deploy.tfplan).
Символ * в шаблонах означает любую последовательность символов. Правила применяются ко всем файлам в каталоге terraform/ и его подкаталогах.

1
