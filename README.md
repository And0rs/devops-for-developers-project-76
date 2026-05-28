### Hexlet tests and linter status:
[![Actions Status](https://github.com/And0rs/devops-for-developers-project-76/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/And0rs/devops-for-developers-project-76/actions)

## Деплой

Проверить доступность серверов:
```
make ping
```

Установить зависимости (роли Ansible Galaxy):
```
make install-roles
```

Подготовить серверы (установка pip, docker):
```
make remote-install
```

Задеплоить приложение Redmine:
```
make deploy
```

## Ссылка

Приложение доступно по адресу (когда запущены VMs): [https://cacao.sknt.ru](https://cacao.sknt.ru)
