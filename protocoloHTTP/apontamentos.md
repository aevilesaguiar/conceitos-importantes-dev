## Protocolo HTTP

Hypertext Transfer Protocol (HTTP)
  

![image](https://user-images.githubusercontent.com/52088444/163247864-3a1ea3b6-df9e-4b72-b79f-6d04411985ba.png)

Objeto Web - É basicamente tudo que compõe a página inclusive a página, vídeo textos, fotos...

![image](https://user-images.githubusercontent.com/52088444/163248202-eeb4434c-7e4a-480a-83b2-21dfb404b7fd.png)

O cliente envia mensagem do tipo HTTP Request para o lado do servidor  solicitando ou enviando um dado, o servidor 
responde com mensagens do tipo response. E o cliente é quem solicita os objetos web, e essa comunicação é realizada 
pelo atravpés do protocolo TCP é um protocolo de transporte. Ele operade duas maneiras:

- conexão persistente
- conexão não persistente

Arquitetura Cliente-Server

O Http ele é um protocolo Stateless ele não guarda o estado, o servidor não armazena estado do cliente.


![image](https://user-images.githubusercontent.com/52088444/163249420-218bf738-c15f-45f6-8c86-c5ff63d71711.png)

Request - realizada pelo o cliente

![image](https://user-images.githubusercontent.com/52088444/163249700-8dbda09a-ebfd-4b97-bb98-989ece1e34ee.png)

![image](https://user-images.githubusercontent.com/52088444/163251907-d0baedf5-66d7-4659-9981-1c47ffd8f9f6.png)

![image](https://user-images.githubusercontent.com/52088444/163251933-44befcd7-0d0d-4f17-8b02-633ee589e222.png)



![image](https://user-images.githubusercontent.com/52088444/163249743-43f93914-db64-4858-9187-0372220b473c.png)

- o método HEAD é parecido com o GET , mas não tem corpo de resposta. E geralmetne vc utiliza quando vc preisa requerer os metadados,
geralmente esses metadados são encapsulados no cabeçalho.

- o MÉTODO TRACE é interessante por que o cliente consegue ver a cadeia de requerimentos, muito utilizados em testes, você verifica de ponta a ponta
- OPTION os clientes podem ver a capacidade do servidor, a parte de conexão
- PATCH é utilizado para modificação parcial de um recurso


MÉTODOS TIDOS COMO SEGUROS

![image](https://user-images.githubusercontent.com/52088444/163252829-31f22c5d-95b2-4566-b066-f038f0fd94f0.png)

Eles tem em comum que nãoa carretam nenhuma alteração de estado, por isso são chamados de métodos seguros

![image](https://user-images.githubusercontent.com/52088444/163253073-150395ae-38e4-423c-a368-2ccf3bdd1f04.png)



![image](https://user-images.githubusercontent.com/52088444/163253228-51b913f1-12b4-4cf1-9a7b-47c3a77f7319.png)


![image](https://user-images.githubusercontent.com/52088444/163253264-09234362-3986-40aa-a662-001e267f8b24.png)
*muito utilizados para cache, e é utilizado do lado do cliente, o qual guarda informações . Isso economiza banda, se houver poucas mudanças sem alteração ele usa o cache

![image](https://user-images.githubusercontent.com/52088444/163253433-b9470ccf-735c-4905-b5ed-15dbb174da22.png)


## Conceitos básicos  - Criptografia por chave

![image](https://user-images.githubusercontent.com/52088444/163253674-e3c9ef98-caac-465d-b203-6ebe432dd744.png)



A criptografia por chave, existem dois tupos

![image](https://user-images.githubusercontent.com/52088444/163253737-e1d5e760-691c-47d1-8448-d0d3fe60f13d.png)


![image](https://user-images.githubusercontent.com/52088444/163253836-8f1d3e5b-949c-4d5b-ac1b-2ee332e9cfe1.png)

![image](https://user-images.githubusercontent.com/52088444/163254003-d9da8ed5-fe03-4140-8285-e37a9a067ef3.png)

![image](https://user-images.githubusercontent.com/52088444/163254035-74899026-341c-47dd-8d77-1cc50f10e5dc.png)

## Procolo ssl

![image](https://user-images.githubusercontent.com/52088444/163254813-84859101-2249-4eb6-bcbe-d99f701647ee.png)

ssl garanta, confidencialidade, integridade e autenticidade

![image](https://user-images.githubusercontent.com/52088444/163255285-17728afc-9019-4a08-af26-0b93dccc219c.png)



