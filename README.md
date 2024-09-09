# Preparação de ambiente
### Vamos preparar o ambiente para o desenvolvimento de aplicações

#### Neste ambiente iremos instalar e configurar as seguintes recursos: 
 - Máquina Virtual (Virtual Box) 
 - Distribuição Linux (Ubuntu server)
 - Nasm 
 - Compilador da linguagem C
 - Configurar o IP e a porta de comunicação entre a máquina real e a virtual
 - Configurar o acesso via SSH entre o VSCode e o ServidorLinux
 - Instalar as extensões: Material Icon, Nasm, SSH e linguagem C/C++

#### Maquina virtual (VirtualBox) 

!["Logo VirtualBox"](virtualbox.png) 


Máquina Virtual é uma ferramenta que permite a criação de novos "computadores" e a instalação de sistemas operacionais, para estudo ou trabalho.

Para o nosso estudo iremos usar o VirtualBox, da Oracle.
Para instalação, basta fazer o download no Link a seguir:

<a href= " https://www.virtualbox.org/wiki/Downloads " target= "_blank"> VirtualBox </a>

##### Criando máquina virtual para o nosso estudo

- Configuração
> - Nome da Máquina: Servidor
> - Memória: 4GB (4096)
> - Processador: 2
> - Disco: 100GB
> - IP e Porta dos Host: 127.0.0.1 e 22
> - IP e Porta do Convidado: 10.0.2.15 e 22

- Tela inicial de configuração 

<img src=comeco_do_virtual_box_(1).png width=500 height=250>

<img src=comeco_do_virtual_box_(2).png width=500 height=250>

<img src=comeco_do_virtual_box_(3).png width=500 height=250>

- Tela configuração de Hardware

 <img src=comeco_do_virtual_box_(4).png width=500 height=250>

- Tela de configuração do Disco

<img src=comeco_do_virtual_box_(5).png width=500 height=250>

- Tela Final de configuração

<img src=comeco_do_virtual_box_(6).png width=500 height=250>

- Tela inicial de configuração de Rede

<img src=comeco_do_virtual_box_(7).png width=500 height=250>

- Tela de configuração de Portas e IP

<img src=comeco_do_virtual_box_(8).png width=500 height=250>

#### Distribuição Ubuntu Server

<img src=logo_ubuntu.png width=300 height=200>

Para o nosso estudo iremo utilizar uma distribuição Linux para servidores chamada Ubuntu. 

*Observação: Você só usará o teclado, não usará o mouse nenhum momento.

Acompanhe o processo de isntalação:

Faça o download aqui: <a href= "https://ubuntu.com/download/server" target= "_blank"> Ubuntu Server </a>

- Acompanhe a instalação
 
 - Tela de inicio de instalação
 <img src=entrada_da_maquina_(1).png>

 - Tela de seleção de idioma
 <img src=entrada_do_ubuntu.png>

 - Tela de seleção de teclado - Português Brasil
 <img src=entrada_do_ubuntu_(3).png>

 - Tela de tipo de instalação
<img src=entrada_do_ubuntu_(4).png>

 - Tela configuração de rede
 <img src=entrada_do_ubuntu_rede.png>

 - Tela configuração do proxy
 <img src=entrada_do_ubuntu_proxy.png>

 - Tela pacotes de atualização
 <img src=entrada_do_ubuntu_pacotes_de_atualizacao.png>

 - Tela configuração do disco
 <img src=entrada_do_ubuntu_configuracao_do_disco.png>

 - Tela layout do disco
 <img src=entrada_do_ubuntu_layout_de_configuracao_disco.png>
 
 - Confirmar 

 <img src=confirmar.png>

 - Tela configuração do usuario
 <img src=entrada_do_ubuntu_layout_de_configuracao_usuario.png>

 - Tela configuração do SSH
 <img src=entrada_do_ubuntu_configuracao_do_ssh.png>

 - Tela do Fim da instalação
 <img src=entrada_do_ubuntu_fim_da_instalacao.png>


#### Atualização do sistema

Para a correta utilização do servidor Ubuntu que acabamos de instalarm será necessário realizar a atualização do sistema:

Execute o comando abaixo: 

```
sudo apt uptade -y && sudo apt upgrade -y
```

Reinicie o seu Servidor usando o comando abaixo:

```
reboot
```

#### Instalação do compilador NASM

O compilador do NASm é uma ferramenta que nos permite programar em Assembly. Assim é possivel criar programar que maniplam dados que estão nos registradores do processador.

Para instalar o nasmo no Ubuntu, usamos o comando:

```
sudo apt install nasm -y
```

#### Instalação do compilador da Linguagem C

Em Linux, o compilador da linguagem C é o GCC. Ele é uma ferramenta importante para o desenvolvimento de programas em C.

Para isntalar use o comando:
```
sudo apt install gcc -y
```


#### Conexão via servidor e VSCode via SSH

Precisamos instalar uma extensão no VCSode para acessar o nosso servidor de forma remota.






