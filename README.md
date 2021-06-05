<img src="img/ico.png" width="80"/>

## Criando um catálogo de jogos usando boas práticas de arquitetura com .NET

<hr>

#### Desafio proposto:

Construção de uma arquitetura base para uma aplicação ( WEB API Core) do zero. Contendo os 5 verbos HTTP:

- **GET**

  Sem passagem de ID: vai retornar todas as notas (ou as notas mais recentes, isso cabe a regra de negócio da aplicação).
  Com passagem de ID: vai retornar a nota com ID especificado.

  

- **POST**

  Normalmente usado sem passagem de parâmetro – usado para criar uma nova nota.

  

- **PUT**

  Normalmente usado com parâmetro; Use para editar o recurso – neste exemplo, uma nota.

  

- **DELETE**

  Usado para remover o recurso (por exemplo uma nota): utilize com passagem de ID.

  

- **PATCH**

  Usado para editar o recurso sem a necessidade de enviar todos os atributos – o consumidor envia apenas aquilo que de fato foi alterado (mais o ID como parâmetro, para que o serviço saiba o que vai ser alterado).

  

#### Arquitetura aplicada

------

<img src="img\Arquitetura.png" style="zoom:60%;" />



#### Telas

------

<img src="img\Index.png" style="zoom:50%;" />



<img src="img\GET.png" style="zoom:50%;" />

<img src="img\GET2.png" style="zoom:50%;" />
