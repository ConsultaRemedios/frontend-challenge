## Consulta Remedios Frontend Challenge

O teste consiste em construir a interface de um pseudo ecommerce de games,
conforme as telas a seguir:

### Carrinho vazio
![mock](https://i.imgur.com/BL3L07z.png)

### Com produtos no carrinho
![mock](https://i.imgur.com/8Ou0fpu.png)

### Sobre o estilo
* Acesse as [**specs**](https://xd.adobe.com/spec/75b714d8-3dc2-4c5c-545f-893589786ad3-0386/) para obter mais detalhes como
o nome da fonte utilizada, tamanhos, cores e espaçamentos. **Senha:** CRtest2018
* Você pode baixar os assets [**aqui**](https://github.com/ConsultaRemedios/frontend-challenge/tree/master/assets)

## Requisitos
* Os produtos devem ser renderizados dinamicamente através do mock json presente neste readme
* Os valores exibidos no checkout (frete, subtotal e total) devem ser calculados dinamicamente
* O usuário poderá adicionar e remover produtos do carrinho
* O botão de adicionar ao carrinho será exibido no over de seu respectivo produto
* O botão de remover o item do carrinho será exibido no over de seu respectivo item no carrinho
* O usuário poderá ordenar os produtos por preço, popularidade (score) e ordem alfabética.
* A cada produto adicionado, deve-se somar R$ 10,00 ao frete.
* O frete é grátis para compras acima de R$ 250,00.

## O que iremos avaliar
Levaremos em conta os seguintes critérios:
* Cumprimento dos requisitos
* Fidelidade do layout e fluidez da UX
* Organização do código e boas práticas
* Domínio das linguagens, bibliotecas e ferramentas utilizadas
* Organização dos commits
* Escrita e cobertura de testes

## Sobre a entrega
Não estipulamos um prazo para a entrega do teste, apenas pedimos que, antes de iniciá-lo,
nos informe uma data estimada de entrega.

Assim que concluir o teste, nos encaminhe a url do repositório onde o teste foi escrito.

### Mock JSON - Obrigatório
Renderize a página a partir dessa estrutura de dados

```js
[
  {
    id: 312,
    name: "Super Mario Odyssey",
    price: 197.88,
    score: 100,
    image: "super-mario-odyssey.png"
  },
  {
    id: 201,
    name: "Call Of Duty Infinite Warfare",
    price: 49.99,
    score: 80,
    image: "call-of-duty-infinite-warfare.png"
  },
  {
    id: 102,
    name: "The Witcher III Wild Hunt",
    price: 119.5,
    score: 250,
    image: "the-witcher-iii-wild-hunt.png"
  },
  {
    id: 99,
    name: "Call Of Duty WWII",
    price: 249.99,
    score: 205,
    image: "call-of-duty-wwii.png"
  },
  {
    id: 12,
    name: "Mortal Kombat XL",
    price: 69.99,
    score: 150,
    image: "mortal-kombat-xl.png"
  },
  {
    id: 74,
    name: "Shards of Darkness",
    price: 71.94,
    score: 400,
    image: "shards-of-darkness.png"
  },
  {
    id: 31,
    name: "Terra Média: Sombras de Mordor",
    price: 79.99,
    score: 50,
    image: "terra-media-sombras-de-mordor.png"
  },
  {
    id: 420,
    name: "FIFA 18",
    price: 195.39,
    score: 325,
    image: "fifa-18.png"
  },
  {
    id: 501,
    name: "Horizon Zero Dawn",
    price: 115.8,
    score: 290,
    image: "horizon-zero-dawn.png"
  }
]
```
