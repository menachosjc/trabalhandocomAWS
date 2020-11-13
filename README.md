# trabalhandocomAWS
Salvar principais estudos em relação a AWS


## Fazer deploy de API na AWS

1) Copie as informações da conta em "My Security Credentials" clicando no seu usuário e depois em ACCESS KEY >  Create New Access Key
2) Instale o AWS CLI
3) Instale o DOCKER
4) Instale o DOCKER MACHINE
5) Digite AWS CONFIGURE e PREENCHA AS INFORMAÇÕES COM SUAS CREDENCIAIS do PASSO 1
6) Digite no console docker-machine create --driver amazonec2 nomedamaquinaquedesejacriar
7) Digite docker-machine env nomedamquinaquecriou
8) Copie e cole a linha que contem "eval"
9) Agora você está conectado na máquina ec2
10) Suba a aplicação digitando no console docker-compose up --build 
