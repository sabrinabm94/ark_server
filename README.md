# Informations
Custom configurations to ark server.

# Criação do servidor (Windows)
## Requisitos
### .NET Framework version 4.5.2
Baixe o [.NET Framework](https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.microsoft.com%2Fpt-br%2Fdownload%2Fconfirmation.aspx%3Fid%3D42642%26fbclid%3DIwAR2QHpRW9fByXXdRUr8BSX2NbsqWVTxr5W7yAOH8IGQ2RNOWwUKixOqWpEo&h=AT25dxDYeuHz96gg54plmVv0zFZr7VXfGsQmj8TYWnjePlktEMKFquHC984jbAk-Ef91mUo-wXlBmEqITWu2l6uPOBIOE4KU06gqxFxIAa25e4mUFWGpgaDcURGcFcCtN60L) e instale

### Steam CMD
Baixar o [Steam CMD](https://arkservermanager.s3.amazonaws.com/release/latest.zip)
Crie um diretório (C://servidores/steam_cmd/) e descompacte os arquivos ali.

### Ark Server Management (ASM)
Baixe e instale o [Ark Server Management 1.0.301](http://arkservermanager.s3.amazonaws.com/release/ArkServerManager_1.0.301.zip)

OBS: sempre execute o ASM como administrador, isso é muito importante.
[Admin](https://i.imgur.com/d1DigPX.png)


# Configuração
## Portas
As portas por padrão são:
* Server Port: 7777
* Query Port: 27015

OBS: caso elas já estejam sendo usadas por outra aplicação, é necessário trocar.


## Firewall
### Firewall do Windows
* O próprio ASM irá abrir as portas corretamente para cada servidor criado.

### Firewall de anti-virus
* Você precisa abrir as portas listadas acima para TCP e UDP.
* Pode ser necessário também indicar o caminho do executável do servidor: seu-local-de instalacao/ShooterGame/Binaries/Win64/ShooterGameServer.exe

#### Exemplos
![Abrindo portas no firewall do Windows](https://i.imgur.com/gWUcQbZ.png)


## Obtendo Ip local
* Verifique seu ip público no site [What is my ip](https://www.whatismyip.com/what-is-my-public-ip-address/)


## Obtendo Ip público
* Abra a cmd e digite ipconfig
* Anote a numeração que vai ser indicada em ipv4, geralmente 192.168.1.x


## Roteador
### Abrindo portas no roteador
* Abra uma aba no navegador e digite http://192.168.1.0/ ou http://192.168.1.1/
* A senha padrão de acesso é usuário vazio e senha admin.

OBS: essas informações podem mudar de acordo com a marca do seu roteador.
* Configure a abertura(Forwarding Port) e eventos(Port Triggers) para as portas: 7777 e 27015, indicando o seu ip local (ipv4)


#### Exemplos

![Forwarding](https://i.imgur.com/BNzSdqx.png?raw=true)

![Port Triggers](https://i.imgur.com/KKW6EPU.png?raw=true)


## Mods
### Oficial
* Mapa: [Ebenus Astrum](https://steamcommunity.com/sharedfiles/filedetails/?id=916417001)
* [Structures Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=731604991)
* [Wild Fertilized Eggs No Tame](https://steamcommunity.com/sharedfiles/filedetails/?id=1191739191)
* [Speedy Flyers](https://steamcommunity.com/sharedfiles/filedetails/?id=919470289)
* [Wyvern Mating](https://steamcommunity.com/sharedfiles/filedetails/?id=814833973)
* [Wyvern Milk Substitute](https://steamcommunity.com/sharedfiles/filedetails/?id=819857895)


## Others
* [Better Milk](https://steamcommunity.com/sharedfiles/filedetails/?id=770949087)
* [Wyvern Milk Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=878539458)


## Maiores informações
* [Ark server management](http://arkservermanager.freeforums.net/thread/4/installation-ark-server-manager)
