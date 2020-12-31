# Sistemas Embarcados

Este livro constitui um curso introdutório de desenvolvimento de sistemas embarcados utilizando microcontroladores. Ele será disponibilizado como um "livro em construção", os capítulos serão disponibilizados a medida que forem escritos em conjunto com uma série de videos no Youtube que podem ajudar a compreensão dos assuntos tratados. 

## Escopo

Os tópicos a seguir serão tratados (eventualmente...):

1. como escrever, compilar, gravar e debugar softwre embarcado utilizando linguagem C;

2. como utilizar periféricos comumente encontrados em microcontroladores tais como controle de pinos de entrada e saída, timers, conversores analógico-digital, modulação por largura de pulso, comunicação serial (SPI, I2C, etc), entre outros;

3. tópicos relacionados com processamento de sinais e controle de sistemas tais como calibração e medição com sensores, filtros digitais, atuadores, etc;

4. tópicos relacionados a sistemas operacionais utilizados em sistemas embarcados tais como interrupções, escalonadores, programação multitarefa, etc.


## Abordagem

Amigável ao iniciante. Não considerarei nenhum conhecimento prévio do leitor (na medida do possível), incluindo conhecimentos em hardware ou software. Tentarei escrever o material de maneira mais autocontida possível, isso implica que algumas seções serão bastante teóricas e tentarei indicá-las para que o leitor que prefira focar nos tópicos mais aplicados possa pular trechos que não esteja interessado. Tenha em mente que eu tenho uma concepção pedagógica ao escrever e talvez seja interessante não saltar a teoria.

Mão na massa. É impossível desenvolver qualquer habilidade sem que você mesmo faça alguma coisa com ela. Trabalhe nos exercícios.

Centrado nas ferramentas. Vamos fazer uso intensivo de ferramentas computacionais para o desenvolvimento de software que irá executar no hardware real. 

# Autor

Meu nome é José Edil, sou professor do [Departamento de Engenharia Elétrica](www.ene.unb.br) da [Universidade de Brasília](www.unb.br) (UnB) desde 2011. Tenho doutorado em Sistemas Eletrônicos e de Automação e sou um dos responsáveis por disciplinas da área de Eletrônica analógica e digital para os cursos de Eng. Elétrica, Eng. de Redes de Comunicação, Eng. Mecatrônica e Eng. de Computação na UnB. O material que você vai encontrar aqui é coberto em parte nas disciplinas Sistemas Digitais e Sistemas Microprocessados que oferecemos em nível de graduação. 

## Por que outro livro sobre sistemas embarcados?

Existem excelentes referências sobre lógica digital e sistemas embarcados, este texto não tem a pretensão de substituí-los, mas de servir como fonte de referência para o aprendizado por milhares de estudantes brasileiros e de países de língua portuguesa que não tem acesso a bons materiais em inglês. Um alerta, entretanto, se você deseja trabalhar com eletrônica ou computação aprenda inglês! Todas as tecnologias são documentadas em inglês e não ser capaz de ler e escrever em inglês te condena a estar sempre atrasado na adoção de novas tecnologias ou para aprender tópicos avançados que não têm boas referências em português. Todas as ferramentas e suas documentações que iremos utilizar estarão escritas em língua inglesa.

# Licença
O material disponibilizado aqui é coberto pela [licença Creative Commons Attribution 4.0 International](https://choosealicense.com/licenses/cc-by-4.0/). Você tem permissão para utilizá-lo comercialmente, redistribuí-lo e modificá-lo, desde de que você faça a atribuição de autoria do material original (mesmo que com modificações), incluindo um link para a fonte original e mantenha a mesma licença original. Caso utilize o material licenciado com modificações, indique as modificações realizadas. O autor abre mão de quaisquer pagamentos relativos a royalties sobre o uso desse material.

Todos os códigos-fonte são licenciados sob a [licença MIT](https://opensource.org/licenses/MIT) e são livres para uso sem restrições. Todos os códigos fornecidos tem a intenção de explicar ou exemplificar algum tópico tratado no livro e deve ser considerado experimental. O autor não se responsabiliza por nenhum dano ou prejuízo causado pelo seu uso em sistemas em produção.

## Contribuições

Contribuições são bem vindas por meio de *pull requests*. A menos que explicitamente manifestado em contrário, todas as contribuições submetidas para inclusão junto ao material original serão tratados de acordo com as licenças acima, sem termos ou condições adicionais.
