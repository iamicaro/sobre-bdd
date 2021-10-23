# BDD: Desenvolvimento Orientado a Comportamento

Muito se fala em desenvolvimento ágil e metodologias que possam ajudar a garantir uma entrega com maior qualidade. Conhecemos amplamente a metodologia de desenvolvimento focada em testes (TDD — Test Driven Development) e agora iremos conhecer o BDD - Behavior Driven Development.

## 🆗 O que é BDD

O BDD, da sigla Behavior Driven Development, é uma metodologia de desenvolvimento ágil orientada a comportamento. Ela foi apresentada por Dan North em meados dos anos 2000 como uma evolução do processo de metodologia do TDD.

Dan North tinha como objetivo aproximar pessoas não técnicas no processo de criação das funcionalidades técnicas do sistema. Ocorre que quando desenvolvemos software, involuntariamente podemos deixar de incluir conceitos negociais presentes na funcionalidade, acarretando em uma possível vazão para bugs recorrentes, e até mesmo graves. E não por negligência do programador, mas sim pela falta de comunicação com quem domina o negocial.

O BDD serve para aperfeiçoar o desenvolvimento e aproximar todas as partes envolvidas no processo de criação. Isso ocorre pela estrutura do BDD ser baseada em uma linguagem comum entre todos os integrantes do time.

Os testes também sofrem um reflexo desse processo, não sendo escritos diretamente utilizando uma linguagem técnica. Agora eles passam a descrever o comportamento da sua aplicação, onde primeiramente os cenários de teste são descritos para então escrevermos nossos testes em si. Agora, o foco deles irá nos dizer em como o sistema deve se comportar e em por que escrevemos aquela funcionalidade.

## ⚙ Na prática

O processo de desenvolvimento do BDD se baseia na escrita de cenários de testes chamados de features(funcionalidades). Estes contém os requisitos e critérios de aceite do comportamento do sistema. Ela diz o que a funcionalidade precisa ter para ser iniciada, o que ela fará em seguida e quais serão os resultados após a sua execução.

As features são regidas por três palavras básicas que definem o corpo da linguagem. Dado, Quando e Então. É claro que não é preciso seguir estas normas, mas North recomenda que seja estabelecido um padrão para a escrita, para que a comunicação entre as partes seja mantida.

### Segue um exemplo de feature abaixo:

```groovy
Dado que o cliente esteja na listagem de cupons de Frete VIP
Quando selecionar o cupom desejado
E obter o cupom selecionado
Então mostrará uma mensagem de sucesso

Eu como cliente do CB VIP
Quero obter um cupom válido para Frete VIP
Para utilizar no carrinho
```

> A ideia é que as features sejam o mais descritivo possível, contendo todos os detalhes de sua funcionalidade, como meios para disparar o negocial e as possíveis validações do contexto. Os critérios de aceite dos cenários também estão especificados nela.

## 🎯 Quem escreve as features?

Os cenários de testes não são escritos apenas pelo desenvolvedor. Existe um conceito na metodologia ágil, difundida por Georgie Dinwiddie, chamada de regra dos três amigos. Nela existem três agentes principais que devem interagir diretamente entre si para construir um produto com melhor qualidade. Aqui podemos dizer que o PO (ou alguém mais próximo dos requisitos do produto podendo até mesmo ser o próprio cliente), o QA e o desenvolvedor se reúnem para debater os cenários de testes e escrevê-los da melhor forma possível.

> É importante frisar que a interação entre todas as partes envolvidas no processo deve ocorrer. Durante a cerimônia, diversas perguntas serão feitas a fim de especificar a feature da melhor forma possível.

## ✅ Conclusão

Vimos diversas formas de como podemos nos beneficiar do processo de BDD em nossos projetos. Podemos listar algumas vantagens de por que aplicar a metodologia em seu dia a dia.

Interação — Ocorre uma interação mais direta entre os envolvidos no time. Mantendo assim a comunicação mais eficiente e permitindo termos testes mais precisos.

Documentação viva — A famosa documentação viva, aquela construída durante o desenvolvimento pode ser levada em consideração. Aqui as features servem como documentação da sua aplicação. Cada feature define os requisitos do sistema e todos os seus critérios de aceitação.

Testes baseados no comportamento — Dessa vez temos testes que nos dizem como o sistema deve se comportar, e não apenas os conceitos técnicos que os definem.

Compartilhamento de conhecimento — Todo o processo de construção das features permite que o time esteja alinhado quanto ao negocial e aos requisitos do sistema. O trabalho em conjunto realmente acontece, e pode sanar aquela mísera dúvida que sempre surge quando começamos a codificar.

Também vale citar alguns livros essenciais para quem quiser se aprofundar no assunto. [BDD In Action](https://amzn.to/2ERdM3a) e [Specification by example](https://amzn.to/2HVePBm), encontrados apenas em inglês mas são de grande valia quando se trata sobre o tema.
