# Clash Royale Full Stack Application

Aplicação Full Stack de Clash Royale para analisar jogadores, cards e estatísticas de batalhas.

## Estrutura

1. Front End: React + Vite
2. Back End: NodeJS
3. Banco de Dados: MongoDB 
4. Deploy: Docker Compose

# Configuração

Primeiro, defina as seguintes variáveis no arquivo `docker-compose.yml`:

    CLASH_TOKEN_API: ''
    DATABASE_URL: ''  

Obs: Essas variáveis são essenciais para conectar o back-end com o banco de dados MongoDB.

## Para obter os componentes

Faça o clone deste repositório:

	git clone https://github.com/renanleitev/api-clash-docker.git

Depois, acesse a pasta com o código (ou usando o terminal):

    cd clash-royale-docker

De dentro da pasta `api-clash-docker`, faça o clone dos repositórios Front End e Back End:

Front End
	
	git clone https://github.com/renanleitev/api-clash-front.git

Back End

	git clone https://github.com/renanleitev/api-clash-royale.git

## Para rodar os containers

	docker compose up

Obs: Pode ser que demore alguns segundos ou até minutos para a aplicação iniciar, se não der certo após dois minutos, tente novamente.

Caso dê tudo certo, abra o seu navegador e acesse o site: ```http://localhost:9090``` ou ```http://<IP_SERVIDOR>:9090```

## Para deletar os containers

	docker compose down

## Para deletar todos os containers

	docker container prune -f

## Equipe

1. Flávio Raposo
2. João Pedro Marinho
3. José Adeilton
4. Renan Leite Vieira
5. Rian Vinícius
6. Robério José