# devops-netology

Игнорируются:
<br>локальные папки terraform
<br>файлы состояний terraform
<br>логи падений

Игнорируются файлы содержащие закрытые данные (пароли, ключи)

Файлы переопределений по умолчанию не отслеживаются
Для добавления к отслеживанию необходимо добавить требуемые файлы по шаблону
	Например '!example_override.tf'

Возможно включение игнорирования вывода команды 'terraform plan -out=tfplan'
	Например '*tfplan*'

Игнорируются файлы конфигурации CLI
