# coolerWhite_infra
coolerWhite Infra repository
alias someinternalhost='ssh -i ~/.ssh/appuser -J appuser@158.160.62.140 appuser@10.128.0.15'
bastion_IP = 158.160.62.140
someinternalhost_IP = 10.128.0.15

====================================
Все задания выполнены, как требовалось в зании. Дополнительный задания - не выполнены
Для запуска скопировать папку packer. В variables.json.example заменить значения пустых строк
Перед стартом используем коману : packer validate -var-file=variables.json.example ubuntu16.json
Для запуска используем команду : packer build -var-file=variables.json.example ubuntu16.json
