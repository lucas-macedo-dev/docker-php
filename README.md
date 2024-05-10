# Template Docker para Projeto PHP com MySQL e NGINX
Este repositório é um template para iniciar rapidamente o desenvolvimento de projetos PHP usando Docker para gerenciamento de contêineres e MySQL como banco de dados.

## Recursos Incluídos
- PHP 8.2-FPM: Use a imagem oficial do PHP para o servidor PHP com FPM (FastCGI Process Manager).
- MySQL 5.7: Banco de dados MySQL para armazenar os dados do seu aplicativo.
- Docker Compose: Gerencie facilmente os serviços do aplicativo usando o Docker Compose.
## Estrutura do Projeto
```
/
├── compose.yaml
├── php
│   ├── Dockerfile
├── nginx
│   ├── Dockerfile
├── www/
│   ├── index.php
│   └── ...
└── db/
    └── ...
```
- compose.yaml: Arquivo de configuração do Docker Compose para definir os serviços do aplicativo.
- Dockerfile: Arquivo Dockerfile para construir a imagem do contêiner PHP.
- www/: Diretório para armazenar o código-fonte do aplicativo PHP.
- db/: Diretório para armazenar os arquivos de inicialização e configuração do MySQL.
##Como Usar
Clone este repositório em sua máquina local:
```
git clone https://github.com/lucas-macedo-dev/docker-php.git
```
Navegue até o diretório do projeto:
```
cd seu-repositorio
```
Inicie os contêineres usando o Docker Compose:
```
docker-compose up -d
```
Acesse o aplicativo em seu navegador:
```
http://localhost:8000
```
