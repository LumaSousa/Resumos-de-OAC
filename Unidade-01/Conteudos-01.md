➔ Diferenças entre arquitetura e organização de computadores:
##

        ARQUITETURA                   X                 ORGANIZAÇÃO:        

• Arquitetura refere-se às características do sistema que são visíveis ao programador.            
                            
• Também descreve o que o computador é capaz de fazer          

• ex: endereçamento, instruções;

• Organização lida com o relacionamento estrutural  da máquina, por isso, é decidida depois da arquitetura.

• ex: periféricos, circuitos (unidades físicas)
##
➔ Diferenças entre nível alto e nível baixo:
##
     NÍVEL BAIXO               X               NÍVEL ALTO:

• O nível baixo é o mais próximo do hardware, em que as instruções estão codificadas.
                          
• O nível alto é o usado pelos programadores, em que o nível de abstração está mais próximo do domínio do problema.

##
➔ A maioria dos computadores modernos tem 2 ou mais níveis, mas existem máquinas com 6: 

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

• A compilação lê todo o código e substitui as instruções por um código equivalente em outra linguagem, gerando um arquivo no final.                                              
• A interpretação busca as instruções uma a uma e converte em outra linguagem, não gerando nenhum arquivo. 

(possui perda de desempenho e depende da velocidade do navegador)

 
➔ Obs: é importante lembrar que para cada arquitetura de computador existe um compilador usado. 

##
➔ Diferenças entre arquitetura RISC e CISC:
##

      ARQUITETURA RISC                  X            ARQUITETURA CISC: 
##    
RISC
##
• Conjunto reduzido de instruções  

• Não tem microprogramação    

• Baixa complexidade   

• Mais rapidez    

• A maioria das instruções é feita em apenas 1 ciclo de clock
                                        
• Uso de registradores
##
CISC
##
• Conjunto complexo de instruções

• Possui microprogramação

• Recebe mais instruções

• É mais lento

• Possui clock elevado
##
➔ O que é microarquitetura? 

É a organização interna de um processador, que inclui todos os mini componentes dele.

➔ O que é microprogramação? 

É uma técnica utilizada em processadores para implementar as instruções de máquina de uma arquitetura específica.
Essa técnica permite que alterações sejam feitas no processador sem precisar mexer nele fisicamente. 

##
         HIERARQUIA DE MEMÓRIA
##

Chamamos de hierarquia de memória a organização em níveis de armazenamento de um sistema. São eles:

1 - Registrador: são os mais rápidos e próximos ao processador.                           
2 - Memória cache: é utilizada para acessar as informações mais frequentemente usadas.                         
3 - Memória principal (RAM): usada para armazenar coisas que o PC não está usando ativamente.                                         
4 - SSD / HD (memórias secundárias): usado para armazenar dados permanentemente, mesmo quando desligar o PC.

##
         MEMÓRIAS:
##

• tipo ROM (Read-only memory): Memória apenas de leitura, não são voláteis, gravadas apenas 1 vez.

• PROM (Programmable read-only memory ): 1 gravação de dados, sem poder apagar;

• EPROM (Erasable programmable read-only memory ): permite 1 regravação de dados;

• EEPROM (Electrically erasable programmable read-only memory): permite regravação elétrica de dados;

• EAROM (Electrically alterable read-only memory): tem a mesma função da EEPROM, mas com vida útil maior e mais rápida;

##
• tipo RAM (Random-acess memory)

➔ SRAM (Static random-acess memory): 

• Rápida e estática 

• Composta de flip-flops e transistores, por isso não necessita de constante atualização.

• Costuma custar mais caro

➔ DRAM (Dynamic random-acess memory):

• Capacidade alta

• Acesso mais lento

• Preço mais baixo 

• Baseada em capacitores

• Precisa de constante atualização pra evitar que os dados sejam perdidos. 

##
     BARRAMENTOS 
     
São linhas de comunicação que o PC usa para interligar suas partes. 

ex: portas USB(barramento serial), PCI(entradas maiores), barramento SATA(entrada do HD)

➔ obs: Quanto mais linhas de endereço tiver um barramento, mais memória a CPU pode endereçar diretamente.

➔ obs: PCI express é a versão mais evoluída do PCI e tem maior taxa de transferência. 

##
     ARBITRAÇÃO 
     
Garante que cada componente do PC receba o tempo adequado para executar suas tarefas de forma justa e eficiente.
## 
     TEMPORIZAÇÃO
     
Os sinais no barramento podem ser sincronizados com um clock central, para garantir uma boa execução das tarefas. 
##
     LARGURA
     
Refere-se ao número de endereços e número de linhas de dados.

##

     BIG ENDIAN     X     LITTLE ENDIAN   

• Essas ideias são as formas como computadores armazenam informações binárias na memória. Eles usam bytes, que são grupos de 8 bits, para armazenar dados. Por exemplo, o número 12345 em binário é 0b00110000 0b00111001. (O '0b' no início indica que o número está em notação binária.)

• No Big Endian, você seguiria a leitura normalmente, começando pelo número "mais significativo" (o que naturalmente vem primeiro) 1 e indo até o "menos significativa" 5. A sequência pelo big endian ficaria: 1 -> 2 -> 3 -> 4 -> 5.

• No Little Endian, você faria o oposto. Começaria pelo menos significativo 5 e iria subindo até chegar à mais significativa 1. A sequência little endian ficaria -> 5 -> 4 -> 3 -> 2 -> 1.

Caso ainda esteja confuso, assista esse vídeo para entender melhor: 
https://www.youtube.com/watch?v=jhErugDB-34



##
     Questões comuns de caírem nas provas:

Obs: atentem-se, muitas vezes caem as mesmas questões com algum detalhe diferente, então prestem atenção.
##

[1-av-OAC.pdf](https://github.com/LumaSousa/Resumos-de-OAC/files/12234837/1-av-OAC.pdf)
##



















