# website
Conteudo relacionado a um projeto de criacao de website e testes de funcionamento em containers com nginx.

Requisitos para o funcionamento do laboratorio.

Docker (https://docs.docker.com/get-docker)

Docker compose instalado.

Remover o diretorio app da pasta website

"Atencao, executar todos os procedimentos abaixo fora do diretorio website".

Mover para fora do diretorio website os arquivos docker-compose.yml, Dockerfile, e nginx.conf 

1 - montar o container inicial

docker-compose build website

2 - inicializar o website
docker-compose up website

Se estiver trabalhando localmente:
Va em sua url e digite localhost ou o ip de sua maquina 
Caso o container esteja funcionando remotamente, aponte o ip da maquina remota no seu browser de internet.

Caso queira inicializar o container em segundo plano, coloque a variavel -d em sua linha do docker compose.

Cada vez que realizar qualquer atualizacao nos arquivos do website, realize sempre as etapas 1 e 2 novamente.
