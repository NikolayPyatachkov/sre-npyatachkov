# sre-npyatachkov
sre course 2023q3
### ДЗ 1 по курсу SRE 
ansible playbook -> каталог ansible_here


helm chart -> каталог helm_herre

Собственно интересен по сути только values.yaml. Почти все в нем. Последняя версия образа , лимиты, ingress. Не припомню чтобы что-то еще там отличалось от дефолта.

Чуть поправлен templates/serviceaccount.yaml. Там подтвержденный баг. Сгенеренный файл не работает - напутали с отступами.

В templates/deploymett.yaml поиграл с параметрами проб. Почему-то было не мало порченых проб на разных других таймерах. Там же env. для подключения контейнера api к базам.
Остальное - как сгенерено, так и оставлено. 
