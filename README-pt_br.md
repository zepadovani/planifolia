## planifolia 0.32

`Planifolia` (do segundo nome da orquídea 'Vanilla planifolia') é um conjunto de abstrações Pure Data projetadas para funcionar sem quaisquer externais compilados.

As abstrações implementam uma série de operações úteis, como operações unárias e binárias arbitrárias em listas e arrays, quicksort, operadores lógicos para verificar a igualdade de tipos de dados arbitrários, envio/recebimento/formatação/roteamento OSC, etc. Também vem com uma GUI de matriz baseada em alternância (projetada para funcionar com objetos `iemmatrix`) e um sequenciador de passos baseado em matriz com alguns recursos não usuais (padrões de tempo, batida e duração independentes, modos col/row/colrow, cores agradáveis, etc).

Alguns bugs ainda podem estar presentes... ;)

#### abstrações

| abstração | descrição |
|---|---|
| `[any.==]` | compara tipos de dados |
| `[array.binop]` | operações binárias em arrays |
| `[array.rand]` | preenche arrays com valores aleatórios |
| `[array.unop]` | operações unárias em arrays |
| `[ls.binop]` | operações binárias em listas |
| `[ls.butlast]` | lista sem o último elemento |
| `[ls.choose]` | escolhe um elemento aleatório da lista |
| `[ls.circgroup]` | agrupa elementos em uma lista circular |
| `[ls.getRotate]` / `[ls.get]` | elemento N rotacionado de uma lista |
| `[ls.group]` | agrupa elementos em uma lista |
| `[ls.iter]` | iteração de lista |
| `[ls.last]` | último elemento da lista |
| `[ls.max]` | maior elemento de uma lista |
| `[ls.mean]` | média dos floats em uma lista |
| `[ls.min]` | menor elemento em uma lista |
| `[ls.mode]` | moda de uma lista |
| `[ls.nearest]` | obtém o valor mais próximo, índice e diferença em uma lista, dado um valor alvo |
| `[ls.quicksort]` | algoritmo quicksort implementado como uma abstração vanilla |
| `[ls.removeAt]` | remove o elemento no índice |
| `[ls.rotate]` | rotação N de uma lista |
| `[ls.scramble]` / `[ls.shuffle]` | randomiza elementos em uma lista |
| `[ls.ser.arithm]` | constrói uma lista de séries aritméticas |
| `[ls.splice]` | substitui um elemento em uma lista por outra lista |
| `[ls.sum]` | soma os elementos em uma lista |
| `[ls.unop]` | realiza operações unárias arbitrárias em elementos de uma lista |
| `[mtxgui]` | interface de matriz vanilla |
| `[mtxstep]` | sequenciador de passos vanilla com alguns recursos não usuais |
| `[osc.in]` | maneira simples de receber mensagens OSC (UDP/binário, -f -u -b) |
| `[osc.io]` / `[osc.out]` | comunicação OSC simples unidirecional ou bidirecional (via UDP/binário) |
| `[osc.match]` / `[osc.route]` | correspondência/roteamento de mensagens OSC simples |
| `[packOSC]` | alias para `[slash.oscformat]` |
| `[slash.oscformat]` | ferramenta para formatar listas OSC no estilo slash |
| `[slash.oscroute]` | ferramenta para rotear listas OSC no estilo slash |
| `[slash.rawlist]` | remove barras e retorna a lista bruta de elementos de endereço OSC e argumentos de mensagens |
| `[symbol.==]` | testa se dois símbolos são iguais |
| `[symbol.split]` | divide um símbolo de acordo com um caractere |
| `[symbol.value]` / `[symbol.v]` | armazena um valor de símbolo, assim como `[value]` faz para floats |

Amostras de percussão brasileira foram gentilmente fornecidas por [Chico Correa](https://www.youtube.com/c/ChicoCorrea).