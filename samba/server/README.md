## Configurando Servidor Samba

> O Samba é um servidor de arquivos muito poderoso, que permite que não só consigamos compartilhar arquivos dentro de uma rede, mas ele atua como um serviço completo de simple storage, como o S3 da AWS ou Google Cloud Storage, com regras customizaveis e vários outros recursos

Antes de usarmos o Samba precisamos fazer a instalação do pacote

### Instalação
```shell
$ sudo apt update
$ sudo apt install samba
```
![install samba](../../media/images/7.jpg)

Após instalar podemos checar o status do funcionamento usando os comandos
```shell
$ sudo systemctl status smbd
$ netstat -an | grep LISTEN
```
![check smbd status](../../media/images/8.jpg)
![check smbd status](../../media/images/9.jpg)

> Com o samba em pleno funcionamento podemos fazer o backup das configurações iniciais dele e começarmos a personalizar!