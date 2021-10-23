# BDD: desenvolvimento orientado a comportamento

Muito se fala em desenvolvimento ágil e metodologias que possam ajudar a garantir uma entrega com maior qualidade. Conhecemos amplamente a metodologia de desenvolvimento focada em testes (TDD — Test Driven Development) e agora iremos conhecer o BDD - Behavior Driven Development.

# O que é BDD

O BDD, da sigla Behavior Driven Development, é uma metodologia de desenvolvimento ágil orientada a comportamento. Ela foi apresentada por Dan North em meados dos anos 2000 como uma evolução do processo de metodologia do TDD.

Dan North tinha como objetivo aproximar pessoas não técnicas no processo de criação das funcionalidades técnicas do sistema. Ocorre que quando desenvolvemos software, involuntariamente podemos deixar de incluir conceitos negociais presentes na funcionalidade, acarretando em uma possível vazão para bugs recorrentes, e até mesmo graves. E não por negligência do programador, mas sim pela falta de comunicação com quem domina o negocial.

O BDD serve para aperfeiçoar o desenvolvimento e aproximar todas as partes envolvidas no processo de criação. Isso ocorre pela estrutura do BDD ser baseada em uma linguagem comum entre todos os integrantes do time.

Os testes também sofrem um reflexo desse processo, não sendo escritos diretamente utilizando uma linguagem técnica. Agora eles passam a descrever o comportamento da sua aplicação, onde primeiramente os cenários de teste são descritos para então escrevermos nossos testes em si. Agora, o foco deles irá nos dizer em como o sistema deve se comportar e em por que escrevemos aquela funcionalidade.

# Na prática

O processo de desenvolvimento do BDD se baseia na escrita de cenários de testes chamados de features(funcionalidades). Estes contém os requisitos e critérios de aceite do comportamento do sistema. Ela diz o que a funcionalidade precisa ter para ser iniciada, o que ela fará em seguida e quais serão os resultados após a sua execução.

As features são regidas por três palavras básicas que definem o corpo da linguagem. Dado, Quando e Então. É claro que não é preciso seguir estas normas, mas North recomenda que seja estabelecido um padrão para a escrita, para que a comunicação entre as partes seja mantida.

## Segue um exemplo de feature abaixo:
