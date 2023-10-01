# devops-netology
Файл terraform/.gitignore указывает гиту игнорировать следующие файлы:
 - Файлы, которые содержат `.tfstate` в имени
 - Файлы с логом ошибок: `crash.log`  или `crash.*.log`
 - Файлы с чувствительными данными: `*.tfvars` и `*.tfvars.json`
 - Файлы переопределнеия terraform по следующему шаблону:
 ```
override.tf
override.tf.json
*_override.tf
*_override.tf.json
 ```
- ФАйлы настройки CLI: `.terraformrc` и `terraform.rc`
new line
