## 
    NÍVEL ISA: 
##
O nível ISA (Instruction Set Architecture) ou Arquitetura de Conjunto de Instruções se refere à interface entre o hardware (processador) e o software (programas ou sistemas operacionais) de um computador. 

##
    CAMINHO DE DADOS:
##

É a parte da CPU que contém a ULA suas entradas e suas saídas.

ULA = Unidade Lógica Aritmética
##

    TIPOS DE DADOS NUMÉRICOS MAIS COMUNS:
##
• Decimal

• Ponto fixo binário 

• Ponto flutuante binário 

##
    PARTES DA CPU:
##
• UC (Unidade de controle) = Não processa os dados, mas intepreta instruções dos programas, controla a entrada e saída de dados.

• ULA (Unidade Lógica Aritmética) = Realmente processa os dados, trabalhando com cálculos, e está situada a nível de microarquitetura. 

• Registradores = Pequenas porções de memória volátil, com dados apagados na ausência de energia, pequena capacidade de armazenamento. 
 
 ex: registrador PC (program counter) = contém o endereço da próxima instrução a ser lida. 

## 

       INTERRUPÇÃO           X           EXCEÇÃO 
##

➔ Interrupções são mecanismos ASSÍNCRONOS usados pra avisar que algo está ocorrendo na CPU, podem ser coisas como:

• interrupção de programa

• interrupção de temporização

• falha de hardware

• interrupção de E/S (entrada/saída)

➔ Quando ocorre uma interrupção, a CPU para o que está fazendo para executar um tratador de interrupção que é um bloco especial de código. Com isso,
ocorre uma mudança no fluxo de controle gerada pelo hardware. 

➔ Interrupções de software e hardware podem sim com partilhar o mesmo vetor de interrupções. 

## 

➔ Exceções são SÍNCRONAS e nelas ocorre uma chamada de procedimento automática gerada pelo SOFTWARE. Essas são as principais diferenças entre
interrupção e exceção.

##
    ANOTAÇÕES PESSOAIS DAS EXPLICAÇÕES:
##

• De acordo com o pulso do clock, a informação leva um tempo Δt para registrar, a informação fica registrada nele de acordo com a forma como estava no momento
em que chegou. 

ex: chegou 0, fica 0. 

• A CPU possio um tempo de propagação dos dados, que são Δw, Δx, Δy e Δz, se esse tempo for menor do que o necessário, os dados não serão processados
corretamente, o PC pode dar tela azul. Isso acontece se tirarmos o cooler do processador.
Daí que vem a ideia do Overclock = resfriar ao máximo o material do processador para que as informações trafeguem com uma velocidade maior. 

• Um processador de 4Ghz suporta até 4,4GHz em média, por causa dos 10% de backup de segurança do fabricante, para que o usuário consiga usá-lo com um 
cooler mediano.

• As memórias DRAM e RAM em geral, acessam suas células com a mesma velocidade, independendo do lugar em que estão localizados na placa; por isso,
as linhas de endereço da informação acessada não têm como influenciar na velocidade de desempenho, já a velocidade do barramento sim, pois é ele que
conecta a memória com a placa da CPU. 

##
     OPERAÇÕES MONÁDICAS          X          OPERAÇÕES DIADÁTICAS:
##

➔ Operações monádicas são aquelas que requerem só um operando (valor) como entrada. Essas operações atuam em um único valor e retornam um resultado baseado
nesse único valor. Ou seja, são funções ou operadores unários, pois trabalham com apenas um argumento.

➔ Operações diadáticas combinam 2 operandos para produzir um resultado. 

##

     FLUXO DE CONTROLE:
##

Sequência de execução realizada pela máquina enquanto um programa está rodando. Ou seja, é a maneira e a ordem que o PC acha melhor para realizar suas 
atividades durante a execução de alguma coisa. 

##

    EXPANSÃO DE OPCODES:
## 

•  Opcode: na memória só é possível guardar valores binários que representam as instruções ao processador, estes são os opcodes, valores binários
que representam instruções.

• Já a expansão de opcodes é um fenômeno que pode acontecer em arquiteturas de processadores ou sistemas que usam instruções de tamanho fixo pra
representar operações e dados. 

Para aprender a fazer uma expansão de opcodes (já caiu na prova), recomendo os vídeos:

• https://youtu.be/GtVzFCPmRs0

• https://youtu.be/pAqZwnlmExs

## 
    PROCEDIMENTO          X          CORROTINA: 
##

• São conceitos relacionados à programação e ao gerenciamento de fluxo de controle. Os dois são blocos de código que podem ser chamados
de diferentes partes de um programa principal para executar uma tarefa específica.

• No procedimento a execução é sempre da primeira linha, e quando chega no final ele volta ao início.

• Na corrotina, a execução volta do lugar que tinha parado no programa principal.

##
➔ O que são instruções?

São opcodes de tamanho fixo ou variável que estão associados à informações como de onde vêm e para onde vão os operandos.
##

     MODOS DE ENDEREÇAMENTO: DMA (Data Management access)
##

➔ Imediato: valor do operando é especificado diretamente na instrução, o que economiza tempo para não ter que acessar a memória, 
mas a desvantagem é que o tamanho do operando é limitado pelo tamanho do campo de endereço da instrução.
##
➔ Direto: nesse tipo, é necessário acessar a memória, pois o campo de endereço da instrução contém o endereço do operando da memória, 
mas é mais vantajoso em questão de largura, dependendo da sua memória, pois ele estará limitado à largura permitida pela memória e não
mais pelo campo de endereço da instrução. 
##
➔ Indireto: contém acessos múltiplos à memória, causando desvantagem temporária, pois o campo de endereço da instrução contém um endereço
da memória cujo conteúdo é o endereço do operando na memória. Mas a vantagem é a maior possibilidade de endereços. 
##
➔ Por registrador: O campo de endereço da instrução contém, agora, o endereço de um registrador, que responde bem mais rápido do que a 
memória principal, mas possui desvantagem na quantidade de endereços a serem acessados. 
##
➔ Indireto por registrador: O campo de endereço da instrução contém um endereço de um registrador, e este, por sua vez, contém o endereço
efetivo do operando que está na memória principal; isso aumenta a capacidade de acesso aos endereços, é mais vantajoso que o endereçamento
indireto. 
##

Esse conteúdo é um pouco complicado de digerir, portanto, recomendo fortemente o vídeo:

https://www.youtube.com/watch?v=VS-V6FFKr6s

##
     PIPELINE
##

• É uma técnica de paralelismo (você estudará melhor o paralelismo na unidade 3) usada nas arquiteturas atuais para reduzir o tempo de execução de tarefas, sendo assim, várias tarefas executam simultaneamente usando recursos diferentes. 

• Os pipelines ajudam a simplificar o desenvolvimento de sistemas complexos, que ficam mais modulares e organizados; também facilitam a reutilização de etapas de processamento e permitem que diferentes equipes trabalhem em paralelo, concentrando-se em tarefas específicas do pipeline.
##
     Questões comuns de caírem nas provas:


[2-av-OAC.pdf](https://github.com/LumaSousa/Resumos-de-OAC/files/12234836/2-av-OAC.pdf)

##














