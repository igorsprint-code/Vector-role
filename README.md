# Ansible Role: Vector-role

Устанавливает Vector 

## Требования
- Ubuntu 22.04
- Ansible 2.9+

## Переменные
| Параметр | Описание | Значение по умолчанию |
|----------|----------|----------------------|
| vector_version | Версия vector | "0.37.1" |


## Пример использования
```yaml
- hosts: vector
  roles:
    - role: vector-role
      