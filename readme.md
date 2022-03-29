# Setup Inside - Mysql

Ambiente recomendado para ser utilizado como base de dados para todos os sistemas da Inside

### Pré-requisitos:
Para trabalhar nesse projeto você ira precisar instalar:
     
*[ Docker ](https://www.docker.com/get-started)			
*[ Docker Compose ](https://docs.docker.com/compose/install/)

### Instalando o ambiente

Crie uma rede docker chamada inside para que todos os sistemas do ambiente inside utilizem a mesma rede

    //verifique se a rede inside já existe se a rede não existir execute o comando para criação da rede.
    docker network ls

    //Criando a rede
    docker network create -d bridge inside

Subindo o ambiente docker:
    docker-compose up -d

    // Lembre-se de acessar o banco de dados a partir da porta: 23306 da sua máquina



