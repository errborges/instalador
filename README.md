ATUALIZAR SISTEMA OPERACIONAL UBUNTU

```bash
sudo apt update -y && sudo apt upgrade -y
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/errborges/instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./instalador && sudo ./install_instancia
```
