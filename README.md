Настройка проекта 


1) Импорт black flake8 и isort
   > pip install black flake8 isort pre-commit
2) Создать файлы .black .flake8 .isort.cfg и тд
   - black
   - .flake8
   - .isort.cfg
   - .pre-commit-config.yaml
   - pre-commit

3) Запуск вручную
   - black .
   - flake8 .
   - isort .
4) Авто
   >bash pre-commit

5) Подключение pre commit хуков
   >pre-commit install
