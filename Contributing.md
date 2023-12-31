# Руководство по внесению изменений

Поддерживайте ваш репозиторий обновлённым. Когда наставник принимает ваш пулреквест, он попадает в репозиторий Академии, но не в ваш форк.

#### 1. Не коммитьте ничего самостоятельно в `master` вашего репозитория

Это помешает вам аккуратно обновлять ваш репозиторий, могут возникнуть конфликты.

#### 2. Прежде чем приступать к новому заданию, обновите `master`

Обновить свой репозиторий можно так:

```
# В вашей локальной копии переключитесь в ветку master
git checkout master

# Заберите изменения из репозитория
git pull

# Отправьте изменения
git push
```

¹ Cсылка на репозиторий:

```
git remote add origin https://github.com/AllaZaharova/drink2go.git
```


--

#### Есть вопрос?

Посмотрите [коллекцию часто задаваемых вопросов по Git](http://firstaidgit.ru).
