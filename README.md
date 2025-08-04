test
# devops-netology
Какое то редактирование 

В игнорирование попадут файлы
.terraformrc
terraform.rc
.terraform.tfstate.lock.info
override.tf
override.tf.json

Все файлы, которые оканчиваются на:
*_override.tf
*_override.tf.json
*.tfvars
*.tfvars.json

Не будут попадать файлы логов crash
crash.log
crash.*.log

Не будут попадать файлы tfstate в любом проявлении 
*.tfstate
*.tfstate.*

Все файлы и каталоги внутри будут игнорированы 
.terraform/