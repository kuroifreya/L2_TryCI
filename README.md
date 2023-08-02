# Урок 2. Тестирование API, CI [![Build status](https://ci.appveyor.com/api/projects/status/3y4oq1emggisqqpq?svg=true)](https://ci.appveyor.com/project/kuroifreya/l2-tryci)

### Насторойка CI
- клонировать проект с лекции из репо Нетологии
- настроить CI
  - создать ```.appveyor.yml```
  - зарегистрироваться на сайте appveyor, авторизоваться GitHub-аккаунтом  и добавить свой репозиторий в новый проект
- удостовериться, что сборка падает на GitHub
- создать папку artifacts и положить в неё jar
- принудительно заставить Git следить за файлом программы: ```git add -f artifacts/app-mbank.jar```
- запушить на GitHub: ```git push```
