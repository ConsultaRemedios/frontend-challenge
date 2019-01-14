## Consulta Remedios Frontend Challenge

O teste consiste em construir a interface de um pseudo ecommerce de games,
conforme as telas a seguir.

### Carrinho vazio
![mock](https://i.imgur.com/BL3L07z.png)

### Com produtos no carrinho
![mock](https://i.imgur.com/8Ou0fpu.png)

### Sobre o estilo
* A família de fonte usada no layout é a OpenSans
* Faça o download dos assets (ícones e imagens) do teste [**aqui**](https://github.com/ConsultaRemedios/frontend-challenge/tree/master/assets)
* Acesse as [**specs**](https://xd.adobe.com/spec/75b714d8-3dc2-4c5c-545f-893589786ad3-0386/) para obter detalhes de tamanho de fontes, cores e espaçamentos. **Senha:** CRtest2018


## Comportamentos esperados
* Os produtos devem ser renderizados dinamicamente através do mock json presente neste readme
* Os valores exibidos no checkout (frete, subtotal e total) devem ser calculados dinamicamente 
* O usuário poderá adicionar e remover produtos do carrinho
* O botão de adicionar ao carrinho será exibido no over do respectivo produto da listagem
* O botão de remover o item do carrinho será exibido no over de seu respectivo item no carrinho
* O usuário poderá ordenar os produtos por preço, popularidade (score) e ordem alfabética.

## Regra do cálculo de frete
A regra para o cálculo de frete é simples.
* A cada produto adicionado, deve-se somar R$ 10,00 ao frete.
* O frete é grátis para compras acima de R$ 250,00.

## O que iremos avaliar
Queremos saber como você organiza seu código, interpreta os requisitos e implementa as features descritas no teste, por isso, você está livre para fazer o setup de sua preferência. Usar frameworks/libs é permitido, porém evite usar código de terceiros para tudo (vale tanto para JS quanto CSS), quanto mais código escrito por você, melhor.

**Importante:**
* Não esqueça de criar um readme explicando como rodar o projeto
* É importante que você utilize o git para versionamento e que faça commits pequenos, isso nos ajudará a acompanhar a
sua linha de raciocínio.

## Prazo e forma de entrega
Não estipulamos um prazo para a entrega do teste, apenas pedimos que antes de iniciá-lo,
faça uma estimativa do tempo que irá levar baseado na sua disponibilidade e nos encaminhe por email.

Levando em consideração que este teste será aplicado a outros desenvolvedores, pedimos que você publique o código em um repositório privado (bitbucket ou gitlab são boas alternativas).

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


