# O que é um microcontrolador?

Um **computador** é uma máquina composta por diversas partes, cada uma especializada em uma tarefa específica relacionada a operação do computador. Essas partes são então integradas para formar um sistema mais complexo, geralmente montando os diversos componentes em uma placa de circuito impresso. Diferentes aplicações requerem o balanço entre diferentes requisitos, por isso vemos uma variedade tão grande de sistemas. Provavelmente você está lendo este texto em um computador de uso geral (um *desktop* ou *notebook*), sistemas cuja principal função é realizar o que chamamos de computação (que definiremos melhor nas próximas sessões).

Em diversos cenários queremos embutir computadores em sistemas cuja finalidade não é servir como uma ferramenta geral de computação. Por exemplo, a função de um veículo é permitir a locomoção de pessoas e cargas, a função de um telefone celular é permitir a comunicação entre pessoas que estão fisicamente distantes, a função de uma geladeira é armazenar alimentos em baixa temperatura. Ainda assim, colocamos computadores nesses equipamentos para automatizar e otimizar seu funcionamento. Ao fazer isso dizemos que o computador está **embarcado** em um outro sistema.

Ao embarcar computadores nos mais diversos sistemas passamos a lidar com as restrições inerentes a estes sistemas e às necessidades da sua aplicação. Um telefone celular precisa ser compacto e consumir pouca energia de forma que possamos utilizar uma bateria de pequeno tamanho e ainda assim conseguir uma autonomia decente. Por outro lado, um telefone celular precisa realizar operações de controle razoavelmente complexas para permitir um bom uso dos recursos de comunicação disponíveis. O computador embarcado em um carro está ali para monitorar um conjunto de sensores espalhados pelo veículo e controlar funções como a quantidade de combustível injetada no motor. A única função de um computador embarcado em um geladeira é monitorar e controlar a temperatura interna do equipamento.

**Microcontroladores** são pequenos computadores integrados em um único chip. Seu projeto procura atender aplicações que envolvem o monitoramento de sensores e a automação do controle de processos. Quando falo em pequenos computadores não quero dizer necessariamente computadores simples, um microcontrolador moderno provavelmente é uma máquina bem mais sofisticada do que aquelas utilizadas para levar o homem para a Lua. Justamente pela extensa gama de aplicações, encontraremos microcontroladores com uma variedade imensa de recursos, mas todos eles compartilham muitos elementos em comum. Ao longo deste livro iremos explorar diversos desses elementos utilizando um microcontrolador específico, o MSP430F5529 fabricado pela Texas Instruments, mas cobriremos os aspectos teóricos de forma que você seja capaz de trabalhar com qualquer tipo de microcontrolador no futuro (claro que com alguma curva de aprendizado). 

## Mas o que é um computador, afinal?

Gostaria de começar analisando o que é um computador do ponto de vista funcional (o que ele faz). A operação de um computador é muito parecida com a operação de uma pessoa realizando determinadas tarefas, por incrível que pareça. Provavelmente o primeiro a parceber isso para construir uma teoria foi o matemático inglês Alan Turing (1912 - 1954), hoje considerado o pai da computação. Em Janeiro de 1937 Turing publicou um artigo intitulado "Sobre números computáveis, com uma aplicação ao problema de decisão" ([*On Computable Numbers, with an Application to the Entscheidungsproblem*](https://londmathsoc.onlinelibrary.wiley.com/doi/abs/10.1112/plms/s2-42.1.230)) em que ele analisa o que um ser humano seria capaz de calcular utilizando papel e caneta. Baseado nessa ideia ele propõe uma máquina abstrata que calcula números e argumenta que essa máquina captura toda a nossa capacidade de realizar desenvolvimentos matemáticos de forma automática (repare que não afirmo que sua proposta seria capaz de capturar toda a matemática que um ser humano seria capaz de fazer, mas captura tudo aquilo que pode ser feito de forma mecânica e automática). 

Na época em que esse trabalho foi escrito um computador era literalmente uma pessoa que realizava cálculos matemáticos seguindo instruções. A foto a seguir, de 1949, mostra a "sala de computadores" do Comitê Nacional para Aconselhamento sobre Aeronáutica (*National Advisory Committee for Aeronautics* - NACA), uma agência de pesquisa aeroespacial do governo americano.

![By NACA (NASA) - Dryden Flight Research Center Photo Collection - http://www.dfrc.nasa.gov/Gallery/Photo/Places/HTML/E49-54.html, Public Domain, https://commons.wikimedia.org/w/index.php?curid=885426](./Human_computers_-_Dryden.jpg)





spero que compreender isso faça com que as coisas fiquem mais simples pois o 




# Referências
