# Tutorial de configuracao para rodar o Druid com o Docker compose

Pre requisitos:
  - Docker e Docker compose 

Para configurar o o ambiente virtual docker e testar o Druid,
siga os seguinte passos:

  - Crie um diretorio em qualquer local dentro da sua maquina
  - Baixe os dois arquivos, **docker-compose.yml** e **environment**
  - Mova esses dois arquivos pra dentro do diretorio criado
  - use o comando abaixo para iniciar
    ~~~
    docker compose up
    ~~~
  - se tudo se iniciou como esperado, ao rodar **localhost:8888** o servico do Druid deve ser iniciado o dashboard do druid deve aparecer em sua pagina web
