# DevOPS Tray
### Acesso ao site
Para acessar, http://cristianhchiareli.ddns.net/respostas/.

### Instalação
1. Para instalar é necessário lançar uma instância de qualquer perfil na AWS com a imagem do Ubuntu 18.04.
2. Acesse a instância como root e copie o arquivo setup para /home/ubuntu.
3. Dê permissão de execução no arquivo com o comando "chmod +x /home/ubuntu/setup".
4. Agora execute o script setup "/home/ubuntu/./setup"

Obs.: Para acessar a instância já criada, utilize a chave tray.

### Novo usuário
Foi criado um novo usuário para acesso ao servidor
Usuário: tray
Senha: tray123

Obs.: Mesmo com a senha, se faz necessário a utilização da chave.

### Softwares e versões instaladas
- PHP 7.2
- Apache2

### Comandos utilizados
- sed
- sudo
- echo
- adduser
- usermod
- apt
- chown
- add-apt-repository
- a2enmod
- rm
- mkdir
- cd
- git
