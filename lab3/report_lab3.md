University: [ITMO University](https://itmo.ru/ru/)<br />
Faculty: [FICT](https://fict.itmo.ru)<br />
Course: [Network programming](https://github.com/itmo-ict-faculty/network-programming)<br /> 
Year: 2025/2026<br />
Author: Голованов Дмитрий Игоревич<br />
Lab: Lab3<br />



# Лабораторная работа №3.

## Конфигурационные файлы

- [Конфигурация Ansible](ansible.cfg)
- [Динамический inventory из NetBox](nb_inventory.yml)
- [Переменные доступа к RouterOS](all.yaml)
- [Playbook выгрузки данных NetBox](dump_netbox.yml)
- [Playbook записи серийного номера в NetBox](serial_to_netbox.yml)
- [Playbook настройки CHR по данным NetBox](configure_from_netbox.yml)

Netbox я поднял у себя на lxc контейнере

![Рисунок 1](1.png)

Девайсы:

![Рисунок 2](2.png)

Сбор из нетбокс:

![Рисунок 3](3.png)

Кусок файла:

![Рисунок 4](4.png)

Конфигурация по netbox:

![Рисунок 5](5.png)

Пинги новых ip:

![Рисунок 6](6.png)

Заполнение серийников:

![Рисунок 7](7.png)

Серийники в netbox:

![Рисунок 8](8.png)

Рисунок:

![Рисунок 9](9.png)

