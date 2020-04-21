<h1 align="center">
 Especificação da linguagem de programação Dart
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

<h4>
 1. Escopo 
 </h4>
 
 <p>Este padrão Ecma especifica a sintaxe e a semântica da linguagem de programação do Dart. Ele não especifica as APIs das bibliotecas Dart, exceto se os elementos da biblioteca forem essenciais para o funcionamento correto da linguagem (por exemplo, a existência de classObject com métodos como **noSuchMethod**, **runtimeType**)
 </p>
 
 
 
 
