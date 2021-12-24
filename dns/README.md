## Configurando servidor DNS

Utilizaremos o comando:

```shell
$ ifconfig -a
```

![obtendo dados da rede](/media/images/IMG-20211222-WA0101.jpg)

E então podemos obter os dados da rede e iniciarmos a configuração.
___
### Vamos começar!

* utilizar comando `$ nano /etc/netplan/00-installer-config.yaml` no modo super user para editar o arquivo e adicionar linhas para configuração estática do IP
