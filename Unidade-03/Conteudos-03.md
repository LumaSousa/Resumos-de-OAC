##
     MEMÓRIA VIRTUAL
##
• Foi a solução encontrada para resolver o problema dos overlays (sobreposições) - que era um método de executar programas maiores em computadores de
memória minúscula- pois era muito trabalhoso para os programadores, em meados de 1960. 

• O sistema operacional da máquina é quem gerencia a memória virtual e ela permite a execução de programas que precisam de mais memória do que a física
que temos disponível. (Arquivos alocados na forma de paginação no disco rígido).

• OBS: O uso demasiado de memória virtual deixa o processamento lento. 
##
     CONCEITOS IMPORTANTES:
##
MMU: dispositivo que faz o mapeamento virtual para físico.
##
Conjunto de trabalho: páginas que o programa usa ativamente. 
##
Swapping: Essa técnica de gerenciamento de memória permite liberar espaço na memória física, deslocando páginas ou processos menos usados da memória
principal para a secundária.
##
Thread: Sequência de instruções que podem ser executadas simultaneamente com outras.
##
Processos: representa a execução de um programa em um ambiente de SO, conjunto de instruções.
## 
Arquivo: É uma unidade lógica de armazenamento de dados em um PC.
##
Diretório/pasta: Estrutura de organização hierárquica de arquivos e diretórios. 
##
Macros: são equivalentes às funções no alto nível(funções que a gente usa quando tá programando), pois realizam sequências de instruções 
que são usadas com frequência. 
##
     PAGINAÇÃO          X          SEGMENTAÇÃO 
##
• São duas técnicas que o SO usa para gerenciar a memória virtual de forma eficiente. 
##
     PAGINAÇÃO:
##

• Na paginação o espaço de endereçamento virtual é dividido em páginas (trechos de programas lidos no disco rígido)
OBS: A memória física é dividida em quadros. Cada página é mapeada para um quadro, mas isso não ocorre com todas as páginas o tempo todo. 

• Falta de página: quando o programa tenta acessar uma página virtual que não está na memória física. Então, o SO busca ela na memória secundária
(disco rígido por ex.), a página é trazida para o quadro. 

• Paginação por demanda: as páginas só são trazidas para o disco rígido quando são requisitados. 

• Em sistemas que usam paginação, é comum que as páginas sejam uma potência de 2, porque simplifica o cálculo dos deslocamentos de memória.

• LRU e FIFO: algoritmos que fazem técnicas de paginação mais eficientes.

• Fragmentação interna: espaço interno às páginas que é desperdiçado. 
##
    SEGMENTAÇÃO:
##

• Outra técnica para gerenciar memória virtual; mas, desta vez, a memória é dividida em segmentos de tamanho variável, que são partes do programa em
execução (ex: código, dados, pilhas).

• Falha de segmento: quando o programa tenta acessar um endereço virtual que não está na memória física. A solução é a mesma que a da "falta de página".
##
    BENEFÍCIOS DA SEGMENTAÇÃO:
##
• Modularidade (módulos independentes e autônomos)

• Proteção de acesso

• Compartilhamento de código e dados. 
##
    BENEFÍCIOS DA PAGINAÇÃO
##
• Compartilhamento de memória

• Melhor utilização dos recursos

• Flexibilidade no gerenciamento da memória (é usado pelo windows e linux)
##
    MODOS DE OPERAÇÃO
##
Os processadores possuem 2 modos de operação que auxiliam à multiprogramação, isso não está restrito aos multicore (vários núcleos), são eles:

• Modo de usuário: são executados programas, aplicativos e processos comuns ao usuário, projetado para manter os programas em execução seguros
e não permitir que qualquer pessoa posssa fazer alterações críticas no sistema. 

• Modo núcleo/Kernel: é o modo privilegiado de acesso aos recursos do sistema, o qual apenas o sistema operacional pode mexer. 
##
    SISTEMA OPERACIONAL
## 
• Um SO interpreta somente algumas das instruções de nível 3 porque sua função é oferecer conexão entre o hardware e o software para o usuário, já um 
microprograma, que é desenvolvido pelo fabricante do processador tem a função de controlar a operação interna do processador. 
##

    O NÍVEL DE LINGUAGEM DE MONTAGEM:
##
• Tradutores: programas que convertem um programa de usuário em uma linguagem para outra (também denominado compilador).
Primeiro gera um programa equivalente na linguagem-alvo e depois executa. 

• Tradutor = assembler

• Linguagem de montagem = assembly
##

    PARALELISMO
##
• A nível de hardware, o paralelismo no chip tem como objetivo melhorar o desempenho e a eficiência computacionais, pois realiza várias tarefas
simultaneamente. ex: pipeline
## 
• A nível de software:

Multithreading - capacidade de um sistema de executar muitas threads (sequências de instruções) ao mesmo tempo. 

• Algumas vantagens são: responsividade, aproveitamento de recuursos, melhoria do desempenho em servidores. 

• Hyperthreading: tecnologia da Intel que divide um núcleo físico de processamento em 2 núcleos lógicos. 

• Multiprocessador: vários processadores independentes trabalhando juntos em um único sistema. 

-> Homogêneo: todos os processadores do conjunto possuem a mesma arquitetura e especificações.

-> Heterogêneo: trabalha com processadores diferentes, geralmente para especificar tarefas à cada um. 

• Coprocessador: Seu objetivo principal é executar cálculos complexos, ele trabalha em conjunto com o processador principal.

• Criptoprocessador: Especializado em algoritmos de cripto/descriptografia, fornecendo um ambiente mais seguro. 

• Multicomputador: Sistema distribuído com várias unidades de processamento diferentes e memórias locais, a comunicação entre os nós é 
feita através da rede. 
##


 
