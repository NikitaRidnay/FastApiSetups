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
   - black . (Black автоматически отформатирует код.)
   - flake8 . (Этот инструмент укажет на стилистические ошибки в коде.)
   - isort . ( автоматически отсортирует импорты.)
4) Авто
   >bash pre-commit

5) Подключение pre commit хуков для  каждого коммита будут автоматически запускаться все проверки.


   >pre-commit install
