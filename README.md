# Laravel Github APP
Script para de banco de dados MySQL com Docker de forma independente de outras imagens.
## Requisitos
- Docker >= 20.10.8 (Não testado em versões inferiores)

## Utilização do Script de criação de aplicação APP e Github repositório 
1. git clone https://github.com/mfabiodias/mysql_docker.git
2. cd mysql_docker
3. docker-compose up -d 

## Dados de conexão rodando sua imagem local
- HOST: 127.0.0.1
- USER: root
- PASS:
- PORT: 3306

Obs: Por padrão os dados do banco de dados serão salvos externamente no volume configurado na pasta ./db, você é livre para altera-lo no arquivo docker-compose.yml, bem como senha e usuário.