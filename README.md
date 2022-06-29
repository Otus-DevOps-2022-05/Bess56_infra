# Bess56_infra
Bess56 Infra repository

#SSH подключение к внутреннему хосту someinternalhost одной командой: ssh 10.128.0.33 -J 51.250.86.61

Alias для команды подключения к внутреннему хосту:
alias someinternalhost='ssh 10.128.0.33 -J 51.250.86.61'

bastion_IP = 10.128.0.9
someinternalhost_IP = 10.128.0.33

homework-4
testapp_IP = 51.250.94.22
testapp_port = 9292

homewark-5
Выполнена сборка образа, параметризированы ключи folder_id, disk_size_gb и service_account_key_file


homework-6
Определены переменные для зоны и приватного ключа, выполнено форматирование terraform fmt. Переменной зоны присвоено значение по умолчанию.
