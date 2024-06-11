FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/juniorfdtech/instalador.git && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./instalador && sudo ./install_instancia
```

https://github.com/juniorfdtech/instalador.git

PARA UPDATES - ENTRAR NA PASTA E FAZER O BUILD NOVAMENTE:

```
npm run build
```
REINICIAR O PM2:

```
pm2 restart all
```
