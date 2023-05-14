# Ajax Get

Gerenciamento Assíncrono Simplificado

# Sobre o projeto

  O projeto Ajax Get é uma implementação prática do conceito de Async Await aplicado ao método GET do Ajax (Asynchronous JavaScript and XML), visando simplificar o gerenciamento de código assíncrono. O objetivo principal é facilitar o trabalho com tarefas que requerem chamadas assíncronas, como requisições HTTP.

Neste projeto, é demonstrado como utilizar o Async Await em conjunto com o método GET do Ajax para acessar recursos de forma assíncrona através da rede. No código fornecido, o evento de clique em um botão dispara a função ajax(), responsável por realizar uma requisição assíncrona.

Dentro da função ajax(), é utilizado o objeto XMLHttpRequest para estabelecer a comunicação assíncrona com o servidor. O método open() configura a requisição GET para acessar o recurso "dados.json". Em seguida, o método send() envia a requisição ao servidor.

O evento onreadystatechange é usado para monitorar o estado da requisição. Quando o valor de readyState é 4, indica que a requisição foi concluída e a resposta está pronta para ser processada. Se o valor de status for 200, significa que a requisição foi bem-sucedida e a resposta contém os dados solicitados.

Nesse caso, o JSON retornado pela resposta é convertido em um objeto JavaScript usando JSON.parse(). Em seguida, os dados do usuário são inseridos em elementos HTML correspondentes, como nome, idade e filhos. É importante ressaltar que filhos é um array de objetos, e o método map() é utilizado para extrair os nomes dos filhos e exibi-los de forma adequada.

Se a requisição não for bem-sucedida (status diferente de 200), uma mensagem de aviso é exibida no console.

Caso ocorra algum erro durante a comunicação com o servidor, um alerta é exibido para informar o usuário sobre a falha.

Ao explorar este projeto, você terá a oportunidade de aprender como o Async Await pode simplificar o código assíncrono e melhorar a organização e legibilidade do projeto. Além disso, poderá compreender o uso do método GET do Ajax para realizar requisições assíncronas e manipular as respostas retornadas pelo servidor.

Aproveite essa abordagem simplificada para aprimorar suas habilidades no desenvolvimento de aplicações que envolvem chamadas assíncronas e ofereça aos usuários uma experiência mais fluída e responsiva.

## Layout D3Js
![Ajax](https://github.com/Thiago771414/imagensProjetos/blob/main/slices/mobile/ajaxGet.png)

## Vídeo de demonstração
[[Vídeo de demonstração]](https://youtu.be/-PSPDSj0ew4)

# Tecnologias utilizadas

## Front end
- Java Script, HTML

# Sobre o Projeto
https://reqres.in/

# Autor

Thiago Reis Lima

https://www.linkedin.com/in/thiago-lima-2a5896166/
