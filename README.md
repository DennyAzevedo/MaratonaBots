MaratonaBots
==============

Exemplos de códigos da [Maratona Bots](https://ticapacitacion.com/curso/botspt/) em Node.js utilizando o SDK do [Microsoft BotBuilder](https://github.com/Microsoft/BotBuilder)
 juntamente com o [BotBuilder-CognitiveServices](https://github.com/Microsoft/BotBuilder-CognitiveServices/) e as plataformas:
 * [QnA Maker](https://qnamaker.ai/).
 * [LUIS](https://www.luis.ai/)

### Instalação

1. Faça o clone deste projeto com `git clone https://github.com/vitoravale/MaratonaBots.git`
2. Entre na pasta do projeto e instale as dependências com `npm install`
3. Atualize as chaves dentro do arquivo `.env` na raiz do projeto. 

| Serviço | Chaves para atualizar |
| ----- | :- |  
| QnA Maker | `QNA_KNOWLEDGE_BASE_ID` e `QNA_SUBSCRIPTION_KEY` |
| LUIS | `LUIS_MODEL_URL` |

3. Rode a aplicação utilizando `npm run CÓDIGO`, onde __código__ pode ser:

| Módulo        | Lição           | Código  |
| ------------- |-------------| :-----:|
| Módulo 2 | Lição 2: QnA Maker e Active Learning | m2l2 |
| Módulo 2 | Lição 3: Testando o seu FAQ Bot | m2l3 |
| Módulo 3 | Lição 1: Componentes Multimídia | m3l1 |
| Módulo 3 | Lição 2: Componentes de Navegação e Manipulação de Arquivos | m3l2 |
| Módulo 3 | Lição 3: Ciclo de vida de um diálogo | m3l3 |
| Módulo 3 | Lição 4: Construção de uma API de Dados no Azure | m3l4 |

#### Recuperar as chaves do QnA Maker

Para utilizar o QnA Maker você precisará informar suas **knowledgeBaseId** e **subscriptionKey** dentro do arquivo __.env__, para isto basta acessar sua lista de serviços na plataforma [QnA Maker](https://qnamaker.ai/) e clicar no botão __View Code__ do serviço a ser utilizado, a janela exibda conterá os dados que você precisa utilizar. A imagem abaixo demonstra a posição de cada item na tela.

![Imagem da tela de exemplo de código da plataforma QnA Maker](/images/codigos.png)

#### Recuperar a url do LUIS

Para utilizar o LUIS você precisará informar seu **Endpoint** dentro do arquivo __.env__, para isto basta acessar sua aplicação na plataforma [LUIS](https://www.luis.ai/applications) e acessar a aba __Publish__ do serviço a ser utilizado, no final da página exibida estarão os dadores referentes à __Resources and Keys__, basta copiar a url listada. A imagem abaixo demonstra a posição do item na tela...

![Imagem da tela de exemplo de código da plataforma LUIS](/images/codigos-luis.png)
