# Guia de tradução da documentação do React

Este guia serve para ajudar no projeto de tradução da documentação do React para Português Brasileiro.

O projeto está acontecendo no [Crowdin](https://crowdin.com/project/react) e qualquer pessoa pode contribuir.

As sugestões a seguir não são obrigatórias, são apenas uma forma de juntarmos em um lugar a discussão de quais as melhores traduções para determinados termos.

Também deve se levar em conta o contexto, talvez a sugestão aqui não se aplique em todas as ocorrências.

Dessa forma podemos ter uma tradução mais correta e consistente.

## Como Sugerir uma Tradução

Você pode abrir uma [Issue](https://github.com/mdapper/react-translation-guide-ptbr/issues) aqui no repositório com uma nova sugestão, ou correção de um dos termos abaixo.

Pode também abrir diretamente um [Pull Request](https://github.com/mdapper/react-translation-guide-ptbr/pulls) se preferir com sua sugestão, neste podemos discutir sobre a melhor tradução.


## Instruções Gerais

* Blocos de código não devem ser traduzidos. Deve-se usar o botão "Copy Source" do Crowdin que vai copiar o código original, e após isso salvar.
* Comentários em blocos de código **devem** ser traduzidos.
* Em caso de dúvida, manter parte inalterada (em inglês) dentro de aspas, por exemplo: "props", "state", "merge", etc.
* Não traduzir elementos quando fazem referência direta a sintaxe do JavaScript, por exemplo: string, array, boolean, arrow function, etc.
* Não traduzir elementos quando fazem referência direta a tags HTML, por exemplo: input, button, textarea, section, header, etc.
* Nos títulos tentar corresponder as letras maiúsculas sempre que possível, por exemplo: "Alternatives to Controlled Components" deve ficar "Alternativas para Componentes Controlados", e não como muitas vezes é sugerido "Alternativas para componentes controlados".


## Sugestões de Tradução

#### A

* App: App
* Application: Aplicação
* Argument: Argumento
* Assignment: Atribuição
* Asynchronous: Assíncrono


#### B

* Batch: Lote / Processar em lote
* Bind: Bind
* Boilerplate: Boilerplate
* Browser: Navegador
* Bug: Bug
* Build (no sentido de compilar o código): Build
* Build: Construir
* Built-in: Nativo


#### C

* Call: Chama
* Callback Function: Função de Callback
* Children: Filhos
* Closure: Closure
* Code snippet: Trecho de código
* Codebase: Base de código
* Coercion: Coerção
* Compilation: Compilação
* Component: Componente
* Constructor: Construtor
* Controlled Components: Componentes Controlados
* Cross-browser: Entre Navegadores
* Cross-Cutting Concerns: Características Transversais
* Curly Braces: Chaves


#### D

* Debug: Debugar
* Decorator: Decorador - não traduzir quando ser referir ao recurso experimental da linguagem JavaScript chamado "decorator"
* Delegation: Delegação
* Deprecated: Descontinuada / Depreciada
* Display: Exibir
* Dynamic typing: Tipagem dinâmica


#### E

* Elements: Elementos
* Embedded: Incorporar
* Engine: Motor
* Enhanced: Melhorado / Aprimorado
* Enhancer-style: Aprimorador de estilo
* Environment: Ambiente
* Equality: Igualdade
* Evaluate: Avaliado
* Event: Evento
* Expressions: Expressões


#### F

* Features: Funcionalidades
* Floating-point: Ponto flutuante
* Flow: Flui - não traduzir caso se refira a biblioteca *Flow*
* Framework: Framework
* Function: Função - a menos que esteja se referindo diretamente ao termo *function* da linguagem JavaScript
* Functional Component: Componente Funcional


#### G

* Garbage Collector: Coletor de lixo


#### H

* Handler: Receptor
* Handling: Manipular
* Hoisting: Hoisting
* Hooks: Ganchos
* Higher-Order Components: Componentes de Ordem Superior (do inglês higher-order component, ou HOC) - Manter o uso da sigla em inglês **HOC** onde esta ocorre, mas em toda nova página que aparecer, na primeira ocorrência usar a tradução em português com a explicação do termo original entre parênteses, conforme vemos aqui.


#### I

* Immutable: Imutável - não traduzir caso se refira à biblioteca *Imutable.js*
* Inline: Inline
* Input: Input (entrada, início)
* Invoked: Invocada


#### J


#### K

* Keyword: Palavra-chave
* Key: Key (ou chave)

#### L

* Libraries: Bibliotecas
* Lifecycle: Ciclo de Vida
* Lifting State Up: Levantando o Estado
* Linter: Linter
* Log: Loga
* Look-up: Consulta


#### M

* Maintainable: Fácil de manter
* Markup: Marcação
* Merged: Mescladas - sugira caso tenha uma sugestão melhor
* Method: Método
* Minifier: Minificador
* Mock: Molde ou Modelo / Simulação
* Modules: Módulos
* Mounting: Montagem


#### N

* Nested Scopes: Escopos aninhados
* Nesting: Aninhamento
* Node: Nó - não traduzir caso se refira ao *Node.js*


#### O

* Operators: Operadores
* Output: Output (saída, retorno, valor)


#### P

* Parameter: Parâmetro
* Parent: Pai
* Parsing: Análise
* Pipe: Canalizar
* Plugin: Plugin
* Polyfill: Polyfill
* Prototype: Protótipo
* Package: Package - Não traduzir.

#### Q

* Quotes: aspas


#### R

* Read-Only: Somente Leitura
* Render: Renderizar - Não traduzir quando for uma referência direta para o método `render()` do React.
* Rendered: Renderizado
* Return: Retorna
* Root: Raiz
* Rule of thumb: Regra de ouro
* Run: Rodar / Executar


#### S

* Scope: Escopo
* Screen: Tela
* Semicolon: Ponto e vírgula
* Shallow: Superficial
* Single source of truth: Única fonte de verdade
* Snippet: Trecho (de código)
* Stack: Stack
* State: Estado - não traduzir quando for uma referência direta ao atributo "state" do React.
* Stateful: Com Estado
* Stateless: Sem Estado
* Statements: Declarações
* Static typing: Tipagem estática
* Strict Mode: Modo estrito (strict mode)


#### T

* Tab: Aba
* Tag: Tag
* Template: Template
* Throws: Lança
* Token: Token
* Tokenizer: Tokenizador
* Tokenizing: Tokenização
* Transpiled: Transpilada
* Transpiling: Transpilar
* Tree: Árvore
* TypedArrays: Arrays Tipados
* Types: Tipos


#### U

* UI: UI (interface do usuário, em inglês) - fazer isso apenas na **primeira ocorrência** na página que estiver traduzindo, depois usar apenas **UI**
* Uncontrolled components: Componentes não controlados
* Unmounting: Desmontar
* Unsigned: Não Sinalizado
* Update: Atualizar


#### V

* Variable: Variável
* View: View


#### W

* Wrap: Encapsular


#### X


#### Y


#### Z
