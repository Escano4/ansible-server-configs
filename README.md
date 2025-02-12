# Ansible Server Configs

Этот репозиторий содержит примеры Ansible-плейбуков для настройки серверов.

## Плейбуки
- `playbook.yml` — базовый плейбук для настройки сервера:
  - Обновление пакетов.
  - Установка必备 инструментов (htop, tmux, curl, fail2ban).
  - Настройка фаервола (UFW).

## Как использовать
1. Установите Ansible:
   ```bash
   sudo apt install ansible
2. Скачайте репозиторий::
   ```bash
   git clone https://github.com/ваш_логин/ansible-server-configs.git
3. Запустите плейбук:
   ```bash
   ansible-playbook -i inventory.yml playbook.yml
## Лицензия
MIT License. Подробнее в файле [LICENSE](LICENSE).
