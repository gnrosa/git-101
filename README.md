# Workshop GIT 101
## Ministrado pela Le Wagon na Google Cloud for Startups
### 20/02/2019

### Iniciando com GIT
Para realizar a instalação do GIT em distribuições Linux baseadas em Debian, basta executar o seguinte comando:

`$ sudo apt install git-all`

Para verificar a versão instalada utilize o comando `$ git --version`.

Crie um diretório para o projeto com o comando `$ mkdir git-101` em seguida acesse o diretório com o comando `$ cd git-101`.

Execute o seguinte comando para configurar o usuário nas configurações globais do git,
uma vez realizado não será necessário realizar essa configuração novamente. No caso utilizei o mesmo que as minha credenciais do github.

`$ git config --global user.name "joaosilva"`

`$ git config --global user.email joaosilva@exemplo.com`

Para verificar o seu diretório atual utilize o comando `pwd` e para inicializar o repositório utilizar o comando `git init`.
