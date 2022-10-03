# devops-netology


asd

Согласно файлу terraform/Terraform.gitignore будут проигнорированы файлы с расширением:
*.tfstate
*.tfvars
*.tfvars.json

Оканчивающие на:
*_override.tf
*_override.tf.json

Начинающие на crash и заканчивающие на .log
crash.*.log

Совпадающие по названию
crash.log
override.tf
override.tf.json
.terraformrc
terraform.rc

И директория
**/.terraform/*

ДОбавил коммит в мастер ветке