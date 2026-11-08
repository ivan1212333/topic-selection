# Установка CLI

Скилл вызывает `python3 -m viraldzen`. Пакет должен быть на PYTHONPATH.

Из клона репозитория ничего ставить не нужно: `python3 -m viraldzen` работает из корня.

Если скилл скопировали в `~/.cursor/skills/` без открытого клона — установите пакет из локального клона:

```bash
pip install -e .
# либо ./install-skill.sh
```

Нужны Python 3.11+ и сеть до `dzen.ru`. Сторонних пакетов нет.

Проверка:

```bash
python3 -m viraldzen -h
```
