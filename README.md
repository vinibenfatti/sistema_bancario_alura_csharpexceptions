# sistema_bancario_alura_csharpexceptions

Conceitos e aprendizagens abordados neste projeto:

-Como funciona a pilha de chamadas (CallStack) no .NET;

-Propagar erros com retorno de métodos não é correto;

-Exceções do .NET;

-Blocos try/catch;

-Propriedades importantes a Message e StackTrace.

-O bloco try pode acompanhar vários blocos catch;

-A CLR visita os blocos catch em ordem, de cima para baixo. Por esta razão, os tipos de exceção mais específicos devem estar no começo;

-A instrução throw;, dentro de um bloco catch, relança uma exceção.

-Campos somente leitura com o modificador readonly;

-Propriedades somente leitura, com omissão do setter;

-O operador nameof();

-A classe de exceção ArgumentException, seus construtores e propriedades;

-Convenções de nomeação de exceções;

-Construtores comuns de exceções;

-Como criar uma exceção mais rica.

-As diferenças entre throw; e throw ex;

-Como a CLR preenche a propriedade StackTrace;

-O padrão de inner exceptions;

-O terceiro construtor que as exceções devem ter: (string mensagem, Exception excecaoInterna);

-O bloco finally;

-Não é obrigatório o bloco catch quando temos um finally;

-Como é usado o bloco using e como ele funciona;

-A interface IDisposable.














