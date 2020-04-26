<h1 align="center">
 Especificação da Linguagem de programação Dart
 </h1>
 
<img src="https://miro.medium.com/max/960/0*JWyRX0OvflgVHFUF" alt="https://miro.medium.com/max/960/0*JWyRX0OvflgVHFUF" class="transparent">

<h2>
Conteúdo
</h2>

<!--
*   [Escopo](#escopo)
    *   [Philosophy](#philosophy)
    *   [Inline HTML](#html)
    *   [Automatic Escaping for Special Characters](#autoescape)
!-->


1.  [Escopo ](#escopo)
2.  [Conformidade](#comformidade)
3.  [Referências Normativas](#referênciasnormativas)
4.  [Termos e Definições](#termosedefinições)
5.  [Notação](#notação)
6.  [Visão Geral](#visãogeral)
      6.1  [Scoping](#scoping)
      6.2  [Privacidade](#privacidade)
      6.3  [Concorrência](#concorrência)
7.  [Erros e Avisos](#erroseavisos)
8.  [Variáveis](#variaveis)
      8.1  [Avaliação de getters implícitos de variáveis](#avaliaçãogetters)
9.  [Funções](#funções)
      9.1   [Declarações de funções](#declaraçãodefunções)
      9.2   [Parâmetros Formais](#parâmetrosformais)
       9.2.1  [Formalidades Necessárias](#formalidadesnecessárias)
       9.2.2  [Formalidades Opcionais](#formalidadesopocionais)
       9.2.3  [Parâmetros Covariantes](#parâmetroscovariantes)
      9.3   [Tipo de uma Função](#tipodeumafunção)
      9.4   [Funções Externas](#funçõesexternas)
 <li> Classes</li>
 <li> Métodos de instância</li>
 <li> Operadores</li>
<li>  O método NoSuchMethod</li> 
 <li> O operador '=='</li>
 <li> Getters</li>
 <li> Setters</li>
 <li> Membros de instância abstratos</li>
 <li> Variáveis ​​de instância</li>
 <li> Construtores</li>
<li>  Construtores generativos</li>
 <li> Fábricas</li>
 <li> Construtores constantes</li>
 <li> Métodos estáticos</li>
 <li> Superclasses</li>
 <li> Herança e substituição</li>
 <li> Superinterfaces</li>
 <li> Conflitos de membros da classe</li>
 <li> Interfaces</li>
 <li> Assinaturas combinadas de membros</li>
 <li> Superinterfaces</li>
 <li> Herança e substituição</li>
 <li> Substituições corretas de membros</li>
 <li> Mixins</li>
 <li> Classes Mixin</li>
<li>  Declaração Mixin</li>
 <li> Mixin</li>
 <li> Enums</li>
 <li> Genéricos</li>
 <li> Variação</li>
 <li> Tipos com limites super</li>
 <li> Instanciação ao limite</li>
 <li> Conceitos auxiliares da instanciação a serem vinculados</li>
 <li> A instanciação ao algoritmo vinculado</li>
 <li> Metadados</li>
 <li> Expressões</li>
 <li> Expression Evaluation</li>
 <li> Identidade do objeto</li>
<li>  Constantes</li>
<li>  Comentários adicionais sobre constantes e constantes potenciais</li> 
 <li> Contextos constantes</li>
<li> Nulo
 <li>Números
<li>Booleanos
<li>Strings
<li>Interpolação de strings
<li>Símbolos
<li>Listas
<li>Mapas
<li>Sets
<li>Throw
<li>Expressões funcionais
<li>Criação de Instâncias
<li>New
<li>Const
<li>Gerando um isolado
<li>Invocação da função
<li>Listas de argumentos reais
<li>Avaliação da lista de argumentos reais
<li>Vinculando dados reais a formais
<li>Invocação não qualificada
<li>Invocação de expressão de função
<li>Fechamento de funções
<li>Instanciação da função genérica
<li>Pesquisa
<li>Invocação de Getter de nível superior
<li> Invocação de método
<li>Invocação ordinária
<li> Invocações cascadas
<li> Super Invocação
<li> Enviando mensagens
<li>Extração de propriedade
<li>Obter acesso e extração de métodos
<li>Super acesso ao getter e encerramento de métodos
<li>Fechamento de membro ordinário
<li>Super Closurization
<li>Instanciação do método genérico
<li>Cessão
<li>Cessão de composto
<li>Condicional
<li>Expressões nulas
<li>Expressões booleanas lógicas
<li>Qualidade
<li>Expressões relacionais
<li>Expressões Bitwise
<li>Shift
<li>Expressões aditivas
<li>Expressões multiplicativas
<li>Expressões unárias
<li>Aguardar expressões
<li>Expressões pós-fixas
<li>Expressões atribuíveis
<li>Referência do identificador
<li>Teste de tipo
<li>Tipo de elenco
<li>Importações
<li>Exportações
<li>Peças
<li>Scripts
<li>URIs
<li>declarações 
<li>Conclusão da declaração
<li>Blocos
<li>Instruções de expressão</li>
<li>Declaração de variável local</li>
<li>Declaração de função local</li>
<li>Se</li>
<li>para</li>
<li>Para loop</li>
<li>Entrada</li>
<li>Entrada assíncrona</li>
<li>Enquanto</li>
 <li>Switch</li>
 <li>Declarações de caso de mudança</li>
<li>Try</li>
<li>cláusulas de captura</li>
<li>Retorno</li>
<li>Etiquetas</li>
<li>Break</li>
<li>Continue</li>
<li>Yield e Yield-Each</li>
<li>Rendimento</li>
<li>Yield-Each</li>
<li>Bibliotecas e scripts</li>
<li>Tipos</li>
<li>Tipos estáticos</li>
<li>Promoção de tipo</li>
<li>Sistema de tipo dinâmico</li>
<li>Aliases de tipo</li>
<li>Subtipos</li>
<li>Meta-variáveis</li>
<li>Regras de subtipo</li>
<li>Sendo um subtipo</li>
<li>Descrições informais de regras de subtipos</li>
<li>Conceitos adicionais de subtipagem</li>
<li>Tipos de funções</li>
<li>Tipo Função</li>
<li>Tipo dinâmico</li>
<li>Digite FutureOr</li>
<li>Tipo Nulo</li>
<li>Solidez do vácuo</li>
<li>Tipos parametrizados</li>
<li>Tipo de declaração real</li>
<li>Limites superiores mínimos</li>
<li>Referência
<li>Regras lexicais</li>
<li>Palavras reservadas</li>
<li>Comentários</li>
<li>Precedência do operador</li>

***

<h4>
 1. Escopo 
 </h4>
 
 
 Este padrão Ecma especifica a sintaxe e a semântica da linguagem    de programação do Dart. Ele não especifica as APIs das bibliotecas Dart, exceto se os elementos da biblioteca forem essenciais para o funcionamento correto da linguagem (por exemplo, a existência de classObject com métodos como <strong>noSuchMethod</strong>, <strong>runtimeType</strong>)
 
 
<h4>
 2. Conformidade
 </h4>
 
 Uma implementação em conformidade da linguagem de programação Dart deve fornecer e suportar todas as APIs (bibliotecas, tipos, funções, getters, setters, seja de nível superior, estático, instância ou local) exigidas nesta especificação. É permitida a implementação em conformidade de fornecer APIs adicionais, mas não sintaxe adicional, exceto para os recursos experimentais no suporte a nulos-awarecascades que provavelmente serão introduzidos na próxima revisão desta especificação.
 
 
 <h4>
 3. Referências Normativas
 </h4>
 
 Os seguintes documentos referenciados são indispensáveis para a aplicação deste documento. Para referências datadas, apenas a edição citada se aplica. Referências detalhadas, a última edição do documento referenciado (incluindo todas as emendas) se aplica.
 1. O Padrão Unicode, Versão 5.0, conforme emendado pelo Unicode 5.1.0, ou sucessor.
 2. Referência da API Dart, [API](https://api.dartlang.org/)
 
 
  <h4>
 4. Termos e Definições
 </h4>
 
 Os termos e definições usados nesta especificação são fornecidos no corpo da especificação propriamente dita. Tais termos são destacados em itálico quando são introduzidos, por exemplo, "usamos o termoverbidade para nos referir à propriedade de excesso de verborragia" e adicionamos um marcador na margem.
 
 
  <h4>
 5. Notação
 </h4>
 
 Distinguimos entre texto normativo e não normativo. O texto normativo define as regras do Dart. É fornecido nesta fonte. No momento, o texto não normativo inclui: 
 
 
 <strong>Fundamentação</strong>  -> A discussão da motivação para decisões de design de linguagem aparece em itálico. A distinção entre normativo e não normativo ajuda a esclarecer qual parte do texto é vinculativa e qual parte é meramente expositiva.
 
 <strong>Comentários</strong> -> Comentários como “O leitor cuidadoso deve ter notado que o nome Dart tem quatro caracteres que  servem para ilustrar ou esclarecer a especificação, mas são insuficientes com o texto normativo. A diferença entre comentário e lógica pode ser sutil. O comentário é mais geral do que o racional e pode incluir exemplos ou esclarecimentos ilustrativos. 
 
 <strong>Perguntas Abertas</strong> -> Perguntas abertas são pontos não resolvidos na mente do (s) autor (es) da especificação; espere que eles (as perguntas, não os autores; a precisão é importante em uma especificação) sejam eliminados na especificação final.Próximo: O texto no final do marcador anterior deve ser racional ou comentar? Palavras reservadas e identificadores internos (16.37) aparecem Os exemplos de produção de gramática são apresentados em uma variante comum do EBNF. O lado esquerdo de uma produção termina com dois pontos. No lado direito, a alternância é representada por barras verticais e a sequência por espaçamento. Como nos PEGs, a alternância dá prioridade à esquerda. Os elementos opcionais de uma produção são sufocados por um ponto de interrogação como este: anElephant ?. Anexar uma estrela a um elemento de uma produção significa que ela pode ser repetida zero ou mais vezes. Anexar uma plussign a uma produção significa que ela ocorre uma ou mais vezes. Parênteses são usados ​​para agrupar. A negação é representada prefixando um elemento de uma produção com um til. A negação é semelhante ao não combinador de PEGs, mas consome a entrada se corresponder. No contexto de uma produção lexical, ele consome um caractere único, se houver; caso contrário, um único token se houver um. Um exemplo seria:
 
 〈aProduction〉::=〈anAlternative〉
 〈anotherAlternative〉
 〈oneThing〉〈after〉 〈another〉
 〈zeroOrMoreThings〉*
 〈oneOrMoreThings〉+
 〈anOptionalThing〉?
   (〈some〉〈grouped〉〈things〉)
    ̃〈notAThing〉
    ‘aTerminal’
  〈A_LEXICAL_THING〉
 
 
  As produções sintáticas e lexicais são representadas dessa maneira.  As produções lexicais são distinguidas por seus nomes. Os nomes das produções lexicais consistem exclusivamente em caracteres maiúsculos e sublinhados. Como sempre, nas produções dramáticas, os espaços em branco e os comentários entre os elementos da produção são implicitamente ignorados, a menos que seja indicado o contrário. Os tokens de pontuação são exibidos entre aspas. O argumento fundado é incorporado, na medida do possível, na discussão dos constructos que eles representam. O termo é uma construção sintática. Pode ser considerado um pedaço de
Texto de Especificação da Linguagem de Programação Dart , que é derivável na gramática e pode ser considerado uma árvore criada por essa derivação. Um subtermo imediato de um dado termo é um construto sintático que corresponde a uma subárvore imediata considerada como uma árvore de derivação. Um subtermo de um determinado termista, ou um subtermo imediato, ou um subtermo de um subtermo imediato.
Uma listax1,. . . , x indica qualquer lista de elementos do formulárioxi, 1≤i≤n. Observe que pode ser zero; nesse caso, a lista está vazia. Usamos essas listas extensivamente em toda essa especificação. Para, seja uma entidade sintática atômica (como um identificador), uma entidade sintática xjacente (como uma expressão ou um tipo) e novamente uma entidade sintática composta. A notação [x1 / y1,. . . , xn / yn] Ethen denota uma cópia de Ein, na qual cada ocorrência de yi, 1≤i≤n foi substituída porxi. Esta operação também é conhecida como substituição e é a variante que evita a captura. Ou seja, quando Contém uma construção que a introduz em um escopo ninho por algum tempo ... n, a substituição não substitui a esse escopo. Por outro lado, se essa substituição colocar um identificador de identificação (um subtermo ofxi) em um escopo em que seja declarado, as declarações relevantes em sistematicamente denominado nomes novos. Em resumo, a liberdade de captura garante que o "significado" de cada identificador seja preservado durante a substituição. Às vezes, abusamos da lista ou mapeamos a sintaxe literal, escrevendo [o1,. . . , on] (respetivamente {k1: o1,.., kn: on}) onde theoiandkimay pode ser objetos em vez de expressões. A intenção é denotar um objeto de lista (mapear, respectivamente), cujos elementos são theoi (respectivamente, cujas chaves são os kiand e os valores são theoi). As especificações dos operadores geralmente envolvem declarações como xopyisequivalent ao método invocationx.op (y). Tais especificações devem ser entendidas como uma abreviação para: • x op é equivalente ao método invocationx.op ′ (y), assumindo que a classe de declarada realmente um método não-operador nomeado como definindo a mesma função como operador.
Essa circunlocução é necessária porqueex.op (y), em que op é um operador, não é uma sintaxe legal. No entanto, é dolorosamente detalhado e preferimos declarar esta regra uma vez aqui e usar uma notação concisa e clara em toda a especificação. Quando a especificação se refere à ordem dada no programa, significa a ordem do texto do código fonte do programa, a verificação da esquerda para a direita e de cima para baixo. Quando a especificação se refere a uma variável nova, significa uma variável com um nome que não ocorre em nenhum lugar do programa atual. Quando a especificação introduz uma variável nova vinculada a um objeto, a variável nova é vinculada implicitamente a um escopo circundante. As referências a nomes não especificados de entidades de programas (como funções de classes ou classes) são interpretados como os nomes dos membros da biblioteca principal do Dart .Exemplos seriam o classObject e o Typer, representando, respectivamente, a raiz da hierarquia de classes e a reificação dos tipos de tempo de execução. Seria possível declarar, por exemplo, uma variável local denominadaObject, por isso geralmente é incorreta
Dart Programming Language Specification9 para assumir que o nameObject será realmente resolvido para a classe principal. No entanto, geralmente omitimos mencionar isso, por uma questão de concisão. Quando a especificação diz que uma parte da sintaxe é equivalente a outra parte da sintaxe, significa que ela é equivalente em todos os aspectos, e o antigo imposto-sin deve gerar a mesma compilação. erros de tempo e têm o mesmo comportamento em tempo de execução que este último, se houver. As mensagens de erro, se houver, sempre devem se referir à sintaxe teórica. Se a execução ou avaliação de uma construção é considerada equivalente à execução ou avaliação de outra construção, apenas o comportamento em tempo de execução é equivalente e os erros em tempo de compilação aplicam-se apenas à sintaxe original. Quando a especificação diz que uma parte da sintaxe é tratada como outra parte da sintaxe ′, isso significa que a análise estática é a análise estática de ′ (em particular , exatamente os mesmos erros em tempo de compilação ocorrem). Além disso, se nenhum erro em tempo de compilação, o comportamento do tempo de execução é exatamente o comportamento da mensagem. As mensagens de erro, se houver, devem sempre se referir às sintaxes originais. Para obter mais informações sobre a análise estática e a semântica dinâmica. A noção de ser 'tratado como' é semelhante à noção de açúcar sintático: "sis tratado burro '" também poderia ter sido "sis desugared intos". É claro que deveria ser chamado de “açúcar semântico”, porque a aplicabilidade da transformação e da construção pode depender de informações da análise estática. O ponto é que apenas especificamos a análise estática e a semântica dinâmica de uma linguagem central que é um subconjunto do Dart (apenas um pouco menor que o Dart) e o desugaring transforma qualquer programa Dart em um programa nessa linguagem. Isso ajuda a manter a especificação da linguagem consistente e compreensível, porque mostra diretamente que alguns recursos da linguagem estão introduzindo semântica essencial e outros são melhor descritos como meras abreviações de construções existentes.
 
 
 
 
 
