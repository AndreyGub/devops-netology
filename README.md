# devops-netology

# Мой первый проект по DevOps


## Описание правил .gitignore для Terraform

В директории terraform/ есть файл `.gitignore`, который исключает из-под контроля Git следующие объекты:

- `*.tfstate` – любые файлы с расширением .tfstate.
- `*.tfstate.*` – любые файлы, содержащие .tfstate.
- `.terraform/` – папка `.terraform` (со всем содержимым).
- `*.tfvars` – все файлы с расширением `.tfvars`.
- `override.tf` – конкретный файл.
- `*_override.tf` – все файлы, заканчивающиеся на `_override.tf`.
- `override.tf.json` – конкретный файл.
- `*_override.tf.json` – все файлы, заканчивающиеся на `_override.tf.json`.
- `.terraformrc` и `terraform.rc` – конфиг файлы.
- `crash.log` – лог-файл.
- `crash.*.log` – все логи 
