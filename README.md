# terraform-portfolio
В этом репозитории собраны 9 учебных заданий по Terraform, выполненных мной в рамках курса. Каждое задание - это отдельная, полностью рабочая конфигурация для Yandex Cloud.

## Что здесь есть

- Создание VPC и подсетей
- Security groups (с динамическими блоками `dynamic`)
- Деплой виртуальных машин (VM)
- Работа с удалённым состоянием (S3 backend)
- Написание переиспользуемых модулей
- Использование `terraform_remote_state` для связи между модулями

## Стек

- Terraform 0.14.8
- Yandex Cloud Provider
- S3 backend (Yandex Object Storage)
