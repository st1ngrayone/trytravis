# Самостоятельное задание 1
Вариант подключения в одну команду к someinternalhost используя команду:
ssh -t -A 35.210.239.172 ssh root@10.132.0.3
# Доп. задание 
Для подключения по алиасу можно добавить запись /etc/hosts на сервере bastion
10.132.0.3 someinternalhost

# Подключение через pritunl
bastion_IP = 35.210.239.172
someinternalhost_IP = 10.132.0.3

#test app
testapp_IP = 35.228.202.63
testapp_port = 9292
