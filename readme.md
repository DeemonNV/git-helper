### Инициализация проекта - **git init**
### Добавление в индекс - **git add --all или git add . **
### Зафиксировать состояние - **git commit -m "Текст комента"**
---

### Подключение к удаленному проекту - **git remote add origin git@github.com:%%USERNAME&&/%%PROJECTNAME%%**
### Переключится на ветку - **git branch -M main**
### Синхронизировать ветки - **git push -u origin main**
### В дальнейшем протос - **git push**
---
### Общая схема:
**git add .**
**git commit -m "ТЕКСТ"**
### После первого коммита можно объединить - **git commit -am "ТЕКСТ"**
### Теперь если надо залить в удаленный репозиторий - **git push**
---
---
### HEAD - файл, содержит запись о последнем коммите. Может использоваться вместо хеша, для передаче командам гита
### **git log** - позволяет смотреть историю коммитов. Ключ **--oneline** выводит сокращенный формат
### Основным идентификатором коммита является Хеш, по алгоритму SHA-1 длиной 40 символов(0-9 и A-F в разных регистрах).
