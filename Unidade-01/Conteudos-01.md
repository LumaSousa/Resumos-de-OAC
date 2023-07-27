➔ Diferenças entre arquitetura e organização de computadores:
##

        ARQUITETURA                   X                 ORGANIZAÇÃO:

• Refere-se às características            • Lida com o relacionamento estrutural
do sistema que são visíveis ao            da máquina, por isso, é decidida depois
programador.                              da arquitetura.
• Descreve o que o computador é           • ex: periféricos, circuitos (unidades físicas)
capaz de fazer
• ex: endereçamento, instruções

##
➔ Diferenças entre nível alto e nível baixo:
##

     NÍVEL BAIXO               X               NÍVEL ALTO:

O nível baixo é o mais                  O nível alto é o usado pelos
próximo do hardware, em                 programadores, em que o nível 
que as instruções estão                 de abstração está mais próximo
codificadas.                            do domínio do problema.

##
➔ A maioria dos computadores modernos tem 2 ou mais níveis, mas existem máquinas com 6: 
##

• Nível 0 - Lógico digital (portas lógicas) -> assunto de SD1 e SD2
• Nível 1 - Microarquitetura
• Nível 2 - Conjunto de instruções
• Nível 3 - Máquina do Sistema operacional
• Nível 4 - Assembly (linguagem de montagem)
• Nível 5 - Linguagem orientada ao problema (alto nível)

##
➔ Diferenças entre compilação e interpretação:
##

   COMPILAÇÃO (TRADUÇÃO)              X               INTERPRETAÇÃO: 

Esse método lê todo o código e                 Esse método busca as instruções  
substitui as instruções por um                 uma a uma e converte em outra 
código equivalente em outra                    linguagem, não gerando nenhum arquivo. 
linguagem, gerando um arquivo                  (possui perda de desempenho e depende da
no final.                                      velocidade do navegador)

➔ Obs: é importante lembrar que para cada arquitetura de computador existe um compilador usado. 

##
➔ Diferenças entre arquitetura RISC e CISC:
##

      ARQUITETURA RISC                  X            ARQUITETURA CISC: 

• Conjunto reduzido de instruções             • Conjunto complexo de instruções
• Não tem microprogramação                    • Possui microprogramação
• Baixa complexidade                          • Recebe mais instruções
• Mais rapidez                                • É mais lento
• A maioria das instruções é feita            • Possui clock elevado
em apenas 1 ciclo de clock                                            
• Uso de registradores

➔ O que é microarquitetura? 
É a organização interna de um processador, que inclui todos os mini componentes dele.

➔ O que é microprogramação? 
É uma técnica utilizada em processadores para implementar as instruções de máquina de uma arquitetura específica.
Essa técnica permite que alterações sejam feitas no processador sem precisar mexer nele fisicamente. 

##
➔ Hierarquia de memória:
##

Chamamos de hierarquia de memória a organização em níveis de armazenamento de um sistema. São eles:

1 - Registrador: são os mais rápidos e próximos ao processador.                           
2 - Memória cache: é utilizada para acessar as informações mais frequentemente usadas.                         
3 - Memória principal (RAM): usada para armazenar coisas que o PC não está usando ativamente.                                         
4 - SSD / HD (memórias secundárias): usado para armazenar dados permanentemente, mesmo quando desligar o PC.

##
➔ Memórias:
##

• ROM (Read-only memory)
Memória apenas de leitura, não são voláteis, gravadas apenas 1 vez.

• PROM (Programmable read-only memory ): 1 gravação de dados, sem poder apagar 
• EPROM (Erasable programmable read-only memory ): permite 1 regravação de dados
• EEPROM (Electrically erasable programmable read-only memory): permite regravação elétrica de dados
• EAROM (Electrically alterable read-only memory): tem a mesma função da EEPROM, mas com vida útil maior e mais rápida.

• RAM (Random-acess memory):

SRAM (Static random-acess memory): 
• Rápida e estática
• Composta de flip-flops e transistores, por isso não necessita de constante atualização.
• Costuma custar mais caro

DRAM (Dynamic random-acess memory):
• Capacidade alta
• Acesso mais lento
• Preço mais baixo 
• Baseada em capacitores
• Precisa de constante atualização pra evitar que os dados sejam perdidos. 

##
Barramentos: são linhas de comunicação que o PC usa para interligar suas partes. 
ex: portas USB(barramento serial), PCI(entradas maiores), barramento SATA(entrada do HD)

obs: Quanto mais linhas de endereço tiver um barramento, mais memória a CPU pode endereçar diretamente.
obs: PCI express é a versão mais evoluída do PCI e tem maior taxa de transferência. 

##

Arbitração: garante que cada componente do PC receba o tempo adequado para executar suas tarefas de forma justa e eficiente.
Temporização: os sinais no barramento podem ser sincronizados com um clock central, para garantir uma boa execução das tarefas. 
Largura: refere-se ao número de endereços e número de linhas de dados.

##
