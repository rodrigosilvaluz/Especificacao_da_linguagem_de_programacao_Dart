<h1 align="center">
 Especificação da linguagem de programação Dart
 </h1>
 
<img src="https://miro.medium.com/max/960/0*JWyRX0OvflgVHFUF" alt="https://miro.medium.com/max/960/0*JWyRX0OvflgVHFUF" class="transparent">

<h2>
Conteúdo
</h2>

<ol>
<li> Escopo  </li>
 <li> Conformidade
 <li> Referências normativas</li>
 <li> Termos e definições</li>
 <li> Notação</li>
 <li> Visão geral</li>
 <li> Escopo</li>
 <li> Privacidade</li>
 <li> Concorrência</li>
 <li> Erros e avisos</li>
 <li> Variáveis</li>
 <li> Avaliação de getters implícitos de variáveis</li>
 <li> Funções</li>
 <li> Declarações de funções</li>
 <li> Parâmetros formais</li>
 <li> Formalidades necessárias</li>
 <li> Formals opcionais</li>
 <li> Parâmetros covariantes</li>
 <li> Tipo de uma função</li>
 <li> Funções externas
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

 </ol>
 
 
 
 <h4>

#### Esse padrão Ecma especifica a sintaxe e a semântica da linguagem de programação Dart. Ele não especifica as APIs das bibliotecas Dart, exceto onde esses elementos da biblioteca são essenciais para o correto funcionamento da própria linguagem (por exemplo, a existência da classe Object com métodos como noSuchMethod, runtimeType).



## EcmaScope



### Conformidade

Uma implementação em conformidade da linguagem de programação Dart deve fornecer e suportar todas as APIs (bibliotecas, tipos, funções, getters, setters, sejam de nível superior, estático, instância ou local) exigidas nesta especificação.

Uma implementação em conformidade é permitida para fornecer APIs adicionais, mas não sintaxe adicional, exceto para recursos experimentais no suporte a cascatas com reconhecimento de nulo que provavelmente serão introduzidas na próxima revisão desta especificação.

### EcmaConformance

Referências normativas

Os seguintes documentos referenciados são indispensáveis ​​para a aplicação deste documento. Para referências datadas, apenas a edição citada se aplica. Para referências sem data, aplica-se a edição mais recente do documento referenciado (incluindo quaisquer alterações).
O Padrão Unicode, Versão 5.0, conforme emendado pelo Unicode 5.1.0 ou sucessor.

Referência da API Dart, https://api.dartlang.org/



### EcmaNormativeReferences



Termos e definições

Os termos e definições usados ​​nesta especificação são fornecidos no corpo da especificação propriamente dita. Tais termos são destacados em itálico quando são

### EcmaTermsAndDefinitions

Introduzido, por exemplo, "usamos o termo verbosidade para nos referir à propriedade de excesso de verborragia" e adicionamos um marcador na margem.

Notação

1. Âmbito


Distinguimos entre texto normativo e não normativo. O texto normativo define as regras do Dart. É fornecido nesta fonte. No momento, o texto não normativo inclui:

Fundamentação da discussão A motivação para as decisões de design de idiomas aparece em itálico. Distinguir normativo de não normativo ajuda a esclarecer qual parte do texto é vinculativa e qual parte é meramente expositiva.

Comentários Comentários como “O leitor cuidadoso deve ter notado que o nome Dart tem quatro caracteres” servem para ilustrar ou esclarecer a especificação, mas são redundantes com o texto normativo. A diferença entre comentário e lógica pode ser sutil. O comentário é mais geral do que racional e pode incluir exemplos ou esclarecimentos ilustrativos.

Perguntas abertas (a seguir: nesta fonte). Perguntas abertas são pontos que não são resolvidos na mente do (s) autor (es) da especificação; espere que eles (as perguntas, não os autores; a precisão é importante em uma especificação) sejam eliminados na especificação final. Próximos: O texto no final do marcador anterior deve ser racional ou comentar?

Palavras reservadas e identificadores internos (16.37) aparecem em negrito.

Exemplos seriam switch ou classe.

As produções gramaticais são dadas em uma variante comum do EBNF. O lado esquerdo de uma produção termina com dois pontos. No lado direito, a alternância é representada por barras verticais e a sequência por espaçamento. Como nos PEGs, a alternância dá prioridade à esquerda. Os elementos opcionais de uma produção são sufixados por um ponto de interrogação da seguinte forma: anElephant ?. Anexar uma estrela a um elemento de uma produção significa que ela pode ser repetida zero ou mais vezes. Anexar um sinal de mais a uma produção significa que ela ocorre uma ou mais vezes. Parênteses são usados ​​para agrupar. A negação é representada prefixando um elemento de uma produção com um til. A negação é semelhante ao não combinador de PEGs, mas consome entrada se corresponder. No contexto de uma produção lexical, ele consome um único caractere, se houver um; caso contrário, um único token, se houver um.

Um exemplo seria:


haProductioni :: = hanAlternativei

| hanotherAlternativei

| honeThingi hafteri hanotheri

| hzeroOrMoreThingsi *

| honeOrMoreThingsi + | hanOptionalThingi?

| (hsomei hgroupedi hthingsi)

| ˜hnotAThingi

| "ATerminal"

| hA_LEXICAL_THINGi


As produções sintáticas e lexicais são representadas dessa maneira. As produções lexicais são distinguidas por seus nomes. Os nomes das produções lexicais consistem exclusivamente em caracteres maiúsculos e sublinhados. Como sempre, nas produções gramaticais, o espaço em branco e os comentários entre os elementos da produção são implicitamente ignorados, a menos que seja declarado o contrário. Os tokens de pontuação aparecem entre aspas.
As produções estão embutidas, na medida do possível, na discussão das construções que elas representam.
Um termo é uma construção sintática. Pode ser considerado um pedaço de texto derivável da gramática e que pode ser considerado uma árvore

criado por essa derivação. Um subtermo imediato de um dado termo t é um construto sintático que corresponde a uma subárvore imediata de t considerada





como uma árvore de derivação. Um subtermo de um determinado termo t é t, ou um subtermo imediato de t, ou um subtermo de um subtermo imediato de t.

Uma lista x1, ..., xn indica qualquer lista de n elementos da forma xi, 1 ≤ i ≤ n. Observe que n pode ser zero; nesse caso, a lista está vazia. Usamos essas listas extensivamente em toda esta especificação.

Para j ∈ 1..n, seja yj uma entidade sintática atômica (como um identificador), xj uma entidade sintática composta (como uma expressão ou um tipo) e E novamente uma





entidade sintática positiva. A notação [x1 / y1, ..., xn / yn] E então denota uma cópia de E na qual cada ocorrência de yi, 1 ≤ i ≤ n foi substituída por xi.





Essa operação também é conhecida como substituição e é a variante que evita a captura. Ou seja, quando E contém uma construção que introduz yi em um escopo aninhado para alguns i ∈ 1..n, a substituição não substitui yi nesse escopo. Por outro lado, se essa substituição colocar um ID de identificador (um subtermo de xi) em um escopo em que o ID for declarado, as declarações relevantes em E serão sistematicamente renomeadas para novos nomes.

Em resumo, a liberdade de captura garante que o "significado" de cada identificador seja preservado durante a substituição.

Às vezes, abusamos da lista ou mapeamos a sintaxe literal, escrevendo [o1, ..., on] (respectivamente {k1: o1, ..., kn: on}), onde oi e ki podem ser objetos e não expressões. A intenção é denotar um objeto de lista (respectivamente mapa) cujos elementos são oi (respectivamente, cujas chaves são o ki e os valores são oi).

As especificações dos operadores geralmente envolvem declarações como x op y é





equivalente à invocação do método x.op (y). Tais especificações devem ser entendidas como um atalho para:

• x op y é equivalente à invocação do método x.op0 (y), assumindo que a classe de x realmente declarou um método não operador denominado op0 definindo a mesma função que o operador op.

Essa circunlocação é necessária porque x.op (y), em que op é um operador, não é uma sintaxe legal. No entanto, é dolorosamente detalhado, e preferimos declarar essa regra uma vez aqui e usar uma notação concisa e clara em toda a especificação.

Quando a especificação se refere à ordem fornecida no programa, significa a ordem do texto do código-fonte do programa, digitalizando da esquerda para a direita e de cima para baixo.





Quando a especificação se refere a uma variável nova, significa uma variável com um nome que não ocorre em nenhum lugar do programa atual. Quando a especificação introduz uma variável nova vinculada a um objeto, a variável nova é implicitamente vinculada a um escopo circundante.

As referências a nomes não especificados de outras entidades de programas (como classes ou funções) são interpretadas como os nomes dos membros da biblioteca principal do Dart.





Os exemplos seriam as classes Object e Type, representando, respectivamente, a raiz da hierarquia de classes e a reificação dos tipos de tempo de execução. Seria possível declarar, por exemplo, uma variável local denominada Object, por isso é geralmente incorreto assumir que o nome Object será realmente resolvido para a classe principal. No entanto, geralmente omitimos mencionar isso, por uma questão de brevidade.

Quando a especificação diz que uma parte da sintaxe é equivalente a outra parte da sintaxe, isso significa que é equivalente em todos os aspectos, e a sintaxe anterior deve gerar os mesmos erros em tempo de compilação e ter o mesmo comportamento em tempo de execução que o último , caso existam. As mensagens de erro, se houver, devem sempre se referir à sintaxe original. Se a execução ou avaliação de uma construção é considerada equivalente à execução ou avaliação de outra construção, apenas o comportamento em tempo de execução é equivalente e os erros em tempo de compilação se aplicam apenas à sintaxe original.





Quando a especificação diz que uma parte da sintaxe s é tratada como outra parte da sintaxe s0, significa que a análise estática de s é a análise estática de s0 (em particular, ocorrem exatamente os mesmos erros em tempo de compilação). Além disso, se s não possui erros em tempo de compilação, o comportamento de s em tempo de execução é exatamente o comportamento de s0.

As mensagens de erro, se houver, devem sempre se referir às sintaxes originais.

Resumindo, sempre que s é tratado como s0, o leitor deve mudar imediatamente para a seção sobre s0 para obter mais informações sobre a análise estática e a semântica dinâmica de s0.

A noção de ser 'tratado como' é semelhante à noção de açúcar sintático: "s é tratado como s0" poderia muito bem ter sido redigido "s é desugarado em s0". Obviamente, deveria ser chamado de “açúcar semântico”, porque a aplicabilidade da transformação e a construção de s0 podem depender de informações da análise estática.

O ponto é que apenas especificamos a análise estática e a semântica dinâmica de uma linguagem principal, que é um subconjunto do Dart (um pouco menor que o Dart), e o desugaring transforma qualquer programa Dart em um programa.
Estou nessa linguagem central. Isso ajuda a manter a especificação da linguagem consistente e compreensível, porque mostra diretamente que alguns recursos da linguagem estão introduzindo semântica essencial, e outros são melhor descritos como meras abreviações de construções existentes.





6 Visão geral

visão global



Dart é uma linguagem de programação pura, baseada em classe, de herança única e orientada a objetos. O dardo é opcionalmente digitado (19) e suporta genéricos reificados. O tipo de tempo de execução de cada objeto é representado como uma instância da classe Type, que pode ser obtida chamando o getter runtimeType declarado na classe Object, a raiz da hierarquia da classe Dart.

Programas de dardo podem ser verificados estaticamente. Programas com erros em tempo de compilação não possuem uma semântica dinâmica especificada. Essa especificação não tenta responder a perguntas adicionais sobre uma biblioteca ou programa no ponto em que se sabe que há um erro em tempo de compilação.

No entanto, as ferramentas podem optar por oferecer suporte à execução de alguns programas com erros. Por exemplo, um compilador pode compilar certas construções com erros, de modo que um erro dinâmico seja gerado se for feita uma tentativa de executar essa construção, ou um tempo de execução integrado ao IDE possa suportar a abertura de uma janela do editor quando essa construção for executada, permitindo que os desenvolvedores para corrigir o erro. Espera-se que esses recursos representem uma extensão natural da semântica dinâmica do Dart, conforme especificado aqui, mas, como mencionado, essa especificação não tenta especificar exatamente o que isso significa.

Conforme especificado neste documento, é garantido que as verificações dinâmicas sejam executadas em determinadas situações e certas violações do sistema de tipos lançam exceções no tempo de execução.

Uma implementação é livre para omitir essas verificações sempre que elas garantam o êxito, por exemplo, com base nos resultados da análise estática.

A coexistência entre digitação opcional e reificação é baseada no seguinte:

As informações de tipo reificado refletem os tipos de objetos em tempo de execução e sempre podem ser consultadas por construções dinâmicas de verificação de tipos (os análogos de instanceOf, cast, case type etc. em outros idiomas). As informações de tipo reificado incluem acesso a instâncias da classe Type que representa tipos, o tipo de tempo de execução (também conhecido como classe) de um objeto e os valores reais dos parâmetros de tipo para construtores e invocações de funções genéricas.

As anotações de tipo declaram os tipos de variáveis ​​e funções (incluindo métodos e construtores).

As anotações de tipo podem ser omitidas; nesse caso, geralmente são preenchidas com a dinâmica de tipo (19.7).



O dardo conforme implementado inclui amplo suporte para inferência de tipos omitidos. Essa especificação supõe que a inferência ocorreu e, portanto, os tipos inferidos já são considerados presentes no programa. No entanto, em alguns casos, nenhuma informação está disponível para inferir uma anotação de tipo omitida e, portanto, essa especificação ainda precisa especificar como lidar com isso. Uma versão futura desta especificação também especificará inferência de tipo.

Os programas Dart são organizados de forma modular em unidades chamadas bibliotecas (18). Bibliotecas são unidades de encapsulamento e podem ser recursivas mutuamente.

No entanto, eles não são de primeira classe. Para que várias cópias de uma biblioteca sejam executadas simultaneamente, é necessário gerar um isolado.

Uma execução do programa dardo pode ocorrer com asserções ativadas ou desativadas.

O método usado para ativar ou desativar asserções é específico da implementação.
6.1 Escopo

escopo



Um espaço para nome é um mapeamento de nomes que denotam declarações para declarações reais





rações. Deixe NS ser um espaço para nome. Dizemos que um nome n está em NS se n é uma chave





de NS. Dizemos que uma declaração d está em NS se uma chave de NS mapeia para d.

Um escopo S0 induz um namespace NS0 que mapeia o nome simples de cada declaração de variável, tipo ou função d declarada em S0 a d. Os rótulos não são incluídos no espaço para nome induzido de um escopo; em vez disso, eles têm seu próprio espaço para nome dedicado.





Portanto, é impossível, por exemplo, definir uma classe que declare um método e um getter com o mesmo nome no Dart. Da mesma forma, não se pode declarar uma função de nível superior com o mesmo nome que uma variável de biblioteca ou classe.

É um erro em tempo de compilação se houver mais de uma entidade com o mesmo nome declarada no mesmo escopo.

Em alguns casos, o nome da declaração difere do identificador usado para declará-la. Os setters têm nomes que são distintos dos getters correspondentes porque sempre possuem um = automaticamente adicionado no final, e unary menos tem o nome especial unary-.

O dardo tem escopo lexicamente. Os escopos podem aninhar. Um nome ou declaração d é





disponível no escopo S se d estiver no espaço de nomes induzido por S ou se d estiver disponível





no escopo lexicamente fechado de S. Dizemos que um nome ou declaração d está no escopo se d estiver disponível no escopo atual.

Se uma declaração d denominada n estiver no espaço de nomes induzido por um escopo S, então d





oculta qualquer declaração denominada n que esteja disponível no escopo lexicamente de S.





Uma conseqüência dessas regras é que é possível ocultar um tipo com um método ou variável. As convenções de nomenclatura geralmente evitam esses abusos. No entanto, o seguinte programa é legal:

classe HighlyStrung {

String () => "?";

}

Os nomes podem ser introduzidos no escopo por declarações dentro do escopo ou por outros mecanismos, como importações ou herança.

A interação do escopo e da herança lexical é sutil. Por fim, a questão é se o escopo lexical tem precedência sobre a herança ou vice-versa. Dart escolhe o primeiro.

Permitir que nomes herdados tenham precedência sobre nomes declarados localmente pode criar situações inesperadas à medida que o código evolui. Especificamente, o comportamento do código em uma subclasse pode mudar silenciosamente se um novo nome for introduzido em uma superclasse. Considerar:

biblioteca L1; biblioteca classe S {} L2; importar 'L1.dart'; foo () => 42; classe C estende S {bar () => foo ();} Agora suponha que um método foo () seja adicionado a S.

biblioteca L1; classe S {foo () => 91;} Se a herança tivesse precedência sobre o escopo lexical, o comportamento de C mudaria de maneira inesperada. Nem o autor de S nem o autor de C estão necessariamente conscientes disso. No Dart, se houver um método lexicamente visível foo (), ele sempre será chamado.

Agora considere o cenário oposto. Começamos com uma versão de S que contém foo (), mas não declaramos foo () na biblioteca L2. Novamente, há uma mudança de comportamento - mas foi o autor de L2 quem introduziu a discrepância que afeta seu código, e o novo código é lexicamente visível. Esses dois fatores aumentam a probabilidade de o problema ser detectado.

Essas considerações se tornam ainda mais importantes se introduzirmos construções como classes aninhadas, que podem ser consideradas em versões futuras da linguagem.

É claro que boas ferramentas devem procurar informar os programadores sobre tais situações (discretamente). Por exemplo, um identificador herdado e lexicamente visível pode ser destacado (via sublinhado ou colorização). Melhor ainda, a forte integração do controle de origem com ferramentas com reconhecimento de idioma detectaria essas alterações quando elas ocorrerem.

6.2 Privacidade

privacidade



O Dart suporta dois níveis de privacidade: público e privado. Uma declaração é





private se seu nome for privado, caso contrário, é público. Um nome q é privado se





qualquer um dos identificadores que compõem q é privado, caso contrário, é público. Um identificador é privado se começar com um sublinhado (o caractere _), caso contrário





é público.





Uma declaração m é acessível a uma biblioteca L se m for declarado em L ou se m for público.

Isso significa que as declarações privadas só podem ser acessadas na biblioteca em que são declaradas.

A privacidade se aplica somente a declarações dentro de uma biblioteca, não às próprias declarações da biblioteca.

As bibliotecas não se referem um ao outro pelo nome e, portanto, a idéia de uma biblioteca privada não faz sentido. Portanto, se o nome de uma biblioteca começar com um sublinhado, isso não afetará a acessibilidade da biblioteca ou de seus membros.

A privacidade é, nesse ponto, uma noção estática vinculada a um pedaço de código específico (uma biblioteca). Ele foi projetado para suportar preocupações de engenharia de software e não de segurança. Código não confiável deve sempre ser executado em outro isolado. É possível que as bibliotecas se tornem objetos de primeira classe e a privacidade seja um de noção dinâmica ligada a uma instância da biblioteca.

A privacidade é indicada pelo nome de uma declaração - portanto, a privacidade e a nomeação não são ortogonais. Isso tem a vantagem de que humanos e máquinas podem reconhecer o acesso a declarações privadas no ponto de uso sem o conhecimento do contexto do qual a declaração é derivada.



Simultaneidade

6.3 Concorrência


O código de dardo é sempre com thread único. Não há simultaneidade de estado compartilhado

em dardo. A simultaneidade é suportada por entidades do tipo ator, chamadas isoladas.

Um isolado é uma unidade de simultaneidade. Ele tem sua própria memória e seu próprio segmento de controle. Isola a comunicação por passagem de mensagem (16.21.4). Nenhum estado é compartilhado entre isolados. Os isolados são criados por desova (16.16).





7 Erros e avisos

Esta especificação distingue entre vários tipos de erros.

errorsAndWarnings



Erros em tempo de compilação são erros que impedem a execução. Um erro em tempo de compilação deve ser relatado por um compilador Dart antes que o código incorreto seja executado.

Uma implementação do Dart tem uma liberdade considerável sobre quando a compilação ocorre. As implementações modernas da linguagem de programação frequentemente intercalam a compilação e a execução, para que a compilação de um método possa ser atrasada, por exemplo, até que seja invocada pela primeira vez. Consequentemente, erros em tempo de compilação em um método m podem ser relatados até o momento da primeira chamada de m.

O dardo geralmente é carregado diretamente da fonte, sem representação binária intermediária. No interesse do carregamento rápido, as implementações do Dart podem optar por evitar a análise completa dos corpos dos métodos, por exemplo. Isso pode ser feito através da tokenização da entrada e da verificação de chaves cacheadas balanceadas na entrada do corpo do método. Nessa implementação, mesmo erros de sintaxe serão detectados apenas quando o método precisar ser executado, quando será compilado (JIT).

Em um ambiente de desenvolvimento, é claro que um compilador deve relatar erros de compilação com entusiasmo, a fim de melhor servir o programador.

Um ambiente de desenvolvimento Dart pode optar por suportar erros, eliminando transformações de programas, por exemplo, substituindo uma expressão incorreta pela invocação de um depurador. Está fora do escopo deste documento especificar como essas transformações funcionam e onde elas podem ser aplicadas.

Se ocorrer um erro não capturado em tempo de compilação no código de um isolado A em execução, A será imediatamente suspenso. A única circunstância em que um erro em tempo de compilação poderia ser detectado seria através do código executado de forma reflexiva, onde o sistema de espelhos pode detectá-lo.

Normalmente, quando um erro em tempo de compilação é gerado e A é suspenso, A será encerrado. No entanto, isso depende do ambiente geral. Um dardo





O mecanismo é executado no contexto de um incorporador, um programa que faz interface entre o mecanismo e o ambiente de computação ao redor. O incorporador geralmente será um navegador da web, mas não precisa ser; pode ser um programa C ++ no servidor, por exemplo. Quando um isolado falha com um erro em tempo de compilação, conforme descrito acima, o controle retorna para o incorporador, junto com uma exceção que descreve o problema. Isso é necessário para que o incorporador possa limpar os recursos etc. É então a decisão do incorporador terminar ou não o isolado.





Os avisos estáticos são situações que não impedem a execução, mas que são





improvável que se destine e provavelmente cause bugs ou inconvenientes. Um aviso estático deve ser relatado por um compilador Dart antes que o código associado seja executado.

Quando esta especificação diz que ocorre um erro dinâmico, significa que um





objeto de erro correspondente é lançado. Quando diz que ocorre um erro de tipo dinâmico, ele representa uma verificação de tipo com falha no tempo de execução, e o objeto lançado implementa TypeError.





Sempre que dizemos que uma exceção ex é lançada, ela age como uma expressão lançada (17.0.1) com ex como objeto de exceção e com um rastreamento de pilha correspondente.





respondendo ao estado atual do sistema. Quando dizemos que um C é lançado, onde C é uma classe, queremos dizer que uma instância da classe C é lançada.

Se uma exceção não capturada for lançada por um isolado A em execução, A será imediatamente suspenso.





8 Variáveis

variáveis



Variáveis ​​são locais de armazenamento na memória.

hvariableDeclarationi :: = hdeclaredIdentifieri (',' hidentifieri) * hdeclaredIdentifieri :: = hmetadatai covariant? hfinalConstVarOrTypei hidentifieri

hfinalConstVarOrTypei :: = htypei final? | const htypei? | hvarOrTypei

hvarOrTypei :: = var | htypei

hinitializedVariableDeclarationi :: = hdeclaredIdentifieri (pression = 'hexpressioni)? (‘, 'HinitializedIdentifieri) * hinitializedIdentifieri :: = hidentifieri (‘ =' hexpressioni)?

hinitializedIdentifierListi :: = hinitializedIdentifieri (‘, 'hinitializedIdentifieri) *

Um hvariableDeclarationi que declara duas ou mais variáveis ​​é equivalente a várias declarações de variáveis ​​que declaram o mesmo conjunto de nomes de variáveis ​​na mesma ordem, com o mesmo tipo e modificadores.

Um hinitializedVariableDeclarationi que declara duas ou mais variáveis ​​é equivalente a várias declarações de variáveis ​​que declaram o mesmo conjunto de nomes de variáveis, na mesma ordem, com a mesma inicialização, tipo e modificadores.

Por exemplo, var x, y; é equivalente a var x; variar; e String estática final s1, s2 = "foo"; é equivalente ao String estático final s1; fi estático
String nal s2 = "foo" ;.

É possível que uma declaração de variável inclua o modificador covariante. O efeito de fazer isso com uma variável de instância é descrito em outra parte (10.5). É um erro em tempo de compilação para a declaração de uma variável que não é uma variável de instância para incluir o modificador covariante.



Em uma declaração variável de uma das formas N v; N v = e; onde N é





derivado de hmetadatai hfinalConstVarOrTypei, dizemos que v é a ocorrência declarante do identificador. Para cada identificador que não é uma ocorrência declarante,





portanto, dizemos que é uma ocorrência de referência. Também abreviamos isso para dizer





que um identificador é um identificador de declaração, respectivamente, um identificador de referência.





Em uma expressão do formato e.id, é possível que e tenha o tipo estático dinâmico e o id não possa ser associado a nenhuma declaração específica denominada id no tempo de compilação, mas nessa situação o id ainda é um identificador de referência.





Uma declaração variável de inicialização é uma declaração variável cuja declaração





identificador é imediatamente seguido por '=' e uma expressão de inicialização.

Uma variável declarada no nível superior de uma biblioteca é referida como um





variável de biblioteca ou uma variável de nível superior.





Uma variável estática é uma variável que não está associada a uma instância específica, mas a uma biblioteca ou classe inteira. Variáveis ​​estáticas incluem variáveis ​​de biblioteca e variáveis ​​de classe. Variáveis ​​de classe são variáveis ​​cuja declaração é imediatamente aninhada dentro de uma declaração de classe e inclui o modificador estático. Uma variável de biblioteca é implicitamente estática. É um erro em tempo de compilação preceder uma declaração de variável de nível superior com o estático do identificador interno (16.37).





Uma variável constante é uma variável cuja declaração inclui o modificador const. Uma variável constante deve ser inicializada para uma expressão constante (16.3) ou ocorre um erro em tempo de compilação.

Uma expressão inicial de uma variável constante ocorre em um contexto constante (16.3.1), o que significa que os modificadores const não precisam ser especificados explicitamente.





Uma variável final é uma variável cuja ligação é fixada na inicialização; uma variável final v sempre se refere ao mesmo objeto após a inicialização de v. Uma variável é final se sua declaração incluir o modificador final ou o modificador const.





Uma variável mutável é uma variável que não é final.

As regras a seguir sobre getters e setters induzidos implicitamente se aplicam a todas as variáveis ​​estáticas e de instância.

Uma declaração variável de uma das formas T v; T v = e; const T v = e; T v final; ou Tv final = e; induz uma função getter implícita (10.2) com a assinatura T get v cuja chamada é avaliada como descrito abaixo (8.1). Nestes casos, o tipo estático de v é T.

Uma declaração variável de um dos formulários var v; var v = e; const v = e; v final; ou v = e final; induz uma função getter implícita com a assinatura dinâmica get v cuja chamada é avaliada conforme descrito abaixo (8.1). Nesses casos, o tipo estático de v é dinâmico (19.7).

Uma declaração de variável mutável no formato T v; ou T v = e; induz uma função setter implícita (10.3) com o conjunto de void de assinatura v = (T x) cuja execução define o valor de v no argumento de entrada x.

Uma declaração de variável mutável no formato var v; ou var v = e; induz uma função setter implícita com assinatura void set v = (dinâmico x) cuja execução define o valor de v para o argumento de entrada x.

O escopo no qual os getters e setters implícitos são introduzidos depende do tipo de declaração de variável envolvida.





Uma variável de biblioteca introduz um getter no escopo de nível superior da biblioteca anexa. Uma variável de classe estática introduz um getter estático na classe imediatamente envolvida. Uma variável de instância introduz um getter de instância na classe imediatamente envolvida.

Uma variável de biblioteca mutável introduz um setter no escopo de nível superior da biblioteca anexa. Uma variável de classe estática mutável introduz um setter estático na classe imediatamente envolvente. Uma variável de instância mutável introduz um configurador de instância na classe imediatamente envolvente.

Seja v declarada variável em uma declaração de variável de inicialização e seja a expressão de inicialização associada. É um erro em tempo de compilação se o tipo estático de e não for atribuível ao tipo declarado de v. É um erro em tempo de compilação se uma variável de instância final cuja declaração tiver uma expressão inicializadora também for inicializada por um construtor, por uma entrada formal de inicialização ou uma lista de inicializadores.

É um erro em tempo de compilação se uma variável de instância final que foi inicializada por meio de um formal de inicialização de um construtor k também é inicializada na lista de inicializadores de k (10.6.1).

Uma variável final estática v não induz um setter, portanto, a menos que um setter chamado v = esteja no escopo, é um erro em tempo de compilação a ser atribuído a v.

Da mesma forma, assignm ent uma variável de instância final v é um erro em tempo de compilação, a menos que um setter chamado v = esteja no escopo ou o receptor tenha um tipo dinâmico. v pode ser inicializado em sua declaração ou em listas de inicializadores, mas inicialização e designação não são a mesma coisa. Quando o receptor possui o tipo dinâmico, essa atribuição não é um erro em tempo de compilação, mas se não houver um configurador, ele causará um erro dinâmico.

Uma variável que não possui expressão de inicialização tem o objeto nulo (16.4) como seu valor inicial. Caso contrário, a inicialização da variável continuará da seguinte maneira:

Declarações de variáveis ​​estáticas com uma expressão inicial são inicializadas preguiçosamente (8.1).

A semântica preguiçosa é dada porque não queremos uma linguagem em que se tende a definir computações caras de inicialização, causando longos tempos de inicialização do aplicativo. Isso é especialmente crucial para o Dart, que deve oferecer suporte à codificação de aplicativos clientes.

A inicialização de uma variável de instância sem expressão de inicialização ocorre durante a execução do construtor (10.6.1).

A inicialização de uma variável de instância v com uma expressão de inicialização e prossegue da seguinte forma: e é avaliado para um objeto oe a variável v é ligada a o.

É especificado em outro lugar quando essa inicialização ocorre e em qual ambiente (p.41, 17.3, 16.17.3).

Se a expressão de inicialização for lançada, o acesso à variável não inicializada será impedido, porque será lançada a criação da instância que causou essa inicialização.

É um erro de tipo dinâmico se o tipo dinâmico de o não for um subtipo do tipo real da variável v (19.10.1).

8.1 Avaliação de Getters variáveis ​​implícitos assessmentOfImplicitVariableGetters


Seja d a declaração de uma variável estática ou de instância v. Se d for uma variável de instância, a chamada do getter implícito de v será avaliada pelo valor armazenado em v. Se d for uma variável estática (que pode ser uma variável de biblioteca ), o método getter implícito de v é executado da seguinte maneira:

• Declaração variável não constante com inicializador. Se d é uma das formas var v = e ;, T v = e ;, final v = e ;, final T v = e ;, estático v = e ;, estático T v = e; , final estático v = e; ou final estático T v = e; e nenhum valor ainda foi armazenado em v, a expressão de inicialização e é avaliada. Se, durante a avaliação de e, o getter para v for chamado, um



CyclicInitializationError é lançado. Se a avaliação de e lança uma exceção ee o rastreamento de pilha s, o objeto nulo (16.4) é armazenado em v; a execução do getter lança ee empilha os traços s. Caso contrário, a avaliação de e conseguiu produzir um objeto o; então o é armazenado em ve a execução do getter é concluída retornando o. Caso contrário, (quando um valor o tiver sido armazenado em v), a execução do getter será concluída retornando o.

• Declaração de variável constante. Se d é uma das formas const v = e ;, const T v = e ;, estática const v = e; ou const estática T v = e; o resultado do getter é o valor da expressão constante e. Observe que uma expressão constante não pode depender de si mesma, portanto, nenhuma referência cíclica pode ocorrer.

• Declaração variável sem inicializador. O resultado da execução do método getter é o valor armazenado na v. Esse pode ser o valor inicial, ou seja, o objeto nulo.

9 funções funções


Resumo de funções sobre ações executáveis.

hfunctionSignaturei :: = hmetadatai htypei? hidentifieri hformalParameterParti hformalParameterParti :: = htypeParametersi? hformalParameterListi

hfunctionBodyi :: = assíncrono? '=>' Hexpressioni ';' | (assíncrono | assíncrono '*' | sincronização '*')? hblocki hblocki :: = ‘{'hstatementsi‘}'

As funções podem ser introduzidas por declarações de função (9.1), declarações de método (10.1, 10.7), declarações getter (10.2), declarações setter (10.3) e declarações construtoras (10.6); e eles podem ser introduzidos por literais de função (16.13).

Uma função é assíncrona se seu corpo estiver marcado com async ou async *





modificador. Caso contrário, a função é síncrona. Uma função é um gerador se





seu corpo é marcado com o modificador sync * ou async *. Mais detalhes sobre esses conceitos são fornecidos abaixo.





Se uma função é síncrona ou assíncrona, é ortogonal a se é um gerador ou não. Funções de gerador são um açúcar para funções que produzem coleções de maneira sistemática, aplicando preguiçosamente uma função que gera elementos individuais de uma coleção. O Dart fornece esse tipo de açúcar no caso síncrono, em que se retorna um iterável, e no caso assíncrono, em que se retorna um fluxo. O Dart também permite funções síncronas e assíncronas que produzem um único valor.

Cada declaração que introduz uma função possui uma assinatura que especifica seu tipo de retorno, nome e parte do parâmetro formal, exceto que o tipo de retorno pode ser omitido e os getters nunca possuem uma parte formal do parâmetro. Literais de função têm uma parte formal de parâmetro, mas nenhum tipo de retorno e nenhum nome. A parte do parâmetro formal especifica opcionalmente a lista de parâmetros do tipo formal da função e sempre especifica sua lista de parâmetros formais. Um corpo de função é:

• uma instrução de bloco (17.1) contendo as instruções (17) executadas pela função, opcionalmente marcada com um dos modificadores: async, async * ou sync *. A menos que seja estaticamente conhecido que o corpo da função não pode ser concluído normalmente (isto é, não pode chegar ao fim e "cair", cf. 17.0.1), é um erro em tempo de compilação se a adição de retorno; no final do corpo, seria um erro em tempo de compilação. Por exemplo, é um erro se o tipo de retorno de uma função síncrona for int e o corpo puder ser concluído normalmente. As regras precisas são fornecidas na seção 17.12.



Como o Dart suporta chamadas de funções dinâmicas, não podemos garantir que uma função que não retorne um valor não seja usada no contexto de uma expressão. Portanto, toda função deve retornar um valor. Um corpo de função que termina sem executar um arremesso ou retornar fará com que a função retorne o objeto nulo (16.4), assim como um retorno sem uma expressão. Para funções de gerador, a situação é mais sutil. Veja mais discussões na seção 17.12.

OU

• da forma => e ou da forma assíncrona => e, que retornam o valor da expressão e como se fosse um retorno e. Os outros modificadores não se aplicam aqui, porque se aplicam apenas a geradores, discutidos abaixo. Os geradores não têm permissão para retornar um valor, os valores são adicionados ao fluxo gerado ou iteráveis ​​usando yield ou yield *. Seja T o tipo de retorno declarado da função que possui esse corpo. É um erro em tempo de compilação se uma das seguintes condições for mantida:



- A função é síncrona, T não é nula e teria sido um erro em tempo de compilação declarar a função com o corpo {return e;



} em vez de => e. Em particular, e pode ter qualquer tipo quando o tipo de retorno for nulo. Isso permite declarações concisas de funções nulas. É razoavelmente fácil entender essa função, porque o tipo de retorno está textualmente próximo da expressão retornada e. Por outro lado, retorne e; no corpo de um bloco só é permitido para um e com um dos poucos tipos estáticos específicos, porque é menos provável que o desenvolvedor entenda que o valor retornado não será usado (17.12).

- A função é assíncrona, o achatamento (T) não é nulo e teria sido um erro em tempo de compilação declarar a função com o corpo assíncrono {return e; } em vez de async => e. Em particular, e pode ter qualquer tipo quando o tipo de retorno nivelado é nulo e a lógica é semelhante ao caso síncrono.



É um erro em tempo de compilação se um modificador async, async * ou sync * estiver anexado ao corpo de um setter ou construtor.

Um setter assíncrono seria de pouca utilidade, pois os setters podem ser usados ​​apenas no contexto de uma atribuição (16.23), e uma expressão de atribuição sempre avalia o valor do lado direito da atribuição. Se o levantador realmente fez seu trabalho de forma assíncrona, pode-se imaginar que retornaria um futuro resolvido para o lado direito da tarefa depois que o levantador fizesse seu trabalho.

Um construtor assíncrono, por definição, nunca retornará uma instância da classe que pretende construir, mas retornará um futuro
. Chamar essa fera de novo seria muito confuso. Se você precisar produzir um objeto de forma assíncrona, use um método

Pode-se permitir modificadores para fábricas. Uma fábrica para o Futuro pode ser modificada por async, uma fábrica para Stream pode ser modificada por async * e uma fábrica para Iterable pode ser modificada por sincronização *. Nenhum outro cenário faz sentido porque o objeto retornado pela fábrica seria do tipo errado. Essa situação é muito incomum, portanto, não vale a pena fazer uma exceção à regra geral dos construtores para permitir isso.

É um erro em tempo de compilação se o tipo de retorno declarado de uma função marcada como assíncrona não for um supertipo de Futuro <T> para algum tipo T. É um erro em tempo de compilação se o tipo de retorno declarado de uma função marcada como sincronização * for não é um supertipo de Iterável <T> para algum tipo T. É um erro em tempo de compilação se o tipo de retorno declarado de uma função marcada como assíncrona * não for um supertipo de fluxo <T> para algum tipo T.

9.1 Declarações de função

functionDeclarations



Uma declaração de função é uma função que não é membro de uma classe nem





uma função literal. As declarações de função incluem exatamente o seguinte: funções de biblioteca, que são declarações de função no nível superior de uma biblioteca e





funções locais, que são declarações de função declaradas dentro de outras funções. As funções da biblioteca geralmente são chamadas simplesmente de funções de nível superior.

Uma declaração de função consiste em um identificador indicando o nome da função, possivelmente precedido por um tipo de retorno. O nome da função é seguido por





uma assinatura e um corpo. Para getters, a assinatura está vazia. O corpo está vazio para funções externas.

O escopo de uma função de biblioteca é o escopo da biblioteca anexa. O escopo de uma função local é descrito na seção 17.4. Nos dois casos, o nome da função está no escopo em seu escopo de parâmetro formal (9.2).

É um erro em tempo de compilação preceder uma declaração de função com o identificador interno estático.





Quando dizemos que uma função f1 encaminha para outra função f2, queremos dizer que invocar f1 faz com que f2 seja executado com os mesmos argumentos e / ou receptor que f1 e retorna o resultado da execução de f2 para o chamador de f1, a menos que f2 jogue uma exceção; nesse caso, f1 lança a mesma exceção. Além disso, usamos apenas o termo para funções sintéticas introduzido pela especificação.





9.2 Parâmetros formais

formalParameters



Toda declaração de função não getter inclui uma lista formal de parâmetros, que consiste em uma lista dos parâmetros posicionais necessários (9.2.1), seguidos por quaisquer parâmetros opcionais (9.2.2). Os parâmetros opcionais podem ser especificados como um conjunto de parâmetros nomeados ou como uma lista de parâmetros posicionais, mas não ambos.





Algumas declarações de função incluem uma lista de parâmetros de tipo formal (9), na qual





Nesse caso, dizemos que é uma função genérica. Uma função não genérica é uma função





o que não é genérico.





A parte do parâmetro formal de uma declaração de função consiste na lista de parâmetros do tipo formal, se houver, e na lista de parâmetros formais.

Os seguintes tipos de funções não podem ser genéricos: Getters, setters, operadores e construtores.

A lista formal de parâmetros de tipo de uma declaração de função introduz um novo





escopo conhecido como escopo do parâmetro de tipo da função. O escopo do parâmetro de tipo de uma função genérica f é incluído no escopo em que f é declarado. Todo parâmetro formal de tipo introduz um tipo no escopo do parâmetro de tipo.

Se existir, o escopo do parâmetro de tipo de uma função f é o escopo atual para a assinatura de f e para a própria lista formal de parâmetros de tipo; caso contrário, o escopo em que f é declarado é o escopo atual para a assinatura de f.

Isso significa que os parâmetros de tipo formal estão no escopo nos limites das declarações de parâmetro, permitindo os chamados parâmetros de tipo com limite F, como a classe C <X estende Comparable <X>> {...},

e os parâmetros de tipo formal estão no escopo um do outro, permitindo dependências como a classe D <X estende Y, Y> {...}.

A lista formal de parâmetros de uma declaração de função introduz um novo escopo





conhecido como escopo formal de parâmetros da função. O escopo formal do parâmetro de uma função não genérica f é incluído no escopo em que f é declarado. O escopo formal do parâmetro de uma função genérica f está incluído no escopo do parâmetro de tipo de f. Todo parâmetro formal introduz uma variável local no escopo do parâmetro formal. O escopo atual da assinatura da função é o escopo que inclui o escopo formal do parâmetro.





Isso significa que em uma declaração de função genérica, as anotações de tipo de retorno e tipo de parâmetro podem usar os parâmetros de tipo formal, mas os parâmetros formais não estão no escopo da assinatura.

O corpo de uma declaração de função introduz um novo escopo conhecido como





escopo do corpo da função. O escopo do corpo de uma função f é delimitado no escopo introduzido pelo escopo do parâmetro formal de f.

É um erro em tempo de compilação se um parâmetro formal for declarado como uma variável constante (8).

hformalParameterListi :: = '(') '

| '(' HnormalFormalParametersi ','? ')'

| '(' HnormalFormalParametersi ',' hoptionalFormalParametersi ')' | '(' HoptionalFormalParametersi ')'

hnormalFormalParametersi :: = hnormalFormalParameteri (',' hnormalFormalParameteri) *

hoptionalFormalParametersi :: = hoptionalPositionalFormalParametersi | hnamedFormalParametersi

hoptionalPositionalFormalParametersi :: =

‘['HdefaultFormalParameteri (', 'hdefaultFormalParameteri) *', '? ‘]’

hnamedFormalParametersi :: =

‘{'HdefaultNamedParameteri (', 'hdefaultNamedParameteri) *', '? ‘}’

As listas formais de parâmetros permitem uma vírgula à direita opcional após o último parâmetro (','?). Uma lista de parâmetros com essa vírgula à direita é equivalente em todos os aspectos à mesma lista de parâmetros sem a vírgula à direita. Todas as listas de parâmetros nesta especificação são mostradas sem uma vírgula à direita, mas as regras e a semântica se aplicam igualmente à lista de parâmetros correspondente com uma vírgula à direita.

9.2.1 Formalidades necessárias

requiredFormals



Um parâmetro formal necessário pode ser especificado de uma de três maneiras:





• Por meio de uma assinatura de função que nomeia o parâmetro e descreve seu tipo como um tipo de função (19.5). É um erro em tempo de compilação se algum valor padrão for especificado na assinatura desse tipo de função.

• Como um formal de inicialização, que é válido apenas como parâmetro para um construtor generativo (10.6.1).

• Através de uma declaração de variável comum (8).



hnormalFormalParameteri :: = hfunctionFormalParameteri

| hfieldFormalParameteri

| hsimpleFormalParameteri

hfunctionFormalParameteri :: = hmetadatai covariant? htypei? hidentifieri hformalParameterParti

hsimpleFormalParameteri :: = hdeclaredIdentifieri | hmetadatai covariant? hidentifieri

hfieldFormalParameteri :: = hmetadatai hfinalConstVarOrTypei? this '.' hidentifieri hformalParameterParti?

É possível incluir o modificador covariante em algumas formas de declaração de parâmetros. O efeito de fazer isso é descrito em uma seção separada (9.2.3).

Observe que o hnormalFormalParameteri não terminal também é usado nas regras gramaticais para parâmetros opcionais, o que significa que esses parâmetros também podem ser covariantes.

É um erro em tempo de compilação se a covariância do modificador ocorrer em um parâmetro de uma função que não é um método de instância, configurador de instância ou operador de instância.

9.2.2 Formals opcionais optionalFormals

Parâmetros opcionais podem ser especificados e fornecidos com valores padrão. hdefaultFormalParameteri :: = hnormalFormalParameteri (pression = 'hexpressioni)?

hdefaultNamedParameteri :: = hnormalFormalParameteri (pression = 'hexpressioni)? | hnormalFormalParameteri (':' hexpressioni)?

A forma hnormalFormalParameteri ':' hexpressioni é equivalente à forma hnormalFormalParameteri '=' hexpressioni. A sintaxe dos dois pontos é incluída apenas para compatibilidade com versões anteriores. Ele foi descontinuado e será removido em uma versão posterior da especificação de idioma.

É um erro em tempo de compilação se o valor padrão de um parâmetro opcional não for uma expressão constante (16.3). Se nenhum padrão for especificado explicitamente para um parâmetro opcional, será fornecido um padrão implícito de null.

É um erro em tempo de compilação se o nome de um parâmetro opcional nomeado começar com um caractere '_'.

A necessidade dessa restrição é uma conseqüência direta do fato de que a nomeação e a privacidade não são ortogonais. Se permitíssemos que os parâmetros nomeados começassem com um sublinhado, eles seriam considerados privados e inacessíveis aos chamadores de fora da biblioteca onde foi definido. Se um método fora da biblioteca substituísse um método com um nome opcional privado, não seria um subtipo do método original. O verificador estático, obviamente, sinalizaria tais situações, mas a conseqüência seria que a adição de um privado nomeado formal interromperia os clientes fora da biblioteca de uma maneira que eles não poderiam corrigir facilmente.



9.2.3 Parâmetros covariantes

O Dart permite que parâmetros formais de métodos de instância, incluindo setters e operadores, sejam declarados covariantes. A sintaxe para fazer isso é especificada em uma seção anterior (9.2.1).

É um erro em tempo de compilação se a covariância do modificador ocorrer na declaração de um parâmetro formal de uma função que não é um método de instância, um configurador de instância ou um operador.

Conforme especificado abaixo, um parâmetro também pode ser covariável por outros motivos. O efeito geral de ter um parâmetro covariante p na assinatura de um determinado método m é permitir que o tipo de p seja substituído covariantemente, o que significa que o tipo exigido no tempo de execução para um determinado argumento real pode ser um subtipo adequado de tipo que é conhecido no momento da compilação no site da chamada.

Esse mecanismo permite que os desenvolvedores solicitem explicitamente que uma garantia em tempo de compilação que seja suportada de outra forma (ou seja: que um argumento real cujo tipo estático satisfaça o requisito também o faça em tempo de execução) seja substituída por verificações dinâmicas de tipo. Em troca da aceitação dessas verificações dinâmicas de tipo, os desenvolvedores podem usar parâmetros covariantes para expressar projetos de software onde as verificações dinâmicas de tipo são conhecidas (ou pelo menos confiáveis) como bem-sucedidas, com base no raciocínio que a análise de tipo estática não captura.

Seja m uma assinatura de método com os parâmetros de tipo formal X1, ..., Xs, parâmetros formais posicionais p1, ..., pn e parâmetros formais nomeados q1, ..., qk. Seja m0 uma assinatura de método com os parâmetros de tipo formal X01, ..., X0s, parâmetros formais posicionais p01, ..., p0n0 e nomeados parâmetros formais q01, ..., q0k0.

Suponha que j ∈ 1..n0 e j ≤ n; dizemos que p0j é o parâmetro em m0 que

covariantParameters



corresponde ao parâmetro formal pj em m. Suponha que j ∈ 1..k0 e l ∈ 1..k;





dizemos que qj0 é o parâmetro em m0 que corresponde ao parâmetro formal ql em m se qj0 = ql. Da mesma forma, dizemos que o parâmetro de tipo formal Xj0 de m0





corresponde ao parâmetro formal do tipo Xj de m, para todos os j ∈ 1..s.

Isso inclui o caso em que m respectivamente m0 possui parâmetros posicionais opcionais; nesse caso, k = 0, respectivamente, k0 = 0 deve se manter, mas podemos ter n 6 = n0. O caso em que os números dos parâmetros do tipo formal diferem não é relevante.

Seja C uma classe que declara um método m que possui um parâmetro p cuja declaração possui o modificador covariante; neste caso, dizemos que o parâmetro





p é covariante-por-declaração. Nesse caso, a interface de C possui a assinatura do método m, e essa assinatura possui o parâmetro p; também dizemos que o





O parâmetro p nesta assinatura de método é covariante por declaração. finalmente, o





O parâmetro p da assinatura do método m da interface de uma classe C é covariante por declaração se uma superinterface direta de C tiver uma assinatura de método acessível m0 com o mesmo nome que m, que possui um parâmetro p0 que corresponde a p, de modo que p0 é covariante por declaração.

Suponha que C é uma classe genérica com declarações de parâmetro de tipo formal X1 estende B1 ..., Xs estende Bs, seja m uma declaração de um método de instância em C (que pode ser um método, um setter ou um operador), deixe p seja um parâmetro declarado por m, e seja T o tipo declarado de p. O parâmetro p





é covariante por classe se, para qualquer j ∈ 1..s, Xj ocorrer em uma covariante ou invariante





posição em T. Nesse caso, a interface de C também possui a assinatura do método m, e essa assinatura possui o parâmetro p; também dizemos que o parâmetro p





neste método, a assinatura é covariante por classe. Finalmente, o parâmetro p do





A assinatura de método m da interface da classe C é covariante por classe se uma superinterface direta de C tiver uma assinatura de método acessível m0 com o mesmo nome que m, que possui um parâmetro p0 que corresponde a p, de modo que p0 é covariável por classe.





Um parâmetro formal p é covariante se p é covariante por declaração ou p é covariante por classe.

É possível que um parâmetro seja simultaneamente covariante por declaração e covariante por classe. Observe que um parâmetro pode ser covariante por declaração ou covariante por classe com base em uma declaração em qualquer superinterface direta ou indireta, incluindo qualquer superclasse: As definições acima propagam essas propriedades para uma interface a partir de cada uma de suas superinterfaces diretas, mas elas por sua vez, receberá a propriedade de suas superinterfaces diretas e assim por diante.





9.3 Tipo de função

Esta seção especifica o tipo estático que é atribuído à função indicada por uma declaração de função e o tipo dinâmico do objeto de função correspondente.

Nesta especificação, a notação usada para denotar o tipo de uma função, que

typeOfAFunction



is, um tipo de função, segue a sintaxe do idioma, exceto que extends é abreviado para /. Isso significa que todo tipo de função é de uma das formas





Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k])

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}) em que T0 é o tipo de retorno , Xj são os parâmetros de tipo formal com limites Bj, j ∈ 1..s, Tj são os tipos de parâmetro formal para j ∈ 1..n + k, e xn + j são os nomes dos parâmetros nomeados para j ∈ 1. k) Os tipos de funções não genéricas são cobertos pelo caso s = 0, onde a lista de declaração de parâmetro de tipo <...> como um todo é omitida. Da mesma forma, os colchetes opcionais [] e {} são omitidos quando não há parâmetros opcionais.

Os dois formulários com opcionais cobrem os tipos de função sem opcionais quando k = 0, e todas as regras nesta especificação são tais que qualquer um dos dois formulários pode ser usado sem ambiguidade para determinar o tratamento de tipos de função sem opcionais.

Se uma declaração de função não declarar um tipo de retorno explicitamente, seu tipo de retorno é dinâmico (19.7), a menos que seja um construtor, caso em que não é considerado um tipo de retorno, ou é um setter ou operador [] = , nesse caso, seu tipo de retorno é nulo.

Uma declaração de função pode declarar parâmetros de tipo formal. O tipo da função inclui os nomes dos parâmetros de tipo e, para cada parâmetro de tipo, o limite superior, que é considerado a classe interna Object, se nenhum limite for especificado. Quando a renomeação consistente dos parâmetros de tipo pode tornar dois tipos de função idênticos, eles são considerados do mesmo tipo.

É conveniente incluir os nomes dos parâmetros de tipo formal nos tipos de função, porque eles são necessários para expressar coisas como relações entre diferentes parâmetros de tipo, limites F e os tipos de parâmetros formais. No entanto, não queremos distinguir entre dois tipos de função se eles tiverem a mesma estrutura e diferirem apenas na escolha dos nomes. Esse tratamento de nomes também é conhecido como equivalência alfa.

Nos três parágrafos a seguir, se o número m de parâmetros do tipo formal for zero, a lista de parâmetros do tipo no tipo de função será omitida.

Seja F uma função com os parâmetros de tipo X1 estendeB1, ..., Xs estendeBs, parâmetro formal exigido es T1, ..., Tn, retorne o tipo T0 e nenhum parâmetro opcional. Então o tipo estático de F é

T0 Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn).

Seja F uma função com os parâmetros de tipo X1 estende B1, ..., Xs estende Bs, exigiu os tipos formais de parâmetro T1, ..., Tn, tipo de retorno T0 e tipo de parâmetro opcional posicional Tn + 1, ..., Tn + k. Então o tipo estático de F é

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]).

Seja F uma função com os parâmetros de tipo X1 estende B1, ..., Xs estende Bs, exigiu os tipos formais de parâmetro T1, ..., Tn, tipo de retorno T0 e nomeou os parâmetros Tn + 1 xn + 1, ..., Tn + k xn + k, onde xn + j, j ∈ 1..k pode ou não ter um valor padrão. Então o tipo estático de F é

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}).

Seja T o tipo estático de uma declaração de função F. Seja u o tipo de tempo de execução de um objeto de função o obtido por fechamento de função (16.18) ou fechamento de método de instância (16.22.3) aplicado a F e seja o tipo real correspondente a T na ocasião em que o foi criado (19.10.1). T pode conter variáveis ​​de tipo livre, mas t contém seus valores reais. O seguinte deve ser mantido: u é uma classe que implementa a classe interna Function; u é um subtipo de t; e u não é um subtipo de qualquer tipo de função que seja um subtipo adequado de t. Se tivéssemos omitido o último requisito, então f é intFunction ([int]) poderia ser avaliado como verdadeiro com a declaração void f () {}, que obviamente não é a intenção.

Cabe à implementação escolher uma representação apropriada para objetos de função. Por exemplo, considere que um objeto de função produzido por meio da extração de propriedades trata a igualdade de maneira diferente de outros objetos de função e, portanto, é provavelmente uma classe diferente. As implementações também podem usar classes diferentes para objetos de função com base em arity e ou type. O Arity pode ser implicitamente afetado se uma função é um método de instância (com um parâmetro implícito de receptor) ou não. As variações são múltiplas e, por exemplo, não se pode assumir que quaisquer dois objetos de função distintos terão necessariamente o mesmo tipo de tempo de execução.

9.4 Funções externas

externalFunctions



Uma função externa é uma função cujo corpo é fornecido separadamente de sua declaração. Uma função externa pode ser uma função de nível superior (18), um método (10.1, 10.7), um getter (10.2), um setter (10.3) ou um construtor não redirecionador (10.6.1, 10.6.2). Funções externas são introduzidas através do identificador interno externo (16.37) seguido pela assinatura da função.





Funções externas nos permitem introduzir informações de tipo para código que não é estaticamente conhecido pelo compilador Dart.

Exemplos de funções externas podem ser funções externas (definidas em C ou Javascript etc.), primitivas da implementação (conforme definidas pelo sistema de tempo de execução do Dart) ou código gerado dinamicamente, mas cuja interface é conhecida estaticamente. No entanto, um método abstrato é diferente de uma função externa, pois não possui corpo.

Uma função externa é conectada ao seu corpo por um mecanismo específico de implementação. Tentar invocar uma função externa que não foi conectada ao seu corpo lançará um NoSuchMethodError ou alguma subclasse dele.

A sintaxe real é fornecida nas seções 10 e 18 abaixo.



Aulas



Uma classe define a forma e o comportamento de um conjunto de objetos que são seus





posturas. As classes podem ser definidas por declarações de classe, conforme descrito abaixo, ou por meio de aplicativos de mixin (12.3).





10 aulas


hclassDefinitioni :: = hmetadatai abstract? classe hidentifieri htypeParametersi?

hsuperclassi? hinterfacesi?

‘{'(Hmetadatai hclassMemberDefinitioni) *‘}'

| resumo hmetadatai? classe hmixinApplicationClassi htypeNotVoidListi :: = htypeNotVoidi (',' htypeNotVoidi) *

hclassMemberDefinitioni :: = hdeclarationi ';' | hmethodSignaturei hfunctionBodyi

hmethodSignaturei :: = hconstructorSignaturei hinitializersi?

| hfactoryConstructorSignaturei

| estático? hfunctionSignaturei

| estático? hgetterSignaturei

| estático? hsetterSignaturei | hoperatorSignaturei

hdeclarationi :: = hConstantConstructorSignaturei (redirecionamentos | inicializadores)?

| hconstructorSignaturei (redirecionamentos | inicializadores)? | external hconstantConstructorSignaturei

| hconstructor externoSignaturei

| (estática externa?)? hgetterSignaturei

| (estática externa?)? hsetterSignaturei

| externo? hoperatorSignaturei

| (estática externa?)? hfunctionSignaturei

| estático (final | const) htypei? hstaticFinalDeclarationListi

| htypei final? hinitializedIdentifierListi

| (estático | covariante)? (var | htypei) hinitializedIdentifierListi hstaticFinalDeclarationListi :: = hstaticFinalDeclarationi (',' hstaticFinalDeclarationi) * hstaticFinalDeclarationi: = hidentatici ‘= 'hexpressioni

É possível incluir o modificador covariante em algumas formas de declaração. O efeito de fazer isso é descrito em outra parte (9.2.3).





Uma aula

possui construtores, membros da instância e membros estáticos. Os membros da instância de uma classe são seus métodos, getters, setters e instâncias da instância





variáveis. Os membros estáticos de uma classe são seus métodos estáticos, getters, setters





e variáveis ​​de classe. Os membros de uma classe são seus membros estáticos e de instância. Uma classe tem vários escopos:





• Um escopo de parâmetro de tipo, que está vazio se a classe não for genérica (14). O escopo anexo do escopo de parâmetro de tipo de uma classe é o escopo anexo da declaração de classe.





Um escopo estático. O escopo delimitador do escopo estático de uma classe é o escopo do parâmetro de tipo (14) da classe.





• Um escopo de instância. O escopo delimitador do escopo da instância de uma classe é o escopo estático da classe.

O escopo anexo de uma declaração de membro da instância é o escopo da instância na classe em que é declarada.

O escopo delimitador de uma declaração de membro estático é o escopo estático da classe na qual é declarada.

Toda classe tem uma única superclasse, exceto a classe Object, que não possui superclasse. Uma classe pode implementar uma série de interfaces, declarando-as em sua cláusula implementa (10.9).





Uma declaração de classe abstrata é uma declaração de classe explicitamente declarada





com o modificador abstrato. Uma declaração de classe concreta é uma declaração de classe





isso não é abstrato. Uma classe abstrata é uma classe cuja declaração é abstrata,





e uma classe concreta é uma classe cuja declaração é concreta.





Queremos um comportamento diferente para classes concretas e abstratas. Se A pretende ser abstrato, queremos que o verificador estático avise sobre qualquer tentativa de instanciar A, e não queremos que o verificador se queixe de métodos não implementados em A. Por outro lado, se A tiver a intenção de ser concreto, o verificador deve avisar sobre todos os métodos não implementados, mas permitir que os clientes o instancem livremente.

A interface de uma classe C é uma interface implícita que declara assinaturas de membros da instância que correspondem aos membros da instância declarados por C e cujas superinterfaces diretas são as superinterfaces diretas de C (11, 10.9).

Quando um nome de classe aparece como um tipo, esse nome indica a interface da classe.

Uma classe concreta deve implementar totalmente sua interface: Seja C uma classe concreta com a interface I. Suponha que eu tenha uma assinatura de membro acessível m.

É um erro em tempo de compilação se C não tiver um membro acessível concreto com o mesmo nome que m, a menos que C tenha um noSuchMethod (10.1.2) não trivial. É um erro em tempo de compilação se C tiver um membro acessível concreto com o mesmo nome que m, com uma assinatura de método m0 que não seja uma substituição correta de m (11.2.2), a menos que esse membro concreto seja um encaminhador noSuchMethod (10.1 .2).

Em particular, é um erro que uma classe seja concreta, mesmo que herda uma implementação de membro para cada assinatura de membro em sua interface, a menos que cada um deles tenha parâmetros e tipos que satisfaçam a assinatura de membro correspondente. Mas quando existe um noSuchMethod não trivial, é permitido deixar alguns membros não implementados, e é permitido ter um encaminhador noSuchMethod que não satisfaça a interface da classe (nesse caso, ele será substituído por outro encaminhador noSuchMethod).

É um erro em tempo de compilação se uma classe declarar dois membros do mesmo nome, porque declara o mesmo nome duas vezes no mesmo escopo (6.1) ou porque declara um membro estático e um membro da instância com o mesmo nome ( 10.10).

Aqui estão exemplos simples, que ilustram a diferença entre "tem um membro"

e "declara um membro". Por exemplo, B declara um membro chamado f, mas possui





dois desses membros. As regras de herança determinam quais membros uma classe possui.

classe A {var i = 0; var j; f (x) => 3;

}

a classe B estende A {int i = 1; // getter ie setter i = substituem versões de A static j; // erro em tempo de compilação: getter e setter estáticos entram em conflito com // getter e setter da instância

// erro em tempo de compilação: o método estático entra em conflito com o método da instância static f (x) => 3;

}

É um erro em tempo de compilação se uma classe chamada C declarar um membro com nome de base (10.10) C. Se uma classe genérica denominada G declarar uma variável de tipo chamada X, será um erro em tempo de compilação se X for igual a G, se G tem um membro cujo nome de base é X e se G tem um construtor chamado GX





10.1 Métodos de instância

instanceMethods



Métodos de instância são funções (9) cujas declarações são imediatamente con-





mantidos em uma declaração de classe e que não são declarados estáticos. Os métodos de instância de uma classe C são os métodos de instância declarados por C e os métodos de instância herdados por C de sua superclasse (10.8.1).

Considere uma classe C. É um erro em tempo de compilação se um método de instância declarar





em C tem uma assinatura de membro m (11) que substitui uma assinatura de membro m0 de uma superinterface direta de C (11.2.1), a menos que seja um c substituição de membro orrect (11.2.2).

Este não é o único tipo de conflito que pode existir: Uma declaração de membro da instância D pode entrar em conflito com outra declaração D0, mesmo no caso em que eles não têm o mesmo nome ou não são o mesmo tipo de declaração. Por exemplo, D pode ser um getter de instância e D0 um setter estático (10.10).

Para cada parâmetro p de m em que covariante está presente, é um erro em tempo de compilação se existir uma superinterface direta ou indireta J de C que possua uma assinatura de método acessível m00 com o mesmo nome que m, de modo que m00 tenha um parâmetro p00 que corresponde a p (9.2.3), a menos que o tipo de p seja atribuível ao tipo de p00.

Isso significa que um parâmetro que é covariante por declaração pode ter um tipo que é um supertipo ou um subtipo do tipo de um parâmetro correspondente em uma superinterface, mas os dois tipos não podem ser independentes. Observe que esse requisito deve ser atendido para cada superinterface direta ou indireta separadamente, porque a atribuibilidade não é transitiva.

A superinterface pode ser o tipo estaticamente conhecido do receptor, portanto, isso significa que relaxamos o potencial relacionamento de digitação entre o tipo estaticamente conhecido de um parâmetro e o tipo que é realmente necessário em tempo de execução para o relacionamento de atribuibilidade, em vez do supertipo estrito relacionamento que se aplica a um parâmetro que não é covariante. Deve-se notar que não é estaticamente conhecido no local da chamada se algum parâmetro é covariável, porque a covariância pode ser introduzida em um subtipo apropriado do tipo estaticamente conhecido do receptor. Optamos por priorizar a flexibilidade em vez da segurança aqui, porque os parâmetros covariantes apontam que os desenvolvedores podem optar por aumentar a flexibilidade em um trade-off em que alguma segurança do tipo estático é perdida.

10.1.1 Operadores

operadores



Operadores são métodos de instância com nomes especiais.





hoperatorSignaturei :: = htypei? operador hoperatori hformalParameterListi

hoperatori :: = '~'

| hbinaryOperatori

| '[]'

| ‘[] =’

hbinaryOperatori :: = hmultiplicativeOperatori

| hadditiveOperatori

| hshiftOperatori

| hrelationalOperatori

| ‘==’

| hbitwiseOperatori

Uma declaração de operador é identificada usando o operador identificador interno (16.37).

Os seguintes nomes são permitidos para operadores definidos pelo usuário: '<', '>', '<=', '> =', '==', '-', '+', '/', '˜ /' , '*', '%', '|', 'ˆ', '&', '<<', '>>', '>>>', '[] =', '[]', '˜ '

É um erro em tempo de compilação se a aridade do operador declarado pelo usuário '[] =' não for 2. É um erro em tempo de compilação se a aridade do operador declarado pelo usuário com um dos nomes: '<' , '>', '<=', '> =', '==', '-', '+', '˜ /', '/', '*', '%', '|', ' ˆ ',' & ',' << ',' >> ',' >>> ',' [] 'não é 1. É um erro em tempo de compilação se a aridade do operador declarado pelo usuário' - ' não é 0 ou 1.

O operador "-" é único, pois duas versões sobrecarregadas são permitidas. Se o operador não tiver argumentos, indica menos unário. Se tiver um argumento, denota subtração binária.

O nome do operador unário '-' é unário -.

Este dispositivo permite distinguir os dois métodos para fins de pesquisa, substituição e reflexão de método.

É um erro em tempo de compilação se a aridade do operador declarado pelo usuário '' '' não for

0

É um erro em tempo de compilação declarar um parâmetro opcional em um operador.

É um aviso estático se o tipo de retorno de um operador declarado pelo usuário '[] =' for declarado explicitamente e não for nulo.

Se nenhum tipo de retorno for especificado para um operador declarado pelo usuário '[] =', seu tipo de retorno será nulo (9.3).

O tipo de retorno é nulo porque uma instrução de retorno em uma implementação do operador '[] =' não retorna um valor. Considere uma avaliação não lançada de uma expressão e da forma e1 [e2] = e3 e assuma que a avaliação de e3 produz uma instância o. e, então, avaliamos como o, e mesmo se o corpo executado do operador '[] =' for concluído com o valor o0, ou seja, se o0 for retornado, esse valor será simplesmente ignorado. A justificativa para esse comportamento é que as atribuições devem ter a garantia de avaliar o valor atribuído.

10.1.2 O método noSuchMethod

O método noSuchMethod é chamado implicitamente durante a execução em situações em que uma ou mais pesquisas de membros falham (16.21.1, 16.22.1, 16.23).

Podemos pensar em noSuchMethod como um backup que entra em ação quando uma chamada de um membro m é tentada, mas não existe um membro chamado m, ou existe, mas a chamada especificada tem um formato de lista de argumentos que não se encaixa na declaração de m (passando menos argumentos posicionais do que o necessário ou mais do que o suportado ou passando argumentos nomeados com nomes não declarados por m). Isso pode ocorrer apenas para uma chamada de método comum quando o receptor tiver um tipo estático dinâmico, ou para uma chamada de função quando a função chamada tiver um tipo estático Function ou dinâmico. O método noSuchMethod também pode ser chamado de outras maneiras, por exemplo, pode ser chamado explicitamente como qualquer outro método e pode estar em invocado de um encaminhador noSuchMethod, conforme explicado abaixo.

theMethodNoSuchMethod



Dizemos que uma classe C tem um noSuchMethod não trivial se C tem um





membro nomeado noSuchMethod, que é diferente daquele declarado na classe interna Object.

Observe que ele deve ser um método que aceite um argumento posicional para substituir corretamente noSuchMethod em Object. Por exemplo, ele pode ter assinatura noSuchMethod (Invocation i) ou noSuchMethod (Object i, [String s]), mas não noSuchMethod (Invocation i, String s). Isso implica que a situação em que noSuchMethod é invocado (explícita ou implicitamente) com um argumento real não pode falhar pelo motivo de “não existir esse método”, de modo que inseriríamos um loop infinito tentando invocar noSuchMethod. É possível, no entanto, encontrar um erro dinâmico durante uma invocação de noSuchMethod, porque o argumento real falha em satisfazer uma verificação de tipo, mas essa situação gera um erro de tipo dinâmico, em vez de uma tentativa repetida de invocar noSuchMethod (16.17.3 ) Aqui está um exemplo em que ocorre um erro de tipo dinâmico porque é feita uma tentativa de passar uma Invocação onde apenas o objeto nulo é aceito:

classe A {

noSuchMethod (nulo covariante n) => n;

}

vazio main () {dinâmico d = A ();

d.foo (42); // Erro de tipo dinâmico ao chamar noSuchMethod. }

Seja C uma classe concreta e L seja a biblioteca que contém as





documentação de C. O membro m é noSuchMethod encaminhado em C se um dos seguintes for verdadeiro:

• C possui um noSuchMethod não trivial, a interface de C contém m e C não possui nenhuma declaração concreta de m (ou seja, nenhum membro m é declarado ou herdado por C).

• Existe uma superinterface direta ou indireta D de C que é declarada na biblioteca L2, a interface de D contém m (o que implica que m é acessível a L2), m é inacessível a L e nenhuma superclasse de C tem um concreto declaração de m acessível a L2.





Para uma classe concreta C, um encaminhador noSuchMethod é implicitamente induzido para cada membro m que não é encaminhado noSuchMethod. Este é um membro concreto de C com a assinatura retirada da interface de C, respectivamente, D acima, e com o mesmo valor padrão para cada parâmetro opcional. Pode ser invocado em uma invocação comum e em uma superinvocação, e quando m é um método, pode ser closurized (16.22.3) usando uma extração de propriedade (16.22).





Isso implica que um encaminhador noSuchMethod tem as mesmas propriedades que um membro concreto declarado explicitamente, exceto é claro que um encaminhador noSuchMethod não impede que seja induzido. Não especificamos o corpo de um encaminhador noSuchMethod, mas ele invocará noSuchMethod e especificamos a semântica dinâmica de executá-lo abaixo.

No início desta seção, mencionamos que invocações implícitas de noSuchMethod só podem ocorrer com um receptor do tipo estático dinâmico ou uma função do tipo estático dinâmico ou Função. Com um encaminhador noSuchMethod, noSuchMethod também pode ser chamado em um receptor cujo tipo estático não é dinâmico. Nenhuma situação semelhante existe para funções, porque é impossível induzir um encaminhador noSuchMethod na classe de um objeto de função.

Para uma classe C concreta, podemos pensar em um noSuchMethod não trivial (declarado ou herdado por C) como uma solicitação de "implementação automática" de todos os membros não implementados na interface de C como encaminhadores noSuchMethod. Da mesma forma, há uma solicitação implícita para implementação automática de todos os membros inacessíveis não implementados de qualquer classe concreta, independentemente de haver ou não um noSuchMethod não trivial. Observe que o último não pode ser escrito explicitamente no Dart, porque seus nomes são inacessíveis; mas a linguagem ainda pode especificar que elas são induzidas implicitamente, porque os compiladores controlam o tratamento de nomes particulares.

É um erro em tempo de compilação se uma classe concreta C tiver uma assinatura de método encaminhado noSuchMethod S para um método chamado m, e uma superclasse de C tiver uma declaração concreta acessível de m que não seja um encaminhador noSuchMethod.

Isso só pode acontecer se essa declaração concreta não substituir corretamente S. Considere o seguinte exemplo:

classe A {

foo (int i) => nulo;

} classe abstrata B {

foo ([int i]);

}

a classe C estende A implementa B {noSuchMethod (Invocação i) => ...;

// Erro: o encaminhador substituirá ‘A.foo‘.

}

Neste exemplo, uma implementação com assinatura foo (int i) é herdada por C, e a superinterface B declara a assinatura foo ([int i]). Este é um erro em tempo de compilação porque C não possui uma implementação de método com a assinatura foo ([int]). Não queremos induzir implicitamente um encaminhador noSuchMethod com assinatura foo ([int]), porque substituiria o A.foo, e isso provavelmente será altamente confuso para os desenvolvedores. Em particular, causaria uma invocação como C (). Foo (42) invocar noSuchMethod, mesmo que seja uma invocação correta para a declaração de foo em A. Portanto, exigimos que os desenvolvedores resolvam explicitamente o conflito sempre que um encaminhador noSuchMethod induzido implicitamente substitua uma implementação herdada explicitamente declarada. Não há problema, no entanto, permitir que um encaminhador noSuchMethod substitua outro encaminhador noSuchMethod e, portanto, não há erro nessa situação.

Para a semântica dinâmica, suponha que uma classe C tenha um encaminhador noSuchMethod induzido implicitamente chamado m, com parâmetros de tipo formal X1, ..., Xr, parâmetros formais posicionais a1, ..., ak (alguns dos quais podem ser opcionais quando m = 0) e nomeou parâmetros formais com nomes x1, ..., xm (com valores padrão, como mencionado acima).

Para esse propósito, não precisamos distinguir entre uma assinatura que possui parâmetros posicionais opcionais e uma assinatura que nomeou parâmetros, porque a primeira é coberta por m = 0.

A execução do corpo de m cria uma instância im da classe predefinida Invocation, de modo que:

• im.isMethod avalia como verdadeiro se m é um método.

• im.isGetter avalia como verdadeiro se m é um getter.

• im.isSetter é avaliado como verdadeiro se m é um levantador.

• im.memberName é avaliado com o símbolo m.

• im.positionalArguments é avaliada como uma lista não modificável com os mesmos valores da lista resultante da avaliação de <Object> [a1, ..., ak].

• im.namedArguments é avaliado como um mapa não modificável com as mesmas chaves e valores que o mapa resultante da avaliação de



<Símbolo, Objeto> {# x1: x1, ..., #xm: xm}.

• im.typeArguments é avaliada como uma lista não modificável com os mesmos valores da lista resultante da avaliação de <Type> [X1, ..., Xr].



Em seguida, noSuchMethod é chamado com i como argumento real e o resultado obtido a partir dele é retornado pela execução de m.

Esta é uma invocação de método comum de noSuchMethod (16.21.1). Ou seja, um encaminhador noSuchMethod em uma classe C pode chamar uma implementação de noSuchMethod que é declarada em uma subclasse de C.

As verificações de tipo dinâmico nos argumentos reais passados ​​para m são executadas da mesma maneira que para uma chamada de um método declarado explicitamente. Em particular, um argumento real passado para um parâmetro covariante será verificado dinamicamente.

Além disso, como outras invocações de métodos comuns, é um erro de tipo dinâmico se o resultado retornado por um encaminhador noSuchMethod tiver um tipo que não seja um subtipo do tipo de retorno do encaminhador.

Um caso especial a ser observado é onde um encaminhador é arrancado e, em seguida, chamado com uma lista de argumentos real que não corresponde à lista formal de parâmetros. Nessa situação, obteremos uma invocação de Object.noSuchMethod em vez de noSuchMethod no receptor original, porque essa é uma invocação de um objeto de função (e eles não substituem noSuchMethod):

classe A {

noSuchMethod (Invocação i) => nulo; void foo ();

}

void main () {

A a = A ();

Função f = a.foo;

// Invoca ‘Object.noSuchMethod which, que lança.

f (42);

}

10.1.3 O operador '=='

O operador '==' é usado implicitamente em determinadas situações e, em particular, expressões constantes (16.3) dão origem a restrições nesse operador. Em ordem

theOperatorEqualsEquals



para especificar essas restrições apenas uma vez que introduzimos a noção de operador primitivo '==':

• Toda instância do tipo int e String possui um operador primitivo '=='.

• Toda instância do tipo Symbol que foi originalmente obtida pela avaliação de um símbolo literal ou uma invocação constante de um construtor da classe Symbol possui um operador primitivo '=='.

• Toda instância do tipo Type que foi originalmente obtida avaliando um literal de tipo constante (19.2) possui um operador primitivo '=='.

• Uma instância o tem um operador primitivo '==' se o tipo dinâmico de o for uma classe C e C tiver um operador primitivo '=='.

• A classe Object possui um operador primitivo '=='.

• Uma classe C possui um operador primitivo '==' se não tiver uma implementação do operador '==' que substitua a herdada do Object. Em particular, o seguinte possui um operador primitivo '==': O objeto nulo (16.4), objetos de função obtidos pelo fechamento de funções de um método estático ou função de nível superior (16.18), instâncias do tipo bool (16.6) e instâncias obtidas pela avaliação de uma lista literal (16.9), um mapa literal (16.10) ou um conjunto literal (16.11).





Quando dizemos que o operador '==' de uma determinada instância ou classe não é primitivo, significa que não é verdade que a instância ou classe tenha um operador primitivo '=='.



getters





10.2 Getters


Getters são funções (9) usadas para recuperar os valores das propriedades do objeto.

hgetterSignaturei :: = htypei? obter identificação

Se nenhum tipo de retorno for especificado, o tipo de retorno do getter será dinâmico.

Uma definição de getter prefixada com o modificador estático define um getter estático. Caso contrário, ele define um getter de instância. O nome do getter é fornecido pelo identificador na definição.





Os getters de instância de uma classe C são thogetters de instância declarados por C, implícita ou explicitamente, e getters de instância herdados por C de seus





superclasse. Os getters estáticos de uma classe C são aqueles getters estáticos declarados por C.

Uma declaração getter pode entrar em conflito com outras declarações (10.10). Em particular, um getter nunca pode substituir um método, e um método nunca pode substituir um getter ou uma variável de instância. As regras para quando um getter substitui corretamente outro membro são fornecidas em outro local (11.2.2).





10.3 Setters

Setters são funções (9) usadas para definir os valores das propriedades do objeto.

hsetterSignaturei :: = htypei? set hidentifieri hformalParameterListi

Se nenhum tipo de retorno for especificado, o tipo de retorno do configurador será nulo (9.3).

Uma definição de setter prefixada com o modificador estático define um setter estático. Caso contrário, ele define um configurador de instância. O nome de um setter é obtido anexando a string '=' ao identificador fornecido em sua assinatura.

Portanto, um nome de setter nunca pode entrar em conflito, substituir ou ser substituído por um getter ou método.

setters



Os configuradores de instância de uma classe C são aqueles configurados por C implícita ou explicitamente, e os configuradores herdados por C de seus





superclasse. Os setters estáticos de uma classe C são aqueles setters estáticos declarados por C, implícita ou explicitamente.

É um erro em tempo de compilação se a lista formal de parâmetros de um levantador não consistir em exatamente um parâmetro formal obrigatório p. Poderíamos aplicar isso por meio da gramática, mas precisaríamos especificar as regras de avaliação nesse caso.

É um aviso estático se um levantador declarar um tipo de retorno diferente de nulo. É um aviso estático se uma classe tiver um setter chamado v = com o tipo de argumento T e um getter chamado v com o tipo de retorno S e S não puder ser atribuído a T.

As regras para quando um levantador substitui corretamente outro membro são fornecidas em outro local (11.2.2). Uma declaração de setter também pode entrar em conflito com outras declarações (10.10).





10.4 Membros da instância abstrata

abstractInstanceMembers



Um método abstrato (respectivamente, getter abstrato ou setter abstrato) é um





método de instância, getter ou setter que não é declarado externo e não fornece uma implementação. Um método concreto (respectivamente, getter de concreto ou





setter concreto) é um método de instância, getter ou setter que não é abstrato.





Os membros da instância abstrata são úteis devido à sua interação com as classes. Toda classe Dart induz uma interface implícita, e o Dart não suporta a especificação explícita de interfaces. Usar uma classe abstrata em vez de uma interface tradicional tem vantagens importantes. Uma classe abstrata pode fornecer implementações padrão. Ele também pode fornecer métodos estáticos, evitando a necessidade de classes de serviço, como Coleções ou Listas, cujo objetivo é agrupar utilitários relacionados a um determinado tipo.

A invocação de um método abstrato, getter ou setter não pode ocorrer, porque a pesquisa (16.19) nunca produzirá um membro abstrato como resultado. Uma maneira de pensar sobre isso é que uma declaração abstrata de membro em uma subclasse não substitui ou oculta uma implementação de membro herdado. Serve apenas para especificar a assinatura do membro especificado do qual todo subtipo concreto deve ter uma implementação; isto é, contribui para a interface da classe, não para a própria classe.

O objetivo de um método abstrato é fornecer uma declaração para fins como verificação e reflexão de tipo. Em mixins, geralmente é útil introduzir essas declarações para métodos que a mixin espera que sejam fornecidos pela superclasse à qual a mixin é aplicada.

Desejamos detectar se alguém declara uma classe concreta com membros abstratos.

No entanto, um código como o seguinte deve funcionar:

classe Base {

int obtém um => 1;

}

classe abstrata Mix {

int obtém um; int obtém dois => um + um;

} classe C estende Base com Mix {}

Em tempo de execução, o método concreto declarado na Base será executado e nenhum problema deverá surgir. Portanto, nenhum erro deve ser gerado se um membro concreto correspondente existir na hierarquia.

10.5 Variáveis ​​de instância

variáveis ​​de instância



Variáveis ​​de instância são variáveis ​​cujas declarações são imediatamente con-





mantidos em uma declaração de classe e que não são declarados estáticos. As variáveis ​​de instância de uma classe C são as variáveis ​​de instância declaradas por C e as variáveis ​​de instância herdadas por C de sua superclasse.

É um erro em tempo de compilação se uma variável de instância for declarada constante.





A noção de uma variável de instância constante é sutil e confusa para os programadores. Uma variável de instância deve variar por instância. Uma variável de instância constante teria o mesmo valor para todas as instâncias e, como tal, já é uma ideia duvidosa.

A linguagem pode interpretar declarações de variáveis ​​de instância const como getters de instância que retornam uma constante. No entanto, uma variável de instância constante couNão seria tratado como uma verdadeira constante em tempo de compilação, pois seu getter estaria sujeito a substituição.

Como o valor não depende da instância, é melhor usar uma variável de classe estática. Um getter de instância para ele sempre pode ser definido manualmente, se desejado.

É possível que a declaração de uma variável de instância inclua o modificador covariant (8). O efeito disso é que o parâmetro formal do correspondente setter induzido implicitamente é considerado covariante por declaração

(9.2.3)

O modificador covariante em uma variável de instância não tem outros efeitos. Em particular, o tipo de retorno do getter implicitamente induzido já pode ser substituído covariantemente sem covariant e nunca pode ser substituído por um supertipo ou um tipo não relacionado, independentemente de o covariante modificador estar presente.

10.6 Construtores

construtores



Um construtor é uma função especial usada nas expressões de criação de instância (16.15) para obter objetos, normalmente criando ou inicializando-os.

Os construtores podem ser generativos (10.6.1) ou podem ser fábricas (10.6.2).





Um nome de construtor sempre começa com o nome de sua classe imediatamente envolvente e, opcionalmente, pode ser seguido por um ponto e uma identificação de identificador. É um erro em tempo de compilação se o nome de um construtor não for um nome de construtor.





O tipo de função de um construtor k é o tipo de função cujo tipo de retorno é a classe que contém a declaração de k e cujos tipos de parâmetros formais, opcionalidade e nomes dos parâmetros nomeados correspondem à declaração de k.

Observe que o tipo de função F de um construtor k pode conter variáveis ​​de tipo declaradas pela classe C. envolvente. Nesse caso, podemos aplicar uma substituição a F, como em [T1 / X1, ..., Tm / Xm] F, em que Xj, j ∈ 1..m são os parâmetros de tipo formal de C e Tj, j ∈ 1..m são especificados no contexto especificado. Também podemos omitir essa substituição quando o contexto fornecido é o escopo da instância de C, onde X1, ..., Xm estão no escopo.

Uma declaração de construtor pode entrar em conflito com declarações de membro estático (10.10).

Se nenhum construtor for especificado para uma classe C, ele implicitamente possui um construtor padrão C (): super () {}, a menos que C seja a classe Object.





10.6.1 Construtores generativos

generativeConstructors



Uma declaração generativa do construtor consiste em um nome do construtor, uma lista de parâmetros do construtor e uma cláusula de redirecionamento ou uma lista do inicializador e um corpo opcional.





hconstructorSignaturei :: = hidentifieri ('.' hidentifieri)? hformalParameterListi

Uma lista de parâmetros do construtor é uma lista de parênteses, separados por vírgula,





parâmetros construtores mal. Um parâmetro formal do construtor é formal





parâmetro (9.2) ou um formal de inicialização. Um formal de inicialização tem o formato this.id, em que id é o nome de uma variável de instância da classe que encerra imediatamente. É um erro em tempo de compilação se id não for uma variável de instância da classe que encerra imediatamente. É um erro em tempo de compilação se um formal de inicialização for usado por uma função que não seja um construtor generativo não redirecionador.

Se um tipo explícito é anexado ao formal de inicialização, esse é o seu tipo estático. Caso contrário, o tipo de um id nomeado formal de inicialização é Tid, em que Tid é o tipo da variável de instância nomeada id na classe que o encerra imediatamente. É um erro em tempo de compilação se o tipo estático de ID não for um subtipo de Tid.

A inicialização de formais constitui uma exceção à regra de que todo parâmetro formal introduz uma variável local no escopo do parâmetro formal (9.2). Quando a lista formal de parâmetros de um construtor generativo não redirecionador contém





qualquer formal de inicialização, um novo escopo é introduzido, o escopo formal do inicializador de parâmetros, que é o escopo atual da lista de inicializadores do construtor e que está incluído no escopo em que o construtor é declarado. Cada inicialização formal na lista de parâmetros formais introduz uma variável local final no escopo do inicializador de parâmetros formais, mas não no escopo dos parâmetros formais; todos os outros parâmetros formais introduzem uma variável local no escopo do parâmetro formal e no inicializador do parâmetro formal.





Isso significa que os parâmetros formais, incluindo os formais de inicialização, devem ter nomes distintos e que os formais de inicialização estão no escopo da lista de inicializadores, mas não no escopo do corpo do construtor. Quando um parâmetro formal introduz uma variável local em dois escopos, ainda é uma variável e, portanto, um local de armazenamento. O tipo do construtor é definido em termos de seus parâmetros formais, incluindo os formais de inicialização.

As formais de inicialização são executadas durante a execução dos construtores generativos detalhados abaixo. A execução de um this.id formal de inicialização faz com que o ID da variável de instância da classe imediatamente circundante receba o valor do valor real correspondente , a menos que o valor designado tenha um tipo dinâmico que não seja um subtipo do tipo declarado do ID da variável de instância; nesse caso, ocorrerá um erro dinâmico.

A regra acima permite que os formais de inicialização sejam usados ​​como parâmetros opcionais:

classe A {

int x;

A ([this.x]); } é legal e tem o mesmo efeito que

classe A {

int x;

A ([int x]): this.x = x;

}

Uma instância nova é uma instância cuja identidade é distinta de qualquer instância alocada anteriormente de sua classe. Um construtor generativo sempre opera em uma nova instância de sua classe imediatamente envolvente.

O acima exposto se aplica se o construtor é realmente executado, como é o novo. Se um construtor c é referenciado por const, c não pode ser executado; em vez disso, um objeto canônico pode ser procurado. Consulte a seção sobre criação de instância (16.15).

Se um construtor generativo c não for um construtor de redirecionamento e nenhum corpo for





fornecido, então c implicitamente possui um corpo vazio {}.





Redirecionando Construtores Generativos

redirectingGenerativeConstructors



Um construtor generativo pode estar redirecionando; nesse caso, sua única ação é chamar outro construtor generativo. Um construtor de redirecionamento não tem corpo; em vez disso, possui uma cláusula de redirecionamento que especifica para qual construtor a chamada é redirecionada e com quais argumentos.

hredirectioni :: = ':' this ('.' hidentifieri)? hargumentsi

Suponha que C <X1 estenda B1 ..., Xm estenda Bm> seja o nome e os parâmetros de tipo formal da classe envolvente, const? significa const ou nothing, N é C ou C.id0 para algum identificador id0 e id é um identificador. Considere uma declaração de um construtor generativo redirecionador k de uma das formas const? N (T1 x1 ..., Tn xn, [Tn + 1 xn + 1 = d1 ..., Tn + k xn + k = dk]):

R; const? N (T1 x1 ..., Tn xn, {Tn + 1 xn + 1 = d1 ..., Tn + k xn + k = dk}): R;

onde R é uma das formas this (e1 ..., ep, x1: ep + 1, ..., xq: ep + q) this.id (e1 ..., ep, x1: ep + 1, ..., xq: ep + q)





O construtor redirecionado para esta declaração é então o construtor indicado por C <X1 ..., Xm> respectivamente C <X1 ..., Xm> .id. É um tempo de compilação





erro se o tipo de lista de argumentos estáticos (16.17.1) de (e1 ..., ep, x1: ep + 1, ..., xq: ep + q) não for uma correspondência atribuível para a lista de parâmetros formal do redirecionado .

Observe que o caso em que nenhum parâmetro nomeado é passado é coberto deixando q ser zero, e o caso em que C é uma classe não genérica é coberto deixando m ser zero, nesse caso a lista de parâmetros de tipo formal e o argumento de tipo real são omitidos (14).

Exigimos uma correspondência atribuível em vez da correspondência de subtipo mais rigorosa, porque um construtor de redirecionamento generativo k chama seu redirecionado k0 de uma maneira que se assemelha à chamada de função em geral. Por exemplo, k poderia aceitar um argumento x e passar uma expressão ej usando x como xf (42) para k0, e seria surpreendente se ej estivesse sujeito a restrições mais estritas do que as aplicadas aos argumentos reais para executar invocações em geral.

Quando const? é const, é um erro em tempo de compilação se o redirecionado não for um construtor constante. Além disso, quando const? é const, cada ei, i ∈ 1..p + q, deve ser uma expressão potencialmente constante (10.6.3).

É um erro de tipo dinâmico se um argumento real passado em uma chamada de um construtor generativo de redirecionamento k não for um subtipo do tipo real

(19.10.1) do parâmetro formal correspondente na declaração de k. É um erro de tipo dinâmico se um argumento real passado ao redirecionado k0 de um construtor generativo de redirecionamento não for um subtipo do tipo real (19.10.1)





do parâmetro formal correspondente na declaração do redirecionado.





Listas do inicializador

Uma lista de inicializadores começa com dois pontos e consiste em um separador de vírgula

initializerLists



lista de inicializadores individuais.

Existem três tipos de inicializadores.

• Um superinicializador identifica um superconstrutor - ou seja, um construtor específico da superclasse. A execução do superinicializador faz com que a lista de inicializadores do superconstrutor seja executada.

• Um inicializador de variável de instância atribui um valor a uma variável de instância individual.

Uma afirmação.



hinitializersi :: = ':' hinitializerListEntryi (',' hinitializerListEntryi) *

hinitializerListEntryi :: = super hargumentsi

| super '.' hidentifieri hargumentsi

| hfieldInitializeri | hassertioni

hfieldInitializeri :: =

(esta '.')? hidentifieri '=' hconditionalExpressioni hcascadeSectioni *

Um inicializador do formulário v = e é equivalente a um inicializador do formulário





this.v = e, os dois formulários são chamados de inicializadores de variáveis ​​de instância. É um erro de compilação se a classe envolvente não declarar uma variável de instância chamada v. Caso contrário, seja T o tipo estático de v. É um erro em tempo de compilação, a menos que o tipo estático de e seja atribuível a T.





Considere um superinicializador s do formulário





super (a1, ..., an, xn + 1: an + 1, ..., xn + k

: an + k) respectivamente super.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Seja S a superclasse da classe envolvente de s. É um erro em tempo de compilação se a classe S não declarar um construtor generativo chamado S (respectivamente S.id). Caso contrário, a análise estática de s é realizada conforme especificado na Seção 16.17.3, como se super respectivamente super.id tivesse o tipo de função do construtor indicado e substituindo as variáveis ​​de tipo formais da superclasse pelos argumentos de tipo reais correspondentes passados para a superclasse no cabeçalho da classe atual.

Seja k um construtor generativo. Então k pode incluir no máximo um superinicializador em sua lista de inicializadores ou ocorrer um erro em tempo de compilação. Se nenhum superinicializador for fornecido, um superinicializador implícito do formato super () será adicionado no final da lista de inicializadores de k, a menos que a classe envolvente seja a classe Object. É um erro em tempo de compilação se um superinicializador aparecer na lista de inicializadores de k em qualquer outra posição que não no final. É um erro em tempo de compilação se mais de um inicializador correspondente a uma determinada variável de instância aparecer na lista de inicializadores de k. É um erro em tempo de compilação se a lista de inicializadores de k contiver um inicializador para uma variável que é inicializada por meio de um formal de inicialização de k. É um erro em tempo de compilação se a lista de inicializadores de k contiver um inicializador para uma variável final f cuja declaração inclua uma expressão de inicialização. É um erro em tempo de compilação se k incluir um formal de inicialização para uma variável final f cuja declaração inclua uma expressão de inicialização.

Seja f uma variável de instância final declarada na classe imediatamente envolvente. Um erro em tempo de compilação ocorre, a menos que f seja inicializado por um dos seguintes meios:

• f é declarado por uma declaração de variável de inicialização.

F é inicializado por meio de um formal de inicialização de k.

• f tem um inicializador na lista de inicializadores de k.



É um erro em tempo de compilação se a lista de inicializadores de k contiver um inicializador para uma variável que não seja uma variável de instância declarada na classe imediatamente circundante.

A lista de inicializadores pode, é claro, conter um inicializador para qualquer variável de instância declarada pela classe imediatamente circundante, mesmo que não seja final.

É um erro em tempo de compilação se um construtor generativo da classe Object incluir

um superinicializador. ExecutionOfGenerativeConstructors

Execução de Construtores Generativos

A execução de um construtor generativo k do tipo T para inicializar uma nova instância i é sempre feita com relação a um conjunto de ligações para seus parâmetros formais e os parâmetros de tipo da classe imediatamente envolvente vinculados a um conjunto de argumentos de tipo reais de T, t1 , ..., tm.

Essas ligações geralmente são determinadas pela expressão de criação da instância que invocou o construtor (direta ou indiretamente). No entanto, eles também podem ser determinados por uma chamada reflexiva.

Se k está redirecionando, sua cláusula de redirecionamento tem o formato this.g (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k)

onde g identifica outro construtor generativo da classe imediatamente circundante. Em seguida, a execução de k para inicializar i prossegue avaliando a lista de argumentos (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) para uma lista de argumentos real formulário (o1, ..., on, xn + 1: on + 1, ..., xn + k: on + k) em um ambiente em que os parâmetros de tipo da classe envolvente estão vinculados a t1, ..., tm.

Em seguida, o corpo de g é executado para inicializar i com relação às ligações que mapeiam os parâmetros formais de g para os objetos correspondentes na lista de argumentos real a, com isso associado a i, e aos parâmetros de tipo da classe imediatamente envolvida. para t1, ..., tm.

Caso contrário, k não está redirecionando. A execução prossegue da seguinte maneira:

As declarações da variável de instância da classe que encerra imediatamente são

visitados na ordem em que aparecem no texto do programa. Para cada uma dessas declarações d, se d tiver o formato hfinalConstVarOrTypei v = e; então e é avaliado para um objeto oe a variável de instância v de i é vinculada a o.

Quaisquer formals de inicialização declarados na lista de parâmetros de k são executados na ordem em que aparecem no texto do programa. Em seguida, os inicializadores da lista de inicializadores de k são executados para inicializar i na ordem em que aparecem no programa, conforme descrito abaixo (p.42).

Poderíamos observar a ordem efetuando rotinas externas, chamadas lado a lado. Então, precisamos especificar o pedido.

Então, se qualquer variável de instância i declarada pela classe imediatamente envolvente ainda não estiver vinculada a um objeto, todas essas variáveis ​​serão inicializadas com o objeto nulo (16.4).

Então, a menos que a classe envolvente seja Object, o superinicializador explicitamente especificado ou adicionado implicitamente (10.6.1) é executado para inicializar i.

Após a conclusão do superinicializador, o corpo de k é executado em um escopo em que isso está vinculado a i.

Esse processo garante que nenhuma variável de instância final não inicializada seja vista pelo código. Observe que isso não está no escopo no lado direito de um inicializador (consulte 16.14) para que nenhum método de instância possa ser executado durante a inicialização: um método de instância não pode ser chamado diretamente, nem pode ser passado para qualquer outro código

sendo invocado no inicializador. ExecutionOfInitializerLists

Execução de listas de inicializadores

Durante a execução de um construtor generativo para inicializar uma instância i, a execução de um inicializador no formato this.v = e prossegue da seguinte forma:

Primeiro, a expressão e é avaliada para um objeto o. Então, a variável de instância v de i é vinculada a o. É um erro de tipo dinâmico se o tipo dinâmico de o não for um subtipo do tipo real (19.10.1) da variável de instância v.

A execução de um inicializador que é uma asserção continua executando a asserção (17.17).

Considere um superinicializador s do formulário

super (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) respectivamente super.id (a1, ..., an, xn + 1: an + 1 , ..., xn + k: um + k).

Seja C a classe na qual s aparece e S seja a superclasse de C. Se S é genérico (14), seja u1, ..., até o tipo de argumento real passado a S, obtido pela substituição de t1, .. ., tm para os parâmetros de tipo formal de C na superclasse, conforme especificado no cabeçalho de C, e t1, ..., tm são as ligações reais das variáveis ​​de tipo de C. Seja k o construtor declarado em S e nomeado S respectivamente S.id.

A execução de s ocorre da seguinte maneira: A lista de argumentos (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) é avaliada para uma lista de argumentos real da forma (o1, ..., on, xn + 1: on + 1, ..., xn + k: on + k). Então o corpo do superconstrutor k é executado em um ambiente em que os parâmetros formais de k são vinculados aos argumentos reais correspondentes de a e os parâmetros de tipo formal de S são vinculados a u1, ..., up.



10.6.2 Fábricas

fábricas



Uma fábrica é um construtor precedido pela fábrica do identificador interno (16.37).

hfactoryConstructorSignaturei :: = identificador de fábrica ('.' identificador)? hformalParameterListi

O tipo de devolução de uma fábrica cuja assinatura é do formulário de fábrica M ou do formulário de fábrica M.id é M se M não for um tipo genérico; caso contrário, o tipo de retorno é M <T1, ..., Tn> onde T1, ..., Tn são os parâmetros de tipo da classe envolvente.

É um erro em tempo de compilação se M não for o nome da classe que encerra imediatamente.

É um erro de tipo dinâmico se uma fábrica retorna um objeto não nulo cujo tipo não é um subtipo de seu tipo de retorno real (19.10.1).

Parece inútil permitir que uma fábrica retorne o objeto nulo (16.4). Mas é mais uniforme permitir isso, como as regras atualmente permitem.

As fábricas abordam os pontos fracos clássicos associados aos construtores em outros idiomas. As fábricas podem produzir instâncias que não são alocadas recentemente: elas podem vir de um cache. Da mesma forma, as fábricas podem retornar instâncias de diferentes





Aulas.





Redirecionando construtores de fábrica

redirectingFactoryConstructors



Um construtor de fábrica de redirecionamento especifica uma chamada para um construtor de outra classe que deve ser usada sempre que o construtor de redirecionamento for chamado.

hredirectingFactoryConstructorSignaturei :: = const? hidentifieri de fábrica ('.' hidentifieri)? hformalParameterListi '=' htypeNotVoidi ('.' hidentifieri)?

Suponha que C <X1 estenda B1 ..., Xm estenda Bm> seja o nome e os parâmetros de tipo formal da classe envolvente, const? é const ou está vazio, N é C ou C.id0 para algum identificador id0, T é um nome de tipo e id é um identificador e, em seguida, considere uma declaração de um construtor de fábrica de redirecionamento k de uma das formas

const? fábrica

N (T1 x1 ..., Tn xn, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) = R;

const? fábrica

N (T1 x1 ..., Tn xn, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) = R;

onde R é uma das formas T <S1 ..., Sp> ou T <S1 ..., Sp> .id.

É um erro em tempo de compilação se T não denotar uma classe acessível no escopo atual. Se T denotar essa classe D, será um erro em tempo de compilação se R não denotar um construtor. Caso contrário, é um erro em tempo de compilação se R





denota um construtor generativo e D é abstrato. Caso contrário, o construtor redirecionado para esta declaração é o construtor indicado por R.





Um construtor de fábrica de redirecionamento q0 é acessível por redirecionamento a partir de um redirecionador





construtor de fábrica q iff q0 é o construtor redirecionado de q ou q00 é o construtor redirecionado de q e q0 é acessível por redirecionamento a partir de q00. É um erro em tempo de compilação se um construtor de fábrica de redirecionamento puder ser acessado por redirecionamento.

Seja Ts o tipo de lista de argumentos estáticos (16.17.1) (T1 ..., Tn + k) quando k não aceita argumentos nomeados e (T1 ..., Tn, Tn + 1 xn + 1, ..., Tn + k xn + k) quando k recebe alguns argumentos nomeados. É um erro em tempo de compilação se Ts não for uma correspondência de subtipo para a lista formal de parâmetros do redirecionado.

Exigimos uma correspondência de subtipo (em vez da correspondência atribuível mais perdoável que é usada com um construtor de redirecionamento generativo), porque um construtor de redirecionamento de fábrica k sempre chama seu redirecionado k0 com exatamente os mesmos argumentos reais que k recebeu. º 
significa que um downcast em um argumento real "entre" k e k0 não seria usado porque o argumento real tem o tipo exigido por k0 ou seria um erro dinâmico que simplesmente atrasa uma única etapa.

Observe que o caso não genérico é coberto por permitir que m ou p ou ambos sejam zero, caso em que a lista formal de parâmetros de tipo da classe C e / ou a lista real de argumentos de tipo do construtor redirecionado é omitida (14).

É um erro em tempo de compilação se k especificar explicitamente um valor padrão para um parâmetro opcional.

Os valores padrão especificados em k seriam ignorados, pois são os parâmetros reais que são passados ​​para k0. Portanto, os valores padrão não são permitidos.

É um erro em tempo de compilação se um parâmetro formal de k0 tiver um valor padrão cujo tipo não seja um subtipo da anotação de tipo no parâmetro formal correspondente em k.

Observe que não é possível modificar os argumentos que estão sendo passados ​​para k0.

À primeira vista, pode-se pensar que os construtores de fábricas comuns poderiam simplesmente criar instâncias de outras classes e devolvê-las, e que o redirecionamento de fábricas é desnecessário. No entanto, o redirecionamento de fábricas tem várias vantagens:

• Uma classe abstrata pode fornecer um construtor constante que utiliza o construtor constante de outra classe.

• Um construtor de fábrica de redirecionamento evita a necessidade de encaminhadores repetirem os parâmetros formais e seus valores padrão.



É um erro em tempo de compilação se k for prefixado com o modificador const, mas k0 não for um construtor constante (10.6.3).

Seja T1, ..., Tm os argumentos de tipo reais passados ​​para k0 na declaração de k. Seja X1, ..., Xm os argumentos de tipo formal declarados pela classe que contém a declaração de k0. Seja F0 o tipo de função de k0 (10.6). É um erro em tempo de compilação se [T1 / X1, ..., Tm / Xm] F0 não for um subtipo do tipo de função k.

No caso em que as duas classes não são genéricas, isso é apenas uma verificação de subtipo nos tipos de função dos dois construtores. Em geral, isso implica que o objeto resultante esteja em conformidade com a interface da classe que encerra imediatamente k.

Para a semântica dinâmica, suponha que k seja um construtor de fábrica de redirecionamento e k0 seja o redirecionado de k.

É um erro de tipo dinâmico se um argumento real passado em uma invocação de k não for um subtipo do tipo real (19.10.1) do parâmetro formal correspondente na declaração de k.

Quando o redirecionado k0 é um construtor de fábrica, a execução de k equivale à execução de k0 com os argumentos reais passados ​​para k. O resultado da execução de k0 é o resultado de k.

Quando o redirecionado k0 é um construtor generativo, seja uma nova instância (10.6.1) da classe que contém k0. A execução de k equivale à execução de k0 para inicializar o, regida pelas mesmas regras que uma expressão de criação de instância (16.15). Se k for concluído normalmente, a execução de k0 concluirá normalmente o retorno de o, caso contrário, k0 será concluído lançando a exceção e o rastreamento de pilha lançados por k.

10.6.3 Construtores constantes

constantConstructors



Um construtor constante pode ser usado para criar objetos constantes em tempo de compilação (16.3). Um construtor constante é prefixado pela palavra reservada const.

hconstantConstructorSignaturei :: = const hqualifiedi hformalParameterListi

Todo o trabalho de um construtor constante deve ser tratado por meio de seus inicializadores.

É um erro em tempo de compilação se um construtor constante for declarado por uma classe que possui uma variável de instância mutável.

A descrição acima refere-se a variáveis ​​de instância declaradas e herdadas localmente.

É um erro em tempo de compilação se um construtor constante for declarado por uma classe C se qualquer variável de instância declarada em C for inicializada com uma expressão que não seja uma expressão constante.

Uma superclasse de C também não pode declarar tal inicializador, porque deve necessariamente declarar também construtor constante (a menos que seja Object, que não declara variáveis ​​de instância).

O superinicializador que aparece, explícita ou implicitamente, na lista de inicializadores de um construtor constante deve especificar um construtor constante da superclasse da classe que encerra imediatamente ou ocorre um erro em tempo de compilação.

Qualquer expressão que aparece na lista do inicializador de um construtor constante deve ser uma expressão potencialmente constante ou ocorre um erro em tempo de compilação.





Uma expressão potencialmente constante é uma expressão e que poderia ser uma expressão constante válida se todos os parâmetros formais do construtor constante que encerram imediatamente foram tratados como constantes em tempo de compilação dos tipos apropriados e onde e também é uma expressão válida se todos os parâmetros formais forem tratados como variáveis ​​não constantes.





A diferença entre uma expressão potencialmente constante e uma expressão constante (16.15.2) merece alguma explicação.

A questão principal é como se trata os parâmetros formais de um construtor.

Se um construtor constante for chamado a partir de uma expressão de objeto constante, os argumentos reais serão necessários ser expressões constantes. Portanto, se tivéssemos certeza de que os construtores constantes sempre eram invocados a partir de expressões constantes de objetos, poderíamos assumir que os parâmetros formais de um construtor eram constantes em tempo de compilação.

No entanto, construtores constantes também podem ser invocados a partir de expressões de criação de instância comuns (16.15.1) e, portanto, a suposição acima não é geralmente válida.

No entanto, o uso dos parâmetros formais de um construtor constante dentro do construtor é de considerável utilidade. O conceito de expressões potencialmente constantes é introduzido para facilitar o uso limitado de tais parâmetros formais. Especificamente, permitimos o uso dos parâmetros formais de um construtor constante para expressões que envolvem operadores internos, mas não para objetos, listas e mapas constantes. Isso permite construtores como:

classe C {

x final; y final; z final;

const C (p, q): x = q, y = p + 100, z = p + q;

}

A atribuição para x é permitida sob a suposição de que q é constante (mesmo que q não seja, em geral uma constante em tempo de compilação). A atribuição para y é semelhante, mas levanta questões adicionais. Nesse caso, a superexpressão de p é p + 100 e requer que p seja uma expressão constante numérica para que toda a expressão seja considerada constante. A redação da especificação nos permite assumir que p é avaliado como um número inteiro. Um argumento semelhante vale para p e q na atribuição a z.

No entanto, os seguintes construtores não são permitidos:

classe D {

w final; const D.makeList (p): w = const [p]; // erro em tempo de compilação const D.makeMap (p): w = const {"help": q}; // erro em tempo de compilação const D.makeC (p): w = const C (p, 12); // erro em tempo de compilação

}

O problema não é que as atribuições para w não sejam potencialmente constantes; eles são. No entanto, tudo isso contraria as regras para listas constantes (16.9), mapas (16.10) e objetos (16.15.2), os quais independentemente exigem que suas subexpressões sejam expressões constantes.

Todos os construtores ilegais de D acima não puderam ser sensivelmente invocados via new, porque uma expressão que deve ser constante não pode depender de um parâmetro formal, que pode ou não ser constante. Por outro lado, os exemplos legais fazem sentido, independentemente de o construtor ser chamado via const ou via new.

É claro que leitores cuidadosos se preocuparão com casos em que os argumentos reais para C () são constantes, mas não são numéricos. Isso é impedido pela regra a seguir, combinada com as regras para avaliar objetos constantes (16.15.2).

Quando um construtor constante k é invocado a partir de uma expressão de objeto constante, é um erro em tempo de compilação se a invocação de k em tempo de execução gerar uma exceção e é um erro em tempo de compilação se a substituição dos argumentos reais pelos argumentos formais parâmetros produz uma expressão de inicialização e na lista de inicializadores de k, que não é uma expressão constante.

Por exemplo, se e é a.length onde a é um argumento formal de k com o tipo dinâmico, e é potencialmente constante e pode ser usado na lista inicializadora de k. É um erro invocar k com um argumento do tipo C se C for uma classe diferente de String, mesmo se C tiver um getter de comprimento, e essa mesma expressão seria avaliada sem erros no tempo de execução.

10.7 Métodos estáticos

staticMethods



Métodos estáticos são funções, exceto getters ou setters, cujas declarações são contidas imediatamente em uma declaração de classe e declaradas estáticas. Os métodos estáticos de uma classe C são aqueles métodos estáticos declarados por C.

A herança de métodos estáticos tem pouca utilidade no Dart. Métodos estáticos não podem ser substituídos. Qualquer função estática necessária pode ser obtida em sua biblioteca de declaração e não há necessidade de trazê-la para o escopo por herança. A experiência mostra que os desenvolvedores estão confusos com a idéia de métodos herdados que não são métodos de instância.

Obviamente, toda a noção de métodos estáticos é discutível, mas é mantida aqui porque muitos programadores estão familiarizados com ela. Os métodos estáticos de dardo podem ser vistos como funções da biblioteca anexa.

Declarações de método estático podem entrar em conflito com outras declarações (10.10).



superclasses





10.8 Superclasses


A superclasse S0 de uma classe C cuja declaração possui uma cláusula with com M1, ..., Mk e uma cláusula extends estende S é a classe abstrata obtida pela aplicação da composição de mixina (12) Mk ∗ ··· ∗ M1 a S. O nome S0 é um identificador novo. Se nenhuma cláusula with for especificada, a cláusula extends de uma classe C especificará sua superclasse. Se nenhuma cláusula extends for especificada, então:

• C é Objeto, que não possui superclasse. OU

• A classe C é considerada como tendo uma cláusula extends do formulário extends Object, e as regras acima se aplicam.



É um erro em tempo de compilação especificar uma cláusula extends para a classe Object.

hsuperclassi :: = estende htypeNotVoidi hmixinsi? | hmixinsi hmixinsi :: = com htypeNotVoidListi

O escopo das extensões e com cláusulas de uma classe C é o escopo de parâmetro de tipo de C.

Eu t é um erro em tempo de compilação se o tipo na cláusula extends de uma classe C for uma variável de tipo (14), um alias de tipo que não denota uma classe (19.3), um tipo enumerado (13), um tipo adiado ( 19.1), digite dinâmico (19.7) ou digite FutureOr <T> para qualquer T (19.8).

Observe que nulo é uma palavra reservada, o que implica que as mesmas restrições se aplicam ao tipo nulo e restrições semelhantes são especificadas para outros tipos, como

Nulo (16,4) e String (16,7).

Os parâmetros de tipo de uma classe genérica estão disponíveis no escopo lexical da cláusula de superclasse, potencialmente sombreando classes no escopo circundante. O código a seguir é, portanto, ilegal e deve causar um erro em tempo de compilação:

classe T {}

/ * Erro de compilação: tentativa de subclasse de um parâmetro de tipo * / classe G <T> estende T {}

Uma classe S é uma superclasse de uma classe C se:

• S é a superclasse de C, ou

• S é uma superclasse de uma classe S0 e S0 é a superclasse de C.



É um erro em tempo de compilação se uma classe C for uma superclasse por si mesma.





10.8.1 Herança e substituição

Seja C uma classe, seja A uma superclasse de C, e seja S1, ..., Sk seja uma superclasse

herditanceAndOverriding



de C que também são subclasses de A. C herda todos os membros de instância concretos e acessíveis de A que não foram substituídos por uma declaração concreta em C ou em pelo menos um de S1, ..., Sk.





Seria mais atraente fornecer uma definição puramente local de herança, que dependesse apenas dos membros da superclasse direta S. No entanto, uma classe C pode herdar um membro m que não é membro de sua superclasse S. Isso pode ocorrer quando o membro m é privado para a biblioteca L1 de C, enquanto S vem de uma biblioteca diferente L2, mas a cadeia da superclasse de S inclui uma classe declarada em L1.

Uma classe pode substituir membros da instância que de outra forma seriam herdados de sua superclasse.

Seja C = S0 uma classe declarada na biblioteca L e {S1, ..., Sk} seja o conjunto de todas as superclasses de C, onde Si é a superclasse de Si-1 para i ∈ 1..k. Sk é a classe interna Object. Seja C declarado um membro concreto m e seja m0 um membro concreto de Sj, j ∈ 1..k, que tenha o mesmo nome que m, de modo que m0 seja acessível a L. Então m substitui m0 se m0 ainda não substituído por um membro concreto de pelo menos um de S1, ..., Sj-1 e nem m nem m0 são variáveis ​​de instância.

As variáveis ​​de instância nunca se substituem. Os getters e setters induzidos por variáveis ​​de instância fazem isso.

Novamente, uma definição local de substituição seria preferível, mas falha ao considerar a privacidade da biblioteca.

Se uma substituição é legal ou não, é especificado em relação a todas as superinterfaces diretas, não apenas à interface da superclasse, e isso é descrito em outra parte (10.1). Os membros estáticos nunca substituem nada, mas podem participar de alguns conflitos que envolvem declarações em superinterfaces (10.10).

Por conveniência, aqui está um resumo das regras relevantes, usando "erro" para indicar erros em tempo de compilação. Lembre-se de que isso não é normativo. A linguagem de controle está nas seções relevantes da especificação.

Existe apenas um espaço para nome para getters, setters, métodos e construtores (6.1). Uma instância ou variável estática f introduz um getter f, e uma instância mutável ou variável estática f também introduz um setter f = (10.5, 8). Quando falamos de membros aqui, queremos dizer instâncias acessíveis ou variáveis ​​estáticas, getters, setters e métodos (10).

Você não pode ter dois membros com o mesmo nome na mesma classe - sejam eles declarados ou herdados (6.1, 10).

Membros estáticos nunca são herdados.

É um erro se você tiver um membro estático chamado m na sua classe e um membro da instância com o mesmo nome (10.10).

É um erro se você tiver um configurador estático v = e um membro da instância v (10.3).

É um erro se você tiver um getter estático ve um configurador de instância v = (10.2).

Se você definir um membro da instância chamado m, e sua superclasse tiver um membro da instância com o mesmo nome, eles se substituirão. Isso pode ou não ser legal.

Se dois membros se substituírem, será um erro, a menos que seja uma substituição correta (11.2.2).

Setters, getters e operadores nunca têm parâmetros opcionais de qualquer tipo; é um erro (10.1.1, 10.2, 10.3).

É um erro se um membro tiver o mesmo nome que sua classe anexa (10).

Uma classe tem uma interface implícita (10).

Membros de superinterface não são herdados por uma classe, mas são herdados por sua interface implícita. As interfaces têm suas próprias regras de herança (11.2.1).

Um membro é abstrato se não tem corpo e não é rotulado como externo (10.4,



9.4)

Uma classe é abstrata se for explicitamente rotulada como abstrata.

É um erro se uma classe concreta não implementar algum membro de sua interface e não houver noSuchMethod (10) não trivial.

É um erro chamar um construtor que não seja de fábrica de uma classe abstrata usando uma expressão de criação de instância (16.15); esse construtor só pode ser chamado de outro construtor usando uma super invocação ( 16.21.3).

Se uma classe define um membro da instância chamado m, e qualquer uma de suas superinterfaces possui uma assinatura de membro chamada m, a interface da classe contém o m da própria classe.

Uma interface herda todos os membros de suas superinterfaces que não são substituídos e não são membros de várias superinterfaces.

Se várias superinterfaces de uma interface definirem um membro com o mesmo nome que m, no máximo um membro será herdado. Esse membro (se existir) é aquele cujo tipo é um subtipo de todos os outros. Se não houver esse membro, ocorrerá um erro (11.2.1).

A regra 8 se aplica às interfaces e às classes (11.2.1).

É um erro se uma classe concreta não tiver uma implementação para um método em sua interface, a menos que tenha um noSuchMethod (10.1.2) não trivial.

O identificador de um construtor nomeado não pode ser igual ao nome de um membro estático declarado na mesma classe (10.10).



10.9 Superinterfaces

superinterfaces



Uma classe possui um conjunto de superinterfaces diretas. Este conjunto contém a interface de sua superclasse e as interfaces das classes especificadas na cláusula implementa da classe.





hinterfacesi :: = implementa htypeNotVoidListi

O escopo da cláusula implementa de uma classe C é o escopo de parâmetro de tipo de C.

É um erro em tempo de compilação se um elemento na lista de tipos da cláusula implementa de uma classe C for uma variável de tipo (14), um alias de tipo que não denota uma classe (19.3), um tipo enumerado (13), um tipo adiado (19.1), tipo dinâmico (19.7) ou tipo FutureOr <T> para qualquer T (19.8). É um erro em tempo de compilação se dois elementos na lista de tipos da cláusula implementa de uma classe C especificarem o mesmo tipo T. É um erro em tempo de compilação se a superclasse de uma classe C for um dos elementos do tipo lista da cláusula de implementos de C. É um erro em tempo de compilação se uma classe C tiver duas superinterfaces que são instanciações diferentes da mesma classe genérica. Por exemplo, uma classe pode não ter ‘List <int>‘ e ‘List <num>‘ como superinterfaces.

Alguém poderia argumentar que é inofensivo repetir um tipo na lista de superinterface, então por que cometer um erro? A questão não é tanto que a situação descrita na fonte do programa é incorreta, mas que é inútil. Como tal, é uma indicação de que o programador pode muito bem ter pretendido dizer algo mais - e esse é um erro que deve ser chamado a sua atenção.

É um erro em tempo de compilação se a interface de uma classe C for uma superinterface de si mesma.

Uma classe não herda membros de suas superinterfaces. No entanto, sua interface implícita sim.

10.10 Conflitos de membro da classe

Alguns pares de declarações de membros da classe não podem coexistir, mesmo que ambos não introduzam o mesmo nome no mesmo escopo. Esta seção especifica esses erros.

classMemberConflicts



O nome base de um getter ou método chamado n é n; o nome da base de um setter chamado n = é n.

Seja C uma classe. É um erro em tempo de compilação se C declarar um construtor chamado C.n e um membro estático com o nome da base n. É um erro em tempo de compilação se C declarar um membro estático com nome de base n e a interface de C tiver um membro de instância com nome de base n. É um erro em tempo de compilação se a interface de C tiver um método chamado n e um setter com o nome da base n.

Esses erros ocorrem quando os getters ou setters são definidos explicitamente, bem como quando são induzidos por declarações de variáveis.

Observe que outros erros de natureza semelhante são abordados em outros lugares. Por exemplo, se C é uma classe que possui duas superinterfaces I1 e I2, em que I1 possui um método denominado me I2 possui um getter denominado m, é um erro porque o cálculo da interface de C inclui o cálculo da combinação assinatura de membro (11.1) desse getter e desse método, e é um erro para uma assinatura de membro combinada incluir um getter e um não getter.





11 Interfaces

Esta seção apresenta a noção de interfaces. Definimos primeiro a noção de assinaturas de membros, porque esse conceito é necessário na definição de interfaces.

interfaces



Uma assinatura de membro s pode ser derivada de uma declaração de membro de instância de classe D. Ele contém as mesmas informações que D, exceto que s omite o corpo, se houver; ele contém o tipo de retorno e os tipos de parâmetro, mesmo que estejam implícitos em D; omite os nomes dos parâmetros posicionais; omite o modificador final de cada parâmetro, se houver; omite metadados (15); e omite informações sobre se o membro é externo, assíncrono, assíncrono * ou sincronizado *. Não faz diferença se D é dado como sintaxe explícita ou é induzido implicitamente, por exemplo, por uma declaração de variável. Finalmente, se s possui parâmetros formais, cada um deles possui o modificador covariante (9.2.1) se e somente se esse parâmetro for covariante por declaração (9.2.3).

Usamos uma sintaxe semelhante à de uma declaração de membro abstrata para especificar





assinaturas de membros. A diferença é que os nomes dos parâmetros posicionais são omitted. Essa sintaxe é usada apenas para fins de especificação.

As assinaturas de membros são entidades sintéticas, ou seja, não são suportadas como sintaxe concreta em um programa Dart, são entidades computadas usadas durante a análise estática. No entanto, é útil poder indicar as propriedades de uma assinatura de membro nesta especificação por meio de uma representação sintática. Uma assinatura de membro torna explícito se um parâmetro é covariante por declaração, mas permanece implícito se é covariante por classe (9.2.3). A razão para isso é que a regra para determinar se uma determinada relação de substituição está correta (11.2.2) depende da primeira e não da segunda.

Seja m uma assinatura de método do formulário

T0 id <X1 estendeB1, ..., Xs estendeBs> (covariável? T1, ..., covariável? Tn,

[covariante? Tn + 1 = dn + 1, ..., covariante? Tn + k = dn + k]).

O tipo de função de m é então

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]).

Seja m uma assinatura de método do formulário

T0 id <X1 estendeB1, ..., Xs estendeBs> (covariável? T1, ..., covariável? Tn,

{covariante? Tn + 1 xn + 1 = dn + 1, ..., covariável? Tn + k xn + k = dn + k}).

O tipo de função de m é então

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}).

Seja m uma assinatura setter do formulário void set id (covariável? T p). o

O tipo de função m é então anulado Function (T).

O tipo de função de uma assinatura de membro permanece inalterado se alguns ou todos os valores padrão forem omitidos.

Não especificamos o tipo de função de uma assinatura getter. Para essas assinaturas, nos referiremos diretamente ao tipo de retorno.





Uma interface é uma entidade sintética que define como alguém pode interagir com um objeto. Uma interface possui método, assinaturas getter e setter e um conjunto de superinterfaces, que são novamente interfaces. Cada interface é o implícito





interface de uma classe; nesse caso, chamamos de interface de classe ou uma combinação





de várias outras interfaces; nesse caso, chamamos de interface combinada.





Seja C uma classe. A interface de classe I de C é a interface que declara uma assinatura de membro derivada de cada membro da instância declarado por C.





superinterfaces diretas de I são as superinterfaces diretas de C (10.9).

Dizemos que a interface da classe 'declara' essas assinaturas de membros, para que possamos dizer que uma interface 'declara' ou 'tem' um membro, assim como fazemos nas aulas. Observe que uma assinatura de membro s da interface da classe C pode ter um parâmetro p com modificador covariante, mesmo que s tenha sido derivado de uma declaração D em C e o parâmetro correspondente a p em D não possua esse modificador. Isso ocorre porque p pode ter "herdado" a propriedade de ser covariante por declaração de uma de suas superinterfaces (9.2.3).





A interface combinada I de uma lista de interfaces I1, ..., Ik é a interface que declara o conjunto de assinaturas de membro M, em que M é determinado conforme especificado





abaixo. As superinterfaces diretas de I são o conjunto I1, ..., Ik.





Seja M0 o conjunto de todas as assinaturas de membros declaradas por I1, ..., Ik. M é então o menor conjunto que satisfaz o seguinte:

• Para cada id de nome e biblioteca L, de modo que M0 contenha uma assinatura de membro nomeada id acessível a L, seja m a assinatura de membro combinada nomeada id de I1, ..., Ik em relação a L. É uma compilação. erro de tempo se o cálculo desta assinatura de membro combinada falhar. Caso contrário, M contém m.

As interfaces devem poder conter assinaturas de membros inacessíveis, porque podem ser acessíveis a partir das interfaces associadas às declarações de subtipos.

Por exemplo, a classe C na biblioteca L pode declarar um membro privado chamado _foo, uma classe D em uma biblioteca diferente L2 pode estender C e uma classe E na biblioteca L pode estender D; E pode então declarar um membro que substitui _foo de C e essa relação de substituição deve ser verificada com base na interface de D. Portanto, não podemos permitir que a interface de D “esqueça” membros inacessíveis como _foo.

Para conflitos, a situação é ainda mais exigente: as classes C1 e C2 na biblioteca L podem declarar membros privados String _foo (int i) e int get _foo, e um subtipo D12 em uma biblioteca diferente L2 pode ter uma cláusula de implementação listando C1 e C2 . Nesse caso, devemos relatar um conflito, mesmo que as declarações conflitantes não sejam acessíveis a L2, porque essas assinaturas de membros não serão encaminhadasSuchMethod (10.1.2) e uma invocação de _foo em uma instância de D em L deve retornar um 'int 'de acordo com a primeira assinatura de membro, e ele deve retornar um objeto de função de acordo com o segundo, e uma invocação de _foo (42) deve retornar uma String com a primeira assinatura de membro e deve falhar (em tempo de compilação ou, por uma invocação dinâmica, tempo de execução) com o segundo.

Pode não ser possível satisfazer tais restrições simultaneamente, e será inevitavelmente uma semântica complexa, por isso optamos por cometer um erro. É lamentável que o aditivo A declaração de uma declaração privada em uma biblioteca pode quebrar o código existente em uma biblioteca diferente. Mas deve-se observar que os conflitos podem ser detectados localmente na biblioteca em que as declarações privadas existem, porque elas só ocorrem para membros privados com o mesmo nome e assinaturas incompatíveis. Renomear esse membro privado para qualquer coisa não usada nessa biblioteca eliminará o conflito e não quebrará nenhum cliente.





11.1 Assinaturas combinadas de membros


Esta seção especifica como calcular uma assinatura de membro que representará adequadamente um conjunto priorizado de várias assinaturas de membros, extraído de uma determinada lista de interfaces.

Em geral, uma assinatura de membro combinada tem um tipo que é um subtipo de todos os tipos fornecidos para esse membro. Isso é necessário para garantir que o tipo de um ID de membro de uma classe C seja bem definido, mesmo no caso em que C herda várias declarações diferentes de ID e não substitua a ID. Em caso de falha, serve para especificar as situações em que um desenvolvedor deve adicionar uma declaração para resolver uma ambiguidade. As assinaturas de membro são priorizadas no sentido de que selecionaremos uma assinatura de membro na interface com o menor índice possível no caso em que várias assinaturas de membro sejam igualmente adequadas para serem escolhidas como a assinatura de membro combinada. Ou seja, "a primeira interface vence".

Para fins de computação de uma assinatura de membro combinada, precisamos de um





noção especial de igualdade de assinaturas de membros. Duas assinaturas de membro m1 e m2 são iguais se tiverem o mesmo nome, estiverem acessíveis ao mesmo conjunto de bibliotecas, tiverem o mesmo tipo de retorno (para getters) ou o mesmo tipo de função e as mesmas ocorrências de covariantes (para métodos e setters).

Em particular, métodos privados de diferentes bibliotecas nunca são iguais. Os principais tipos também diferem. Por exemplo, Função dinâmica () e Função de objeto () não são iguais, mesmo que sejam subtipos um do outro. Precisamos dessa distinção porque o gerenciamento de discrepâncias de tipo superior é um dos propósitos de calcular uma interface combinada.

Agora, definimos assinaturas combinadas de membros. Seja id um identificador, L uma biblioteca, I1, ..., Ik uma lista de interfaces e M0 o conjunto de todas as assinaturas de membros





de I1, ..., Ik nomeado id e acessível a L. A assinatura de membro combinada nomeada id de I1, ..., Ik em relação a L é a assinatura de membro obtida da seguinte forma:

Se M0 estiver vazio, o cálculo da assinatura do membro combinado falhou.

Se M0 contiver exatamente uma assinatura de membro m0, a assinatura de membro combinada será m0.

Caso contrário, M0 contém mais de uma assinatura de membro m1, ..., mq.

Caso hFailing mixturesi. Se M0 contiver pelo menos uma assinatura getter e pelo menos uma assinatura não getter, o cálculo da assinatura do membro combinado falhará.

Case hGettersi. Se M0 contiver apenas assinaturas getter, o cálculo da assinatura combinada do membro continuará conforme descrito abaixo para métodos e setters, exceto pelo uso do tipo de retorno da assinatura getter, em que métodos e setters usam o tipo de função da assinatura do membro.

Case hMethods and settersi. Nesse caso, M0 consiste apenas em assinaturas de setter ou apenas em assinaturas de método, porque o nome id no primeiro caso sempre termina em '=', o que nunca é verdadeiro no último caso.

Determine se existe um conjunto não vazio N ⊆ 1..q de modo que, para cada i ∈ N, o tipo de função de mi seja um subtipo do tipo de função de mj para cada j ∈

1..q. Se esse conjunto não existir, o cálculo da assinatura combinada do membro





falhou. Uma intuição útil sobre essa situação é que as assinaturas de membro fornecidas não concordam com o tipo adequado para o membro nomeado id. Caso contrário, temos um conjunto de assinaturas de membros que são "mais específicas" no sentido de que seus tipos de funções são subtipos de todos eles.

Caso contrário, quando um conjunto N, como especificado acima, existir, seja Nall o maior conjunto que satisfaça o requisito em N e seja Mall = {mi | Eu não. Ou seja, o Mall contém todas as assinaturas de membros nomeadas id com o tipo mais específico. A subtipagem de dardo é uma pré-ordem parcial, que garante a existência de um conjunto tão grande de menos elementos, se existir um conjunto não vazio de elementos. Podemos ter várias dessas assinaturas porque as assinaturas de membros podem ser iguais a elas e, ainda assim, seus tipos de funções são subtipos uns dos outros. Precisamos calcular uma assinatura de membro do Mall, e fazemos isso usando a ordem das interfaces fornecidas.

Seja j ∈ 1..k o menor número, de modo que Mfirst = Mall∩Ij não esteja vazio. Seja mi o único elemento que o Mfirst contém. Este conjunto contém exatamente um elemento porque não está vazio e nenhuma interface contém mais de uma assinatura de membro denominada id. Em outras palavras, escolhemos mi como a assinatura do membro da primeira interface possível entre as assinaturas de membros mais específicas do Mall.

A assinatura combinada do membro é então m0, que é obtida fr om mi adicionando a covariante modificadora a cada parâmetro p (se ainda não estiver presente) quando existir um j ∈ 1..q tal que o parâmetro correspondente a p (9.2.3) possua a covariância modificadora. Em outras palavras, cada parâmetro na assinatura combinada do membro é marcado como covariante se algum dos parâmetros correspondentes estiver marcado como covariante, não apenas entre as assinaturas mais específicas, mas entre todas as assinaturas nomeadas id (acessíveis a L) na lista fornecida. interfaces.

11.2 Superinterfaces

Uma interface possui um conjunto de superinterfaces diretas (11). Uma interface J é uma

interfaceSuperinterfaces



superinterface de uma interface I se J for uma superinterface direta de I ou J for uma superinterface de uma superinterface direta de I.



interfaceInheritanceAndOverriding



11.2.1 Herança e substituição

Seja J uma interface e K uma biblioteca. Definimos herdado (J, K) como o conjunto de assinaturas de membros m, de forma que todos os itens a seguir sejam mantidos:

• m é acessível a K e

• A é uma superinterface direta de J e



- A declara uma assinatura de membro m ou - m é um membro herdado (A, K).



• m não é substituído por J.



Além disso, definimos substituições (J, K) como o conjunto de assinaturas de membros m0, para que todos os itens a seguir sejam mantidos:

• J é a interface de uma classe C.

• C declara uma assinatura de membro m.

• m0 tem o mesmo nome que m.

• m0 é acessível a K.

• A é uma superinterface direta de J e



- A declara uma assinatura de membro m0 ou

- m0 é um membro herdado (A, K).



Seja eu a interface de uma classe C declarada na biblioteca L. Herdo todos





membros herdados (I, L) e I substituem m0 se m0 ∈ substitui (I, L).

Todos os erros em tempo de compilação relativos à substituição de membros da instância fornecidos na seção 10 também se aplicam à substituição entre interfaces.

Se a regra acima fizer com que várias assinaturas de membros com o mesmo nome de ID sejam herdadas, exatamente um membro será herdado, ou seja, a assinatura de membro combinada denominada id, das superinterfaces diretas na ordem textual em que são declaradas, com relação a L ( 11.1) É um erro de compilação se o cálculo da referida assinatura de membro combinada falhar.





11.2.2 Substituições corretas de membros

Seja m e m0 assinaturas de membros com o mesmo nome de identificação. Então m é um

correctMemberOverrides



substituição correta de m0 se os seguintes critérios forem atendidos:





• m e m0 são ambos métodos, ambos getters ou ambos setters.

• Se m e m0 são ambos métodos ou ambos setters: Seja F o tipo de função de m, exceto que o tipo de parâmetro é a classe interna Objeto para cada parâmetro de m que possui o covariável modificador. Seja F0 o tipo de função de m0. F deve então ser um subtipo de F0.



O requisito de subtipo assegura que as formas da lista de argumentos admissíveis para uma chamada de um método com assinatura m0 também sejam admissíveis para uma chamada de método com a assinatura m. Por exemplo, m0 pode aceitar 2 ou 3 argumentos posicionais, e m pode aceitar 1, 2, 3 ou 4 argumentos posicionais, mas não vice-versa. Esta é uma propriedade interna das regras de subtipo de tipo de função. Observe que uma assinatura de membro difere de uma declaração sintática subjacente D em uma classe C. Em particular, um parâmetro em uma assinatura de membro possui o modificador covariante se e somente se o parâmetro for covariante por declaração (9.2.3) e que pode ser o caso de declarações em um supertipo de C, de modo que o modificador não precise estar presente em D. Há um possível erro em tempo de compilação adicional associado a um parâmetro que é covariante por declaração (10.1). Mas não podemos cobrir isso aqui como uma propriedade de substituições de membros, porque se preocupa com declarações em todas as superinterfaces, indiretas e também diretas.

• Se m e m0 são os dois métodos, p é um parâmetro opcional de m, p0 é o parâmetro de m0 correspondente a p, p tem valor padrão d e p0 tem valor padrão d0, então d e d0 devem ser idênticos ou estáticos aviso ocorre.

• Se m e m0 são ambos getters: O tipo de retorno de m deve ser um subtipo do tipo de retorno de m0.



Um mixin descreve a diferença entre uma classe e sua superclasse. Um mixin é derivado de uma declaração de classe existente ou introduzido por uma declaração de mixin.

A aplicação de mixina ocorre quando um ou mais mixins são misturados em uma declaração de classe através da cláusula with (12.3). A aplicação de mixina pode ser usada para estender uma classe de acordo com a seção 10; alternativamente, uma classe pode ser definida como um aplicativo mixin, conforme descrito na seção a seguir.

mixins



12.1 Classes Mixin

hmixinApplicationClassi :: = identificadores htypeParametersi? ‘= 'HmixinApplicationi'; 'hmixinApplicationi :: = htypeNotVoidi hmixinsi hinterfacesi?

É um erro em tempo de compilação se um elemento na lista de tipos da cláusula with de um aplicativo mixin for uma variável de tipo (14), um tipo de função (19.5), um alias de tipo que não denote uma classe (19.3), um enumera tipo diferido (13), tipo diferido (19.1), tipo dinâmico (19.7), tipo nulo (19.9) ou tipo FutureOr <T> para qualquer T

mixinClasses



(19,8) Se T é um tipo na cláusula with, a mixina de T é a mixina derivada de T se T denota uma classe ou a mixina introduzida por T se T denota uma declaração de mixina.





Seja D uma declaração de classe de aplicação mixin do resumo do formulário? classe N = S com M1, ..., Mn





12 Mixins


acessórios I1, ..., Ik;

É um erro em tempo de compilação se S for um tipo enumerado (13). É um erro de compilação se M1, ..., Mk for um tipo enumerado (13). É um erro em tempo de compilação se uma mixina bem formada não puder ser derivada de cada um dos M1, ..., Mk.

O efeito de D na biblioteca L é introduzir o nome N no escopo de L, vinculado à classe (10) definida pela cláusula S com M1, ..., Mn com o nome N, conforme descrito abaixo. Se k> 0, a classe também implementa I1, ..., Ik. Se a declaração da classe é prefixada pelo resumo do identificador interno, a classe que está sendo definida se torna uma classe abstrata.

Uma cláusula do formato S com M1, ..., Mn com o nome N define uma classe da seguinte maneira:

Se houver apenas uma mixina (n = 1), S com M1 definirá a classe gerada pelo aplicativo de mixina (12.3) da mixina de M1 (12.2) para a classe indicada por S com o nome N.

Se houver mais de um mixin (n> 1), seja X a classe definida por S com M1, ..., Mn-1 com o nome F, onde F é um nome novo, e faça X abstrato. Então S com M1, ..., Mn define a classe produzida pela aplicação de mixina da mixina de Mn na classe X com o nome N.

Em qualquer um dos casos, seja K uma declaração de classe com os mesmos construtores,

superclasse, interfaces e membros da instância como a classe definida. É um erro de compilação se a declaração de K causar um erro em tempo de compilação.

É um erro, por exemplo, se M contiver uma declaração de membro d que substitua uma assinatura de membro m na interface de S, mas que não seja uma substituição correta de m (11.2.2).





12.2 Declaração de Mixin mixinDeclaration


Um mixin define zero ou mais declarações de membros do mixin, zero ou mais

superinterfaces necessárias, uma superinterface combinada e zero ou mais



interfaces mentadas.

O mixin derivou de uma declaração de classe: abstract? classe X implementa I1, ..., Ik {

membros }

tem Object como superinterface necessária e superinterface combinada, I1, ..., Ik como interfaces implementadas, e os membros da instância dos membros como declarações de membros mixin. Se X é genérico, o mixin também é.

Uma declaração de mixin introduz um mixin e fornece um escopo para declarações de membros estáticos.

hmixinDeclarationi :: = como misturar identificadores htypeParametersi?

(em htypeNotVoidListi)? hinterfacesi?

‘{'(Hmetadatai hclassMemberDefinitioni) *‘}'

É um erro em tempo de compilação declarar um construtor em uma declaração mixin.

Uma declaração mixin sem a cláusula on é equivalente a uma com a cláusula Object.

Seja M uma declaração mixin da forma mixin N <X1 estende B1, ..., Xs estendeBs> em T1, ..., Tn im

implementa I1, ..., Ik {membros

}

É um erro de tempo de compilação se algum dos tipos T1 a Tn ou I1 a Ik for uma variável de tipo (14), um tipo de função (19.5), um alias de tipo que não denota uma classe (19.3), um tipo enumerado (13 ), um tipo adiado (19.1), tipo dinâmico (19.7), tipo nulo (19.9) ou tipo FutureOr <T> para qualquer T (19.8).

Seja MS a interface declarada pela classe abstrata de declaração de classe Msuper <P1, ..., Pm> implementemen

onde Msuper é um nome novo. É um erro em tempo de compilação para a declaração mixin se a declaração da classe MS causar um erro em tempo de compilação, ou seja, se algum membro for declarado por mais de uma superinterface declarada e não houver uma assinatura mais específica para esse membro entre as super interfaces. A interface MS é chamada de interface de superinvocação da declaração de mixin M. Se a declaração de mixin M tiver apenas uma superinterface declarada, T1, a interface de superinvocação Msuper terá exatamente os mesmos membros que a interface T1.

Seja MI a interface que seria definida pelo resumo da declaração de classe; a classe N <X1 estendeB1, ..., Xs estendeBs> implementa T1, ..., Tn, I1, ..., Ik {



members0

}

onde members0 são as declarações dos membros da declaração mixin M

exceto que todas as superinvocações são tratadas como se super fosse uma expressão válida com o tipo estático MS. É um erro em tempo de compilação para o mixin M se esta declaração de classe N causar um erro em tempo de compilação, ou seja, se as superinterfaces necessárias, as interfaces implementadas e as declarações não definirem uma interface consistente, se alguma declaração de membro contiver um erro em tempo de compilação que não seja uma super invocação ou se uma super invocação não for válida na interface MS. A interface introduzida pela declaração mixin M tem as mesmas assinaturas e superinterfaces de membros que o MI.





A declaração mixin M introduz um mixin com a superinterface necessária





f aces T1, ..., Tn, a superinterface combinada MS, implementou as interfaces I1,





..., Ik e os membros da instância declarados em M como declarações de membros mixin.





12.3 Aplicação Mixin

Um mixin pode ser aplicado a uma superclasse, gerando uma nova classe.

mixinApplication



Seja S uma classe, M seja uma mistura com as superinterfaces necessárias T1, ..., Tn,





superinterface combinada MS, interfaces implementadas I1, ..., Ik e membros





como declarações de membros mixin e seja N um nome.

É um erro em tempo de compilação aplicar M a S se S não implementar, direta ou indiretamente, todos os T1, ..., Tn. É um erro em tempo de compilação se algum dos membros contiver uma super invocação de um membro m (por exemplo, super.foo, super + 2 ou super [1] = 2) e S não tiver uma implementação concreta de m que é uma substituição válida do membro m na interface MS. Tratamos super-





invocações em mixins como invocações de interface na superinterface combinada, portanto, exigimos que a superclasse de um aplicativo mixin tenha implementações válidas dos membros da interface que são realmente super invocados.

O aplicativo mixin de M para S com o nome N apresenta uma nova classe, C, com o nome N, superclasse S, interface implementada I1, ..., Ik e membros como membros da instância. A classe C não possui membros estáticos. Se S declarar algum construtor generativo, o aplicativo apresentará construtores generativos em C da seguinte maneira:

Seja LC a biblioteca que contém o aplicativo mixin. Ou seja, a biblioteca que contém a cláusula S com M ou a cláusula S0 com M1, ..., Mk, M deu origem ao aplicativo mixin.

Seja SN o nome de S.

Para cada construtor generativo do formato Sq (T1 a1, ..., Tk ak) de S acessível a LC, C possui um construtor implicitamente declarado do formulário

Cq (T1 a1, ..., Tk ak): superq (a1, ..., ak);

onde Cq é obtido de Sq substituindo ocorrências de SN, que denotam a superclasse, por N, e superq é obtido de Sq, substituindo ocorrências de SN que denotam a superclasse por super. Se Sq é um construtor const generativo e C não declara nenhuma variável de instância, Cq também é um construtor const.

Para cada construtor generativo do formato Sq (T1 a1, ..., Tk ak, [Tk + 1 ak + 1 = d1, ..., Tk + p ak + p = dp]) de S acessível a LC , C tem um construtor implicitamente declarado do formulário

Cq (T1 a1, ..., Tk ak, [Tk + 1 ak + 1 = d01, ..., Tk + p ak + p = d0p])

: superq (a1, ..., ak, ak + 1, ..., ap);

onde Cq é obtido de Sq substituindo ocorrências de SN, que denotam a superclasse, por N, superq é obtido de Sq, substituindo ocorrências de SN que denotam a superclasse por super, e d..p, é uma expressão constante que avalia o mesmo valor que di. Se Sq for um construtor const generativo e o MC não declarar nenhuma variável de instância, Cq também será um construtor const.

Para cada construtor generativo do formato Sq (T1 a1, ..., Tk ak, {Tk + 1 ak + 1 = d1, ..., Tk + n ak + n = dn}) de S acessível a LC , C tem um construtor implicitamente declarado do formulário

Cq (T1 a1, ..., Tk ak, {Tk + 1 ak + 1 = d01, ..., Tk + n ak + n = d0n})

: superq (a1, ..., ak, ak + 1: ak + 1, ..., ap: ap);

onde Cq é obtido de Sq substituindo ocorrências de SN que denotam a superclasse por N, superq é obtido de Sq substituindo ocorrências de SN que denotam a superclasse por super, e d..n, é uma expressão constante

avaliando o mesmo valor que di. Se Sq for um construtor const generativo e M não declarar nenhum campo, Cq também será um construtor const.





13 Enums

enums



Um tipo enumerado, ou enum, é usado para representar um número fixo de constantes





valores.





henumTypei :: = hmetadatai enum hidentifieri

'HenumEntryi (', 'henumEntryi) * (', ')? ‘} 'HenumEntryi :: = hmetadatai hidentifieri

A declaração de uma enum da forma m enum E {m0 id0, ..., mn-1 idn-1} tem o mesmo efeito que uma declaração de classe

m classe E {

índice int final; const E (este.índice); m0 const E estático id0 = const E (0);

...

mn-1 const E estático idn-1 = const E (n - 1); const estático Lista <E> valores = const <E> [id0, ..., idn-1]; String toString () => {0: 'E.id0', ..., n-1: 'E.idn-1'} [índice]

}

Também é um erro em tempo de compilação subclasse, mistura ou implementação de uma enumeração ou instanciar explicitamente uma enumeração. Essas restrições são apresentadas de forma normativa nas seções 10.8, 10.9, 12.3 e 16.15, conforme apropriado.



genéricos



Uma declaração de classe (10), alias de tipo (19.3) ou função (9) G pode ser genérica, ou seja, G pode ter parâmetros formais de tipo declarados.

Quando uma entidade nesta especificação é descrita como genérica e o caso especial é considerado onde o número de argumentos de tipo é zero, a lista de argumentos de tipo deve ser omitida.

Isso permite que casos não genéricos sejam incluídos implicitamente como casos especiais. Por exemplo, uma invocação de uma função não genérica surge como o caso especial em que a função recebe argumentos de tipo zero e argumentos de tipo zero a re passado. Nesta situação, algumas operações também são omitidas (não têm efeito), por exemplo, operações em que os parâmetros de tipo formal são substituídos por argumentos de tipo reais.





Uma declaração de classe genérica introduz uma classe genérica na lista





âmbito de aplicação. Uma classe genérica é um mapeamento que aceita uma lista de argumentos de tipo reais e os mapeia para uma classe. Considere uma declaração genérica de classe G denominada C com declarações formais de parâmetro de tipo X1 estende B1, ..., Xm estende Bm e um tipo de parâmetro T no formato C <T1, ..., Tl>.

É um erro em tempo de compilação se m 6 = l. É um erro em tempo de compilação se T não estiver bem delimitado (14.2).

Caso contrário, o referido tipo parametrizado C <T1, ..., Tm> indica uma aplicação da classe genérica declarada por G aos argumentos de tipo T1, ..., Tm. Isso gera uma classe C0 cujos membros são equivalentes aos de uma declaração de classe obtida da declaração G substituindo cada ocorrência de Xj por Tj.

Outras propriedades de C0, como os relacionamentos de subtipo, são especificadas em outra parte (19.4).





Um alias de tipo genérico é uma declaração D de uma das seguintes formas:





14 genéricos


• m typedef id <X1 estendeB1, ..., Xs estendeBs> = T;

• m typedef S? id <X1 estendeB1, ..., Xs estendeBs> (



T1 p1, ..., Tn pn, [Tn + 1 pn + 1, ..., Tn + k pn + k]);



m typedef S? id <X1 estendeB1, ..., Xs estendeBs> (

T1 p1, ..., Tn pn, {Tn + 1 pn + 1, ..., Tn + k pn + k});

onde m é derivado de hmetadatai, T é um tipo e S? é um tipo ou a sequência vazia. Seja S0 S? se for um tipo, caso contrário, deixe S0 ser dinâmico. O tipo associado de D, chamado F, é, respectivamente:

• T

• Função S0 (T1, ..., Tn, [Tn + 1, ..., Tn + k])

• Função S0 (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k})



D introduz um mapeamento das listas de argumentos de tipos reais para tipos. Sob a suposição de que X1, ..., Xs são tipos tais que Xj <: Bj, para todos os j ∈ 1..s, é um erro em tempo de compilação se T não tiver limites regulares e é um compilador- erro de tempo se algum tipo que ocorre em T não estiver bem delimitado.

Isso significa que os limites declarados para os parâmetros de tipo formal de um alias de tipo genérico devem ser tais que, quando forem satisfeitos, os limites que pertencem ao corpo também sejam satisfeitos e um tipo que ocorra como um subtermo do corpo possa violar seus limites. , mas apenas se for um tipo super-limitado correto.

Além disso, seja T1, ..., Tl tipos e U seja o tipo de parâmetro parametrizado <T1, ..., Tl> em um local onde id denota D. É um erro em tempo de compilação se l 6 = s. É um erro em tempo de compilação se U não estiver bem delimitado (14.2).

Caso contrário, U denota uma aplicação do mapeamento indicado por D para os argumentos de tipo T1, ..., Ts, produzindo o tipo [T1 / X1, ..., Ts / Xs] F.

Observe que a sintaxe do alias de tipo sem '=' pode expressar apenas tipos de função e não pode expressar o tipo de uma função genérica. Quando esse alias de tipo é genérico, ele sempre expressa uma família de tipos de funções não genéricas. Essas restrições existem porque essa sintaxe foi definida antes da adição de funções genéricas ao Dart.

O requisito de que a satisfação dos limites nos parâmetros de tipo formal de um alias de tipo genérico D deve implicar a satisfação de todos os limites pertencentes a todos os tipos que ocorrem no corpo de D limita o poder expressivo dos aliases de tipo genérico. No entanto, exigiria que as restrições nos parâmetros de tipo formal fossem expressas em uma linguagem muito mais poderosa se permitíssemos que um conjunto significativamente maior de tipos fosse expresso usando um alias de tipo genérico.

Por exemplo, considere o seguinte código:

classe A <X estende a Função nula (num)> {}

typedef F <Y> = A <Função nula (Y)> Função (); // erro em tempo de compilação

Não há como especificar um limite em Y na declaração de F, o que garantirá que todos os limites do lado direito sejam respeitados. Isso ocorre porque o requisito real é que Y seja um supertipo de num, mas o Dart não suporta limites inferiores para parâmetros de tipo. O tipo A <Função nula (U)> Função () ainda pode ser especificado explicitamente para cada U que satisfaça os limites declarados por A. Portanto, os tipos podem ser expressos, apenas não podem ser abreviados usando um alias de tipo genérico.

Um tipo genérico é um tipo que é introduzido por uma declaração de classe genérica ou um alias de tipo genérico, ou é o tipo FutureOr.

Uma declaração de função genérica introduz uma função genérica (9.2) no escopo final. Considere uma expressão de invocação de função no formato f <T1, ..., Tl> (...), em que o tipo estático de f é um tipo de função genérico com parâmetros de tipo formal

X1 estende B1, ..., Xm estende Bm.

É um erro em tempo de compilação se m 6 = l. É um erro em tempo de compilação se existir um j tal que Tj não seja um subtipo de [T1 / X1, ..., Tm / Xm] Bj.

Ou seja, se o número de argumentos de tipo estiver incorreto ou se o j-ésimo argumento de tipo real não for um subtipo do limite correspondente, em que cada parâmetro formal de tipo foi substituído pelo argumento de tipo real correspondente. htypeParameteri :: = hmetadatai hidentifieri (estende htypeNotVoidi)?

htypeParametersi :: = '<' htypeParameteri (',' htypeParameteri) * ''> '

Um parâmetro de tipo T pode ter o sufixo de uma cláusula extends que especifica o limite superior para T. Se nenhuma cláusula extends estiver presente, o limite superior será Object. É um erro em tempo de compilação se um parâmetro de tipo for um supertipo de seu limite superior quando esse limite superior for uma variável de tipo.

Isso evita declarações circulares como X estende X e X estende Y, Y estende X.

Os parâmetros de tipo são declarados no escopo do parâmetro de tipo de uma classe ou função. Os parâmetros de tipo de um G genérico estão no escopo nos limites de todos os parâmetros de tipo de G. Os parâmetros de tipo de uma declaração de classe genérica G também estão no escopo nas cláusulas de extensão e implementação de G (se existirem) e em o corpo de G.

No entanto, um parâmetro de tipo de uma classe genérica é considerado um tipo malformado quando referenciado por um membro estático (19.1). Os escopos associados aos parâmetros de tipo de uma função genérica são descritos em (9.2).

A restrição de membros estáticos é necessária, pois uma variável de tipo não tem significado no contexto de um membro estático, porque as estáticas são compartilhadas entre todas as instâncias genéricas de uma classe genérica. No entanto, uma variável de tipo pode ser referenciada a partir de um inicializador de instância, mesmo que isso não esteja disponível.

Como os parâmetros de tipo estão no escopo em seus limites, apoiamos a quantificação limitada por F (se você não sabe o que é isso, não pergunte). Isso permite digitar códigos de verificação como:

classe Ordenada <T> {

operador> (T x);

}

Classificador Classificador <T estende Ordenado <T>> {

classificar (Lista <T> l) ... l [n] <l [n + 1] ...

}

Mesmo onde os parâmetros de tipo estão no escopo, existem inúmeras restrições no momento:

Um parâmetro de tipo não pode ser usado para nomear um construtor em uma expressão de criação de instância (16.15).

• Um parâmetro de tipo não pode ser usado como superclasse ou superinterface (10.8, 10.9,

11.2)

• Um parâmetro de tipo não pode ser usado como um tipo genérico.



As versões normativas destes são fornecidas nas seções apropriadas desta especificação. Algumas dessas restrições podem ser levantadas no futuro.

14.1 Variação

variação



Dizemos que um tipo S ocorre covariantemente em um tipo T, se S ocorre em uma posição covariante em T, mas não em uma posição contravariante, e não em uma posição invariante.





Dizemos que um tipo S ocorre de forma contravariante em um tipo T, se S ocorre em uma posição contravariante em T, mas não em uma posição covariante, e não em uma posição invariante.





Dizemos que um tipo S ocorre invariantemente em um tipo T, se S ocorre em uma posição invariante em T, ou S ocorre em uma posição covariante, bem como em uma posição contravariante.





Dizemos que um tipo S ocorre em uma posição covariante em um tipo T se uma das seguintes condições for verdadeira:

• T é S

• T é da forma G <S1, ..., Sn>, onde G denota uma classe genérica e S ocorre em uma posição covariante em Sj para alguns j ∈ 1..n.

• T tem o formato S0 Função <X1 estende B1, ...> (S1 x1, ...) onde a lista de parâmetros de tipo pode ser omitida, e S ocorre em uma posição covariante em S0.

• T é da forma



Função S0 <X1 estende B1, ...>

(S1 x1, ..., Sk xk, [Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn]) ou no formato

Função S0 <X1 estende B1, ...>

(S1 x1, ..., Sk xk, {Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn})





onde a lista de parâmetros de tipo e cada valor padrão podem ser omitidos e S ocorre em uma posição contravariante em Sj por alguns j ∈ 1..n.

• T tem a forma G <S1, ..., Sn> em que G denota um alias de tipo genérico tal que j ∈ 1..n, o parâmetro de tipo formal correspondente a Sj é covariante, e S ocorre em uma posição covariante em Sj.





T é da forma G <S1, ..., Sn> onde G denota um alias de tipo genérico tal que j ∈ 1..n, o parâmetro de tipo formal correspondente a Sj é contravariante e S ocorre em uma posição contravariante em Sj .

Dizemos que um tipo S ocorre em uma posição contravariante no tipo T se uma das seguintes condições for verdadeira:

• T tem a forma G <S1, ..., Sn> onde G denota uma classe genérica e S ocorre em uma posição contravariante em Sj para alguns j ∈ 1..n.

• T tem o formato S0 Função <X1 estende B1, ...> (S1 x1, ...) onde a lista de parâmetros de tipo pode ser omitida e S ocorre em uma posição contravariante em S0.

• T é da forma



Função S0 <X1 estende B1, ...>

(S1 x1, ..., Sk xk, [Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn]) ou no formato

Função S0 <X1 estende B1, ...>

(S1 x1, ..., Sk xk, {Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn}) em que a lista de parâmetros de tipo e cada valor padrão podem ser omitidos e S ocorre em uma posição covariante em Sj para alguns j ∈ 1..n.

• T tem a forma G <S1, ..., Sn>, em que G denota um alias de tipo genérico tal que j ∈ 1..n, o parâmetro de tipo formal correspondente a Sj é covariante e S ocorre em uma posição contravariante em Sj.

• T tem a forma G <S1, ..., Sn> em que G denota um alias de tipo genérico tal que j ∈ 1..n, o parâmetro de tipo formal correspondente a Sj é contravariante e S ocorre em uma covariante position em Sj.





Dizemos que um tipo S ocorre em uma posição invariável em um tipo T se uma das seguintes condições for verdadeira:





• T tem a forma G <S1, ..., Sn> em que G denota uma classe genérica ou um alias de tipo genérico, e S ocorre em uma posição invariante em Sj para alguns j ∈ 1..n.

• T é da forma



Função S0 <X1 estende B1, ..., Xm estende Bm>

(S1 x1, ..., Sk xk, [Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn]) ou no formato

Função S0 <X1 estende B1, ..., Xm estende Bm>

(S1 x1, ..., Sk xk, {Sk + 1 xk + 1 = dk + 1, ..., Sn xn = dn}) em que a lista de parâmetros de tipo e cada valor padrão podem ser omitidos e S ocorre em uma posição invariável em Sj para alguns j ∈ 0..n ou S ocorre em Bi para alguns i ∈ 1..m.

T é da forma G <S1, ..., Sn> onde G denota um alias de tipo genérico, j ∈ 1..n, o parâmetro de tipo formal correspondente a Sj é invariante e S ocorre em Sj.

Considere uma declaração de alias de tipo genérico G com declarações de parâmetro de tipo formal X1 estende B1, ..., Xm estende Bm e o lado direito T. Let





j ∈ 1..m. Dizemos que o parâmetro formal do tipo Xj é invariável se Xj ocorrer





invariantemente em T, Xj é covariante se Xj ocorre covariantemente em T e Xj é





contravariante se Xj ocorre contravariantemente em T.

A variação fornece uma caracterização da maneira como um tipo varia conforme o valor de um subtermo varia, por exemplo, uma variável de tipo: Assuma que T é um tipo em que uma variável de tipo X ocorre e L e U são tipos que L é um subtipo de U. Se X ocorre covariantemente em T, então [L / X] T é um subtipo de [U / X] T. Da mesma forma, se X ocorre de forma contrária em T, então [U / X] T é um subtipo de [L / X] T. Se X ocorrer invariávelmente, não é garantido que [L / X] T e [U / X] T sejam subtipos um do outro em qualquer direção. Em resumo: com covariância, o tipo covaria; com contravariância, o tipo contraria; com invariância, todas as apostas estão fora.





14.2 Tipos super limitados

Esta seção descreve como os limites superiores declarados dos parâmetros de tipo formal são aplicados, incluindo alguns casos em que uma forma limitada de violação é permitida.

superBoundedTypes



Um tipo top é um tipo T, que Object é um subtipo de T. Por exemplo, Object, dynamic e void são tipos top, assim como FutureOr <void> e FutureOr <FutureOr <dynamic>>.





Todo tipo que não é um tipo parametrizado é limitado regularmente.

Em particular, toda classe não genérica e todo tipo de função são de tipo regular.

Seja T um tipo parametrizado no formato G <S1, ..., Sn> em que G denota uma classe genérica ou um alias de tipo genérico. Seja X1 estenda B1, ..., Xn estenda Bn





seja o parâmetro formal do tipo declarações de G. T é limitado regularmente se Sj for um subtipo de [S1 / X1, ..., Sn / Xn] Bj, para todos os j ∈ 1..n.

Isso significa que tipos limitados regulares são aqueles que não violam seus limites de parâmetro de tipo.

Seja T um tipo parametrizado da forma G <S1, ..., Sn> onde G denota





uma classe genérica ou um alias de tipo genérico. T é super-limitado se as seguintes condições forem verdadeiras:





• T não é limitado regularmente.

• Seja T0 o resultado da substituição de todas as ocorrências em T de um tipo superior em uma posição covariante por Nulo, e todas as ocorrências em T de Nulo em uma posição contravariante por Objeto. É necessário, então, que T0 seja vinculado regularmente. Além disso, se G denota um alias de tipo genérico com o corpo U, é necessário que todo tipo que ocorra como um subtermo de [S1 / X1, ..., Sn / Xn] U seja bem delimitado (definido abaixo).



Em resumo, pelo menos um argumento de tipo viola seu limite, mas o tipo é vinculado regularmente após a substituição de todas as ocorrências de um tipo extremo por um tipo extremo oposto, dependendo da variação.

Um tipo T é bem delimitado se for delimitado regularmente ou super delimitado. Qualquer uso de um tipo T que não seja bem delimitado é um erro em tempo de compilação.

É um erro em tempo de compilação se um tipo parametrizado T for super-limitado quando usado de qualquer uma das seguintes maneiras:

• T é um subtermo imediato de uma nova expressão (16.15.1) ou de uma expressão de objeto constante (16.15.2).

• T é um subtermo imediato de uma assinatura de construtor de fábrica de redirecionamento



(10.6.2)

• T é um subtermo imediato de uma cláusula extends de uma classe (10.8) ou ocorre como um elemento na lista de tipos de uma cláusula de implementos (10.9) ou de cláusula with (10).



Não é um erro se um tipo com super-limite ocorrer como um subtermo imediato de uma cláusula extends que especifica o limite de uma variável de tipo (14).

Os tipos de membros de tipos de classe com limite limitado são calculados usando as mesmas regras que os tipos de membros de outros tipos. Os tipos de aplicativos de função que envolvem tipos com limite limitado são calculados usando as mesmas regras que os tipos de aplicativos de função que envolvem outros tipos. Aqui está um exemplo:

classe A <X estende num> {

X x;

}

A <Objeto> a;

Com isso, a.x possui o tipo estático Object, mesmo que o limite superior na variável de tipo X seja num.

Os tipos com limite limitado permitem a expressão de supertipos comuns informativos de alguns conjuntos de tipos cujos supertipos comuns seriam muito menos informativos.

Por exemplo, considere a seguinte classe:

classe C <X estende C <X>> {

X próximo;

}

Sem tipos com super limite, não existe um tipo T que faça de C  um supertipo comum de todos os tipos do formato C  (observando que todos os tipos devem ter limite regular quando não temos a noção de tipos com limite superior ) Portanto, se desejamos permitir que uma variável mantenha qualquer instância "do tipo C", essa variável deve usar Object ou outro tipo superior como sua anotação de tipo, o que significa que um membro



sabe-se que existe o seguinte (que é o que queremos dizer com dizer que o tipo é

"Menos informativo").

Poderíamos introduzir uma noção de tipos recursivos (infinitos) e expressar o menor limite superior de todos os tipos da forma C  como alguma sintaxe cujo significado poderia ser aproximado p. No entanto, esperamos que qualquer conceito desse tipo no Dart acarrete um custo significativo para desenvolvedores e implementações em termos de complexidade e sutileza adicionais; portanto, optamos por não fazer isso. Tipos super-limitados são finitos, mas oferecem uma aproximação útil controlada pelo desenvolvedor a esses tipos infinitos.

Por exemplo, C <Object> e C <C <C <void> >> são tipos que um desenvolvedor pode optar por usar como uma anotação de tipo. Essa escolha serve como um compromisso com um nível finito de desdobramento do tipo infinito e permite uma certa quantidade de controle no ponto em que o desdobramento termina: Se c tiver o tipo C <C <dinâmico>>, então c.next. next tem o tipo dynamic e c.next.next.whatever não tem erro em tempo de compilação, mas se c tiver o tipo C <C <void>>, então o Object x = c.next.next; é um erro em tempo de compilação. Portanto, é possível que os desenvolvedores obtenham um tratamento mais ou menos rigoroso das expressões cujo tipo prossegue além do desdobramento finito especificado.

14.3 Instanciação ao limite

Esta seção descreve como calcular argumentos de tipo que são omitidos de um tipo ou de uma chamada de uma função genérica.

Observe que se supõe que a inferência de tipo já tenha ocorrido (6), portanto, os argumentos de tipo não são considerados omitidos se forem inferidos. Isso significa que a instanciação a ser ligada é um mecanismo de backup, que será usado quando nenhuma informação estiver disponível para inferência.

Considere a situação em que um termo t do formato hqualifiedi (que é sintaticamente o mesmo que htypeNamei) denota uma declaração de tipo genérica e é usado como um tipo ou uma expressão no programa anexo. Isso implica

instantiationToBound



argumentos desse tipo são aceitos, mas não fornecidos. Usamos a frase tipo bruto





respectivamente expressão de tipo bruto para identificar esses termos. A seguir, apenas





mencionar tipos brutos, mas tudo o que é dito sobre tipos brutos se aplica a expressões de tipo bruto da maneira óbvia.

Por exemplo, com a declaração Type listType () => List ;, a avaliação da expressão bruta de tipo List no corpo gera uma instância da classe Type reifying List <dynamic>, porque List está sujeita a instanciação a ser vinculada. Observe que List <dynamic> não é sintaticamente uma expressão, mas ainda é possível obter acesso a uma instância Type reifying List <dynamic> sem instanciação a ser vinculada, porque pode ser o valor de uma variável de tipo.

Podemos definir inequivocamente tipos brutos para denotar o resultado da aplicação do tipo genérico a uma lista de argumentos de tipos reais fornecidos implicitamente, e a instanciação para ligação é um mecanismo que faz exatamente isso. Isso ocorre porque o Dart não suporta e não suporta tipos de classe superior; por exemplo, o valor de uma variável de tipo X será um tipo, não pode ser a classe genérica List como tal e não pode ser aplicada aos argumentos de tipo, por exemplo, X <int>.

No caso típico em que apenas a covariância é encontrada, a instanciação para o limite produzirá um supertipo de todos os tipos de limites regulares que podem ser expressos. Isso permite que os desenvolvedores considerem um tipo bruto como um tipo usado para especificar que "os argumentos do tipo real não importam". Por exemplo, supondo que a classe de declaração C <X estenda num> {...}, a instanciação para ligar em C produz C <num>, e isso significa que C x; pode ser usado para declarar uma variável x cujo valor pode ser um C <T> para todos os valores possíveis de T.

Por outro lado, considere a situação em que um alias de tipo genérico denota um tipo de função e possui um parâmetro de tipo que é contravariante. A instanciação a ser vinculada nesse alias de tipo produzirá um subtipo de todos os tipos com limite regular que podem ser expressos variando o argumento desse tipo. Isso permite que os desenvolvedores considerem um alias de tipo usado como um tipo bruto como um tipo de função que permite que a função seja passada aos clientes "onde não importa quais valores para o argumento de tipo o cliente espera". Por exemplo, com typedef F <X> = Função (X); a instanciação ligada a F produz F <dinâmico>, e isso significa que F f; pode ser usado para declarar uma variável f cujo valor será uma função que pode ser passada para clientes que esperam um F <T> para todos os valores possíveis de T.

14.3.1 Auxil
vários conceitos de instanciação para vincular

Antes de especificarmos a instanciação como vinculada, precisamos definir dois auxiliares

auxiliarryConceptsForInstantiationToBound



conceitos. Seja T um tipo bruto. Um tipo S então depende de T se uma ou mais das seguintes condições forem mantidas:





• S possui o formato htypeNamei e S é T. Observe que este caso não é aplicável se S for um subtermo de um termo no formato S <typeArguments>, ou seja, se S receber algum argumento de tipo. Observe também que S não pode ser uma variável de tipo, porque 'S é T' não pode ser mantido. Veja a discussão abaixo e a referência a 19.4.2 para obter mais detalhes sobre o motivo.

• S tem o formato htypeNamei htypeArgumentsi, e um dos argumentos de tipo raw depende de T.

• S tem o formato htypeNamei htypeArgumentsi? onde htypeNamei indica um apelido de tipo F, e o corpo de F bruto depende de T.

• S tem a forma htypei? Função htypeParametersi? hparameterTypeListi e htypei? Raw-depende de T, ou um limite em htypeParametersi? raw depende de T ou um tipo em hparameterTypeListi depende de T.



Meta-variáveis ​​(19.4.1) como S e T são entendidas como denotando tipos e são consideradas iguais (como em 'S é T') no mesmo sentido que na seção sobre regras de subtipo (19.4.2) . Em particular, mesmo que duas partes idênticas da sintaxe possam denotar dois tipos distintos e duas partes diferentes da sintaxe possam denotar o mesmo tipo, a propriedade de interesse aqui é se elas denotam o mesmo tipo e não se estão escritas de forma idêntica.

A intuição por trás da situação em que um tipo bruto depende de outro tipo é que precisamos calcular quaisquer argumentos de tipo ausentes para o último, a fim de podermos dizer o que o primeiro significa.

Na regra sobre aliases de tipo, F pode ou não ser genérico e os argumentos de tipo podem ou não estar presentes. No entanto, não há necessidade de considerar o resultado da substituição de argumentos de tipo real por parâmetros de tipo formal no corpo de F (ou mesmo a correção de passar esses argumentos de tipo para F), porque precisamos apenas inspecionar todos os tipos do formulário htypeNamei em seu corpo, e eles não são afetados por essa substituição. Em outras palavras, a dependência bruta é uma relação simples e barata de calcular.

Seja G uma classe genérica ou um alias de tipo genérico com k declarações de parâmetro de tipo formal contendo parâmetros de tipo formal X1, ..., Xk e os limites B1, ..., Bk. Para qualquer j ∈ 1..k, dizemos que o parâmetro de tipo formal Xj tem um





limite simples quando um dos seguintes requisitos for atendido:

• Bj é omitido.

• Bj está incluído, mas não contém X1, ..., Xk. Se Bj rawdepende de um tipo bruto T, todos os parâmetros de tipo T devem ter um limite simples.



A noção de um limite simples deve ser interpretada indutivamente, e não coindutivamente, ou seja, se um Bj ligado de uma classe genérica ou um alias de tipo genérico G for alcançado durante uma investigação sobre se Bj é um limite simples, a resposta é não.

Por exemplo, com a classe C <X estende C> {}, o parâmetro de tipo X não possui um limite simples: um C bruto é usado como um limite para X, portanto, C deve ter limites simples, mas um dos limites de C é o limite de X e esse limite é C, então C deve ter limites simples: esse era um ciclo; portanto, a resposta é "não", C não possui limites simples.





Seja G uma classe genérica ou um alias de tipo genérico. Dizemos que G possui limites simples se todo parâmetro de tipo de G possui limites simples.





Agora podemos especificar em que sentido a instanciação a ser vinculada requer que os tipos envolvidos sejam "bastante simples". Nós impomos a seguinte restrição em todos os limites de parâmetro de tipo, porque todos os parâmetros de tipo podem estar sujeitos a instanciação para ligação.

É um erro em tempo de compilação se um parâmetro de tipo formal vinculado B contiver um tipo bruto T, a menos que T tenha limites simples.

Portanto, argumentos de tipo nos limites só podem ser omitidos se eles próprios tiverem limites simples. Em particular, a classe C <X estende C> {} é um erro em tempo de compilação, porque o limite C é bruto e o parâmetro formal do tipo X que corresponde ao argumento do tipo omitido não possui um limite simples.

Seja T um tipo do formato htypeNamei que denota uma classe genérica ou um alias de tipo genérico (para que T seja bruto). Então T é equivalente ao tipo parametrizado, que é o resultado obtido pela aplicação da instanciação para vincular a T. É um erro em tempo de compilação se a instanciação para vincular falhar.

Esta regra é aplicável a todas as ocorrências de tipos brutos, por exemplo, quando ocorre como uma anotação de tipo de uma variável ou parâmetro, como um tipo de retorno de uma função, como um tipo que é testado em um teste de tipo, como o tipo em um honParti, etc.

14.3.2 A instanciação ao algoritmo vinculado

theInstantiationToBoundAlgorithm



Agora especificamos como a instanciação para o algoritmo vinculado prossegue. Seja T um tipo bruto. Seja X1, ..., Xk os parâmetros de tipo formal na declaração de G e B1, ..., Bk sejam seus limites. Para cada i ∈ 1..k, deixe Si denotar o resultado da instanciação para ligar em Bi; em caso o omésimo limite seja omitido, seja dinâmico.





Se Bi para alguns i é bruto (em geral: se depende de algum tipo U), todos os argumentos de tipo omitidos (respectivamente U's) têm limites simples. Isso limita a complexidade da instanciação a ser ligada a Bi e, em particular, não pode envolver um ciclo de dependência em que precisamos que o resultado da instanciação seja ligado a G, a fim de calcular a instanciação a ser ligada a G.

Seja Ui, 0 seja Si, para todos os i ∈ 1..k. Este é o "valor atual" do limite para a variável de tipo i, na etapa 0; em geral, consideraremos a etapa atual, m, e usaremos os dados para essa etapa, por exemplo, o Ui, m ligado, para calcular os dados da etapa m + 1.

Seja → m uma relação entre as variáveis ​​de tipo X1, ..., Xk, de modo que Xp → m Xq se xq ocorrer em Up, m. Portanto, cada variável de tipo está relacionada a, ou seja, depende de cada variável de tipo em seu limite, que pode incluir a si mesma. Seja → + m o fechamento transitivo (mas não reflexivo) de → m. Para cada m, Ui, m + 1, para i ∈ 1..k, seja determinado pelo seguinte processo iterativo, em que Vm denota G <U1, m, ..., Uk, m>:

Se existir um j ∈ 1..k tal que Xj → + m Xj (ou seja, se o gráfico de dependência tiver um ciclo), M1, ..., Mp sejam os componentes fortemente conectados (SCCs) em relação a → m. Ou seja, os subconjuntos máximos de X1, ..., Xk, onde cada par de variáveis ​​em cada subconjunto está relacionado nas duas direções por → + m; observe que os SCCs são pareados; Além disso, eles são definidos exclusivamente para reordenar, e a ordem não importa para esse algoritmo. Seja M a união de M1, ..., Mp (ou seja, todas as variáveis ​​que participam de um ciclo de dependência). Deixe eu 1k. Se Xi não pertence a M, então



Ui, m + 1 é Ui, m. Caso contrário, existe um q tal que Xi ∈ Mq; Ui, m + 1 é então obtido a partir de Ui, m substituindo dinâmica por toda ocorrência de uma variável em Mq que esteja em uma posição em Vm que não seja contravariante e substituindo Nulo por toda ocorrência de uma variável em Mq que esteja em um posição contravariante em Vm.

Caso contrário (quando não houver ciclos de dependência), j seja o número mais baixo, de modo que Xj ocorra em Up, m para alguns p e Xj → 6 m Xq para todos q em 1..k (ou seja, o limite de Xj não contém nenhuma variável de tipo, mas Xj ocorre no limite de outra variável de tipo). Então, para todos os i ∈ 1..k, Ui, m + 1 é obtido de Ui, m substituindo Uj, m por cada ocorrência de Xj que está em uma posição em Vm que não é contravariante e substituindo Nulo por cada ocorrência de Xj que está em uma posição contravariante em Vm.

Caso contrário (quando não houver nenhuma dependência), termine com o resultado <U1, m, ..., Reino Unido, m>.



Esse processo sempre terminará, porque o número total de ocorrências de variáveis ​​de tipo de {X1, ..., Xk} nos limites atuais está diminuindo estritamente a cada etapa, e terminamos quando esse número chega a zero.

Pode parecer um tanto arbitrário tratar parâmetros não utilizados e invariantes da mesma maneira que parâmetros covariantes, principalmente porque os parâmetros invariantes falham em satisfazer a expectativa de que um tipo bruto denota um supertipo de todos os tipos limitáveis ​​regulares expressáveis.

Poderíamos facilmente ter feito toda instanciação para limitar um erro quando aplicado a um tipo em que a invariância ocorre em qualquer lugar durante a execução do algoritmo. No entanto, existem vários casos em que essa opção produz um tipo utilizável e decidimos que não é útil proibir esses casos.

typedef Inv <X> = Função X (X); classe B <Y estende num, Z estende Inv <Y>> {}

B b; // O B bruto significa B <num, Inv <número>>.

Por exemplo, o valor de b pode ter um tipo dinâmico B <int, intFunction (num)>. No entanto, os argumentos de tipo devem ser escolhidos com cuidado ou o resultado não será um subtipo de B. Por exemplo, b não pode ter um tipo dinâmico B <int, Inv <int>>, porque Inv <int> não é um subtipo de B. Inv <num>.

Um tipo bruto T é um erro em tempo de compilação se a instanciação a ser ligada em T produzir um tipo que não seja bem delimitado (14.2).

Esse tipo de erro pode ocorrer, conforme demonstrado no seguinte exemplo:

classe C <X estende C <X>> {} typedef F <X estende C <X>> = X Função (X);

Ff; // Erro em tempo de compilação.

Com essas declarações, o F bruto que é usado como anotação de tipo é um erro em tempo de compilação: O algoritmo gera F <C <dinâmico>>, e esse não é um tipo com limite regular nem com super limite. O tipo resultante pode ser especificado explicitamente como Função C <dinâmica> (C <dinâmica>). Esse tipo existe, simplesmente não podemos expressá-lo passando um argumento de tipo para F, portanto, cometemos um erro ao invés de permitir implicitamente.

A principal razão pela qual faz sentido cometer um erro desse tipo bruto é que não há relação de subtipo entre os tipos parametrizados relevantes. Por exemplo, F <T1> e F <T2> não são relacionados, mesmo quando T1 <: T2 ou vice-versa. De fato, não existe nenhum tipo T, de modo que uma variável com o tipo declarado F <T> possa ser atribuída a uma variável do tipo C <dinâmica> Função (C <dinâmica>). Portanto, o F bruto, se permitido, não seria "um supertipo de F <T> para todos l possível T ”, seria um tipo não relacionado a F <T> para cada T único que satisfaça o limite de F. Isso é tão inútil que cometemos um erro.

Quando a instanciação ao limite é aplicada a um tipo, ela procede recursivamente: Para um tipo parametrizado G <T1, ..., Tk>, é aplicada a T1, ..., Tk. Para um tipo de função

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]) e um tipo de função

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}) é aplicada a T0, ..., Tn + k.

Isso significa que a instanciação ao limite não tem efeito em um tipo que não contém nenhum tipo bruto. Por outro lado, a instanciação para atos vinculados em tipos que são subtermos sintáticos, também quando estão profundamente aninhados.





15 Metadados Metadados


O Dart suporta metadados que são usados ​​para anexar anotações definidas pelo usuário às estruturas do programa.

hmetadatai :: = ('@' hqualifiedi ('.' hidentifieri)? hargumentsi?) *

Os metadados consistem em uma série de anotações, cada uma começando com o caractere '@', seguida por uma expressão constante e derivável de hqualifiedi ('.' Hidentifieri)? hargumentsi ?. É um erro em tempo de compilação se e não for um dos seguintes:

• Uma referência a uma variável constante.

• Uma chamada para um construtor constante.



A expressão e ocorre em um contexto constante (16.3.1), o que significa que os modificadores const não precisam ser especificados explicitamente.

Os metadados estão associados à árvore de sintaxe abstrata da construção do programa p que segue imediatamente os metadados e que não são os próprios metadados ou um comentário. Os metadados podem ser recuperados no tempo de execução por meio de uma chamada reflexiva, desde que a construção do programa anotado p seja acessível por reflexão.

Obviamente, os metadados também podem ser recuperados estaticamente, analisando o programa e avaliando as constantes por meio de um intérprete adequado. De fato, muitos, se não a maioria, dos metadados são totalmente estáticos.

É importante que nenhuma sobrecarga de tempo de execução seja incorrida pela introdução de metadados que não são realmente usados. Como os metadados envolvem apenas constantes, o tempo em que são calculados é irrelevante. Portanto, as implementações podem ignorar os metadados durante a análise e execução comuns e avaliá-los preguiçosamente.

É possível associar metadados a construções que podem não ser acessíveis via reflexão, como variáveis ​​locais (embora seja concebível que, no futuro, bibliotecas reflexivas mais ricas também possam fornecer acesso a eles). Isso não é tão inútil quanto pode parecer. Como observado acima, os dados podem ser recuperados estaticamente se o código fonte estiver disponível.

Os metadados podem aparecer antes de uma biblioteca, cabeçalho da peça, classe, typedef, tipo pa-

parâmetro, construtor, fábrica, função, parâmetro ou declaração de variável e antes de uma diretiva de importação, exportação ou peça.

A expressão constante fornecida em uma anotação é do tipo marcada e avaliada no escopo em torno da declaração que está sendo anotada.



expressões



Uma expressão é um fragmento do código Dart que pode ser avaliado em tempo de execução.

Toda expressão tem um tipo estático associado (19.1) e pode ter um tipo de contexto estático associado que pode afetar o tipo estático e a avaliação da expressão. Todo valor tem um tipo dinâmico associado (19.2).

hexpressioni :: = hassignableExpressioni hassignmentOperatori hexpressioni

| hconditionalExpressioni hcascadeSectioni * | hthrowExpressioni

hexpressionWithoutCascadei :: = hassignableExpressioni hassignmentOperatori hexpressionWithoutCascadei | hconditionalExpressioni

| hthrowExpressionWithoutCascadei hexpressionListi :: = hexpressioni (',' hexpressioni) *

hprimaryi :: = hthisExpressioni

| super hunconditionalAssignableSelectori

| hfunctionExpressioni

| hliterali

| hidentifieri

| hnewExpressioni

| hconstObjectExpressioni

| "(" Hexpressioni ")"

Uma expressão e sempre pode estar entre parênteses, mas isso nunca tem efeito semântico em e.

No entanto, pode afetar a expressão circundante. Por exemplo, dada uma classe C com um método estático m () => 42, C.m () retorna 42, mas (C) .m () é um erro em tempo de compilação. O ponto é que o significado de C.m () é especificado em termos de várias partes, em vez de ser especificado de maneira estritamente composicional. Concretamente, o significado de C e (C) como expressões é o mesmo, mas o significado de Cm () não é definido em termos do significado de C como expressão e difere do significado de (C) .m ( )





16.1 Avaliação de expressão

expressionEvaluation



A avaliação de uma expressão produz um objeto ou lança uma exceção





16 expressões




objeto de organização e um rastreamento de pilha associado. No primeiro caso, também dizemos que

a expressão é avaliada para um objeto.

Se a avaliação de uma expressão, e, é definida em termos de avaliação de outra expressão e1, geralmente uma subexpressão de e, e a avaliação de e1 gera uma exceção e um rastreamento de pilha, a avaliação de e para nesse ponto e gera a mesma objeto de exceção e rastreamento de pilha.





16.2 Objeto

Identity objectIdentity


A função Dart predefinida idêntica () é definida de forma que idêntica (c1, c2) iff:

• c1 avalia o objeto nulo (16.4) ou uma instância de bool e c1



== c2, OR

• c1 e c2 são instâncias de int e c1 == c2, OR

• c1 e c2 são cadeias constantes e c1 == c2, OR

• c1 e c2 são instâncias de double e um dos seguintes é válido:



- c1 e c2 são diferentes de zero e c1 == c2.

- Ambos c1 e c2 são +0,0.

- c1 e c2 são -0,0.

- Tanto c1 como c2 representam um valor de NaN com o mesmo padrão de bits subjacente.



OU

• c1 e c2 são listas constantes definidas para serem idênticas na especificação de expressões de lista literal (16.9), OU

• c1 e c2 são mapas constantes que são definidos para serem idênticos na especificação de expressões literais de mapa (16.10), OU

• c1 e c2 são objetos constantes da mesma classe C e o valor de cada variável de instância de c1 é idêntico ao valor da variável de instância correspondente de c2. OU

• c1 e c2 são o mesmo objeto.



A definição de identidade para dobras difere da de igualdade, pois um NaN é idêntico a si mesmo e que o zero negativo e o positivo são distintos.

A definição de igualdade para duplos é ditada pelo padrão IEEE 754, que postula que os NaNs não obedecem à lei da reflexividade. Dado que o hardware implementa essas regras, é necessário apoiá-las por razões de eficiência.

A definição de identidade não é restrita da mesma maneira. Em vez disso, assume que as dobras com bits idênticos são idênticas.

As regras de identidade tornam impossível para um programador Dart observar se um valor booleano ou numérico está dentro ou fora de caixa.

16.3 Constantes

Todos os usos da palavra "constante" no Dart estão associados ao tempo de compilação. Uma expressão potencialmente constante é uma expressão que geralmente gera um valor constante quando o valor de determinados parâmetros é fornecido. As expressões constantes são um subconjunto das expressões potencialmente constantes que podem ser avaliadas inteiramente em tempo de compilação.

As expressões constantes são restritas a expressões que executam apenas operações aritméticas simples, condições booleanas e criação de cadeia e instância. Nenhum corpo de função gravado pelo usuário é executado durante a avaliação de expressão constante, apenas membros das classes do sistema int, double, bool, String ou Null.

constantes



As expressões potencialmente constantes e constantes são as seguintes





lowing:





• Um literal booleano, verdadeiro ou falso (16,6), é uma expressão potencialmente constante e constante.

• Um número literal (16.5) é uma expressão potencialmente constante e constante se for avaliado para uma instância do tipo int ou double.

• Uma string literal (16.7) com interpolações de string (16.7.1) com expressões e1, ..., en é uma expressão potencialmente constante se e1, ..., en forem expressões potencialmente constantes. O literal é ainda uma expressão constante se e1, ..., en forem expressões constantes avaliando instâncias de int, doubleString, bool ou Null. Esses requisitos são triviais se não houver interpolações na string. Seria tentador permitir a interpolação de cadeias onde o valor interpolado é qualquer constante em tempo de compilação. No entanto, isso exigiria a execução do método toString () para objetos constantes, que poderiam conter código arbitrário.

• Um símbolo literal (16.8) é uma expressão potencialmente constante e constante.

• O literal nulo (16.4) é uma expressão potencialmente constante e constante.

• Um identificador que denota uma variável constante é uma expressão potencialmente constante e constante.

• Uma referência qualificada a uma variável constante estática (8) que não é qualificada por um prefixo adiado, é uma expressão potencialmente constante e constante. Por exemplo, se a classe C declara uma variável estática constante v, C.v é uma constante. O mesmo acontece se C for acessado através de um prefixo p; p.C.v é uma constante, a menos que p seja um prefixo adiado.

• Um identificador simples ou qualificado que denota uma classe, um mixin ou um alias de tipo que não é qualificado por um prefixo adiado, é uma expressão potencialmente constante e constante. A expressão constante sempre é avaliada como um objeto Type. Por exemplo, se C é o nome de um alias de classe ou tipo, a expressão C é uma constante e se C é importado com um prefixo p, p.C é uma instância de Type constante que representa o tipo de C, a menos que p seja um prefixo adiado.





Um identificador simples ou qualificado que denota uma função de nível superior (9) ou um método estático (10.7) que não é qualificado por um prefixo adiado, é uma expressão potencialmente constante e constante.

• Uma expressão identificadora que indica um parâmetro de um construtor constante (10.6.3) que ocorre na lista de inicializadores do construtor, é uma expressão potencialmente constante.

• Uma expressão de objeto constante (16.15.2), const C <T1, ..., Tk> (argumentos) ou const C <T1, ..., Tk> .id (argumentos) ou qualquer expressão sem a const principal que ocorre em um contexto constante, é um potentia expressão constante. Além disso, é uma expressão constante se a chamada for avaliada para um objeto. É um erro em tempo de compilação se uma expressão de objeto constante não for uma expressão constante (16.15.2).

• Um literal de lista constante (16.9), const <T> [e1, ..., en] ou <T> [e1, ..., en] que ocorre em um contexto constante, é uma expressão potencialmente constante se T é uma expressão de tipo constante e e1, ..., en são expressões constantes. Além disso, é uma expressão constante se o literal da lista for avaliado para um objeto.

• Um conjunto constante de literal (??), const <T> {e1, ..., en} ou <T> {e1, ..., en} que ocorre em um contexto constante, é uma expressão potencialmente constante se T é uma expressão de tipo constante e e1, ..., en são expressões constantes. Além disso, é uma expressão constante se o literal da lista for avaliado para um objeto.

• Um literal de mapa constante (16.10), const <K, V> {k1: v1, ..., kn: vn} ou <K, V> {k1: v1, ..., kn: vn} que ocorre em um contexto constante, é uma expressão potencialmente constante. É ainda uma expressão constante se o literal do mapa for avaliado para um objeto.

• Uma expressão entre parênteses (e) é uma expressão potencialmente constante se e é uma expressão potencialmente constante. Além disso, é uma expressão constante se e é uma expressão constante.

• Uma expressão da forma idêntica (e1, e2) é uma expressão potencialmente constante se e1 e e2 forem expressões potencialmente constantes e idênticas estiver estaticamente vinculada à função de dardo predefinida idêntica () discutida acima (16.2). Além disso, é uma expressão constante se e1 e e2 são expressões constantes.

• Uma expressão do formato e1! = E2 é equivalente a! (E1 == e2) em todos os aspectos, incluindo se é potencialmente constante ou constante.

• Uma expressão do formato e1 == e2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 e e2 forem constantes e e1 for avaliado para um objeto que é uma instância de int, double, String, bool ou Null ou se e2 for avaliado para o objeto nulo.



(16,4)

Uma expressão da forma! E1 é potencialmente constante se e1 for potencialmente constante. É ainda mais constante se e1 é uma expressão constante que é avaliada para uma instância do tipo bool.

• Uma expressão do formato e1 && e2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 for uma expressão constante e



e1 é avaliado como falso ou

e1 é avaliado como verdadeiro e e2 é uma expressão constante que é avaliada para uma instância do tipo bool.



• Uma expressão do formato e1 || e2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 for uma expressão constante e



e1 é avaliado como verdadeiro ou

e1 é avaliado como falso e e2 é uma expressão constante que é avaliada para uma instância do tipo bool.



• Uma expressão da forma ´e1 é uma expressão potencialmente constante se e1 for uma expressão potencialmente constante. Além disso, é uma expressão constante se e1 é uma expressão constante que é avaliada para uma instância do tipo int.

• Uma expressão de uma das formas e1 e e2, e1 | e2 ou e1 ˆe2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 e e2 são expressões constantes que são avaliadas tanto para instâncias de int quanto para instâncias de bool.

• Uma expressão de uma das formas e1 / e2, e1 >> e2, e1 >>> e2 ou e1 << e2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 e e2 forem expressões constantes que são avaliadas para uma instância de int.

• Uma expressão da forma e1 + e2 é uma expressão potencialmente constante se e1 e e2 forem expressões potencialmente constantes. Além disso, é uma expressão constante se e1 e e2 são expressões constantes e ambas são avaliadas para uma instância de int ou double ou ambas são avaliadas para uma instância de String.

• Uma expressão da forma -e1 é uma expressão potencialmente constante se e1 for uma expressão potencialmente constante. Além disso, é uma expressão constante se e1 é uma expressão constante que é avaliada para uma instância do tipo int ou double.

• Uma expressão no formato e1-e2, e1 * e2, e1 / e2, e1% e2, e1 <e2, e1 <= e2, e1> e2 ou e1> = e2 é potencialmente constante se e1 e e2 forem potencialmente possíveis expressões constantes. É ainda mais constante se e1 e e2 forem expressões constantes que são avaliadas para instâncias de int ou double.



Uma expressão do formato e1? E2: e3 é potencialmente constante se e1, e2 e e3 forem expressões potencialmente constantes. É constante se e1 for uma expressão constante e

e1 é avaliado como verdadeiro e e2 é uma expressão constante, ou

e1 é avaliado como falso e e3 é uma expressão constante.



• Uma expressão do formato e1 ?? e2 é potencialmente constante se e1 e e2 forem expressões potencialmente constantes. É ainda mais constante se e1 for uma expressão constante e



e1 é avaliado para um objeto que não é o objeto nulo ou

e1 é avaliado para o objeto nulo e e2 é uma expressão constante.



• Uma expressão da forma e.length é potencialmente constante se e for uma expressão potencialmente constante. É ainda mais constante se e é uma expressão constante que é avaliada para uma instância de String.

• Uma expressão da forma e como T é potencialmente constante se e for uma expressão potencialmente constante e T for uma expressão do tipo constante e será ainda mais constante se e for constante. É um erro em tempo de compilação avaliar a expressão constante se a operação de conversão for lançada, ou seja, se e for avaliada para um objeto que não é o objeto nulo e não é do tipo T.

• Uma expressão da forma e é T é potencialmente constante se e é uma expressão potencialmente constante e T é uma expressão do tipo constante e é ainda mais constante se e é constante.

• Uma expressão da forma e é! T é equivalente a! (E é T) em todos os aspectos, incluindo se é potencialmente constante ou constante.



Uma expressão de tipo constante é uma das seguintes:

• Um identificador simples ou qualificado que denota uma declaração de tipo (um alias de tipo, declaração de classe ou mixin) que não é qualificada por um prefixo adiado, opcionalmente seguido por argumentos de tipo no formato <T1, ..., Tn> em que T1,. .., Tn são expressões de tipo constante.

• Um tipo do formulário FutureOr <T> em que T é uma expressão de tipo constante.

• Uma função do tipo R Função <typeParameters> (argumentTypes) (onde R e <typeParameters> podem ser omitidos) e onde R, typeParameters e argumentTypes (se presentes) contêm apenas expressões de tipo constante.

• O tipo nulo.

• O tipo dinâmico.





É um erro em tempo de compilação se for necessário que uma expressão seja uma expressão constante, mas sua avaliação geraria uma exceção. É um erro em tempo de compilação se uma asserção for avaliada como parte de uma avaliação de expressão de objeto constante e a asserção gerará uma exceção.

Observe que não é necessário que todas as expressões constantes sejam avaliadas corretamente. Somente quando uma expressão constante é necessária (por exemplo, para inicializar uma variável constante, ou como valor padrão de um parâmetro formal ou como metadados), insistimos que uma expressão constante seja realmente avaliada com êxito no tempo de compilação.

O acima exposto não depende do fluxo de controle do programa. A mera presença de uma constante de tempo de compilação necessária cuja avaliação falharia em um programa é um erro. Isso também se aplica recursivamente: como as constantes compostas são compostas de constantes, se qualquer subparte de uma constante geraria uma exceção quando avaliada, isso é um erro.

Por outro lado, como as implementações são livres para compilar o código com atraso, alguns erros em tempo de compilação podem se manifestar com atraso.

const x = 1/0; y final = 1/0;

classe K {m1 () {

var z = false; se (z) {retornar x; } else {retorno 2; }

}

m2 () {

se (verdadeiro) {retornar y; } else {retorno 3; }

}

}

Uma implementação é livre para emitir imediatamente um erro de compilação para x, mas não é necessário. Pode adiar erros se não compilar imediatamente as declarações que fazem referência a x. Por exemplo, poderia atrasar a ocorrência de um erro de compilação sobre o método m1 até a primeira chamada de m1. No entanto, não foi possível optar por executar m1, veja que o ramo que se refere a x não é obtido e retorna

2 com sucesso.

A situação em relação a um m2 de chamada é diferente. Como y não é uma constante em tempo de compilação (mesmo que seu valor seja), não é necessário fornecer um erro em tempo de compilação ao compilar m2. Uma implementação pode executar o código, o que fará com que o getter para y seja invocado. Nesse ponto, a inicialização de y deve ocorrer, o que exige que o inicializador seja compilado, o que causará um erro de compilação.

O tratamento de null merece alguma discussão. Considere nulo + 2. Essa expressão sempre causa um erro. Poderíamos ter escolhido não tratá-lo como uma expressão constante (e, em geral, não permitir nulo como uma subexpressão de expressões constantes numéricas ou booleanas). Existem dois argumentos para incluí-lo:

É constante. Podemos avaliar em tempo de compilação.

Parece mais útil fornecer o erro decorrente da avaliação explicitamente.



Alguém poderia perguntar, razoavelmente, por que e1? E1: e3 e e1 ?? e2 têm formas constantes. Por exemplo, se e1 é conhecido estaticamente, por que precisamos testá-lo? A resposta é que existem contextos em que e1 é uma variável. Em particular, inicializadores constantes de construtores, como

const C (foo): this.foo = foo ?? someDefaultValue;

É um erro em tempo de compilação se o valor de uma expressão constante depende de si mesmo.

Como exemplo, considere:

classe CircularConsts {

// Programa ilegal - constantes de tempo de compilação recursivas mutuamente static const i = j; // uma constante estática em tempo de compilação const j = i; // uma constante em tempo de compilação

}

hliterali :: = hnullLiterali

| hbooleanLiterali

| hnumericLiterali

| hstringLiterali

| hsymbolLiterali

| hmapLiterali

| hsetLiterali

| hsetOrMapLiterali

| hlistLiterali

16.3.1 Contextos constantes constantContexts

eu et e ser uma expressão; e ocorre em um contexto constante se um dos seguintes itens se aplicar:

• e é um elemento de uma lista ou conjunto literal cujo primeiro token é const ou e é uma chave ou um valor de uma entrada de um literal de mapa cujo primeiro token é const.

• e ocorre como @e em uma construção derivada de hmetadatai.

• e é um argumento real em uma expressão derivada de hconstObjectExpressioni.

• e é a expressão inicial de uma declaração de variável constante (8).

• e é uma expressão de maiúsculas e minúsculas (17.9).

• e é uma subexpressão imediata de uma expressão e0 que ocorre em um contexto constante, onde e0 não é uma função literal (16.13).



Um contexto constante é introduzido em situações em que uma expressão precisa ser constante. Isso é usado para permitir que o modificador const seja omitido nos casos em que não contribui com nenhuma informação nova.

16.4 Nulo

nulo



A palavra reservada nulo é avaliada para o objeto nulo.

hnullLiterali :: = null

O objeto nulo é a única instância da classe interna Null. Tentar instanciar Null causa um erro em tempo de compilação. É um erro em tempo de compilação para uma classe estender, misturar ou implementar Null. A classe Null estende a classe Object e não declara métodos, exceto aqueles também declarados por Object. Em particular, a classe Null não substitui o operador '==' herdado da classe Object.

O tipo estático de nulo é o tipo Nulo.





16.5 Números

números



Um literal numérico é um numeral decimal ou hexadecimal que representa um valor inteiro ou uma representação dupla decimal.

hnumericLiterali :: = hNUMBERi

| hHEX_NUMBERi

hNUMBERi :: = hDIGITi + ('.' hDIGITi +)? hEXPONENTi? | H. 'HDIGITi + hEXPONENTi?

hEXPONENTi :: = ('e' | 'E') ('+' | | '-')? hDIGITi +

hHEX_NUMBERi :: = '0x' hHEX_DIGITi + | '0X' hHEX_DIGITi +

hHEX_DIGITi :: = 'a' .. 'f'

| 'A' .. 'F'

| hDIGITi





Um literal numérico começando com '0x' ou '0X' é um literal inteiro hexadecimal. Ele tem o valor inteiro numérico do numeral hexadecimal após '0x' (respectivamente '0X').





Um literal numérico que contém apenas dígitos decimais é um literal inteiro decimal. Possui o valor inteiro numérico do numeral decimal.





Um literal inteiro é um literal inteiro hexadecimal ou um literal inteiro decimal.

Seja l um número inteiro literal que não seja o operando de um operador menos unário e seja T o tipo de contexto estático de l. Se double é atribuível a T e int não é atribuível a T, então o tipo estático de l é duplo; caso contrário, o tipo estático de l é int. Isso significa que um literal inteiro denota um duplo quando satisfaz o requisito de tipo, e um int não. Caso contrário, é um int, mesmo em situações em que isso é um erro.
Um literal numérico que não é um literal inteiro é um literal duplo. Um literal duplo sempre contém um ponto decimal ou uma parte do expoente. O tipo estático de um literal duplo é duplo.

Se l for um literal inteiro com valor numérico ie tipo estático int, e l não for o operando de um operador menos unário, a avaliação de l continuará da seguinte forma:

* Se l é um literal inteiro hexadecimal, [263 ≤ i <264] e a classe int é implementada como um número inteiro de complemento assinado de dois bits de 64 bits, l é avaliada como uma instância da classe int que representa o valor numérico i - 264

* Caso contrário, eu avalio para uma instância da classe int que representa o valor numérico i. É um erro em tempo de compilação se o número inteiro i não puder ser representado exatamente por uma instância de int.



Os números inteiros no Dart foram projetados para serem implementados como representações inteiras de complemento de dois bits de 64 bits. Na prática, as implementações podem ser limitadas por outras considerações. Por exemplo, o Dart compilado no JavaScript pode usar o tipo de número JavaScript, equivalente ao dobro do Dart, para representar números inteiros e, nesse caso, literais inteiros com mais de 53 bits de precisão não podem ser representados exatamente.

Um literal duplo é avaliado como uma instância da classe double que representa um número de ponto flutuante de precisão dupla de 64 bits, conforme especificado pelo padrão IEEE 754.

Um literal inteiro com valor estático double e numérico i é avaliado para uma instância da classe double que representa o valor i. É um erro em tempo de compilação se o valor i não puder ser representado precisamente pela instância de double. Geralmente, um número de ponto flutuante de precisão dupla de 64 bits representa um intervalo de números reais em torno do valor preciso indicado pelo sinal, mantissa e expoente do número. Para literais inteiros que avaliam valores duplos, insistimos que o valor numérico do literal inteiro é o valor preciso da instância dupla.

É um erro em tempo de compilação para uma classe estender, misturar ou implementar int. É um erro em tempo de compilação para uma classe estender, misturar ou implementar o dobro. É um erro em tempo de compilação para qualquer classe que não seja int e double estender, misturar ou implementar num.

As instâncias de int e double substituem o operador '==' herdado da classe Object.





16.6 Booleanos

booleanos



As palavras reservadas true e false são avaliadas como objetos true e false que





representam os valores booleanos true e false respectivamente. Eles são os literais booleanos.

hbooleanLiterali :: = true

| falso





Verdadeiro e falso são instâncias da classe interna bool e existem





nenhum outro objeto que implemente bool. É um erro em tempo de compilação para uma classe estender, misturar ou implementar bool.

A classe bool não substitui o operador '==' herdado da classe Object.

Invocar o getter runtimeType em um valor booleano retorna o objeto Type, que é o valor da expressão bool. O tipo estático de um literal booleano é bool.





16.7 Strings

cordas



Uma sequência é uma sequência de unidades de código UTF-16.





Esta decisão foi tomada para compatibilidade com navegadores da web e Javascript. As versões anteriores da especificação exigiam que uma sequência fosse uma sequência de pontos de código Unicode válidos. Os programadores não devem depender dessa distinção.

hstringLiterali :: = (hmultilineStringi | hsingleLineStringi) +

Uma sequência pode ser uma sequência de sequências de linhas únicas e de várias linhas.

hsingleLineStringi :: = ‘" 'hstringContentDQi * ‘"'

| "HstringContentSQi *"

| 'R' '' ('(' '' | hNEWLINEi)) * '' ''

| 'R "' (˜ (‘ "’ | hNEWLINEi)) * ‘" '

Uma string de linha única é delimitada por aspas simples ou aspas duplas correspondentes.

Portanto, 'abc' e 'abc' são ambos elementos jurídicos, assim como 'Ele disse' ser ou não ser ', não é?' E 'Ele disse' ser ou não ser ', não é? No entanto, “Este‘ não é uma string válida nem ‘isto”.

A gramática garante que uma sequência de linhas única não possa abranger mais de uma linha de código-fonte, a menos que inclua uma expressão interpolada que abranja várias linhas.

Seqüências de caracteres adjacentes são implicitamente concatenadas para formar uma única seqüência de caracteres literal. Aqui está um exemplo de impressão ("Uma string" "e depois outra"); // Uma string e depois outra

O Dart também suporta o operador + para concatenação de cadeias.

O operador + em Strings requer um argumento String. Não coagiu seu argumento em uma string. Isso ajuda a evitar quebra-cabeças como

print ("Uma soma simples: 2 + 2 =" +

2 + 2);

que imprime "Uma soma simples: 2 + 2 = 22" em vez de "Uma soma simples: 2 + 2 = 4". No entanto, o uso da operação de concatenação ainda é desencorajado por motivos de eficiência. Em vez disso, o idioma recomendado do Dart é usar a interpolação de string.

print ("Uma soma simples: 2 + 2 = $ {2 + 2}");

A interpolação de strings funciona bem na maioria dos casos. A principal situação em que não é totalmente satisfatória é para literais de string grandes demais para caber em uma linha. Cadeias de linhas múltiplas podem ser úteis, mas em alguns casos, queremos alinhar visualmente o código. Isso pode ser expresso escrevendo cadeias menores separadas por espaços em branco, como mostrado aqui:

Imagine que essa é uma string muito longa que não cabe em uma linha. O que devemos fazer? '

'Oh, o que devemos fazer? 'Vamos dividi-lo em pedaços' como assim '.

hmultilineStringi :: = ‘" "" ’hstringContentTDQi *‘ "" "" '

| '' '' 'HstringContentTSQi *' '' ''

| ‘R" "" ’(˜‘ "" "’) * ‘" "" ’

| 'R' '' ('' '' ') *' '' '' '

hESCAPE_SEQUENCEi :: = "\ n"

| "R"

| '\ F'

| "\ B"

| "\ T"

| "\ V"

| ‘\ X 'hHEX_DIGITi hHEX_DIGITi

| "HHEX_DIGITi hHEX_DIGITi hHEX_DIGITi hHEX_DIGITi

| "\ U {" hHEX_DIGIT_SEQUENCEi ""

hHEX_DIGIT_SEQUENCEi :: = hHEX_DIGITi hHEX_DIGITi? hHEX_DIGITi? hHEX_DIGITi? hHEX_DIGITi? hHEX_DIGITi?


Cadeias de linhas múltiplas são delimitadas por triplos correspondentes de aspas simples ou triplos correspondentes de aspas duplas. Se a primeira linha de uma sequência multilinha consistir apenas nos caracteres de espaço em branco definidos pela produção hWHITESPACEi (20.1), possivelmente prefixados por '\', essa linha será ignorada, incluindo a quebra de linha no final.

A idéia é ignorar uma primeira linha somente de espaço em branco de uma sequência multilinha, em que espaço em branco é definido como tabulações, espaços e a quebra de linha final. Eles podem ser representados diretamente, mas, como para a maioria dos caracteres prefixados por barra invertida é uma identidade em uma sequência não bruta, permitimos esses formulários também.

As seqüências de caracteres oferecem suporte a seqüências de escape para caracteres especiais. As fugas são:

• '\ n' para nova linha, equivalente a '\ x0A'.

• '\ r' para retorno de carro, equivalente a '\ x0D'.

• '\ f' para feed de formulário, equivalente a '\ x0C'.

• '\ b' para backspace, equivalente a '\ x08'.

• '\ t' para a guia, equivalente a '\ x09'.

• '\ v' para a guia vertical, equivalente a '\ x0B'.

• '\ x' hHEX_DIGITi1 hHEX_DIGITi2, equivalente a '\ u {' hHEX_DIGITi1 hHEX_DIGITi2 ‘} '.

• '\ u' hHEX_DIGITi1 hHEX_DIGITi2 hHEX_DIGITi3 hHEX_DIGITi4, equivalente a



‘\ U {'hHEX_DIGITi1 hHEX_DIGITi2 hHEX_DIGITi3 hHEX_DIGITi4

.} '.

• '\ u {' hHEX_DIGIT_SEQUENCEi '' 'é o ponto de código Unicode representado pelo hHEX_DIGIT_SEQUENCEi. É um erro em tempo de compilação se o valor do hHEX_DIGIT_SEQUENCEi não for um ponto de código Unicode válido.

• '$' indicando o início de uma expressão interpolada.

• Caso contrário, '\ $ k $' indica o caractere k para qualquer k que não esteja em {'n', 'r', 'f',



'B', 't', 'v', 'x', 'u'}.

Qualquer sequência de caracteres pode ser prefixada com o caractere 'r', indicando que é uma sequência bruta; nesse caso, nenhuma fuga ou interpolação é reconhecida.

Quebras de linha em uma cadeia de linhas múltiplas são representadas pela produção hNEWLINEi. Uma quebra de linha introduz um único caractere de nova linha no valor da sequência.

É um erro em tempo de compilação se um literal de sequência não bruta contiver uma sequência de caracteres do formato '\ x' que não seja seguida por uma sequência de dois dígitos hexadecimais. É um erro em tempo de compilação se uma literal de seqüência de caracteres não bruta contiver uma sequência de caracteres do formato '\ u' que não seja seguida por uma sequência de quatro dígitos hexadecimais ou por uma sequência delimitada por colchetes de dígitos hexadecimais.

hstringContentDQi :: = '((' \ '| |' "'| | $' | hNEWLINEi)

| ‘\’ (HNEWLINEi)

| hstringInterpolationi

hstringContentSQi :: = '(' \ '| |' '' | '$' | hNEWLINEi)

| ‘\’ (HNEWLINEi)

| hstringInterpolationi

hstringContentTDQi :: = ˜ (‘\’ | ‘" "" ’|‘ $ ')

| ‘\’ (HNEWLINEi)

| hstringInterpolationi

hstringContentTSQi :: = '((' \ '| |' '' '| |' $ ')

| ‘\’ (HNEWLINEi)

| hstringInterpolationi

hNEWLINEi :: = "\ n"

| "R"

| "R \ n"

Todos os literais de sequência são avaliados para instâncias da classe interna String. É um erro em tempo de compilação para uma classe estender, misturar ou implementar String. A classe String substitui o operador '==' herdado da classe Object. O tipo estático de uma string literal é String.

16.7.1 Interpolação de strings

É possível incorporar expressões em literais de cadeia não bruta, para que essas expressões sejam avaliadas e os valores resultantes sejam convertidos em cadeias e concatenados com a cadeia envolvente. Esse processo é conhecido como

stringInterpolation
interpolação de string.

hstringInterpolationi :: = '$' hIDENTIFIER_NO_DOLLARi

| '$ {' Hexpressioni '' '

O leitor notará que a expressão dentro da interpolação pode incluir strings, que podem ser interpoladas novamente recursivamente.

Um caractere '$' sem escape em uma string significa o início de uma expressão interpolada. O sinal '$' pode ser seguido por:

• Um único identificador que não contém o caractere '$'.

• Uma expressão delimitada por chaves.

O formulário $ id é equivalente ao formulário $ {id}. Uma cadeia interpolada, s, com o conteúdo 's0 $ {e1} s1 ... sn − 1 $ {en} sn' (onde qualquer um de s0, ..., sn pode estar vazio) é avaliada avaliando cada expressão ei ( 1 ≤ i ≤ n) em uma sequência ri na ordem em que ocorrem no texto de origem, da seguinte maneira:

• Avalie ei para um objeto oi.

• Invoque o método toString no oi sem argumentos e deixe ri ser o valor retornado.

• Se ri não for uma instância do tipo interno String, gere um erro.



Finalmente, o resultado da avaliação de s é a concatenação das seqüências de caracteres s0, r1, ..., rn e sn.

16.8 Símbolos

símbolos



Um literal de símbolo indica um nome que seria um nome de declaração válido ou um nome de biblioteca válido em um programa Dart.





hsymbolLiterali :: = '#' (hoperatori | (hidentifieri ('.' hidentifieri) *))

Um literal de símbolo #id em que id é um identificador que não começa com um sublinhado ('_'), é avaliado como uma instância de Symbol que representa o ID do identificador. Todas as ocorrências de #id são avaliadas para a mesma instância (as instâncias de símbolo são canonizadas) e nenhum outro literal de símbolo é avaliado para a instância Symbol ou para uma instância Symbol igual (de acordo com o operador to == '16.27) a essa instância.

Um símbolo literal # id.id2 ... idn em que id ... idn são identificadores, é avaliado para uma instância de Symbol que representa essa sequência específica de identificadores. Todas as ocorrências de # id.id2 ... idn com a mesma sequência de identificadores são avaliadas para a mesma instância e nenhum outro literal de símbolo é avaliado para essa instância de símbolo ou para uma instância de símbolo que é '==' para essa instância. Esse tipo de símbolo literal indica o nome de uma declaração da biblioteca. Os nomes das bibliotecas não estão sujeitos à privacidade da biblioteca, mesmo que alguns de seus identificadores iniciem com um sublinhado.

Um símbolo literal #operator é avaliado como uma instância de Symbol que representa esse nome de operador específico. Todas as ocorrências de #operator são avaliadas para a mesma instância e nenhum outro literal de símbolo é avaliado para a instância Symbol ou para uma instância Symbol que é '==' para essa instância.

Um literal de símbolo #_id é avaliado como uma instância de Symbol que representa o identificador privado _id da biblioteca que o contém. Todas as ocorrências de #_id na mesma biblioteca são avaliadas para a mesma instância e nenhum outro literal de símbolo é avaliado para essa instância de símbolo ou para uma instância de símbolo que é '==' para essa instância.

Todos os objetos criados por literais de símbolo substituem o operador '==' herdado da classe Object.

Pode-se perguntar qual é a motivação para a introdução de símbolos literais? Em algumas línguas, os símbolos são canonizados, enquanto as cordas não. No entanto litro Todas as strings já são canonizadas no Dart. Os símbolos são um pouco mais fáceis de digitar em comparação com as strings e seu uso pode se tornar estranhamente viciante, mas isso não é justificativa suficiente para adicionar uma forma literal ao idioma. A principal motivação está relacionada ao uso da reflexão e a uma prática específica da web conhecida como minificação.

A minificação compacta os identificadores de forma consistente em todo o programa para reduzir o tamanho do download. Essa prática apresenta dificuldades para programas reflexivos que se referem a declarações de programas por meio de strings. Uma string se referirá a um identificador na fonte, mas o identificador não será mais usado no código minificado, e o código reflexivo usando estes falhará. Portanto, a reflexão Dart usa objetos do tipo Symbol em vez de seqüências de caracteres. As instâncias do Symbol são garantidas como estáveis ​​em relação à minificação. Fornecer uma forma literal para símbolos facilita a leitura e gravação do código reflexivo. O fato de os símbolos serem fáceis de digitar e frequentemente atuarem como substitutos convenientes para enum é um benefício secundário.

O tipo estático de um literal de símbolo é Symbol.

16.9 Listas

listas



Um literal de lista denota uma lista, que é uma coleção inteira de objetos indexados. hlistLiterali :: = const? htypeArgumentsi? '[' (HexpressionListi ','?)? ‘]’

Uma lista pode conter zero ou mais objetos. O número de elementos em uma lista é seu tamanho. Uma lista tem um conjunto associado de índices. Uma lista vazia possui um conjunto vazio de índices. Uma lista não-vazia possui o conjunto de índices {0, ..., n-1} em que n é o tamanho da lista. É um erro dinâmico tentar acessar uma lista usando um índice que não é membro de seu conjunto de índices.

Se uma lista literal 'começa com a palavra reservada const ou ' ocorre em uma constante





contexto (16.3.1), é uma lista constante de literal, que é uma expressão constante (16.3)





e, portanto, avaliado em tempo de compilação. Caso contrário, é uma lista literal de tempo de execução e é avaliada em tempo de execução. Somente literais da lista de tempo de execução podem ser alterados após serem criados. Tentar alterar um literal da lista constante resultará em um erro dinâmico.





Observe que as expressões de elemento de um literal de lista constante ocorrem em um contexto constante (16.3.1), o que significa que os modificadores de const não precisam ser especificados explicitamente.

É um erro em tempo de compilação se um elemento de um literal de lista constante não for uma expressão constante. É um erro em tempo de compilação se o argumento de tipo de um literal de lista constante não for uma expressão de tipo constante.

A ligação de um parâmetro de tipo formal não é conhecida no momento da compilação; portanto, não podemos usar parâmetros de tipo dentro de expressões constantes.
oni hsetOrMapLiterali :: = const? htypeArgumentsi? ‘{’} ’

Um hsetOrMapLiterali é um literal de conjunto (16.11) ou um literal de mapa, determinado pelos parâmetros de tipo ou pelo tipo de contexto estático. Se e tiver exatamente um argumento de tipo, será um conjunto literal. Se e tiver dois argumentos de tipo, será um literal do mapa. Se e tiver três ou mais argumentos de tipo, será um erro em tempo de compilação. Se e não tiver argumentos de tipo, deixe S ser o tipo de contexto estático do literal. Se futureOrBase (S) (19.8) for um subtipo de Iterável <Object> e futureOrBase (S) não for um subtipo de Mapa <Objeto, Objeto>, e será definido literalmente; caso contrário, será um literal de mapa. Um literal de mapa derivado de hsetOrMapLiterali é tratado da mesma maneira que um derivado de hmapLiterali, conforme descrito abaixo.





Um literal de mapa consiste em zero ou mais entradas. Cada entrada possui uma chave e um





valor. Cada chave e cada valor é indicado por uma expressão. É um erro em tempo de compilação se um literal de mapa tiver um argumento de tipo ou mais de dois argumentos de tipo. Se um literal do mapa `começar com a palavra reservada const, ou se` ocorrer em





Em um contexto constante (16.3.1), é um literal de mapa constante que é uma expressão constante (16.3) e, portanto, é avaliado em tempo de compilação. Caso contrário, é um





literal de mapa de tempo de execução e é avaliado em tempo de execução. Somente literais de mapa de tempo de execução





podem ser modificados após serem criados. Tentar alterar um literal de mapa constante resultará em um erro dinâmico.

Observe que as expressões de chave e valor de um literal de lista constante ocorrem em um contexto constante (16.3.1), o que significa que os modificadores de const não precisam ser especificados explicitamente.

É um erro em tempo de compilação se uma chave ou um valor de uma entrada em um literal de mapa constante não for uma expressão constante. É um erro em tempo de compilação se o operador '==' da chave de uma entrada em um literal de mapa constante não for primitivo (10.1.3). É um erro em tempo de compilação se um argumento de tipo de um literal de mapa constante não for uma expressão de tipo constante (16.3).

O valor de um mapa constante literal const? <K, V> {k1: e1, ..., kn: en} é um objeto m cuja classe implementa a classe interna Map <K, V>. As entradas de m são ui: vi, i ∈ 1..n, onde ui é o valor da expressão em tempo de compilação ki e vi é o valor da expressão em tempo de compilação ei. O valor de uma constante literal de mapa constante? {K1: e1, ..., kn: en} é definido como o valor da constante literal de mapa constante <dinâmica, dinâmica> {k1: e1, ..., kn: en }

Seja map1 um mapa constante literal da forma const? <K, V> {k11: e11, ..., k1n: e1n} e map2 um mapa constante literal da forma const? <J, U> {k21: e21 , ..., k2n: e2n}. Permita que as chaves de map1 e map2 avaliem para s11, ..., s1n e s21, ..., s2n, respectivamente, e que os elementos de map1 e map2 avaliem para o11, ..., o1n e o21, ... , o2n, respectivamente. Se idêntico (o1i, o2i) e idêntico (s1i, s2i) para i ∈ 1..n, e K == J, V == U, então idênticos (mapa1, mapa2).

Em outras palavras, literais constantes do mapa são canonizados.

É um erro em tempo de compilação se duas chaves de um literal de mapa constante são iguais de acordo com o operador '==' (16,27).

Um literal de mapa de tempo de execução <K, V> {k1: e1, ..., kn: en} é avaliado da seguinte maneira:

• Para cada i ∈ 1..n em ordem numérica, primeiro a expressão ki é avaliada produzindo o objeto ui e depois ei é avaliada produzindo o objeto oi. Isso produz todos os objetos u1, o1, ..., un, on.

• Uma nova instância (10.6.1) m cuja classe implementa a classe interna Map <K, V> é alocada.

• O operador '[] =' é chamado em m com o primeiro argumento ui e o segundo argumento oi para cada i '1..n.

• O resultado da avaliação é m.



Os objetos criados pelos literais do mapa não substituem o operador '==' herdado da classe Object.

Um literal de mapa de tempo de execução {k1: e1, ..., kn: en} é avaliado como

<dinâmico, dinâmico> {k1: e1, ..., kn: en}.

Um literal de mapa é ordenado: a iteração sobre as chaves e / ou valores dos mapas sempre acontece na ordem em que as chaves apareceram no código-fonte.

Obviamente, se uma chave se repetir, a ordem é definida pela primeira ocorrência, mas o valor é definido pela última.

O tipo estático de um literal de mapa no formato const <K, V> {k1: e1, ..., kn:

en} ou o formato <K, V> {k1: e1, ..., kn: en} é Mapa <K, V>. O tipo estático de um literal de mapa no formato const {k1: e1, ..., kn: en} ou no formato {k1: e1, ..., kn: en} é Mapa <dinâmico, dinâmico>.

16.11 Sets

conjuntos



Um literal definido denota um objeto definido.

hsetLiterali :: = const? htypeArgumentsi?

Pression {'hexpressioni (‘,' hexpressioni) *‘, '? ‘}’

Um hsetOrMapLiterali é um literal de conjunto ou um literal de mapa (16.10). Um conjunto literal derivado de hsetOrMapLiterali é tratado da mesma maneira que um derivado de hsetLiterali, conforme descrito abaixo.

Um conjunto literal consiste em zero ou mais expressões de elemento. É um erro em tempo de compilação se um literal definido tiver mais de um argumento de tipo.

Um literal definido sem argumento de tipo é sempre convertido em literal com argumento de tipo por inferência de tipo (6); portanto, a seção a seguir aborda apenas th

O valor de uma constante da lista literal const? <E> [e1, ..., en] é um objeto a cuja classe implementa a classe interna List <E>. Seja vi o valor da expressão constante ei, i ∈ 1..n. O i-ésimo elemento de a (no índice i-1) é vi. O valor de uma constante da lista literal const? [E1, ..., en] é definido como o valor da constante da lista literal const <dynamic> [e1, ..., en].

Seja list1 = const? <V> [e11, ..., e1n] e list2 = const? <U> [e21, ..., e2n] sejam dois literais constantes da lista e permita que os elementos da lista1 e da lista2 sejam avaliados como o11 , ..., o1n e o21, ..., o2n, respectivamente. Se idêntico (o1i, o2i) para i ∈ 1..n e V == U então idêntico (lista1, lista2).

Em outras palavras, os literais constantes da lista são canonizados.

Uma lista de tempo de execução literal <E> [e1, ..., en] é avaliada da seguinte maneira:

• Primeiro, as expressões e1, ..., en são avaliadas na ordem em que aparecem no programa, produzindo os objetos o1, ..., on.

• Uma nova instância (10.6.1) a, de tamanho n, cuja classe implementa a classe interna List <E> está alocada.

• O operador '[] =' é chamado em a com o primeiro argumento ie segundo argumento oi + 1,0 ≤ i <n.

• O resultado da avaliação é a.



Os objetos criados pelos literais da lista não substituem o operador '==' herdado da classe Object.

Observe que este documento não especifica uma ordem na qual os elementos estão definidos. Isso permite atribuições paralelas na lista, se uma implementação desejar. A ordem só pode ser observada da seguinte forma (e não pode ser invocada): se o elemento i não for um subtipo do tipo de elemento da lista, ocorrerá um erro de tipo dinâmico quando um [i] for atribuído oi-1.

Uma lista de tempo de execução literal [e1, ..., en] é avaliada como <dynamic> [e1, ..., en].

Não há restrição que impede o aninhamento de literais de lista. Segue-se das regras acima que <List <int>> [<int> [1, 2, 3], <int> [4, 5, 6]] é uma lista com o parâmetro de tipo List <int>, contendo duas listas com o tipo parâmetro int.

O tipo estático de uma lista literal do formato const <E> [e1, ..., en] ou o formato <E> [e1, ..., en] é Lista <E>. O tipo estático de uma lista literal do formato const [e1, ..., en] ou o formato [e1, ..., en] é List <dynamic>.

16.10 Mapas

mapas



Um literal de mapa indica um objeto de mapa.

hmapLiterali :: = const? htypeArgumentsi?

'HmapLiteralEntryi (', 'hmapLiteralEntryi) *', '? "HmapLiteralEntryi :: = hexpressioni": "hexpressi" O comportamento de literais com argumentos de tipo.

Se um conjunto literal `começa com a palavra reservada const ou` ocorre em uma constante





contexto (16.3.1), é um conjunto literal constante que é uma expressão constante (16.3)





e, portanto, avaliado em tempo de compilação. Caso contrário, é um literal definido em tempo de execução e é avaliado em tempo de execução. Somente literais definidos em tempo de execução podem ser alterados após serem criados. Tentar alterar um literal de conjunto constante resultará em um erro dinâmico.





Observe que as expressões de elemento de um literal de conjunto constante ocorrem em um contexto constante (16.3.1), o que significa que os modificadores de const não precisam ser especificados explicitamente.

É um erro em tempo de compilação se uma expressão de elemento em um literal de conjunto constante não for uma expressão constante. É um erro em tempo de compilação se o operador '==' de uma expressão de elemento em um literal de mapa constante não for primitivo (10.1.3). É um erro em tempo de compilação se o argumento de tipo de um literal de conjunto constante não for uma expressão de tipo constante (16.3). É um erro em tempo de compilação se dois elementos de um literal de conjunto constante são iguais, de acordo com o operador '==' (16,27).

O valor de um conjunto constante de constante literal? <E> {e1, ..., en} é um objeto s cuja classe implementa a classe interna Set <E>. Os elementos de m são vi, i ∈ 1..n, onde vi é o valor da expressão constante ei. O valor de uma constante literal de conjunto constante? {E1, ..., en} é definido como o valor da constante literal de conjunto constante <dynamic> {e1, ..., en}.

Seja set1 um literal de conjunto constante com argumento de tipo E e expressões de elemento, na ordem de origem, e11, ..., e1n avaliando os valores v11, ..., v1n. Seja set2 um literal de conjunto constante com argumento de tipo F e expressões de elemento, na ordem de origem, e21, ..., e2n avaliando os valores v21, ..., v2n. Se idêntico (v1i, v2i) para i ∈ 1..n, e E e F são do mesmo tipo, então idênticos (conjunto1, conjunto2).

Em outras palavras, literais de conjunto constante são canonizados se tiverem o mesmo tipo e os mesmos valores na mesma ordem. Dois literais de conjunto constante nunca são idênticos se tiverem um número diferente de elementos.

Um literal de conjunto de tempo de execução com expressões de elemento e1, ..., en (na ordem de origem) e com o argumento de tipo E é avaliado da seguinte maneira:

• Para cada i ∈ 1..n em ordem numérica, a expressão ei é avaliada produzindo o objeto vi.

• Um objeto novo (10.6.1) s implementando a classe incorporada Set E, é criado.

• O conjunto s é feito para ter os valores v1, ..., vn como elementos, iterados em ordem numérica.

• O resultado da avaliação é s.



Os objetos criados pelos literais definidos não substituem o operador '==' herdado da classe Object.

Um literal de conjunto é ordenado: a iteração sobre os elementos dos conjuntos sempre acontece na ordem em que os elementos apareceram pela primeira vez no código-fonte.

Se um valor se repetir, a ordem será definida pela primeira ocorrência, mas o valor será definido pela última.

Um literal definido em tempo de execução {e1, ..., en} é avaliado como <dinâmico> {e1, ..., en}.

O tipo estático de um conjunto literal do formulário const E {e1, ..., en} ou o formulário E {e1, ..., en} é Set E. O tipo estático de uma lista literal do formulário const {e1, ..., en} ou o formulário {e1, ..., en} é Set dynamic.





16.12 Lançamento


A expressão throw é usada para lançar uma exceção.

hthrowExpressioni :: = throw hexpressioni hthrowExpressionWithoutCascadei :: = throw hexpressionWithoutCascadei

Avaliação de uma expressão de lançamento da forma throw e; procede da seguinte maneira: A expressão e é avaliada para um objeto v (16.1).

Não há exigência de que a expressão e deva ser avaliada para qualquer tipo especial de objeto.

Se v for o objeto nulo (16.4), um NullThrownError será lançado. Caso contrário, seja t um rastreamento de pilha correspondente ao estado de execução atual, e a instrução throw será lançada com v como objeto de exceção et como rastreamento de pilha (16.1).

Se v for uma instância da classe Error ou uma subclasse dela, e for a primeira vez que o objeto Error for lançado, o rastreamento da pilha t será armazenado em v, para que seja retornado pelo getTrace get do v

Se o mesmo objeto Error for lançado mais de uma vez, seu getTrack StackTrace retornará o rastreamento da pilha desde a primeira vez em que foi lançado. O tipo estático de uma expressão throw é ⊥.

16.13 Expressões de funções

functionExpressions



Um literal de função é uma declaração anônima e uma expressão que encapsula uma unidade de código executável.

hfunctionExpressioni :: = hformalParameterParti hfunctionBodyi

A gramática não permite que uma literal de função declare um tipo de retorno, mas





é possível que uma literal de função tenha um tipo de retorno declarado, porque pode ser obtida por meio da inferência de tipo. Esse tipo de retorno é incluído quando nos referimos ao tipo de retorno declarado de uma função.

A inferência de tipo será especificada em uma versão futura deste documento. Atualmente, consideramos que a inferência de tipo é uma fase que foi concluída, e este documento especifica o significado dos programas Dart nos quais tipos inferidos já foram adicionados.





Nós

defina a função auxiliar achatar (T), que é usada abaixo e em outras seções, da seguinte maneira:





• Se T for FutureOr <S> para alguns S, achatar (T) = S.

• Caso contrário, se T <: Futuro, então S seja um tipo tal que T <: Futuro <S> e para todos os R, se T <: Futuro <R> e S <: R.



Isso garante que Future <S> seja a instanciação genérica mais específica de Future que seja um supertipo de T. Observe que S está bem definido por causa dos requisitos em superinterfaces.

Achatar (T) = S.

• Em qualquer outra circunstância, aplainar (T) = T.



Caso hPosicional, arrowi. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) => e é

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]),

onde T0 é o tipo estático de e.

Caso hPosicional, seta, futuro. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) assíncrono => e é

Futuro <achatar (T0)>

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]),

onde T0 é o tipo estático de e.

Case hNamed, arrowi. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) => e é

Função T0 <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}), onde T0 é a estática tipo de e.

Caso hNomeado, seta, futuro. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) async => e é

Futuro <achatar (T0)>

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}), em que T0 é o tipo estático de e.

Caso hPosicional, bloco. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., XS estendeBS>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) {s} é

dinâmico

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k])

Caso hPosicional, bloco, futuro. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) async {s} é

Futuro

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]).

Caso hPosicional, bloco, streami. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) assíncrono * {s

} é

Corrente

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]).

Caso hPosicional, bloco, iterável. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) sincronização * {s} é

Iterável

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]). Case hNamed, blocki. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) {s} é

dinâmico

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, [Tn + 1, ..., Tn + k]).

Caso hNomeado, bloco, futuro. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) async {s} é

Futuro

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}).



Caso hNomeado, bloco, streami. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) assíncrono * {s

} é

Corrente

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}).



Caso hNomeado, bloco, iterável. O tipo estático de uma função literal do formulário

<X1 estendeB1, ..., Xs estendeBs>

(T1 a1, ..., Tn an, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) sincronização * {s} é

Iterável

Função <X1 / B1, ..., Xs / Bs> (T1, ..., Tn, {Tn + 1 xn + 1, ..., Tn + k xn + k}).



Em todos os casos acima, as listas de argumentos de tipo são omitidas quando m = 0 e, sempre que Ti não for especificado, i ∈ 1..n + k, é considerado como especificado como dinâmico.

A avaliação de uma literal de função gera um objeto de função o.

O tipo de tempo de execução de o é especificado com base no tipo estático T da função literal e na ligação das variáveis ​​de tipo que ocorrem em T na ocasião em que a avaliação ocorreu (9.3).





16.14 Este presente


A palavra reservada denota o destino da chamada de membro da instância atual.

hthisExpressioni :: = this

O tipo estático disso é a interface da classe que encerra imediatamente.

Não oferecemos suporte a tipos próprios neste momento.

É um erro em tempo de compilação se isso aparecer, implícita ou explicitamente, em uma função de nível superior ou inicializador de variável, em um construtor de fábrica, ou em um método estático ou inicializador de variável, ou no inicializador de uma variável de instância.

16.15 Criação de instância

As expressões de criação de instância geralmente produzem instâncias e invocam construtores para inicializá-las.

O exc

A idéia é que uma chamada de construtor de fábrica funcione como uma chamada de função regular. É claro que ele pode avaliar uma expressão de criação de instância e, assim, produzir uma instância nova, mas nenhuma instância nova é criada como uma conseqüência direta da chamada do construtor de fábrica.

É um erro em tempo de compilação se o tipo T em uma expressão de criação de instância de um dos novos formulários T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: A soma de dois números naturais é igual a: (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), const T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), const T (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) é um tipo enumerado (13).

instanceCreation



16.15.1 - novo

Novo



A nova expressão chama um construtor (10.6).





hnewExpressioni :: = new htypeNotVoidi ('.' hidentifieri)? hargumentsi

Seja e uma nova expressão da forma

novo T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) ou a forma novo T (a1, ..., an, xn + 1 : an + 1, ..., xn + k: an + k).

É um erro em tempo de compilação se T não for uma classe ou um tipo parametrizado acessível no escopo atual ou se T for um tipo parametrizado que não é uma classe. Por exemplo, new F <int> () é um erro se F for um alias de tipo que não indica uma classe.

Se T for um tipo parametrizado (19.10) S <U1, ..., Um>, seja R a classe genérica S e seja X1 estendido B1, ..., Xp estenda Bp seja o parâmetro formal do tipo S. Se T não é um tipo parametrizado, seja R T.

• Se e tiver a forma nova T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), será um erro em tempo de compilação se R. id não é o nome de um construtor declarado por R ou id não está acessível.

• Se e tiver a forma T novo (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), será um erro em tempo de compilação se R não for o nome de um construtor declarado por R.



Seja q o construtor mencionado acima, chamado R.id ou R.

É um erro em tempo de compilação se R for abstrato eq não for um construtor de fábrica. É um erro em tempo de compilação se R for uma classe não genérica e T for um tipo parametrizado. É um erro em tempo de compilação se R for uma classe genérica e T não for um tipo parametrizado. É um erro em tempo de compilação se R for uma classe genérica, T for um tipo parametrizado e m 6 = p. Ou seja, o número de argumentos do tipo está incorreto. É um erro em tempo de compilação se R for uma classe genérica, T for um tipo parametrizado e T não for limitado regularmente (14.2).

Se q for um construtor de fábrica de redirecionamento, será um erro em tempo de compilação se q em algum número de redirecionamentos de fábrica de redirecionamento redirecionar para si mesmo. É possível e permitido que uma fábrica de redirecionamento q0 entre em um loop infinito, por exemplo, porque q0 redireciona para um construtor de fábrica não redirecionador q00 cujo corpo usa q0 em uma expressão de criação de instância. Somente loops que consistem exclusivamente no redirecionamento de redirecionamentos de fábrica são detectados no momento da compilação.

Seja Si o tipo estático do parâmetro formal do construtor R.id (respectivamente R) correspondente ao argumento real ai, i ∈ 1..n + k. É um erro em tempo de compilação se o tipo estático de ai, i ∈ 1..n + k não for atribuível a [U1 / X1, ..., Um / Xm] Si. O caso não genérico é coberto com m = 0.

O tipo estático de e é T.

A avaliação de e procede da seguinte forma:

Primeiro, a parte do argumento

<U1, ..., Um> (a1, ..., an, xn + 1: an + 1, ..., xn + k:

é avaliado, produzindo a parte do argumento real avaliado

um + k)



<u1, ..., um> (o1, ..., on, xn + 1: on + 1, ..., xn + k:

em + k).



Observe que o caso não genérico é coberto por deixar m = 0. Se, para qualquer j ∈ 1..n + k, o tipo de tempo de execução de oj não for um subtipo de [u1 / X1, ..., um / Xm ] Sj, ocorre um erro de tipo dinâmico.

Caso hConstrutores adiados não carregados. Se T for um tipo adiado com o prefixo p, se p não tiver sido carregado com êxito, ocorrerá um erro dinâmico.

Case hGenerative constructorsi. Quando q é uma avaliação do construtor generativo (10.6.1) passa a alocar uma instância nova (10.6.1), i, da classe T. Em seguida, q é executado para inicializar i com relação às ligações que resultaram da avaliação do argumento list e, se R for uma classe genérica, com seus parâmetros de tipo vinculados a u1, ..., um.

Se a execução de q for concluída normalmente (17.0.1), e avalia como i. Caso contrário, a execução de q lança um objeto de exceção x e rastreia a pilha t, e a avaliação de e também lança o objeto de exceção xe rastreia a pilha t (16.1).

Case hRedirecionando construtores de fábricas. Quando q é um construtor de fábrica de redirecionamento (10.6.2) do formulário const? T (p1, ..., pn + k) = c; ou da forma const? T.id (p1, ..., pn + k) = c; onde const? indica que const pode estar presente ou ausente, a avaliação restante de e é equivalente a avaliar novo c (v1, ..., vn, xn + 1: vn + 1, ..., xn + k: vn + k) em um ambiente em que vj é uma variável nova vinculada a oj para j ∈ 1..n + k, e Xj é vinculada a uj para j ∈ 1..m.

Precisamos acessar as variáveis ​​de tipo porque c pode contê-las.

Case hNon-redirecionando fabricantes de fábrica. Quando q é um construtor de fábrica não redirecionador, o corpo de q é executado com relação às ligações que resultaram da avaliação da lista de argumentos e com t Parâmetros ype, se houver, de q ligados aos argumentos de tipo reais u1, ..., um. Se essa execução retornar um valor (17.0.1), e será avaliado como o valor retornado. Caso contrário, se a execução for concluída normalmente ou retornar sem valor, e será avaliado para o objeto nulo (16.4). Caso contrário, a execução lança uma exceção xe empilha o rastreio t, e a avaliação de e também lança x e t (16.1).

Um construtor de fábrica pode ser declarado em uma classe abstrata e usado com segurança, pois produzirá uma instância ou lançamento válido.

16.15.2 Const const

Uma expressão de objeto constante chama um construtor constante (10.6.3). hconstObjectExpressioni :: = const htypeNotVoidi ('.' hidentifieri)? hargumentsi

Seja e uma expressão constante do objeto na forma const T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) ou na forma const T (a1 , ..., an, xn + 1: an + 1, ..., xn + k: an + k).

É um erro em tempo de compilação se T não for uma classe ou um tipo parametrizado acessível no escopo atual ou se T for um tipo parametrizado que não é uma classe. É um erro em tempo de compilação se T for um tipo adiado (19.1). Em particular, T não deve ser uma variável de tipo.

É um erro em tempo de compilação se ai não for uma expressão constante para alguns i ∈ 1..n + k.

Se T for um tipo parametrizado (19.10) S <U1, ..., Um>, seja R a classe genérica S e seja X1 estendido B1, ..., Xp estenda Bp seja o parâmetro formal do tipo S. Se T não é um tipo parametrizado, seja R T.

Se T for um tipo parametrizado, será um erro em tempo de compilação se Uj não for uma expressão de tipo constante para qualquer j ∈ 1..m.

• Se e tiver a forma const T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), será um erro em tempo de compilação se R. id não é o nome de um construtor constante declarado por R ou id não está acessível.

• Se e tiver a forma const T (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), será um erro em tempo de compilação se R não for o nome de um construtor constante declarado por R.



Seja q o construtor constante mencionado acima, chamado R.id ou R.

É um erro em tempo de compilação se R for abstrato eq não for um construtor de fábrica. É um erro em tempo de compilação se R for uma classe não genérica e T for um tipo parametrizado. É um erro em tempo de compilação se R for uma classe genérica e T não for um tipo parametrizado. É um erro em tempo de compilação se R for uma classe genérica, T for um tipo parametrizado e m 6 = p. Ou seja, o número de argumentos do tipo está incorreto. É um erro em tempo de compilação se R for uma classe genérica, T for um tipo parametrizado e T não for limitado regularmente (14.2).

Seja Si o tipo estático do parâmetro formal do construtor R.id (respectivamente R) correspondente ao argumento real ai, i ∈ 1..n + k. É um erro em tempo de compilação se o tipo estático de ai, i ∈ 1..n + k não for atribuível a [U1 / X1, ..., Um / Xm] Si. O caso não genérico é coberto com m = 0.

O tipo estático de e é T.

A avaliação de e procede da seguinte forma:

Se e tiver a forma const T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k)

Seja o valor da expressão e0: new T.id (a1, ..., an, xn + 1: an + 1, ..., xn + k:

um + k). Seja o resultado de uma avaliação de e0, em algum momento de alguma execução do programa na biblioteca L onde e ocorre. O resultado de uma avaliação de e0 em L em algum outro momento e / ou em alguma outra execução produzirá um resultado o0, de modo que o0 seja substituído por o por canonização, conforme descrito abaixo. Isso significa que o valor está bem definido.

Se e tiver a forma const T (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), seja o valor do novo T (a1 ,. ..., an, xn + 1: an + 1, ..., xn + k: an + k). O que é bem definido pelo mesmo motivo.

• Se durante a execução do programa, uma expressão de objeto constante já foi avaliada para uma instância j da classe R com argumentos de tipo Ui, 1 ≤ i ≤ m, então:



- Para cada variável de instância f de i, seja vif o valor da variável de instância f em i, e seja vjf o valor da variável de instância f em j. Se idêntico (vif, vjf) para todas as variáveis ​​de instância f in i, o valor de e é j, caso contrário, o valor de e é i.

• Caso contrário, o valor de e é i.



Em outras palavras, objetos constantes são canonizados. Para determinar se um objeto é realmente novo, é preciso calculá-lo; então ele pode ser comparado a qualquer instância em cache. Se um objeto equivalente existir no cache, jogamos fora o objeto recém-criado e usamos o em cache. Os objetos são equivalentes se tiverem argumentos de tipo idênticos e variáveis ​​de instância idênticas. Como o construtor não pode induzir efeitos colaterais, a execução do construtor é inobservável. O construtor precisa ser executado apenas uma vez por site de chamada, em tempo de compilação.

É um erro em tempo de compilação se a avaliação de um objeto constante resultar em uma exceção não capturada sendo lançada.

Para ver como essas situações podem surgir, considere os seguintes exemplos:

classe A {

x final;

const A (p): x = p * 10;

}

classe IntPair {const IntPair (this.x, this.y); final int x; final int y;

operador * (v) => novo IntPair (x * v, y * v);

}

const a1 = const A (verdadeiro); // erro em tempo de compilação const a2 = const A (5); // legal

const a3 = const A (const IntPair (1,2)); // erro em tempo de compilação

Devido às regras que regem os construtores constantes, a avaliação do construtor A () com o argumento "x" ou o argumento const IntPair (1, 2) causaria uma exceção, resultando em um erro em tempo de compilação. Neste último caso, o erro é causado pelo fato de que o operador * só pode ser usado com alguns tipos "bem conhecidos", o que é necessário para evitar a execução de código arbitrário durante a avaliação de expressões constantes.

16.16 Gerando um isolado

A geração de um isolado é realizada por meio do que é sintaticamente uma chamada de biblioteca comum, invocando uma das funções spawnUri () ou spawn () definidas na biblioteca dart: isolate. No entanto, essas chamadas têm o efeito semântico de criar um novo isolado com sua própria memória e thread de controle.

A memória de um isolado é finita, assim como o espaço disponível para a pilha de chamadas de seu encadeamento. É possível que um isolado em execução esgote sua memória ou pilha, resultando em um erro dinâmico que não pode ser capturado efetivamente, o que forçará a suspensão do isolado.

Conforme discutido na seção 7, o manuseio de um isolado suspenso é de responsabilidade do incorporador.

spawningAnIsolate

functionInvocation





16.17 Chamada de função


A invocação de função ocorre nos seguintes casos: quando uma expressão de função (16.13) é invocada (16.17.5), quando um método (16.21), getter (16.20, 16.22) ou setter (16.23) é invocado ou quando um construtor é invocado (por meio da criação da instância (16.15), redirecionamento do construtor (10.6.1) ou superinicialização). Os vários tipos de invocação de função diferem quanto à forma como a função a ser invocada, f, é determinada, bem como se esta (16.14) está vinculada. Depois que f é determinado, os parâmetros de tipo formal de f são vinculados aos argumentos do tipo real correspondentes e os parâmetros formais de f são vinculados aos argumentos reais correspondentes. Quando o corpo de f é executado, ele será executado com as ligações mencionadas acima.

Executar um corpo do formulário => e é equivalente a executar um corpo do formulário {return e; } Executar um corpo no formato assíncrono => e é equivalente a executar um corpo no formato assíncrono {return e; }

Se f é síncrono e não é um gerador (9), a execução do corpo de f começa imediatamente. Se a execução do corpo de f retornar um valor, v, (17.0.1), a chamada será avaliada como v. Se a execução for concluída normalmente ou ela retornar sem um valor, a chamada será avaliada para o objeto nulo (16.4). Se a execução lança um objeto de exceção e o rastreamento da pilha, a chamada lança o mesmo objeto de exceção e o rastreamento da pilha (16.1).

Um corpo completo da função nunca pode interromper ou continuar (17.0.1) porque uma instrução de interrupção ou continuação sempre deve ocorrer dentro da instrução que é o destino da interrupção ou continua. Isso significa que um corpo de função só pode ser concluído normalmente, jogar ou retornar. Concluir normalmente ou retornar sem um valor é tratado da mesma forma que retornar o objeto nulo (16.4), portanto, o resultado da execução de um corpo da função sempre pode ser usado como resultado da avaliação de uma expressão, avaliando para um objeto ou pelo método avaliação jogando.

Se f estiver marcado como sincronizado * (9), uma instância nova (10.6.1) i implementando Iterable U será retornada imediatamente, onde U é determinado da seguinte forma: Seja T o tipo de retorno real de f (19.10.1) . Se T é Iterável S para algum tipo S, então U é S, caso contrário U é Objeto.

Uma implementação do Dart precisará fornecer uma implementação específica do Iterable que será retornada pelos métodos sync *. Uma estratégia típica seria produzir uma instância de uma subclasse da classe IterableBase definida em dart: core. O único método que precisa ser adicionado pela implementação do Dart nesse caso é o iterador.

A implementação iterável deve estar em conformidade com o contrato da Iterable e não deve executar nenhuma etapa identificada como excepcionalmente eficiente nesse contrato.

O contrato menciona explicitamente várias situações em que certas iteráveis ​​podem ser mais eficientes que o normal. Por exemplo, pré-computando seu comprimento. Os iteráveis ​​normais devem iterar sobre seus elementos para determinar seu comprimento. Isso certamente é verdade no caso de um gerador síncrono, em que cada elemento é calculado por uma função. Não seria aceitável pré-calcular os resultados do gerador e armazená-los em cache, por exemplo.

Quando a iteração sobre o iterável é iniciada, obtendo um iterador j do iterável e chamando moveNext (), a execução do corpo de f será iniciada. Quando a execução do corpo de f for concluída (17.0.1),

• Se retornar sem um valor ou for concluído normalmente (17.0.1), j será posicionado após o último elemento, de modo que seu valor atual seja o objeto nulo (16.4) e a chamada atual para moveNext () em j retorne false, assim como todas as outras chamadas.

• Se ele lança um objeto de exceção ee o rastreamento de pilha t, o valor atual de j é o objeto nulo (16.4) e o A chamada atual para moveNext () lança e e também. Outras chamadas para moveNext () devem retornar false.



Cada iterador inicia um cálculo separado. Se a função sync * for impura, a sequência de valores gerada por cada iterador pode ser diferente.

Pode-se derivar mais de um iterador de um dado iterável. Observe que as operações no próprio iterável podem criar iteradores distintos. Um exemplo seria comprimento. É concebível que diferentes iteradores possam produzir sequências de diferentes comprimentos. O mesmo cuidado deve ser tomado ao escrever funções sync * como ao escrever uma classe Iterator. Em particular, ele deve lidar com vários iteradores simultâneos normalmente. Se o iterador depender de um estado externo que pode mudar, verifique se o estado ainda é válido após cada rendimento (e talvez gere um

ConcurrentModificationError, se não estiver).

Cada iterador é executado com suas próprias cópias rasas de todas as variáveis ​​locais; em particular, cada iterador tem os mesmos argumentos iniciais, mesmo que suas ligações sejam modificadas pela função Duas execuções de um iterador interagem apenas via estado fora da função.

Se f estiver marcado como assíncrono (9), uma instância nova (10.6.1) o será associada à chamada, onde o tipo dinâmico de o implementa Future <flatten (T)> e T é o tipo de retorno real de f ( 19.10.1). Em seguida, o corpo de f é executado até que seja suspenso ou concluído, momento em que o é retornado. O corpo de f pode suspender durante a avaliação de uma expressão de espera ou execução de um loop for assíncrono. O futuro o é concluído quando a execução do corpo de f é concluída (17.0.1). Se a execução do corpo retornar um valor, o for concluído com esse valor, se for concluído normalmente ou retornar sem um valor, o for concluído com o objeto nulo (16.4) e se ele lançar uma exceção ee o rastreamento de pilha t, o é concluído com o erro ee o rastreamento de pilha t. Se a execução do corpo for lançada antes que o corpo seja suspenso pela primeira vez, a conclusão de o ocorrerá em algum momento futuro após o retorno da invocação. O chamador precisa de tempo para configurar o tratamento de erros para o futuro retornado, para que o futuro não seja concluído com um erro antes de ser devolvido.

Se f estiver marcado como assíncrono * (9), uma nova instância (10.6.1) s implementando o Stream <U> será imediatamente retornada, onde U é determinado da seguinte forma: Seja T o tipo de retorno real de f (19.10.1) . Se T for Fluxo <S> para algum tipo S, então U é S, caso contrário U é Objeto. Quando s é ouvido, a execução do corpo de f começará. Quando a execução do corpo de f é concluída:

• Se for concluído normalmente ou retornar sem valor (17.0.1), se s tiver sido cancelado, seu futuro cancelamento será concluído com o objeto nulo (16.4).

• Se ele lança um objeto de exceção ee o rastreamento de pilha t:



- Se s foi cancelado, seu futuro cancelamento será concluído com o erro ee o rastreamento de pilha t.

- caso contrário, o erro e e o rastreamento de pilha t são emitidos por s.



• s está fechado.



O corpo de uma função de gerador assíncrono não pode interromper, continuar ou retornar um valor (17.0.1). Os dois primeiros são permitidos apenas em contextos que manipularão a interrupção ou continuarão, e as instruções de retorno com uma expressão não serão permitidas nas funções do gerador.

Quando o fluxo de um gerador assíncrono for cancelado, a limpeza ocorrerá nas cláusulas finalmente (17.11) dentro do gerador. Optamos por direcionar quaisquer exceções que ocorram nesse momento para o futuro do cancelamento, em vez de perdê-las.

16.17.1 Listas de argumentos reais actualArgumentLists

As listas de argumentos reais têm a seguinte sintaxe:

hargumentsi :: = '(' (hargumentListi ','?)? ')'

hargumentListi :: = hnamedArgumenti (',' hnamedArgumenti) * | hexpressionListi (',' hnamedArgumenti) * hnamedArgumenti :: = hlabeli hexpressioni

As listas de argumentos permitem uma vírgula à direita opcional após o último argumento (','?). Uma lista de argumentos com essa vírgula à direita é equivalente em todos os aspectos à mesma lista de parâmetros sem a vírgula à direita. Todas as listas de argumentos nesta especificação são mostradas sem uma vírgula à direita, mas as regras e a semântica se aplicam igualmente à lista de argumentos correspondente com uma vírgula à direita.

Seja L uma lista de argumentos da forma (e1 ..., em, ym + 1: em + 1 ..., ym + p:

em + p) e assuma que o tipo estático de ei é Si, i ∈ 1..m + p. O tipo de lista de argumentos estáticos de L é então (S1 ..., Sm, Sm + 1 ym + 1 ..., Sm + p ym + p). Seja Ss o tipo de lista de argumentos estáticos

(S1 ..., Sm, Sm + 1 ym + 1 ..., Sm + p ym + p) e deixe Ps ser a lista formal de parâmetros

(T1 x1 ..., Tn xn, [Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk]) onde cada parâmetro pode ser marcado como covariável (não mostrado, mas permitido).





Dizemos que Ss é uma correspondência de subtipo para Ps se p = 0, n ≤ m ≤ n + k, e Si





é um subtipo de Ti para todos os i ∈ 1..m. Dizemos que Ss é uma correspondência atribuível para Ps se p = 0, n ≤ m ≤ n + k, e Si é atribuível a Ti para todos os i ∈ 1..m. Seja Ss o tipo de lista de argumentos estáticos

(S1 ..., Sm, Sm + 1 ym + 1 ..., Sm + p ym + p) e seja Ps o parâmetro formal Lista

(T1 x1 ..., Tn xn, {Tn + 1 xn + 1 = d1, ..., Tn + k xn + k = dk}) em que cada parâmetro pode ser marcado como covariável (não mostrado, mas permitido).





Dizemos que Ss é uma correspondência de subtipo para Ps iff m = n, {ym + 1 ..., ym + p} ⊆ {xn + 1 ..., xn + k}, Si é um subtipo de Ti para todos os i .. 1..m, e Si é um subtipo de Tj sempre que yi = xj e j ∈ n + 1..n + k, para todos os i ∈ m + 1..m + p. Dizemos que Ss é





uma correspondência atribuível para Ps se m = n, {ym + 1 ..., ym + p} ⊆ {xn + 1 ..., xn + k}, Si é atribuível a Ti para todos os i ∈ 1..m, e Si é atribuível a Tj sempre que yi = xj e j ∈ n + 1..n + k, para todos os i m + 1..m + p.

Em resumo, uma lista de argumentos real corresponde a uma lista formal de parâmetros sempre que a primeira puder ser passada com segurança para a segunda.



actualArguments



16.17.2 Avaliação real da lista de argumentos

A invocação de função envolve a avaliação da lista de argumentos reais para a função e a ligação dos resultados aos parâmetros formais da função.

Ao analisar uma lista de argumentos, uma ambiguidade pode surgir porque o mesmo código fonte pode ser uma chamada de função genérica e pode ser duas ou mais expressões relacionais e / ou expressões de deslocamento. Nessa situação, a expressão é sempre analisada como uma chamada de função genérica.

Um exemplo é f (a <B, C> (d)), que pode ser uma invocação de f passando dois argumentos reais do tipo bool ou uma invocação de f passando o resultado retornado por uma invocação da função genérica a. Observe que a ambiguidade pode ser eliminada omitindo os parênteses em torno da expressão d ou adicionando parênteses em torno de uma das expressões relacionais.

Quando a intenção é passar várias expressões relacionais ou de mudança como argumentos reais e houver uma ambiguidade, o código-fonte pode ser facilmente ajustado para uma forma não ambígua. Além disso, esperamos que seja mais comum ter invocações de funções genéricas como argumentos reais do que ter expressões relacionais ou de mudança que coincidam e tenham parênteses no final, de modo que a ambiguidade surja.

Avaliação de uma parte real do argumento do formulário

<A1, ..., Ar> (a1, ..., am, q1: am + 1, ..., ql: am + l) procede da seguinte maneira:

Os argumentos de tipo A1, ..., Ar são avaliados na ordem em que aparecem no programa, produzindo os tipos t1, ..., tr. Os argumentos a1, ..., am + l são avaliados na ordem em que aparecem no programa, produzindo objetos o1, ..., om + l.

Em termos simples, uma parte do argumento que consiste em argumentos do tipo s, m argumentos posicionais e l nomeados argumentos é avaliada da esquerda para a direita. Observe que a lista de argumentos de tipo é omitida quando r = 0 (14).

16.17.3 Vinculando dados reais a formais bindingActualsToFormals

A seguir, o caso não genérico é abordado implicitamente: Quando o número de argumentos do tipo real é zero, a lista de argumentos do tipo inteiro <...> é omitida e da mesma forma para as listas de parâmetros do tipo vazio (14).

Considere uma invocação i de uma função f com uma parte real do argumento da forma <A1, ..., Ar> (a1, ..., am, q1: am + 1, ..., ql: am + l) .

Observe que f denota uma função no sentido semântico, em vez de uma construção sintática. Uma referência a esta seção é usada em outras seções quando a análise estática de uma chamada é especificada e o tipo estático de f foi determinado. A função em si pode ter sido obtida de uma declaração de função, de uma instância vinculada a esta e de uma declaração de método de instância ou como um objeto de função obtido pela avaliação de uma expressão. Por isso, não podemos indicar aqui qual construto sintático corresponde a f. Uma referência a esta seção também é usada em outras seções quando argumentos reais devem ser vinculados aos parâmetros formais correspondentes, e f está prestes a ser chamado, para especificar a semântica dinâmica.

Não chamamos f de 'objeto de função' aqui, porque não queremos sugerir que toda chamada de função deve envolver uma avaliação separada de uma expressão que produz um objeto de função, seguida por uma invocação desse objeto de função. Por exemplo, uma implementação deve ter permissão para compilar a chamada de uma função de nível superior como uma série de etapas pelas quais um quadro de pilha é criado, seguido por um salto de baixo nível no código gerado para o corpo. Portanto, nesta seção, a palavra 'função' é de nível mais baixo que 'objeto de função', mas 'função' ainda denota uma entidade semântica associada a uma declaração de função, mesmo que não exista uma entidade correspondente no pilha em tempo de execução.

É um erro em tempo de compilação se qj = qk para qualquer j 6 = k.

Se o tipo estático de f for dinâmico ou a classe interna Function, nenhuma outra

verificações estáticas são realizadas e o tipo estático de i é dinâmico; caso contrário, será um erro em tempo de compilação se o tipo estático de f não for um tipo de função.

Caso contrário, o tipo estático de f é um tipo de função F. Seja S0 o tipo de retorno de F, seja X1 estendido B1, ..., Xs estenda Bs sejam os parâmetros de tipo formal, seja h o número de parâmetros necessários, seja p1, ..., pn são os parâmetros posicionais e deixe ph + 1, ..., ph + k ser a opção Todos os parâmetros de F. Seja Si o tipo estático dos parâmetros formais pi, i ∈ 1..h + k, e para cada q seja Sq o tipo do parâmetro denominado q, onde cada tipo de parâmetro será obtido substituindo Xj por Aj, j ∈ 1..s, na anotação de tipo de parâmetro fornecida. Finalmente, deixe Ti ser o tipo estático de ai.

Temos uma lista de argumentos real que consiste em argumentos do tipo r, m argumentos posicionais e eu nomeado argumentos. Temos uma função com parâmetros do tipo s, h parâmetros obrigatórios e k parâmetros opcionais. A Figura 1 mostra como essa situação surge.

Argumentos reais:

argumentos do tipo hr argumentos posicionais, l nomeado argumentos

Declaração com parâmetros nomeados: n = h

 h parâmetros obrigatórios, k parâmetros opcionais  hs type parametersi que também podem ser visualizados como 

n parâmetros posicionais, k parâmetros nomeados

Declaração com parâmetros posicionais opcionais: n = h + k

 h parâmetros requeridos, k parâmetros opcionais 

parâmetros do tipo hs, que também podem ser vistos como

n parâmetros posicionais

Figura 1: Possíveis partes reais do argumento e partes formais de parâmetros

É um erro em tempo de compilação se r 6 = s. É um erro em tempo de compilação se r = se, para alguns j ∈ 1..s, Aj 6 <: [A1 / X1, ..., Ar / Xs] Bj. É um erro em tempo de compilação, a menos que h ≤ m ≤ n. Se l> 0, é um erro em tempo de compilação, a menos que F tenha nomeado parâmetros e qj ph {ph + 1, ..., ph + k}, j ∈ 1..l.

Ou seja, o número de argumentos de tipo deve corresponder ao número de parâmetros de tipo e os limites devem ser respeitados. Devemos receber pelo menos o número necessário de argumentos posicionais, e não mais que o número total de parâmetros posicionais. Para cada argumento nomeado, deve haver um parâmetro nomeado com o mesmo nome.

O tipo estático de i é [A1 / X1, ..., Ar / Xs] S0.

É um erro em tempo de compilação se Tj não puder ser atribuído a Sj, j ∈ 1..m. É um erro em tempo de compilação se Tm + j não puder ser atribuído a Sqj, j ∈ 1..l.

Considere o caso em que a chamada de função em foco aqui é uma chamada de método de instância. Nesse caso, para cada argumento real, o parâmetro correspondente pode ser covariante. No entanto, os requisitos de atribuibilidade acima se aplicam igualmente quando o parâmetro é covariante e quando não é.

A covariância de parâmetros em uma invocação de método de instância pode ser introduzida por um subtipo do tipo de receptor estaticamente conhecido, o que significa que qualquer tentativa de sinalizar um dado argumento real como perigoso devido à verificação de tipo dinâmico a que ele estará sujeito ficará incompleta: alguns argumentos reais podem ser submetidos a uma verificação dinâmica desse tipo, mesmo que isso não seja conhecido estaticamente no site da chamada. Isso não é surpreendente para um mecanismo como covariância de parâmetros, projetado com o objetivo de permitir que os desenvolvedores solicitem explicitamente que esse tipo específico de segurança em tempo de compilação seja violado. O ponto é que esse mecanismo adia a imposição do invariante subjacente ao tempo de execução e, em troca, permite alguns projetos de programas úteis que, de outra forma, seriam rejeitados em tempo de compilação.

Para a semântica dinâmica, seja f uma função com parâmetros do tipo s e h parâmetros necessários; sejam p1, ..., pn os parâmetros posicionais de f; e sejam ph + 1, ..., ph + k os parâmetros opcionais declarados por f.

Uma parte do argumento real avaliado

<t1, ..., tr> (o1, ..., om, q1: om + 1, ..., ql: om + l) derivado de uma parte real do argumento do formulário

<A1, ..., Ar> (a1, ..., am, q1: am + 1, ..., ql: am + l) está vinculado aos parâmetros do tipo formal e aos parâmetros formais de f da seguinte maneira:

Se r = 0 e s> 0, substitua a lista de argumentos de tipo real: seja r s e ti = dinâmico para i ∈ 1..s. Então, se r 6 = s, um NoSuchMethodError é lançado. Se l> 0 en 6 = h, um NoSuchMethodError é lançado. Se m <h ou m> n, um NoSuchMethodError é lançado. Além disso, cada qi, i ∈ 1..l, deve ter um parâmetro nomeado correspondente no conjunto {ph + 1, ..., ph + k} ou um NoSuchMethodError é acionado. Então pi é vinculado a oi, i ∈ 1..m, e qj é vinculado a om + j, j ∈ 1..l. Todos os parâmetros formais restantes de f estão vinculados aos seus valores padrão.

Todos esses parâmetros restantes são necessariamente opcionais e, portanto, têm valores padrão.

É um erro de tipo dinâmico se ti não for um subtipo do limite real (19.10.1) do i-ésimo argumento do tipo f, para argumentos do tipo real t1, ..., tr. É um erro de tipo dinâmico se oi não for o objeto nulo (16.4) e o tipo real (19.10.1) de pi não for um supertipo do tipo dinâmico de oi, i ∈ 1..m. É um erro de tipo dinâmico se om + j não for o objeto nulo e o tipo real (19.10.1) de qj não for um supertipo do tipo dinâmico de om + j, j ∈ 1..l.

16.17.4 Invocação não qualificada unqualifiedInvocation

Uma invocação de função não qualificada i tem o ID do formulário <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), em que id é um identificador.

Observe que a lista de argumentos de tipo é omitida quando r = 0 (14).

É um erro em tempo de compilação se ocorrer dentro de uma função estática ou de nível superior (seja

função, método, getter ou setter) ou um inicializador de variável estática ou de nível superior, e não há uma definição lexicamente visível identificação nomeada no escopo.

Se existir uma declaração lexicamente visível denominada id, deixe Did seja a declaração mais interna. Então:

• Considere a situação em que Did é uma declaração de tipo. Se Did é uma declaração de uma classe C que possui um construtor chamado C, o significado de i depende do contexto: se ocorrer em um contexto constante (16.3.1), i será equivalente a const i; se i não ocorrer em um contexto constante, i será equivalente ao novo i. Caso contrário, ocorrerá um erro em tempo de compilação (ou seja, se Did não declara uma classe ou declara uma classe que não possui construtor chamado C).

• Caso contrário, se Did for uma diretiva de importação em que o ID seja declarado como um prefixo da biblioteca, ocorrerá um erro em tempo de compilação.

• Caso contrário, se Did declara uma função local, uma função de biblioteca ou uma biblioteca ou getter estático ou uma variável, i é tratado como uma invocação de expressão de função (16.17.5).

• Caso contrário, se Did é um método estático da classe C envolvente, i é equivalente a C.id <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, .. ., xn + k: um + k).

• Caso contrário, se eu ocorrer em um corpo de método de instância, i será equivalente à invocação do método comum this.id <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1 ,. .., xn + k: um + k).



Caso contrário, o id não está no escopo e eu devo ocorrer dentro de uma função de nível superior ou estática (seja função, método, getter ou setter) ou de um inicializador de variável de nível superior ou estático; nesse caso, ocorre um erro em tempo de compilação , conforme especificado anteriormente nesta seção.

16.17.5 Invocação de expressão de função functionExpressionInvocation

Uma chamada de expressão de função i tem o formato ef <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k), onde ef é uma expressão.

Observe que a lista de argumentos de tipo é omitida quando r = 0 (14).

Considere a situação em que ef denota uma classe C que contém uma declaração de um construtor chamado C ou é do formato e0f.id onde e0f indica uma classe C que contém uma declaração de um construtor chamado C.id. Se i ocorre em um contexto constante (16.3.1), então eu é tratado como const i, e se eu não ocorre em um contexto constante, então é tratado como novo i.

Quando i é tratado como outra construção i0, a análise estática e a semântica dinâmica são especificadas na seção sobre i0 (5).

Caso contrário, será um erro em tempo de compilação se ef for um tipo literal.

Este erro já foi especificado em outra parte (16.17.4) para o caso em que ef é um identificador, mas ef também pode ter outras formas, por exemplo, p.C.

Caso contrário, se ef for um ID de identificador, ele deverá necessariamente indicar um local

function, uma função de biblioteca, uma biblioteca ou getter estático ou uma variável conforme descrito acima, ou eu não teria sido tratado como uma invocação de expressão de função.

Se ef é uma expressão de extração de propriedade (16.22), então eu trato como uma invocação de método comum (16.21.1).

a.b (x) é tratado como uma invocação de método do método b () no objeto a, não como uma invocação do getter b em a seguida por uma chamada de função (a.b) (x). Se um método ou getter existir, os dois serão equivalentes. No entanto, se b não for definido em a, a chamada resultante de noSuchMethod () seria diferente. A Invocação passada para noSuchMethod () descreveria uma chamada para um método b com argumento x no primeiro caso, e uma chamada para um getter b (sem argumentos) no último.

Seja F o tipo estático de ef. A análise estática de i é realizada conforme especificado na Seção 16.17.3, usando F como o tipo estático da função invocada, e o tipo estático de i é como especificado lá.

A avaliação de uma chamada de expressão de função ef <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) prossegue para avaliar ef, produzindo um objeto o. Seja f uma nova variável vinculada a o. Se o é um objeto de função, a chamada de função f <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) é avaliado vinculando dados reais a formais, conforme especificado na Seção 16.17.3, e executando o corpo de f com essas ligações; o resultado retornado é o resultado da avaliação i.

Caso contrário, o não é um objeto de função. Se o tiver um método chamado call, a seguinte chamada de método comum será avaliada e seu resultado será o resultado da avaliação de i:

f.call <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Caso contrário, o não possui um método chamado call. Uma nova instância im da classe predefinida Invocation é criada, de modo que:

• im.isMethod é avaliado como verdadeiro.

• im.memberName é avaliado com o símbolo #call.

• im.positionalArguments é avaliada como uma lista não modificável com os valores resultantes da avaliação de <Object> [a1, ..., an].

• im.namedArguments é avaliado como um mapa não modificável com as chaves e valores resultantes da avaliação de



<Símbolo, Objeto> {# xn + 1: an + 1, ..., # xn + k: an + k}.

• im.typeArguments é avaliada como uma lista não modificável com os valores resultantes da avaliação de <Type> [A1, ..., Ar].



Em seguida, a chamada do método f.noSuchMethod (im) é avaliada e seu resultado é o resultado da avaliação i.

A situação em que noSuchMethod é chamado só pode surgir quando o tipo estático e de ef é dinâmico. A semântica de tempo de execução garante que uma chamada de função possa equivaler a uma chamada da chamada do método da instância. No entanto, um tipo de interface com um método chamado call não é um subtipo de nenhum tipo de função (19.4.2).

16.18 Fechamento de funções

Seja f uma expressão que denota uma declaração de uma função local, um método estático ou uma função de nível superior (16.37) ou seja f uma função literal (16.13).

functionClosurization



A avaliação de f produz um objeto de função que é o resultado de um fechamento de função aplicado à declaração denotada por f respectivamente para a função





literal f considerado como uma declaração de função. Closurization indica encerramento de método de instância (16.22.3), bem como fechamento de função, e também é usado como uma abreviação para qualquer um deles quando não há ambiguidade.

O fechamento da função aplicado a uma declaração de função f equivale à criação de um objeto de função o, que é uma instância de uma classe C cuja interface é um subtipo do tipo real F (19.10.1) correspondente à assinatura na declaração de função f, usando as ligações atuais das variáveis ​​de tipo, se houver. Não existe um tipo de função F0 que seja um subtipo adequado de F, de modo que C seja um subtipo de F0. Se f denota um método estático ou uma função de nível superior, a classe C não substitui o operador '==' herdado da classe Object.

Em outras palavras, C tem a liberdade de ser um subtipo apropriado do tipo de função que podemos ler da declaração de f, pois pode precisar ser uma classe definida específica da plataforma interna, mas C não tem a liberdade de ser um subtipo de um tipo de função diferente e mais especial e não pode ser nulo.

Uma invocação de o com uma determinada lista de argumentos vinculará valores reais a formais da mesma maneira que uma invocação de f (16.17.3) e, em seguida, executará o corpo de f no escopo capturado alterado com o escopo do parâmetro vinculado, produzindo o mesmo conclusão (17.0.1), pois a invocação de f teria rendido.



genericFunctionInstantiation



16.18.1 Instanciação de função genérica

A instanciação de função genérica é um mecanismo que gera um objeto de função não genérico, com base em uma referência a uma função genérica.

É um mecanismo muito semelhante ao encerramento de funções (16.18), mas ocorre apenas em situações em que um erro em tempo de compilação ocorreria.

A essência da instanciação de função genérica é permitir invocações "com curry", no sentido de que uma função genérica pode receber seus argumentos de tipo reais separadamente durante o fechamento (ela deve receber todos os argumentos de tipo, não apenas alguns deles), e isso gera um objeto de função não genérico. Os argumentos de tipo são transmitidos implicitamente, com base na inferência de tipo; uma versão futura do Dart pode permitir a sua passagem explícita. Aqui está um exemplo: X fg <X estende num> (X x) => x;

classe A {

estático X fs <X estende num> (X x) => x;

}

void main () {

X fl <X estende num> (X x) => x;

Lista <int Function (int)> funções = [fg, A.fs, fl]; }

Cada objeto de função armazenado em funções possui o tipo dinâmico int Function (int) e é obtido implicitamente "passando o argumento do tipo real int" para a função genérica correspondente.

Deixe f do formulário hidentifieri ('.' Hidentifieri ('.' Hidentifieri)?)? seja uma expressão que denote uma declaração de uma função local, um método estático ou uma função de nível superior e permita que G seja o tipo estático de f. Considere a situação em que G é um tipo de função no formato T0 Função <X1 / B1, ..., Xs / Bs> (parâmetros) com s> 0 (ou seja, G é um tipo de função genérico) e o tipo de contexto é uma função não genérica do tipo F. Nessa situação, ocorre um erro em tempo de compilação (8, 9, 10.6.1, 10.6.1, 10.6.1, 16.15.1, 16.15.2, 16.15.2, 16.17.3, 16.23, 17.3 , 17.9, 17.12, 17.16.2), exceto quando a etapa a seguir tiver êxito:

Instanciação de tipo de função genérica: a inferência de tipo é aplicada a G com o tipo de contexto F e é bem-sucedida, produzindo a lista de argumentos de tipo real T1, ..., Ts.

A instanciação do tipo de função genérica falha no caso em que a inferência de tipo falha; nesse caso, ocorre o erro em tempo de compilação mencionado acima. Será especificado em uma versão futura deste documento como a inferência de tipo calcula T1, ..., Ts (6).

Caso contrário, a instanciação do tipo de função genérica foi bem-sucedida. Seja F0 o tipo [T1 / X1, ..., Ts / Xs] (Função T0 (parâmetros)). Observe que é garantido que F0 é atribuível a F ou a inferência teria falhado.

Caso h Funções de nível superior e métodos estáticosi. Considere a situação em que f denota uma função de nível superior ou um método estático. Nessa situação, o programa é modificado de forma que f é substituído por uma referência f0 para uma função não genérica induzida implicitamente cuja assinatura é F0, cujo tipo dinâmico é [t1 / T1, ..., ts / Ts] F0 e cuja semântica para cada chamada é a mesma que chamar f com t1, ..., ts como a lista de argumentos de tipo real, onde t1, ..., ts é o valor real de T1, ..., Ts no ponto durexecução onde f0 foi avaliado. Aqui está um exemplo:

Lista <T> foo <T> (T t) => [t];

Lista <int> fooOfInt (int i) => [i]; Barra de strings (Lista <int> f (int)) => "$ f (42)";

void main () {

print (barra (foo));

}

Neste exemplo, foo como um argumento real para bar será modificado como se a chamada tivesse sido bar (fooOfInt), exceto pela igualdade, especificada a seguir.

Considere a situação em que o programa antes da instanciação da função genérica contém duas ocorrências de f no mesmo escopo ou escopos diferentes, mas denota a mesma função, respectivamente, a situação em que uma execução do programa que contém f a avalia duas vezes. Deixe o1 e o2 denotarem os objetos de função obtidos pela avaliação dessas duas expressões, respectivamente as duas avaliações dessa expressão.

No caso em que os valores reais dos argumentos de tipo são os mesmos para ambas as avaliações, é garantido que o1 e o2 sejam iguais de acordo com o operador '=='. No entanto, não é especificado se idêntico (o1, o2) é avaliado como verdadeiro ou falso.

Nenhuma noção de igualdade é apropriada quando argumentos de tipo diferentes são fornecidos, mesmo que os objetos de função resultantes tenham exatamente o mesmo tipo em tempo de execução, porque a execução de dois objetos de função que diferem dessa maneira pode ter efeitos colaterais diferentes e retornar resultados diferentes quando executados a partir exatamente do mesmo estado. Por exemplo, poderia haver um parâmetro de tipo X que não ocorre na assinatura da função e a função poderia criar e retornar uma Lista <X>.

Case hLocal Functionsi. Considere a situação em que f é um identificador que denota uma função local. Para uma função local, apenas um identificador pode denotá-la. Nessa situação, o programa é modificado de forma que f é substituído por uma referência f0 para uma função não genérica induzida implicitamente cuja assinatura é F0, cujo tipo dinâmico é [t1 / T1, ..., ts / Ts] F0 e cuja semântica para cada chamada é igual a chamar f com t1, ..., ts como a lista de argumentos de tipo real, onde t1, ..., ts é o valor real de T1, ..., Ts no ponto durante execução onde f0 foi avaliado.

Nenhuma garantia é fornecida em relação à igualdade de funções não genéricas obtidas de uma função local por instanciação de função genérica.

Essa função local poderia ter recebido exatamente os mesmos argumentos de tipo real nos dois casos, e ainda assim seu corpo poderia conter referências a declarações de tipos, variáveis ​​e outras entidades nos escopos anexos. Essas referências podem indicar entidades diferentes quando os dois objetos de função foram criados. Nessa situação, não é razoável considerar os dois objetos de função como a mesma função.

16.19 Pesquisa

olho para cima



Uma pesquisa é um procedimento que seleciona uma declaração de membro de instância concreta com base na passagem de uma sequência de classes, começando com uma determinada classe C e prosseguindo com a superclasse da classe atual em cada etapa. Uma pesquisa pode fazer parte da análise estática e pode ser executada em tempo de execução. Pode ter sucesso ou falhar.





Definimos vários tipos de pesquisa com uma estrutura muito semelhante. Nós explicamos cada um deles, apesar da redundância, para evitar a introdução de mecanismos de abstração de meta-nível apenas para esse fim. O ponto é que devemos indicar para cada pesquisa que tipo de membro ele procura, porque, por exemplo, uma 'pesquisa de método' e uma 'pesquisa de busca' são usadas em diferentes situações.

Seja m um identificador, um objeto, L uma biblioteca e C uma classe que seja a classe de ou uma superclasse dela.

O resultado de uma pesquisa de método para m in o em relação a L começando na classe C é o resultado de uma pesquisa de método para m em C em relação a L. O resultado de uma pesquisa de método para m em C em relação a L é: Se C declarar um método de instância concreto chamado m que é acessível a L, essa declaração é o resultado da pesquisa do método, e dizemos que o método foi consultado em C. Caso contrário, se C tiver uma superclasse S, o resultado da pesquisa de método é o resultado de uma pesquisa de método para m em S em relação a L. Caso contrário, dizemos que a pesquisa de método falhou.

O resultado de uma pesquisa getter para m in o em relação a L começando na classe C é o resultado de uma pesquisa getter para m em C em relação a L. O resultado de uma pesquisa getter para m em C em relação a L é: Se C declarar um getter de instância concreto chamado m que é acessível a L, essa declaração de getter é o resultado da pesquisa do getter, e dizemos que o getter foi consultado em C. Caso contrário, se C tiver uma superclasse S, o resultado da pesquisa getter é o resultado de uma pesquisa getter para m em S em relação a L. Caso contrário, dizemos que a pesquisa getter falhou.

O resultado de uma pesquisa de incubadora para m em o em relação a L começando na classe C é o resultado de uma pesquisa de incubadora para m em C em relação a L. O resultado de uma pesquisa de incubadora para m em C em relação a L é: Se C declarar um configurador de instância concreto chamado m que é acessível a L, então esse A declaração tter é o resultado da pesquisa do levantador e dizemos que o pesquisador foi procurado em C. Caso contrário, se C tiver uma superclasse S, o resultado da pesquisa do levantador é o resultado de uma pesquisa do levantador em m em relação a S para L. Caso contrário, dizemos que a pesquisa do setter falhou.

Seja m um identificador, um objeto e L uma biblioteca. O resultado de uma pesquisa de método para m in o em relação a L é o resultado de uma pesquisa de método para m in o em relação a L começando com a classe de o. O resultado de uma pesquisa getter para m in o em relação a L é o resultado de uma pesquisa getter para m in o em relação a L começando com a classe de o. O resultado de uma pesquisa do setter para m in o em relação a L é o resultado de uma pesquisa do setter para m in o em relação a L começando com a classe de o.

Observe que, para a pesquisa de getter (setter), o resultado pode ser um getter (setter) que foi induzido por uma declaração de variável de instância.

Observe que, às vezes, usamos frases como "método de pesquisa m" para indicar que uma pesquisa de método é realizada e da mesma forma para pesquisas de levantadores e de levantadores.

A motivação para ignorar membros abstratos durante a pesquisa é, em grande parte, permitir uma composição de mixina mais suave.





16.20 Invocação de Getter de nível superior topLevelGetterInvocation


A avaliação de uma chamada de getter de nível superior i do formato m, em que m é um identificador, procede da seguinte forma:

A função getter m é chamada. O valor de i é o resultado retornado pela chamada para a função getter. Observe que a chamada é sempre definida. De acordo com as regras para referências de identificador, um identificador não será tratado como uma chamada de getter de nível superior, a menos que o getter i esteja definido.

O tipo estático de i é o tipo de retorno declarado de m.

16.21 Invocação do método

A invocação de método pode assumir várias formas, conforme especificado abaixo.

methodInvocation



16.21.1 Invocação comum

Uma chamada de método comum pode ser condicional ou incondicional.

commonInvocation



Caso ele? .M <···> (···) i. Considere uma invocação condicional de método ordinário i da forma e? .M <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k:

um + k).

Observe que invocações não genéricas surgem como o caso especial em que o número de argumentos de tipo é zero; nesse caso, a lista de argumentos de tipo é omitida e da mesma forma para listas formais de parâmetros de tipo (14).

O tipo estático de i é o mesmo que o tipo estático de

e.m <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por

e.m <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k)

também são gerados no caso de i.

A avaliação de i procede da seguinte forma:

Se e é um tipo literal, i é equivalente a

e.m <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Caso contrário, avalie e para um objeto o. Se o for o objeto nulo, eu avalia o objeto nulo (16.4). Caso contrário, v seja uma variável nova vinculada a oe avalie vm <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k ) para um objeto r. Então e avalia para r.





Caso he.m <···> (···) i. Uma invocação de método ordinário incondicional que eu tenho





a forma e.m <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Invocações não genéricas surgem novamente como o caso especial em que o número de argumentos de tipo é zero (14).

Seja T o tipo estático de e. É um erro em tempo de compilação se T não tiver um membro da instância acessível (6.2) chamado m, a menos que:

• T é dinâmico. Ou

• T é Função e m é chamada. Isso significa que, para invocações de um método de instância chamado call, um receptor do tipo Function é tratado como um receptor do tipo dinâmico. A expectativa é que qualquer subclasse concreta de Function implemente a chamada, mas não existe uma assinatura de método que possa ser assumida para a chamada na Function porque cada assinatura entrará em conflito com algumas possíveis declarações de substituição. Observe que qualquer uso de chamada em uma subclasse de Function que não implemente a chamada provocará um erro de compilação, pois essa isenção é limitada ao tipo Function e não se aplica a seus subtipos.



Se T não tiver um membro acessível chamado m, o tipo estático de i é dinâmico e nenhuma verificação estática adicional é executada em i (exceto que as subexpressões de i estão sujeitas à sua própria análise estática).

Caso contrário, T.m indica um membro da instância. Seja L a biblioteca que

contém i. Seja d o resultado da pesquisa de método para m em T em relação a L e, se a pesquisa de método for bem-sucedida, seja F o tipo estático de d. Caso contrário, seja d o resultado da pesquisa de getter para m em T em relação a L e seja F o tipo de retorno de d. (Como a T.m existe, não podemos falhar nas duas pesquisas.)

A análise estática de i é realizada conforme especificado na Seção 16.17.3, e o tipo estático de i é conforme especificado lá.

É um erro em tempo de compilação chamar qualquer um dos métodos da classe Object em um objeto de prefixo (18.1) ou em um literal de tipo constante que é imediatamente seguido pelo token '.'.

A razão para o último é que essa sintaxe é reservada para invocação de métodos estáticos. Por exemplo, int.toString () é semelhante a C.someStaticMethod (), e seria confuso se apenas algumas expressões desse formulário fossem invocações de métodos de instância. Se necessário, (int) .toString () pode ser usado.

Avaliação de uma invocação incondicional do método ordinário i da forma em <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) procede da seguinte forma:

Primeiro, a expressão e é avaliada para um objeto o. Seja f o resultado da pesquisa (16.19) do método m in o em relação à biblioteca atual L.

Se a pesquisa do método for bem-sucedida, a ligação de argumentos reais a parâmetros formais é executada conforme especificado na Seção 16.17.3. O corpo de f é então executado com relação às ligações que resultaram da avaliação da lista de argumentos e com isso ligado a o. O valor de i é o objeto retornado pela execução do corpo de f.

Se a pesquisa do método falhar, seja g o resultado da pesquisa de getter (16.19) m in o em relação a L.

Se a pesquisa do getter tiver êxito, chame o getter o.m e deixe vg ser o valor retornado. Então o valor de i é o valor de

vg <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Se a pesquisa do getter também falhar, será criada uma nova instância im da classe predefinida Invocation, de modo que:

• im.isMethod é avaliado como verdadeiro.

• im.memberName é avaliado com o símbolo m.

• im.positionalArguments é avaliada em uma lista não modificável com os valores resultantes da avaliação de <Object> [a1, ..., an].

• im.namedArguments é avaliado em um mapa não modificável com as chaves e valores resultantes da avaliação de



<Símbolo, Objeto> {# xn + 1: an + 1, ..., # xn + k: an + k}.

• im.typeArguments é avaliada como uma lista não modificável com os valores resultantes da avaliação de <Type> [A1, ..., Ar].



Em seguida, o método noSuchMethod () é consultado em o e invocado com o argumento im, e o resultado dessa invocação é o resultado da avaliação de i.

A situação em que noSuchMethod é chamado só pode surgir quando o tipo estático de e é dinâmico. Observe que o texto evita reavaliar o receptor o e os argumentos ai.

16.21.2 Invocações em cascata

cascadedInvocations



Uma chamada de método em cascata tem o formato e..suffix, onde e é uma expressão e sufixo é uma sequência de chamadas de operador, método, getter ou setter.





hcascadeSectioni :: = '..' (hcascadeSelectori hargumentParti *)

(hassignableSelectori hargumentParti *) *

(hassignmentOperatori hexpressionWithoutCascadei)?

hcascadeSelectori :: = '[' hexpressioni ‘] '| hidentifieri hargumentParti :: = htypeArgumentsi? hargumentsi

A avaliação de uma expressão de invocação de método em cascata c do formato e..suffix ocorre da seguinte maneira:

Avalie e para um objeto o. Seja t uma variável nova vinculada a o. Avalie

t.suffix para um objeto. Então c é avaliado como o.

O tipo estático de c é o tipo estático de e.

Com a introdução de expressões atribuíveis condicionais com reconhecimento de nulo (16.36), faria sentido estender cascatas com uma forma condicional com reconhecimento de nulo. Pode-se definir e? .. sufixo como equivalente à expressão t == null? null: t.suffix, em que t é uma variável nova vinculada ao valor de e.

A presente especificação não adicionou essa construção, no interesse da simplicidade e da rápida evolução da linguagem. No entanto, as implementações do Dart podem experimentar essas construções, conforme observado na seção 2.

16.21.3 Super Invocação superInvocation

Uma super chamada de método i tem o formato super.m <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k).

Observe que invocações não genéricas surgem como o caso especial em que o número de argumentos de tipo é zero; nesse caso, a lista de argumentos de tipo é omitida e da mesma forma para listas formais de parâmetros de tipo (14).

É um erro em tempo de compilação se ocorrer uma chamada de super método em uma função de nível superior ou inicializador de variável, em um inicializador de variável de instância ou lista de inicializadores, na classe Object, em um construtor de fábrica ou em um método estático ou inicializador de variável.

Seja Ssuper a superclasse (10.8) da classe imediatamente envolvente para i e seja L a biblioteca que contém i. Seja a declaração d o resultado da pesquisa do método m em Ssuper em relação a L (16.19), e seja F o tipo estático de d. Caso contrário, se a pesquisa do método falhar, deixe a declaração d ser o resultado de procurar o getter m em relação a L em Ssuper (16.19) e F seja o tipo de retorno de d. Se ambas as pesquisas falharem, ocorrerá um erro em tempo de compilação.

Caso contrário (quando uma das pesquisas for bem-sucedida), a análise estática de i é executada conforme especificado na Seção 16.17.3, considerando que a função possui o tipo estático F e o tipo estático de i é especificado lá.

Observe que as pesquisas de membros ignoram declarações abstratas, o que significa que haverá um erro em tempo de compilação se o membro de destino m for abstrato, bem como quando ele não existir.

A avaliação de i procede da seguinte forma: Seja o ligação atual disso, seja C a classe envolvente de i, e seja Ssuper a superclasse (10.8) de C. Seja a declaração d o resultado de procurar o método m em relação a L in o começando com Ssuper (16.19 ) Se a pesquisa for bem-sucedida, deixe f denotar a função associada a d. Caso contrário (quando a pesquisa do método falhar), deixe a declaração ser o resultado de procurar o getter m em relação a L in o começando com Ssuper (16.19). Se a pesquisa do getter tiver êxito, chame o getter com esse limite para o e deixe f denotar o objeto retornado.

Se as duas pesquisas falharem, as mesmas pesquisas teriam falhado no tempo de compilação e o programa apresentará um erro no tempo de compilação.

Caso contrário, execute a ligação de argumentos reais a parâmetros formais para f <A1, ..., Ar> (a1, ..., an, xn + 1: an + 1, ..., xn + k: an + k) conforme especificado na Seção 16.17.3, e execute o corpo de f com as referidas ligações mais uma ligação disso a o. O resultado retornado por f é o resultado da avaliação de i.

16.21.4 Enviando mensagens

As mensagens são o único meio de comunicação entre isolados. As mensagens são enviadas invocando métodos específicos nas bibliotecas do Dart; não há sintaxe específica para enviar uma mensagem.

Em outras palavras, os métodos que dão suporte ao envio de mensagens incorporam primitivas do Dart que não são acessíveis ao código comum, assim como os métodos que geram isolamentos.

sendMessages



16.22 Extração de propriedade

propertyExtraction



A extração de propriedades permite que um membro seja acessado como uma propriedade e não como uma função. Uma extração de propriedade pode ser:

Um encerramento de método de instância, que converte um método em um objeto de função (16.22.3). Ou

Uma chamada getter, que retorna o resultado da chamada de um método getter (16.22.1).



Objetos de função derivados de membros por meio de closurization são conhecidos coloquialmente como destacamentos.

A extração de propriedades pode ser condicional ou incondicional.





Case hConditionali. Considere uma expressão de extração de propriedade condicional





i da forma e? .id.

Se e é um tipo literal, i é equivalente a e.id.

Caso contrário, o tipo estático de i é o mesmo que o tipo estático de e.id. Seja T o tipo estático de e, e seja uma variável nova do tipo T. Exceto pelos erros dentro de e referências ao nome y, exatamente os mesmos erros em tempo de compilação que seriam causados ​​por y.id também serão gerados no caso de e? .id.

A avaliação de uma expressão de extração de propriedade condicional i do formato e? .Id ocorre da seguinte maneira:

Se e é um tipo literal, a avaliação de i equivale à avaliação de e.id.

Caso contrário, avalie e para um objeto o. Se o for o objeto nulo, eu avalia o objeto nulo (16.4). Caso contrário, seja x uma nova variável vinculada a oe avalie x.id para um objeto r. Então eu avalia para r.





Caso hcondicional. Seja id um identificador; uma extração incondicional de propriedades pode ter a forma e.id em que e é uma expressão (16.22.1) ou a forma super.id (16.22.2).



getterAccessAndMethodExtraction



16.22.1 Acesso ao getter e extração de métodos

Considere uma extração incondicional de propriedades i (16.22) do formato e.id. É um erro em tempo de compilação se id for um membro da classe Object ee for um objeto de prefixo (18.1) ou um tipo literal.

Pode parecer óbvio que é um erro usar o objeto prefixo, mas é mais surpreendente que isso também se aplique a um tipo literal. Em particular, não podemos usar int.toString para obter um objeto de função para o método toString do objeto Type para int. Mas podemos usar (int) .toString: e, então, não é um tipo literal, mas uma expressão entre parênteses.

Este é um trade-off pragmático. A capacidade de separar métodos de instância em instâncias de Type foi considerada menos útil, e foi considerado mais útil insistir na regra simples de que um destacamento de método em um literal de tipo é sempre um destacamento de um método estático no classe denotada.

Seja T o tipo estático de e. É um erro em tempo de compilação se T não tiver um método ou getter chamado id, a menos que T seja dinâmico ou T seja Function e id seja chamada. O tipo estático de i é:

• O tipo de retorno declarado de T.id, se T tiver um getter de instância acessível chamado id.

• O tipo de função da assinatura do método T.id, se T tiver um método de instância acessível chamado id.

• O tipo dinâmico, caso contrário. Isso ocorre apenas quando T é dinâmico ou



Função.

Observe que o tipo de destacamento de um método ignora se algum parâmetro é covariante. No entanto, o tipo dinâmico de um objeto de função assim obtido leva em consideração a covariância dos parâmetros.

A avaliação de uma extração de propriedade i da forma e.id ocorre da seguinte forma:

Primeiro, a expressão e é avaliada para um objeto o. Seja f o resultado da pesquisa do método (16.19) (10.1) id em o com relação à biblioteca atual L. Se a pesquisa do método for bem-sucedida, eu avaliarei a closurização do método f no objeto o (16.22.3).

Observe que f nunca é um método abstrato, porque a pesquisa de métodos ignora os métodos abstratos. Se o método parecer falhou, por exemplo, porque há uma declaração abstrata de id, mas nenhuma declaração concreta, continuaremos com a próxima etapa. No entanto, como os métodos e os getters nunca se substituem, a pesquisa do getter também falhará necessariamente, e noSuchMethod () acabará sendo invocado. A implicação lamentável é que o erro se refere a um getter ausente, em vez de uma tentativa de fechar um método abstrato.

Caso contrário, i é uma invocação getter. Seja f o resultado de procurar (16.19) getter (10.2) id em o em relação a L. Caso contrário, o corpo de f é executado com isso vinculado a o. O valor de i é o resultado retornado pela chamada para a função getter.

Se a pesquisa do getter falhar, será criada uma nova instância im da classe predefinida Invocation, de modo que:

• im.isGetter avalia como verdadeiro.

• im.memberName é avaliado com o símbolo m.

• im.positionalArguments é avaliado como uma instância vazia e não modificável de List <Object>.

• im.namedArguments é avaliado como uma instância vazia e não modificável do Map <Symbol, Object>.

• im.typeArguments é avaliado como uma instância vazia e não modificável de List <Type>.



Em seguida, o método noSuchMethod () é consultado em o e invocado com o argumento im, e o resultado dessa invocação é o resultado da avaliação de i.

A situação em que noSuchMethod é chamado só pode surgir quando o tipo estático de e é dinâmico.

16.22.2 Acesso ao super getter e encerramento de método superGetterAccessAndMethodClosurization

Considere uma extração de propriedade i no formato super.id.

Seja S a superclasse da classe imediatamente envolvente. É um erro de compilação se S não tiver um método de instância acessível ou getter chamado id. O tipo estático de i é:

• O tipo de retorno declarado de S.id, se S tiver um getter de instância acessível chamado id.

• O tipo de função da assinatura do método S.id, se S tiver um método de instância acessível chamado id.

• O tipo dinâmico, caso contrário. Isso ocorre apenas quando T é dinâmico ou



Função.

Observe que o tipo de destacamento de um método ignora se algum parâmetro é covariante. No entanto, o tipo dinâmico de um objeto de função assim obtido leva em consideração a covariância dos parâmetros.

A avaliação de uma extração de propriedade i, no formato super.m, segue da seguinte forma:

Seja g a implementação do método atualmente em execução e C seja a classe na qual g é declarado. Seja S a superclasse de C. Seja f o resultado da pesquisa da identificação do método em S com relação à biblioteca atual L. Se a pesquisa do método for bem-sucedida, avaliamos a closurização do método f com relação à superclasse S (16.22.4 )

Caso contrário, i é uma invocação getter. Seja f o resultado de procurar o getter id em S com relação a L. O corpo de f é executado com isso vinculado ao valor atual disso. O valor de i é o resultado retornado pela chamada para a função getter.

A pesquisa do getter não falha, porque é um erro em tempo de compilação ter uma extração de superpropriedade de um ID de membro quando a superclasse S não tiver um membro concreto chamado id.

16.22.3 Encerramento de membros comuns

Esta seção especifica a semântica dinâmica de closurizations de membros comuns.

Observe que o caso não genérico é abordado implicitamente usando s = 0; nesse caso, a declaração de parâmetro de tipo lista e as listas de argumentos de tipo reais passadas em invocações são omitidas (14).

commonMemberClosurization



Um encerramento de método de instância é um encerramento de algum método em algum objeto, definido abaixo, ou um super encerramento (16.22.4).

Seja o um objeto e seja uma variável final nova vinculada a o. o





A closurização do método f no objeto o é definida como equivalente (exceto para





igualdade, conforme observado abaixo) para:

• <X1 estende B01, ..., Xs estende B0s>



(T1 p1, ..., Tn pn, {Tn + 1 pn + 1 = d1, ..., Tn + k pn + k = dk}) =>

u.m <X1, ..., Xs> (p1, ..., pn, pn + 1: pn + 1, ..., pn + k: pn + k);

onde f é um método de instância chamado m que possui declarações de parâmetro de tipo X1 estende B1, ..., Xs estendeBs, parâmetros necessários p1, ..., pn e parâmetros nomeados pn + 1, ..., pn + k com os padrões d1 , ..., dk, usando null para parâmetros cujo valor padrão não está especificado.

• <X1 estende B01, ..., Xs estende B0s>



(T1 p1, ..., Tn pn, [Tn + 1 pn + 1 = d1, ..., Tn + k pn + k = dk]) =>

u.m <X1, ..., Xs> (p1, ..., pn + k);

onde f é um método de instância denominado m que possui declarações de parâmetro de tipo X1 estende B1, ..., Xs estendeBs, parâmetros necessários p1, ..., pn e parâmetros posicionais opcionais pn + 1, ..., pn + k com padrões d1, ..., dk, usando null para parâmetros cujo valor padrão não está especificado.

B..s são determinados da seguinte forma: Se o é uma instância de uma classe não genérica, B Bj, j ∈ 1..s. Caso contrário, sejam X10, ..., Xs00 os parâmetros de tipo formal da classe de o, e t01, ..., t0s0 sejam os argumentos de tipo reais. Então

Bj0 = [t01 / X10, ..., t0s0 / Xs00] Bj, j ∈ 1..s.

Ou seja, substituímos os parâmetros de tipo formal da classe envolvente, se houver, pelo argumen de tipo real correspondente ts.

Os tipos de parâmetro Tj, j ∈ 1..n + k, são determinados da seguinte forma: Seja a declaração do método D a implementação de m que é invocada pela expressão no corpo. Seja T a classe que contém D.

Observe que T é o tipo dinâmico de o, ou uma superclasse dele.

Para cada parâmetro pj, j ∈ 1..n + k, se pj for covariante (9.2.3), então Tj é a classe interna Object.

Isso está relacionado ao tipo dinâmico do objeto de função obtido pela finalização do membro. O tipo estático da expressão que dá origem à finalização do membro é especificado em outra parte (16.22, 16.22.1). Observe que, para o tipo estático, é ignorado se um parâmetro é covariante.

Se T for uma classe não genérica, então para j ∈ 1..n + k, Tj é uma anotação de tipo que denota o mesmo tipo que é indicado pela anotação de tipo na declaração de parâmetro correspondente em D. Se essa declaração de parâmetro não possui anotação de tipo, Tj é dinâmico.

Caso contrário, T é uma instanciação genérica de uma classe genérica G. Seja X100, ..., Xs0000 os parâmetros de tipo formal de G, e t001, ..., t00s00 sejam os argumentos de tipo reais de o em T. Então Tj é um anotação de tipo que indica [t001 / X100, ..., ts0000 / Xs0000] Sj, em que Sj é a anotação de tipo do parâmetro correspondente em D. Se essa declaração de parâmetro não tiver anotação de tipo, Tj será dinâmico.

Existe uma maneira pela qual o objeto de função gerado pelo encerramento do método de instância difere do objeto de função obtido pelo encerramento da função na literal da função mencionada acima: Suponha que o1 e o2 são objetos, m é um identificador e c1 e c2 são funções objetos obtidos por closurization de m em o1 respectivamente o2. Então c1 == c2 é avaliado como verdadeiro se e somente se o1 e o2 são o mesmo objeto.

Em particular, duas closurizations de um método m do mesmo objeto são iguais e duas closurizations de um método m de objetos não idênticos não são iguais. Supondo que vi seja uma variável nova vinculada a um objeto, i ∈ 1..2, também se segue que idêntico (v1.m, v2.m) deve ser falso quando v1 e v2 não estiverem vinculados ao mesmo objeto. No entanto, as implementações do Dart não são necessárias para canonizar objetos de função, o que significa que não é garantido que idênticas (v1.m, v2.m) sejam verdadeiras, mesmo quando se sabe que as v1 e v2 estão vinculadas ao mesmo objeto.

O tratamento especial da igualdade, neste caso, facilita o uso de funções de propriedade extraídas nas APIs em que os retornos de chamada, como ouvintes de eventos, geralmente devem ser registrados e posteriormente não registrados. Um exemplo comum é a API DOM nos navegadores da web.

16.22.4 Super Closurization

Esta seção especifica a semântica dinâmica de super closurizations.

Observe que o caso não genérico é abordado implicitamente usando s = 0; nesse caso, as declarações de parâmetro de tipo são omitidas (14).

Considere expressões no corpo de uma classe T, que é uma subclasse de uma determinada classe S, onde existe uma declaração de método que implementa f em S, e não há classe U, que é uma subclasse de S e uma superclasse de T, que implementa f .

Em resumo, considere uma situação em que uma super invocação de f executará f conforme declarado em S.

superClosurization



Uma super closurization é uma closurization de um método com relação a uma classe,





conforme definido a seguir. A closurização de um método f em relação à classe S é





definido como equivalente (exceto para a igualdade, conforme observado abaixo) a:

• <X1 estende B01, ..., Xs estende B0s>



(T1 p1, ..., Tn pn, {Tn + 1 pn + 1 = d1, ..., Tn + k pn + k = dk}) => super.m <X1, ..., Xs> ( p1, ..., pn, pn + 1: pn + 1, ..., pn + k: pn + k);

onde f é um método de instância chamado m que possui declarações de parâmetro de tipo X1 estende B1, ..., Xs estendeBs, parâmetros necessários p1, ..., pn e parâmetros nomeados pn + 1, ..., pn + k com os padrões d1 , ..., dk.

• <X1 estende B01, ..., Xs estende B0s>



(T1 p1, ..., Tn pn, [Tn + 1 pn + 1 = d1, ..., Tn + k pn + k = dk]) => super.m <X1, ..., Xs> ( p1, ..., pn + k);

onde f é um método de instância denominado m que possui declarações de parâmetro de tipo X1 estende B1, ..., Xs estendeBs, parâmetros necessários p1, ..., pn e parâmetros posicionais opcionais pn + 1, ..., pn + k com padrões d1, ..., dk.

Observe que uma super closurização é uma closurization de método de instância, conforme definido em (16.22.3).

B..s são determinados da seguinte forma: Se S é uma classe não genérica, então B Bj, j ∈ 1..s. Caso contrário, seja X10, ..., Xs00 os parâmetros de tipo formal de S, e t01, ..., t0s0 sejam os argumentos de tipo reais disso em S. Então Bj0 =

[t01 / X10, ..., t0s0 / Xs00] Bj, j ∈ 1..s.

Ou seja, substituímos os parâmetros de tipo formal da classe envolvente, se houver, pelos argumentos de tipo real correspondentes. Precisamos considerar os argumentos de tipo em relação a uma classe específica, porque é possível que uma classe passe argumentos de tipo diferentes para sua superclasse dos que recebe em si.

Os tipos de parâmetro Tj, j ∈ 1..n + k, são determinados da seguinte forma: Seja a declaração do método D a implementação de m em S.

Para cada parâmetro pj, j ∈ 1..n + k, if pj é covariante (9.2.3) e Tj é a classe interna Object.

Isso se refere ao tipo dinâmico do objeto de função obtido pela super closurização. O tipo estático da expressão que origina a super-securização é especificado em outra parte (16.22, 16.22.2). Observe que, para o tipo estático, é ignorado se um parâmetro é covariante.

Se S é uma classe não genérica, então para j ∈ 1..n + k, Tj é uma anotação de tipo que denota o mesmo tipo que é indicado pela anotação de tipo na declaração de parâmetro correspondente em D. Se essa declaração de parâmetro não possui anotação de tipo, Tj é dinâmico.

Caso contrário, S é uma instanciação genérica de uma classe genérica G. Sejam X100, ..., Xs0000 os parâmetros de tipo formal de G, e t001, ..., t00s00 sejam os argumentos de tipo reais de o em S. Então Tj é um anotação de tipo que indica [t001 / X100, ..., ts0000 / Xs0000] Sj, em que Sj é a anotação de tipo do parâmetro correspondente em D. Se essa declaração de parâmetro não tiver anotação de tipo, Tj será dinâmico.

Existe uma maneira pela qual o objeto de função gerado pela super closurização difere do objeto de função obtido pela closurization da função no literal da função acima mencionado: Suponha que uma ocorrência da expressão super.m em uma determinada classe seja avaliada em duas ocasiões em que isso é vinculado a o1, respectivamente, o2, e os objetos de função resultantes são c1, respectivamente, c2: c1 == c2 será verdadeiro se e somente se o1 e o2 forem o mesmo objeto.

16.22.5 Instanciação de método genérico genericMethodInstantiation

A instanciação de método genérico é um mecanismo que gera um objeto de função não genérico, com base em uma extração de propriedade que denota um encerramento de método de instância (16.22.3, 16.22.4).

É um mecanismo muito semelhante ao encerramento do método de instância, mas ocorre apenas em situações em que um erro em tempo de compilação ocorreria.

A essência da instanciação genérica do método é permitir invocações "curry", no sentido de que um método de instância genérico pode receber seus argumentos de tipo reais separadamente durante a closurization (ele deve receber todos os argumentos de tipo, não apenas alguns deles), e que gera um objeto de função não genérico. Os argumentos de tipo são transmitidos implicitamente, com base na inferência de tipo; uma versão futura do Dart pode permitir a sua passagem explícita. Aqui está um exemplo:

classe A {

X fi <X estende num> (X x) => x;

}

classe B estende / * ou implementa * / A {

X fi <X estende num> (X x, [Lista <X> xs]) => x;

}

void main () {

A a = B ();

int Função (int) f = a.fi;

}

O objeto de função que é armazenado em f no final do main possui o tipo dinâmico int Function (int, [List <int>]) e é obtido implicitamente "passando o argumento do tipo real int" para o método de instância genérica indicado, obtendo assim um objeto de função não genérica do tipo especificado. Observe que esse objeto de função aceita um argumento posicional opcional, mesmo que isso não faça parte do tipo estaticamente conhecido do método de instância correspondente, nem do tipo de contexto.

Em outras palavras, a instanciação genérica do método produz uma função cuja assinatura corresponde ao tipo de contexto, tanto quanto possível, mas com relação ao formato da lista de parâmetros (ou seja, o número de parâmetros posicionais e sua opcionalidade ou o conjunto de nomes de parâmetros nomeados ), será determinado pela assinatura do método de instância real do receptor especificado. Obviamente, a diferença só pode ser tal que o tipo real seja um subtipo do tipo de contexto especificado, caso contrário, a declaração desse método de instância teria sido um erro em tempo de compilação.

Seja eu uma expressão de extração de propriedade no formato e? .Id, e.id ou super.id (16.22, 16.22.2), que é resolvido estaticamente para indicar um método de instância chamado id e seja G o tipo estático de i. Considere a situação em que G é um tipo de função no formato T0 Função [<X1 / B1, ..., Xs / Bs>] (parâmetros) com s> 0 (ou seja, G é um tipo de função genérico) e o tipo de contexto é uma função não genérica do tipo F. Nessa situação, ocorre um erro em tempo de compilação (8, 9, 10.6.1, 10.6.1, 10.6.1, 16.15.1, 16.15.2, 16.15.2, 16.17.3, 16.23, 17.3 , 17.9, 17.12, 17.16.2), exceto quando a instanciação do tipo de função genérica (16.18.1) for bem-sucedida, ou seja:

A inferência de tipo é aplicada a G com o tipo de contexto F e é bem-sucedida, produzindo a lista de argumentos de tipo real T1, ..., Ts.

Considere a situação em que a instanciação do tipo de função genérica foi bem-sucedida. Seja gmiNameid um novo nome associado ao id, que é privado se e somente se o id for privado. Uma implementação pode usar, digamos, foo_ * quando id for foo, que é conhecido por ser novo porque os identificadores escritos pelo usuário não podem conter '*'. O programa é modificado da seguinte maneira:

• Quando i é e? .Id: Substitua i por e? .GmiNameid <T1, ..., Ts> ().

• Quando i é e.id: substitua i por ex .miNameid <T1, ..., Ts> ().

• Quando i é super.id: substitua i por super.gmiNameid <T1, ..., Ts> ().



As expressões inseridas não possuem erro em tempo de compilaçãoree pode ser executado, porque o método genérico correspondente é induzido implicitamente. Nós usamos o





método genérico de instanciação para designar esses métodos implicitamente induzidos,





e designar o método que o induziu como alvo.





Suponha que uma classe C declare um método de instância genérico chamado id, com uma assinatura de método correspondente a uma função genérica tipo G, parâmetros de tipo formal X1 estende B1, ..., Xs estende Bs e parâmetros formais de declaração de parâmetro. Deixe argumentos denotar a lista de argumentos real correspondente, passando esses parâmetros. Por exemplo, os parâmetros podem ser

T1 p1, ..., Tn pn, {Tn + 1 pn + 1 = d1, ..., Tn + k pn + k = dk}, caso em que os argumentos seriam p1, ..., pn, pn + 1 : pn + 1, pn + k: pn + k.

Seja G0 o mesmo tipo de função que G, exceto pelo fato de omitir as declarações formais dos parâmetros de tipo. Por exemplo, se G é nulo Função <X, Y estende num> (X x, Lista <Y> ys), então G0 é nulo Função (X x, Lista <Y> ys). Observe que G0 normalmente contém variáveis ​​de tipo livre.

Um método de instância com o nome gmiNameid é induzido implicitamente, com o mesmo comportamento da declaração a seguir (exceto a igualdade do objeto de função retornado, especificado abaixo):

G0 gmiNameid <X1 estendeB1, ..., Xs estendeBs> () {return (parâmetros) => this.id <X1, ..., Xs> (argumentos);

}

Seja uma instância de uma classe que contenha uma declaração implicitamente induzida de gmiNameid, conforme descrito acima. Considere a situação em que o programa avalia duas invocações desse método com o mesmo receptor oe com argumentos de tipo real cujos valores reais são os mesmos tipos t1, ..., ts para ambas invocações e suponha que as invocações retornaram as instâncias o1 respectivamente o2. É então garantido que o1 e o2 são iguais de acordo com o operador '=='. Não é especificado se idêntico (o1, o2) é avaliado como verdadeiro ou falso.

Nenhuma noção de igualdade é apropriada para receptores diferentes, nem quando argumentos de tipo diferentes são fornecidos, porque a execução de dois objetos de função que diferem dessa maneira pode ter efeitos colaterais diferentes e retornar resultados diferentes quando executados começando exatamente no mesmo estado.





16.23 Designação de atribuição


Uma atribuição altera o valor associado a uma variável ou propriedade mutável.

hassignmentOperatori :: = ‘= '

| hcompoundAssignmentOperatori

Caso hv = ei. Considere uma atribuição a da forma v = e, em que v é um identificador ou um identificador qualificado por um prefixo de importação e v indica uma variável (8) ou v = indica um setter (que pode ser declarado explicitamente ou induzido por uma instância) variável etc.). Seja T o tipo estático de v quando v denota uma variável, caso contrário, seja T o tipo estático do parâmetro formal do setter v =. É um erro em tempo de compilação se o tipo estático de e não puder ser atribuído a T. O tipo estático de a é o tipo estático de e.

É um erro em tempo de compilação se uma atribuição do formato v = e ocorrer dentro de uma função estática ou de nível superior (seja função, método, getter ou setter) ou inicializador de variável e não houver uma declaração de variável local mutável com nome v nem uma declaração de setter com nome v = no escopo lexical que encerra a atribuição.

A avaliação de uma atribuição a da forma v = e prossegue da seguinte forma: Seja d a declaração mais interna cujo nome é v ou v =, se existir. É um erro de compilação se d denota um objeto de prefixo, declaração de tipo ou declaração de função.

Se d é a declaração de uma variável local, a expressão e é avaliada para um objeto o. Então, a variável v é vinculada a o. Se nenhum erro ocorrer, o valor da expressão de atribuição é o.

Se v for uma variável final, ocorreu um erro em tempo de compilação e a execução não é especificada. Mas um programa sem erros em tempo de compilação pode resultar em um erro de tipo dinâmico.

Se d é a declaração de uma variável de biblioteca, getter de nível superior ou setter de nível superior, a expressão e é avaliada para um objeto o. Então o setter v = é chamado com seu parâmetro formal vinculado a o. O valor da expressão de atribuição é o.

Caso contrário, se d for a declaração de uma variável de classe, getter estático ou setter estático na classe C, a atribuição será equivalente à atribuição C.v = e.

Caso contrário, se ocorrer dentro de uma função estática ou de nível superior (seja função, método, getter ou setter) ou inicializador de variável, ocorrerá um erro em tempo de compilação.

Caso contrário, a atribuição é equivalente à atribuição this.v = e.

É um erro de tipo dinâmico se o tipo dinâmico de o não for um subtipo do tipo real (19.10.1) de v.

Caso he1? .V = e2i. Considere uma atribuição a no formato e1? .V = e2. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por e1.v = e2 também são gerados no caso de a. O tipo estático de a é o tipo estático de e2.

A avaliação de uma atribuição a no formato e1? .V = e2 prossegue da seguinte forma: Se e1 for um tipo literal, a será equivalente a e1.v = e2. Caso contrário, avalie e1 para um objeto o. Se o for o objeto nulo, uma avaliação tes para o objeto nulo (16.4). Caso contrário, seja x uma variável nova vinculada a oe avalie x.v = e2 para um objeto r. Então a é avaliado como r.

Caso he1.v = e2i. Considere uma atribuição a no formato e1.v = e2. Seja T o tipo estático de e1. Se T for dinâmico, nenhuma verificação adicional será realizada. Caso contrário, é um erro em tempo de compilação, a menos que T tenha um configurador de instância acessível chamado v =. É um erro em tempo de compilação, a menos que o tipo estático de e2 possa ser atribuído ao tipo declarado do parâmetro formal do referido setter. Independentemente de T ser dinâmico, o tipo estático de a é o tipo estático de e2.

A avaliação de uma atribuição no formato e1.v = e2 prossegue da seguinte forma: A expressão e1 é avaliada para um objeto o1. Em seguida, a expressão e2 é avaliada para um objeto o2. Em seguida, o levantador v = é consultado (16.19) em o1 em relação à biblioteca atual. É um erro de tipo dinâmico se o tipo dinâmico de o2 não for um subtipo do tipo de parâmetro atual do referido setter (19.10.1). Caso contrário, o corpo do setter é executado com seu parâmetro formal vinculado a o2 e este vinculado a o1.

Se a pesquisa do setter falhar, será criada uma nova instância im da classe predefinida Invocation, de modo que:

• im.isSetter é avaliado como verdadeiro.

• im.memberName é avaliado com o símbolo v =.

• im.positionalArguments avalia uma lista não modificável com os mesmos valores que <Object> [o2].

• im.namedArguments é avaliado como uma instância vazia e não modificável do Map <Symbol, Object>.

• im.typeArguments é avaliado como uma instância vazia e não modificável de List <Type>.



Em seguida, o método noSuchMethod () é pesquisado em o1 e invocado com o argumento im.

A situação em que noSuchMethod é chamado pode surgir apenas quando o tipo estático de e1 é dinâmico.

O valor da expressão de atribuição é o2, independentemente de a pesquisa do setter falhar ou ter êxito.

Caso hsuper.v = ei. Considere uma atribuição a no formato super.v = e. Seja Sstatic a superclasse da classe imediatamente envolvente. É um erro de compilação se o Sstatic não tiver um configurador de instância acessível e concreto chamado v =. Caso contrário, é um erro em tempo de compilação se o tipo estático de e não puder ser atribuído ao tipo estático do parâmetro formal do referido setter. O tipo estático de a é o tipo estático de e.

A avaliação de uma atribuição no formato super.v = e prossegue da seguinte forma: Seja g o método atualmente em execução e C seja a classe na qual g foi pesquisado. Seja Sdynamic a superclasse de C. A expressão e é avaliada para um objeto o. Em seguida, o setter v = é pesquisado (16.19) no Sdynamic com relação à biblioteca atual. O corpo de v = é executado com seu parâmetro formal vinculado a oe este vinculado ao valor atual disso.

A pesquisa do setter não falhará, porque é um erro em tempo de compilação quando nenhum setter concreto chamado v = existe no Sstatic.

O valor da expressão de atribuição é o.

É um erro de tipo dinâmico se o não for o objeto nulo (16.4) e o tipo dinâmico de o não for um subtipo do tipo real do parâmetro formal de v =

(19.10.1) em Sstatic. Caso he1 [e2] = e3i. Considere uma atribuição a no formato e1 [e2] = e3. Seja T o tipo estático de e1. Se T for dinâmico, nenhuma verificação adicional será realizada. Caso contrário, é um erro em tempo de compilação, a menos que T tenha um método chamado [] =. Seja S2 o tipo estático do primeiro parâmetro formal do método [] =, e S3 o tipo estático do segundo. É um erro em tempo de compilação, a menos que o tipo estático de e2, respectivamente, e3 possa ser atribuído a S2, respectivamente, S3. Independentemente de T ser dinâmico, o tipo estático de a é o tipo estático de e3.

A avaliação de uma atribuição a no formato e1 [e2] = e3 ocorre da seguinte forma:

Avalie e1 para um objeto a, depois avalie e2 para um objeto i e, finalmente, avalie e3 para um objeto v. Chame o método [] = em a com i com i como primeiro argumento e v como segundo argumento. Então, a avalia para v.

Caso hsuper [e1] = e2i. Considere uma atribuição a da forma super [e1] = e2. Seja Sstatic a superclasse da classe imediatamente envolvente. É um erro em tempo de compilação se o Sstatic não tiver um método [] =. Caso contrário, seja S1 o tipo estático do primeiro parâmetro formal do método [] = e S2 o tipo estático do segundo. É um erro em tempo de compilação se o tipo estático de e1, respectivamente, e2 não puder ser atribuído a S1, respectivamente, S2. O tipo estático de a é o tipo estático de e2.

Para avaliação, uma atribuição do formato super [e1] = e2 é equivalente à expressão super. [E1] = e2.

16.23.1 Atribuição do composto

Caso hv ?? = ei. Considere uma atribuição composta a da forma v ?? = e em que v é um identificador ou um identificador qualificado por um prefixo de importação, de modo que v denota uma variável ou v denota um getter e v = denota um setter. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por v = e também são gerados no caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de ve tipo estático de e.

Avaliação de uma atribuição composta a da forma v ?? = e proocorre da seguinte maneira: Avalie v para um objeto o. Se o não for o objeto nulo (16.4), a será avaliado como o. Caso contrário, avalie v = e para um objeto r e a avalie como r.

Caso hC.v ?? = ei. Considere uma atribuição composta a da forma C.v ?? = e onde C é um tipo literal que pode ou não ser qualificado por um prefixo de importação, de modo que C.v denuncie um getter e C.v = denuncie um setter. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por C.v = e também são gerados no caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de C.v e o tipo estático de e.

A avaliação de uma atribuição composta a da forma C.v ?? = e em que C é um tipo literal prossegue da seguinte forma: Avalie C.v para um objeto o. Se o não for o objeto nulo (16.4), a será avaliado como o. Caso contrário, avalie C.v = e para um objeto r e, em seguida, a é avaliado como r.

Caso he1.v ?? = e2i. Considere uma atribuição composta a da forma e1.v ?? = e2. Seja T o tipo estático de e1 e x seja uma variável nova do tipo T. Exceto pelos erros dentro de e1 e pelas referências ao nome x, exatamente os mesmos erros em tempo de compilação que seriam causados ​​por xv = e2 também são gerados em o caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de e1.v e o tipo estático de e2.

A avaliação de uma atribuição composta a da forma e1.v ?? = e2 prossegue da seguinte forma: Avalie e1 para um objeto u. Seja x uma nova variável vinculada a u. Avalie x.v para um objeto o. Se o não for o objeto nulo (16.4), a será avaliado como o.

Caso contrário, avalie x.v = e2 para um objeto r e, em seguida, a é avaliado como r.

Caso he1 [e2] ?? = e3i. Considere uma atribuição composta a da forma e1 [e2] ?? = e3. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por e1 [e2] = e3 também são gerados no caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de e1 [e2] e o tipo estático de e3.

A avaliação de uma atribuição composta a da forma e1 [e2] ?? = e3 procede da seguinte forma: Avalie e1 para um objeto u e avalie e2 para um objeto i. Chame o método [] em u com o argumento i, e deixe o ser o valor retornado. Se o não for o objeto nulo (16.4), a será avaliado como o. Caso contrário, avalie e3 para um objeto ve chame o método [] = em u com i como primeiro argumento e v como segundo argumento. Então, a avalia para v.

Caso hsuper.v ?? = ei. Considere uma atribuição composta a da forma super.v ?? = e. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por super.v = e também são gerados no caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de super.v e o tipo estático de e.

A avaliação de uma atribuição composta a da forma super.v ?? = e prossegue da seguinte forma: Avalie super.v para um objeto o. Se o não for o objeto nulo (16.4), a será avaliado como o. Caso contrário, avalie super.v = e para um objeto r e, em seguida, a é avaliado como r.

Caso he1? .V ?? = e2i. Considere uma atribuição composta a da forma e1? .V ?? = e2. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por e1.v ?? = e2 também são gerados no caso de a. O tipo estático de a é o limite superior mínimo do tipo estático de e1? .V e o tipo estático de e2.

A avaliação de uma atribuição composta a da forma e1? .V ?? = e2 procede da seguinte forma: Avalie e1 para um objeto u. Se u é o objeto nulo (16.4), a é avaliado para o objeto nulo. Caso contrário, seja x uma nova variável vinculada a u. Avalie x.v para um objeto o. Se o não for o objeto nulo (16.4), a será avaliado como o. Caso contrário, avalie x.v = e2 para um objeto r e, em seguida, a é avaliado como r.

Caso hC? .V ?? = e2i. Uma atribuição composta da forma C? .V ?? = e2 em que C é um tipo literal que pode ou não ser qualificado por um prefixo de importação é equivalente à expressão C.v ?? = e.

Caso hv op = ei. Para qualquer outro operador válido, uma atribuição composta no formato v op = e é equivalente a v = v op e, em que v é um identificador ou um identificador qualificado por um prefixo de importação.

Caso hC.v op = ei. Uma atribuição composta no formato C.v op = e em que C é um tipo literal que pode ou não ser qualificado por um prefixo de importação é equivalente a C.v = C.v op e.

Caso he1.v op = e2i. Considere uma atribuição composta a no formato e1.v op = e2. Seja x uma nova variável cujo tipo estático seja o tipo estático de e1. Exceto pelos erros dentro de e1 e pelas referências ao nome x, exatamente os mesmos erros em tempo de compilação que seriam causados ​​por x.v = x.v op e2 também são gerados no caso de a. O tipo estático de a é o tipo estático de e1.v op e2.

A avaliação de uma atribuição composta a da forma e1.v op = e2 prossegue da seguinte forma: Avalie e1 para um objeto u e seja x uma nova variável vinculada a u.

Avalie x.v = x.v op e2 para um objeto re, em seguida, a é avaliado como r.

Caso he1 [e2] op = e3i. Considere uma atribuição composta a da forma e1 [e2] op = e3. Seja x e i novas variáveis ​​em que o tipo estático do primeiro é o tipo estático de e1 e o tipo estático do último é o tipo estático de e2. Exceto por erros dentro de e1 e e2 e referências aos nomes x e i, exatamente o os mesmos erros em tempo de compilação que seriam causados ​​por x [i] = x [i] op e3 também são gerados no caso de a. O tipo estático de a é o tipo estático de x [i] op e3.

A avaliação da atribuição s de composto a da forma e1 [e2] op = e3 ocorre da seguinte maneira: Avalie e1 para um objeto u e avalie e2 para um objeto v. Seja x e i novas variáveis ​​vinculadas a u e v, respectivamente. Avalie x [i] = x [i] op e3 para um objeto r, e então a é avaliado como r.

Caso he1? .V op = e2i. Considere uma atribuição composta a da forma e1? .V op = e2. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por e1.v op = e2 também são gerados no caso de a. O tipo estático de a é o tipo estático de e1.v op = e2.

A avaliação de uma atribuição composta a da forma e1? .V op = e2 ocorre da seguinte forma: Avalie e1 para um objeto u. Se u é o objeto nulo, a é avaliado para o objeto nulo (16.4). Caso contrário, seja x uma nova variável vinculada a u. Avalie x.v op = e2 para um objeto r. Então a é avaliado como r.

Caso hC? .V op = e2i. Uma atribuição composta da forma C? .V op = e2 em que C é um tipo literal é equivalente à expressão C.v op = e2.

hcompoundAssignmentOperatori :: = ‘* = '

| ‘/ =’

| ‘~ / =’

| '% ='

| ‘+ =’

| ‘- =’

| "<< ="

| ‘>> =’

| ‘>>> =’

| "& ="

| = ^ = | | ‘| =’

| ‘?? =’



16.24 Condicional

condicional



Uma expressão condicional avalia uma das duas expressões com base em uma condição booleana.





hconditionalExpressioni :: = hifNullExpressioni

("?" HexpressionWithoutCascadei ":" hexpressionWithoutCascadei)?

A avaliação de uma expressão condicional c do formato e1? E2: e3 ocorre da seguinte maneira:

Primeiro, e1 é avaliado para um objeto o1. É um erro dinâmico se o tipo de tempo de execução o1 não for booleano. Se r for verdadeiro, o valor de c é o resultado da avaliação da expressão e2. Caso contrário, o valor de c é o resultado da avaliação da expressão e3.

Se e1 mostrar que uma variável local v possui o tipo T, o tipo de v é conhecido como T em e2, a menos que qualquer um dos seguintes seja verdadeiro:

• v é potencialmente mutado em e2,

• v é potencialmente mutado dentro de uma função diferente daquela em que v é declarado, ou

• v é acessado por uma função definida em e2 e v é potencialmente mutado em qualquer lugar no escopo de v.



É um erro em tempo de compilação se o tipo estático de e1 não puder ser atribuído ao bool. O tipo estático de c é o limite mínimo (19.10.2) do tipo estático de e2 e o tipo estático de e3.

16.25 Expressões If-null

ifNull



Uma expressão if-null avalia uma expressão e se o resultado é o objeto nulo (16.4), avalia outra.

hifNullExpressioni :: = hlogicalOrExpressioni (‘?? 'hlogicalOrExpressioni) *

Avaliação de uma expressão if-null e do formato e1 ?? e2 prossegue da seguinte maneira:

Avalie e1 para um objeto o. Se o não for o objeto nulo (16.4), e será avaliado como o. Caso contrário, avalie e2 para um objeto r e, em seguida, e avalie para r.

O tipo estático de e é o limite superior mínimo (19.10.2) do tipo estático de e1 e o tipo estático de e2.





16.26 Expressões booleanas lógicas

As expressões lógicas booleanas combinam objetos booleanos usando os operadores booleanos de conjunção e disjunção.

hlogicalOrExpressioni :: = hlogicalAndExpressioni ('||' hlogicalAndExpressioni) * hlogicalAndExpressioni :: = hequalityExpressioni ('&&' hequalityExpressioni) *

logicBooleanExpressions



Uma expressão booleana lógica é uma expressão de igualdade (16.27) ou uma chamada de um operador booleano lógico em uma expressão e1 com o argumento e2.

A avaliação de uma expressão booleana lógica b no formato e1 || e2 causa a avaliação de e1 em um objeto o1. É um erro dinâmico se o tipo de tempo de execução de o1 não for booleano. Se o1 for verdadeiro, o resultado da avaliação de b será verdadeiro, caso contrário, e2 será avaliado para um objeto o2. É um erro dinâmico se o tipo de tempo de execução de o2 não for booleano. Caso contrário, o resultado da avaliação de b é o2.





A avaliação de uma expressão booleana lógica b da forma e1 && e2 causa a avaliação de e1 produzindo um objeto o1. É um erro dinâmico se o tipo de tempo de execução de o1 não for booleano. Se o1 for falso, o resultado da avaliação de b será falso; caso contrário, e2 será avaliado para um objeto o2. É um erro dinâmico se o tipo de tempo de execução de o2 não for booleano. Caso contrário, o resultado da avaliação de b é o2.

Uma expressão booleana lógica b no formato e1 && e2 mostra que uma variável local v possui o tipo T se as duas condições a seguir forem válidas:

• E1 mostra que v possui o tipo T ou e2 mostra que v possui o tipo T.

• v não é modificado em e2 ou dentro de uma função diferente daquela em que v é declarado.



Se e1 mostrar que uma variável local v possui o tipo T, o tipo de v é conhecido como T em e2, a menos que qualquer um dos seguintes seja verdadeiro:

• v é potencialmente mutado em e1,

• v é potencialmente mutado em e2,

• v é potencialmente mutado dentro de uma função diferente daquela em que v é declarado, ou

• v é acessado por uma função definida em e2 e v é potencialmente mutado em qualquer lugar no escopo de v.



É umerro em tempo de compilação se o tipo estático de e1 não puder ser atribuído ao bool ou se o tipo estático de e2 não puder ser atribuído ao bool. O tipo estático de uma expressão booleana lógica é bool.
ni) +

hadditiveOperatori :: = '+'

| '-'

aditivoExpressões



Uma expressão aditiva é uma expressão multiplicativa (16.32) ou uma invocação de um operador aditivo em super ou em uma expressão e1, com o argumento e2.

Uma expressão aditiva da forma e1 op e2 é equivalente à invocação do método e1.op (e2). Uma expressão aditiva da forma super op e2 é equivalente à invocação do método super.op (e2).

O tipo estático de uma expressão aditiva é geralmente determinado pela assinatura dada na declaração do operador utilizado. No entanto, as invocações dos operadores + e - da classe int são tratadas especialmente pelo typechecker. O tipo estático de uma expressão e1 + e2 em que e1 tem o tipo estático int é int se o tipo estático de e2 for int e o dobro se o tipo estático de e2 for duplo. O tipo estático de uma expressão e1 - e2 em que e1 tem o tipo estático int é int se o tipo estático de e2 for int e o dobro se o tipo estático de e2 for duplo.





16.32 Expressões multiplicativas

Expressões multiplicativas invocam os operadores de multiplicação nos objetos.

hmultiplicativeExpressioni :: = hunaryExpressioni (hmultiplicativeOperatori hunaryExpressioni) * | super (hmultiplicativeOperatori hunaryExpressioni) +

hmultiplicativeOperatori :: = ‘* '

| ‘/’

| '%'

| '~ /'

multiplicativeExpressions



Uma expressão multiplicativa é uma expressão unária (16.33) ou uma invocação de um operador multiplicativo em super ou em uma expressão e1, com o argumento e2.

Uma expressão multiplicativa da forma e1 op e2 é equivalente à invocação do método e1.op (e2). Uma expressão multiplicativa da forma super op e2 é equivalente à invocação do método super.op (e2).

O tipo estático de uma expressão multiplicativa é geralmente determinado pela assinatura dada na declaração do operador usado. No entanto, as invocações dos operadores * e% da classe int são tratadas especialmente pelo typechecker. O tipo estático de uma expressão e1 ∗ e2 em que e1 possui o tipo estático int é int se





o tipo estático de e2 é int e duplo se o tipo estático de e2 for duplo. O tipo estático de uma expressão e1% e2 em que e1 possui o tipo estático int é int se o tipo estático de e2 for int e o dobro se o tipo estático de e2 for duplo.

16.33 Expressões unárias

Expressões unárias invocam operadores unários em objetos.

hunaryExpressioni :: = hprefixOperatori hunaryExpressioni | hawaitExpressioni

| hpostfixExpressioni

| (hminusOperatori | htildeOperatori) super

| hincrementOperatori hassignableExpressioni

hprefixOperatori :: = hminusOperatori

| hnegationOperatori | htildeOperatori hminusOperatori :: = '-' hnegationOperatori :: = '!' htildeOperatori :: = '' ~ '

unaryExpressions



Uma expressão unária é uma expressão postfix (16.35), uma expressão aguardada





(16.34) ou uma invocação de um operador de prefixo em uma expressão ou uma invocação de um operador unário em super ou em uma expressão e.

A expressão! E é equivalente à expressão e? False: true.

A avaliação de uma expressão da forma ++ e é equivalente a e + = 1. A avaliação de uma expressão da forma --e é equivalente a e- = 1.

Seja e uma expressão do formulário -l onde l é um literal inteiro (16,5) com valor inteiro numérico i e com o tipo de contexto estático T. Se double for atribuível a T e int não for atribuível a T, o tipo estático de e é duplo; caso contrário, o tipo estático de e é int.

Se o tipo estático de e é int, então e é avaliado para uma instância da classe int que representa o valor numérico -i. Se i é zero e a classe int pode representar um valor zero negativo, a instância resultante representa esse valor zero negativo. É um erro em tempo de compilação se o número inteiro -i não puder ser representado exatamente por uma instância de int.

Se o tipo estático de e for duplo, e será avaliado como uma instância da classe double que representa o valor numérico -i. Se i for zero, a instância resultante representa o valor duplo zero negativo, -0,0. É um erro de compilação se o número inteiro -i não puder ser representado exatamente por uma instância de double. Tratamos -l como se fosse um único literal inteiro com um valor numérico negativo. Não avaliamos l individualmente como expressão, nem nos preocupamos com seu tipo estático.

Qualquer outra expressão da forma op e é equivalente ao método invocado

e.op (). Uma expressão da forma op super é equivalente à invocação do método (16.21.3) super.op ().





16.34 Aguardar expressões waititExpressions


Uma expressão de espera permite que o código produza controle até que uma operação assíncrona (9) seja concluída.

hawaitExpressioni :: = aguarde hunaryExpressioni

A avaliação de uma expressão de espera a da forma aguardar e prossegue da seguinte forma: Primeiro, a expressão e é avaliada para um objeto o.

Então, se o não for uma instância de Future, seja f o resultado da criação de um novo objeto usando o construtor Future.value () com o como argumento; caso contrário, seja f.

Em seguida, o st





16.27 Igualdade Igualdade


Expressões de igualdade testam objetos quanto à igualdade.

hequalityExpressioni :: = hrelationalExpressioni (hequalityOperatori hrelationalExpressioni)? | super hequalityOperatori hrelationalExpressioni

hequalityOperatori :: = ‘== '

| '! ='

Uma expressão de igualdade é uma expressão relacional (16.28) ou a invocação de um operador de igualdade em super ou em uma expressão e1, com o argumento e2.

A avaliação de uma expressão de igualdade ee do formato e1 == e2 prossegue da seguinte forma:

• A expressão e1 é avaliada para um objeto o1.

• A expressão e2 é avaliada para um objeto o2.

• Se o1 ou o2 é o objeto nulo (16.4), ee avalia como true se o1 e o2 são o objeto nulo e false em caso contrário. De outra forma,

• avaliação de ee é equivalente à invocação do método o1. == (o2).



A avaliação de uma expressão de igualdade ee da forma super == e ocorre da seguinte forma:

• A expressão e é avaliada para um objeto o.

• Se este ou o é o objeto nulo (16.4), ee avalia como verdadeiro se este e o são o objeto nulo e falso caso contrário. De outra forma,

• avaliação de ee é equivalente à invocação do método super. == (o).



Como resultado da definição acima, os métodos '==' definidos pelo usuário podem assumir que seu argumento é não nulo e evitar o prelúdio padrão da placa da caldeira:

if (idêntico (nulo, arg)) retorna falso;

Outra implicação é que nunca é necessário usar o idêntico () para testar contra nulo, nem alguém deve se preocupar em escrever nulo == e ou e == null.

Uma expressão de igualdade do formato e1! = E2 é equivalente à expressão! (E1 == e2). Uma expressão de igualdade do formato super! = E é equivalente à expressão! (Super == e).

O tipo estático de uma expressão de igualdade é bool.

16.28 Expressões relacionais

Expressões relacionais invocam os operadores relacionais nos objetos.

hrelationalExpressioni :: = hbitwiseOrExpressioni

(htypeTesti | htypeCasti | hrelationalOperatori hbitwiseOrExpressioni)? | super hrelationalOperatori hbitwiseOrExpressioni

hrelationalOperatori :: = ‘> =’

| ">"

| '<='

| '<'

relationalExpressions



Uma expressão relacional é uma expressão bit a bit (16.29) ou uma chamada





de um operador relacional em super ou em uma expressão e1, com o argumento e2.

Uma expressão relacional do formato e1 op e2 é equivalente à invocação do método e1.op (e2). Uma expressão relacional da forma super op e2 é equivalente à invocação do método super.op (e2).

16.29 Expressões bit a bit

Expressões bit a bit invocam os operadores bit a bit nos objetos.

hbitwiseOrExpressioni :: = hbitwiseXorExpressioni ('| hbitwiseXorExpressioni) * | super ('| hbitwiseXorExpressioni) +

hbitwiseXorExpressioni :: = hbitwiseAndExpressioni (‘^ 'hbitwiseAndExpressioni) * | super (‘^ 'hbitwiseAndExpressioni) +

hbitwiseAndExpressioni :: = hshiftExpressioni ('&' hshiftExpressioni) * | super ('&' hshiftExpressioni) +

hbitwiseOperatori :: = "&"

| '^'

| '|'

bitwiseExpressions



Uma expressão bit a bit é uma expressão shift (16.30) ou uma invocação de um operador bit a bit em super ou em uma expressão e1, com o argumento e2.

Uma expressão bit a bit do formato e1 op e2 é equivalente à invocação do método e1.op (e2). Uma expressão bit a bit da forma super op e2 é equivalente à invocação do método super.op (e2).

Deveria ser óbvio que as regras de tipo estático para essas expressões são definidas pela equivalência acima, portanto, pelas regras de tipo para invocação de método e pelas assinaturas dos operadores no tipo e1. O mesmo ocorre em situações semelhantes ao longo desta especificação.





16.30 Turno

Expressões de deslocamento chamam os operadores de deslocamento nos objetos.

hshiftExpressioni :: = hadditiveExpressioni (hshiftOperatori hadditiveExpressioni) * | super (hshiftOperatori hadditiveExpressioni) +

hshiftOperatori :: = "<<"

| ‘>>’

| '>>>'

mudança



Uma expressão shift é uma expressão aditiva (16.31) ou uma chamada de um operador shift em super ou em uma expressão e1, com o argumento e2.

Uma expressão de deslocamento do formato e1 op e2 é equivalente à invocação do método e1.op (e2). Uma expressão de deslocamento da forma super op e2 é equivalente à invocação do método super.op (e2).
Observe que essa definição implica ordem de avaliação da esquerda para a direita entre as expressões shift: [e1 << e2 << e3] é avaliado como [(e1 << e2).  (e3) que é equivalente a (e1 << e2) << e3 O mesmo vale para expressões aditivas e multiplicativas.]



16.31 Expressões aditivas

Expressões aditivas chamam os operadores de adição nos objetos.

hadditiveExpressioni :: = hmultiplicativeExpressioni

(hadOperatori hmultiplicativeExpressioni) *

| super (hadditiveOperatori hmultiplicativeExpressioni a resma associada ao loop for assíncrono (17.6.3), se houver, está em pausa. A chamada atual do corpo da função que encerra imediatamente a é suspensa até que f seja concluído. Em algum momento após a conclusão de f, o controle retorna à chamada atual. Se f foi concluído com um erro xe o rastreamento de pilha t, a lança x e t (16.1). Se f for concluído com o valor v, a será avaliado como v.

Normalmente, é um erro em tempo de compilação se a função que encerra imediatamente um não for declarada assíncrona. Por exemplo, pode ser um erro de sintaxe, pois aguardar não tem significado especial no contexto de uma função normal. No entanto, wait (e) também pode ser uma chamada de função.

Uma expressão de espera não tem significado em uma função síncrona. Se essa função suspendesse a espera de um futuro, não seria mais síncrona.

Não é um erro em tempo de compilação se o tipo de e não for um subtipo de Futuro. As ferramentas podem optar por dar uma dica nesses casos.

O tipo estático de a é achatado (T) (achatado () é definido na seção 16.13) onde T é o tipo estático de e.





16.35 Expressões do Postfix postfixExpressions


As expressões postfix invocam os operadores postfix nos objetos.

hpostfixExpressioni :: = hassignableExpressioni hpostfixOperatori

| hconstructorInvocationi hselectori * | hprimaryi hselectori * hpostfixOperatori :: = hincrementOperatori

hconstructorInvocationi :: = htypeNamei htypeArgumentsi '.' hidentifieri hargumentsi

hselectori :: = hassignableSelectori

| hargumentParti

hincrementOperatori :: = '++'

| '-'

Uma expressão postfix é uma expressão primária; uma função, método ou chamada de getter; uma invocação de um construtor nomeado; ou uma invocação de um operador postfix em uma expressão e. Todos, exceto os dois últimos, são especificados em outro lugar.

Case hConstructor Invocationsi. Considere uma hconstructorInvocationi no formato n <typeArguments> .id (argumentos). Se n não denota uma classe C que declara um construtor chamado C.id, ocorre um erro em tempo de compilação.

Caso contrário, se e ocorrer em um contexto constante (16.3.1), e será tratado como const e, e se não ocorrer em um contexto constante, e será tratado como novo e.

Observe que e não pode ser outra coisa senão uma criação de instância (constante ou não) porque e fornece argumentos de tipo reais para n, que não são suportados se n denota um prefixo de biblioteca, e se e é uma invocação de método estático.

Caso hv ++, v - i. Considere uma expressão postfix e no formato v op, em que v é um identificador e op é '++' ou '-'. Ocorre um erro em tempo de compilação, a menos que v indique uma variável ou v indique um getter e haja um setter associado v =. Seja T o tipo estático da variável v ou o tipo de retorno do getter. Um erro em tempo de compilação ocorre se T não é dinâmico e T não possui um operador '+' (quando op é '++') ou operador '-' (quando op é '-') ou se o tipo de retorno desse operador não é atribuível à variável, respectivamente, o tipo de argumento do setter. Um erro em tempo de compilação ocorre se int não for atribuível ao tipo de parâmetro do referido operador. O tipo estático de e é T.

A avaliação de uma expressão postfix e no formato v ++, respectivamente v--, em que v é um identificador, procede da seguinte forma: Avalie v para um objeto r e seja y uma nova variável vinculada a r. Avalie v = y + 1, respectivamente, v = y - 1. Então, e avalia para r.

O item acima garante que, se a avaliação envolver um getter, ela será chamada exatamente uma vez. Da mesma forma nos casos abaixo.

Caso hC.v ++, C.v - i. Considere uma expressão postfix e no formato C.v op, em que C é um tipo literal e op é '++' ou '-'. Um erro em tempo de compilação ocorre a menos que C.v denuncie um getter estático e haja um setter estático associado v = (possivelmente induzido implicitamente por uma variável estática). Seja T o tipo de retorno do referido getter. Um erro em tempo de compilação ocorre se T não é dinâmico e T não possui um operador '+' (quando op é '++') ou operador '-' (quando op é '-') ou se o tipo de retorno desse operador não é atribuível ao tipo de argumento do setter. Um erro em tempo de compilação ocorre se int não for atribuível ao tipo de parâmetro do referido operador. O tipo estático de e é T.

A avaliação de uma expressão postfix e da forma C.v ++, respectivamente C.v - em que C é um tipo literal, procede da seguinte maneira: Avalie C.v para um objeto r e deixe que seja uma variável nova vinculada a r. Avalie C.v = y + 1 respectivamente C.v

= y - 1. Então e avalia como r.

Caso he1.v ++, e1.v - i. Considere uma expressão postfix e no formato e1.v op, em que op é '++' ou '-'. Seja S o tipo estático de e1. Ocorre um erro em tempo de compilação, a menos que S tenha um getter chamado v e um setter chamado v = (possivelmente induzido implicitamente por uma variável de instância). Seja T o tipo de retorno do referido getter. Um erro em tempo de compilação ocorre se T não é dinâmico e T não possui um operador '+' (quando op é '++') ou operador '-' (quando op é '-') ou se o tipo de retorno desse operador não é atribuível ao tipo de argumento do setter. Um erro em tempo de compilação ocorre se int não for atribuível ao patipo rameter do referido operador. O tipo estático de e é T.

A avaliação de uma expressão pós-fixada e do formato e1.v ++, respectivamente, e1.v-prossegue da seguinte forma: Avalie e1 para um objeto u e deixe x ser uma variável nova vinculada a u. Avalie x.v para um objeto r e deixe y ser uma variável nova vinculada a r. Avalie x.v = y + 1 respectivamente x.v = y - 1. Então e avalia para r.

Caso he1 [e2] ++, e1 [e2] - i. Considere uma expressão postfix e no formato e1 [e2] op, em que op é '++' ou '-'. Seja S1 o tipo estático de e1 e S2 seja o tipo estático de e2. Um erro em tempo de compilação ocorre, a menos que S1 tenha um operador '[]' e um operador '[] ='. Seja T o tipo de retorno do primeiro. Um erro de compilação ocorre a menos que S2 seja atribuível ao primeiro tipo de parâmetro do referido operador '[] ='. Um erro em tempo de compilação ocorre se T não é dinâmico e T não possui um operador '+' (quando op é '++') ou operador '-' (quando op é '-') ou se o tipo de retorno deste operador não é atribuível ao segundo tipo de argumento do referido operador '[] ='. Um erro em tempo de compilação ocorre se passar o literal inteiro 1 como argumento para o operador '+' ou '-' seria um erro. O tipo estático de e é T.

A avaliação de uma expressão pós-fixada e do formato e1 [e2] ++ respectivamente e1 [e2] prossegue da seguinte maneira: Avalie e1 para um objeto u e e2 para um objeto v. Seja a e i novas variáveis ​​vinculadas a u e v respectivamente. Avalie a [i] para um objeto r e seja y uma nova variável vinculada a r. Avalie a [i] = y + 1 respectivamente a [i] = y - 1. Em seguida, e avalia como r.

Caso he1? .V ++, e1? .V - i. Considere uma expressão postfix e no formato e1? .V op, em que op é '++' ou '-'. Exatamente os mesmos erros em tempo de compilação que seriam causados ​​por e1.v op também são gerados no caso de e1? .V op. O tipo estático de e é o tipo estático de e1.v.

A avaliação de uma expressão pós-fixada e do formato e1? .V ++, respectivamente, e1? .V-prossegue da seguinte forma: Se e1 for um tipo literal, a avaliação de e será equivalente à avaliação de e1.v ++, respectivamente, e1.v--. Caso contrário, avalie e1 para um objeto u. se u é o objeto nulo, e é avaliado para o objeto nulo (16.4). Caso contrário, seja x uma nova variável vinculada a u. Avalie x.v ++ respectivamente x.v-- para um objeto o.

Então e avalia como o.





16.36 Expressões atribuíveis assignableExpressions


Expressões atribuíveis são expressões que podem aparecer no lado esquerdo de uma atribuição. Esta seção descreve como avaliar essas expressões quando elas não constituem o lado esquerdo completo de uma tarefa.

Obviamente, se as expressões atribuíveis sempre aparecessem no lado esquerdo, não seria necessário seu valor e as regras para avaliá-las seriam desnecessárias. No entanto, expressões atribuíveis podem ser subexpressões de outras expressões e, portanto, devem ser avaliadas.

hassignableExpressioni :: = hprimaryi hassignableSelectorParti

| super hunconditionalAssignableSelectori

| hconstructorInvocationi hassignableSelectorParti + identificador hassignableSelectorParti :: = hargumentParti * hassignableSelectori

hunconditionalAssignableSelectori :: = '[' 'hexpressioni' ']' | Hidentifieri

hassignableSelectori :: = hunconditionalAssignableSelectori | Hidentifieri

Uma expressão atribuível é:

• um identificador.

• Uma chamada (possivelmente condicional) de um getter (10.2) ou operador de acesso à lista em uma expressão e.

• Uma chamada de um operador de acesso getter ou lista no super.



Uma expressão atribuível do ID do formulário é avaliada como uma expressão identificadora (16.37).

Uma expressão atribuível do formato e.id ou e? .Id é avaliada como uma extração de propriedade (16.22).

Uma expressão atribuível do formato e1 [e2] é avaliada como uma invocação de método do método do operador [] em e1 com o argumento e2.

Uma expressão atribuível do formulário super.id é avaliada como uma extração de propriedade.

A avaliação de uma expressão atribuível da forma super [e2] é equivalente à avaliação da invocação do método super. [] (E2).







