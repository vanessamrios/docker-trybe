# Docker Excercise CLI Comands

- Este exercício, realizado durante o modulo de Backend do curso de desenvolvimento de software da Trybe, favorece a prática de comandos Docker no CLI. OBS: o projeto para praticar DOcker foi fornecido pela Trybe, apenas os arquivos com os comandos (docker/docker-commands) são de minha propriedade intelectual. 

- A proposta é praticar os comandos docker necessários de acordo com os requisitos como:
  - Usar comandos dockers no CLI - Interface de linha de comando;
  - Criar um contêiner Docker para uma aplicação de front-end;
  - Criar um contêiner Docker para uma aplicação de back-end;
  - Criar um contêiner Docker para uma aplicação de testes;
  - Orquestrar os três contêineres utilizando o Docker compose.
 
- A lista de requisitos segue abaixo e os respectivos comando necessários pra executá-los está contido em docker/docker-commands.

- [x] 1. Crie um novo container de modo interativo sem roda-lo nomeando-o como 01container e utilizando a imagem alpine usando a versão 3.12
- [x] 2. Inicie o container 01container
- [x] 3. Liste os containers filtrando pelo nome 01container
- [x] 4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele
- [x] 5. Remova o container 01container que está em andamento.
- [x] 6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.
- [x] 7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro.
- [x] 8. Pare o container 02images que está em andamento.
- [x] 9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.
- [ ] 10. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend.
- [ ] 11. Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests.
- [ ] 12. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar.
