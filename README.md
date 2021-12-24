<p align="center">
  <img src="media/images/logo-if.png" alt="Logo Ifal" width="250"/>
</p>

<br/>

## Lab Redes 2021 - Rede Samba com DNS
___
#### Alunos: Manuel Eduardo - Arthur Brito
#### Turma: 914

#### Disciplina: SRED (Serviços de Redes)

#### Professor: Alaelson Jatobá
___
> O Roteiro preparado discorre sobre a implementação de uma rede samba de compartilhamento de arquivos que permite conectar duas máquinas virtuais de uma mesma rede, nomeando-as usando o protocolo DNS

## Sumário:


Indice            |  link
:-------------------------------:|:--------------------------------:
Configuração de dns   |   [clique aqui](/dns)
Configuração de servidor samba   |   [clique aqui](/samba/server)
Configuração de cliente samba   |   [clique aqui](/samba/client)
____

> Todas as cofigurações apresentadas foram feitas via SSH usando as máquinas propostas na diciplina

![conexão ssh](/media/images/1.jpg)


### Tabela de definições

___
<table>
<td align="center">
Gateway
</td>
<td align="center">

gw.arthurmanuel914.labredes.ifalarapiraca.local

</td>
</tr>
<tr>
<td align="center">
Name Server 1
</td>
<td align="center">

ns.arthurmanuel914.labredes.ifalarapiraca.local

</td>
</tr>
<tr>
<td align="center">
Samba-SRV
</td>
<td align="center">

samba.arthurmanuel914.labredes.ifalarapiraca.local

</td>
</tr>
</table>

___


<p align="center">
  Arapiraca - 2021 
</p>