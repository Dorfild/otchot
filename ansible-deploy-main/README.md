# Ansible Deploy

Ansible playbook для автоматической настройки Ubuntu Server.

## Структура проекта
ansible-deploy/
├── inventory.ini.example ← пример файла инвентаризации
├── setup.yml ← главный playbook
└── roles/
├── base/ ← базовая настройка сервера
├── nginx/ ← установка и настройка Nginx
├── app/ ← деплой статического сайта
└── ssh/ ← настройка SSH и ключей

## Требования

- Ansible 2.9+
- Ubuntu Server 24.04 LTS
- SSH доступ к серверу


