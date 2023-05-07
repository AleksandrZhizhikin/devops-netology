training repository 
07.05.2023 - Git test
--------
Игнорировать скрытую директорию .terraform и все её вложения во всех папках корневой директории  
**/.terraform/*

Игнорировать файлы с расширением .tfstate и имеющие в имени ".tfstate."
*.tfstate
*.tfstate.*

Игнорировать лог файлы
crash.log
crash.*.log

Игнорировать файлы с расширением .tfvars и файлы .json имя которых заканчивается на ".tfvars"
*.tfvars
*.tfvars.json

Игнорировать файлы:
override.tf
override.tf.json
Игнорировать файлы имена которых заканчиваются на:
*_override.tf
*_override.tf.json
Исключение для файла "!example_override.tf"
!example_override.tf

Игнорировать файлы настроек CLI
.terraformrc
terraform.rc

