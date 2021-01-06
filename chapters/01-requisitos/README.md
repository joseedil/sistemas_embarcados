# Requisitos

## Conhecimentos prévios

Apesar de fornecer um capítulo com revisão sobre lógica digital e representações numéricas, suponho que o leitor tem familiaridade com esses temas. Não suponho nenhum conhecimento em programação de computadores, apesar de que pode ser de grande ajuda. Minha abordagem será começar com programação em um nível muito próximo ao hardware com foco em arquitetura de computadores. Com o andar do curso passaremos a programar em C, a linguagem de alto nível mais amplamente utilizada para programação de sistemas embarcados.

## Kit de desenvolvimento e periféricos

Vou supor que você tem acesso ao kit de desenvolvimento [Launchpad MSP430F5529 da Texas Instruments](https://www.ti.com/tool/MSP-EXP430F5529LP). Essa placa custa US$12,99 (mais US$8,99 de frete), cerca de R$117,00 considerando um dólar de R$5,30 (em Janeiro de 2021). Esse kit é bem mais caro do que as cópias chinesas do Arduino que estão disponíveis no mercado brasileiro por cerca de R$50,00. A grande vantagem do hardware da Texas é a existência de um debuger integrado que permite observar a execução de software e o conteúdo da memória utilizando um ambiente de desenvolvimento. A proposta do Arduino é ser amigável para quem quer fazer um projeto de fim de semana sem maiores complicações, a proposta da Texas é mais interessante para quem quer aprender de verdade sobre hardware digital.

Outros periféricos serão descritos no futuro (sensores, displays, etc)

## Software

O primeiro requisito é que você tenha acesso a um computador onde possa acompanhar o material. Recomendo fortemente que utilize o sistema operacional Linux, é de longe a alternativa mais amigável para desenvolvedores e com o tempo você vai perceber que ferramentas mais avançadas geralmente não estão disponíveis para ambiente Windows. O MacOS é razoável (é o que eu pessoalmente utilizo) e quando preciso de bibliotecas ou ferramentas GNU utilizo o [MacPorts](https://www.macports.org/) (o [Homebrew](https://brew.sh/) é uma alternativa viável). Como usaremos o ambiente de desenvolvimento da Texas Instruments ao longo de todo este livro você não terá grandes problemas ao utilizar o ambiente Windows, mas provavelmente vai te limitar ao longo do tempo.

O ambiente integrado de desenvolvimento (IDE) da Texas Instruments é chamado de [Code Composer Studio](https://www.ti.com/tool/CCSTUDIO). Baixe a versão para o seu sistema operacional e siga as instruções de instalação que vem com o arquivo. 

Outras ferramentas serão descritas no futuro (terminais seriais, etc).
