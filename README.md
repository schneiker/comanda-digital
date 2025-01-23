# comanda-digital
Projeto de um sistema de gerenciamento de pedidos e delivery para gestão de um restaurante, onde pode ser criado um pedido, acessar o cardapio separado por categorias, gerenciamento de pedidos novos, em preparo ou pronto para entrega, gerenciamento de motoboys e atribuição a entrega, sistema de CEP integrado, para o motoboy é possivel receber um pedido para realizar a entrega e o cliente poder monitorar o status em tempo real do seu pedido.
(este projeto foi desenvolvido para fins academicos, qualquer falha, feedback ou dúvidas pode estar entrando em contato através do e-mail: vitorschneiker@gmail.com)

O sistema de comanda digital foi desenvolvido utilizando arquitetura Angular, contendo: HTML, CSS, TS, JAVA.
O arquivo neste repositório é a versão final do projeto que foi desenvolvido em grupo academico.
Para execução do sistema é preciso:
  - Um ambiente de desenvolvimento (eu utilizei o IntelliJEI IDEA) para manter em execução a parte de back-end;
  - MySQL Workbench, para armazenar o noso banco de dados;
  - Instalação de pacotes como: NPM, NG, json-server (caso queira rodar o codigo utilizando fake api).

Para iniciar o codigo angular é preciso abrir a pasta em que esta localizado o código, neste caso na pasta "Front_dish_app"
De o comando: Ng serve
Após isso sera iniciado em localhost:4200


Preparando a parte back-end:

dentro do mysql workbench, crie um novo banco de dados nomeado como "comanda_digital" na porta 8080;
para iniciar a parte back-end é preciso abrir a pasta de back-end dentro de um abiente de desenvolvimento, iniciar o arquivo/código "ComandaDigitalApplication.java",

finalizado, o codigo estara rodando e você podera acessar o sistema em "localhost:4200"
