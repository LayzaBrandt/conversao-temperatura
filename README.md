# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

Todo container é baseado em uma imagem, então é necessário para criação do mesmo.
<br/>
<br/>
<br/>
<br/>




## Projeto apenas para introdução do conteúdo de Docker

### Alguns comandos do docker apresentados e que podem ser utilizados:

*docker container run Hello-word¹*                        → exercutar um container;

*docker container ls *                                    → mostra todos os containers em execução;

*docker container ls -a*                                  → mostra os container mesmo que a execução tenha encerrado;

*docker container run —name Meu-container²*               → executa um container com um nome definido;

*docker container rm *nome do container* *                → remover um container.

*docker container run nginx*                              → baixar a imagem do nginx;

*docker container run nginx -d*                           → libera o terminal;

*docker container exec -it *id do container*/bin /bash*   → para aqueles containers que acabaram sua execução mas, precisa executar novamente;

*docker container run -d -p 8080:80 nginx*                → mudando a porta do docker



¹- Imagem a ser criada, sem nome

²- Nome do arquivo(imagem) a ser criado
