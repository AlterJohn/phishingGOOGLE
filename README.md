Ferramentas utilizadas:

Máquina virtual (VirtualBox)
Kali Linux
Setoolkit (Ferramenta com diversos payloads, disponivel por padrão no Kali Linux)

Configurações iniciais:

 Na VM -> Configurações -> Rede -> Selecionar a opção 'Placa em modo Bridge'.
 
Configurando o phishing no kali linux:

Acesso root: sudo su
Obtendo o endereço da máquina: ifconfig
Iniciando o setoolkit: setoolkit
Tipo de ataque: Social-Engineering Attacks
Vetor de ataque: Credential Harvester Attack Method
Vetor de ataque: Web Templates
Select template: Google

Dentro do site clone:

Inserir credenciais a serem capturadas.

Resultado:

Informações impressas no terminal com os campos de USERNAME e PASSWORD.

![Resultado]([URL_da_Imagem](https://github.com/AlterJohn/phishingGOOGLE/blob/main/image.png))
