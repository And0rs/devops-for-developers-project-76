### Hexlet tests and linter status:
[![Actions Status](https://github.com/And0rs/devops-for-developers-project-76/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/And0rs/devops-for-developers-project-76/actions)

## Требования

- 3 VM с Ubuntu 22.04+
- Ansible на управляющей машине

## Установка зависимостей

Роли Ansible Galaxy:
```
make install-roles
```

Коллекции Ansible Galaxy:
```
make install-collections
```

## Деплой

Проверить доступность серверов:
```
make ping
```

Подготовить серверы (установка pip, docker):
```
make remote-install
```

Задеплоить приложение Redmine:
```
make deploy
```

Установить мониторинг Datadog:
```
make install-datadog
```

## Тестирование

После пуша GitHub Actions (Hexlet) запускает проверки автоматически.
Статус бейджа выше должен быть зелёным.

## Ссылка

Приложение доступно по адресу (с оговорками, когда запущены VMs): [https://cacao.sknt.ru](https://cacao.sknt.ru)
Из жадности проект выполнялся через VirtualBox что стало отдельным испытанием. На скорую руку взятый у провайдера DNS так и не начал резолвится к окончанию проекта, так что в /etc/hosts был указан `<IP машины с балансировщиком> cacao.sknt.ru`
