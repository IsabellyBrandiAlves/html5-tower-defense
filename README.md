HTML5 Jogo de Tower Defense
==================================================

 * Author: oldj
 * Email: oldj.wu@gmail.com
 * Blog: http://oldj.net/
 * Source: https://github.com/oldj/html5-tower-defense


 Corrida：
----------

entrar src ou build diretório，Navegador（como IE9）aberto td.html Para executar este jogo.
ou veja[Demonstração Online](http://oldj.net/static/html5-tower-defense/td.html).

 explicação：
----------

 1. Este jogo é inteiramente em HTML5 / JavaScript / Implementação CSS, não usar o Flash, tecnologia Silverlight.
 2. Esta versão não utilizar fotos de todos os itens do jogo são desenhados usando HTML5.
 3. Esta é uma parte da versão local do IE9 para fazer um especial otimizado para ser executado sob IE9 normal.


 Diretório：
----------

    /build          Arquivos compactados pode ser publicado
    /screenshorts   screenshots
    /src            fonte
        /css        stylesheet
        /js         Arquivo de origem JavaScripts
    /tools          Gadgets, o script
    /README.md      este documento


 Métodos Cheating：
----------

Para facilitar os testes, o jogo construiu vários métodos de trapaça, como se segue：

 1. Aumente 1000000 Money:javascript:_TD.cheat="money+";void(0);
 2. Dificuldade de duplicação:javascript:_TD.cheat="difficulty+";void(0);
 3. Dificuldade para metade:javascript:_TD.cheat="difficulty-";void(0);
 4. Recuperação de valor de vida:javascript:_TD.cheat="life+";void(0);
 5. O valor da vida reduzido ao mínimo:javascript:_TD.cheat="life-";void(0);

Na barra de endereços do navegador digite o "javascript: ...;" acima e pressione Enter, você pode conseguir fazer a trapaça.

Note-se que o método acima de fazer a trapaça é principalmente para o design de teste, o curso normal do jogo, por favor, use discrição, caso contrário ele pode reduzir o jogo divertido.


  Histórico de atualização：
----------

 --2015-09-06 Tela retina Suporte.
  --2011-01-01 Ajuste os parâmetros, mas também com os amigos sugeriu adicionar verificações para novos edifícios, proibir a utilização do edifício cercado pelo monstro (v0.1.14).
  --2010-12-29 De acordo com amigos sugeriu a adição de função de auto recuperação da vida (a cada 5 recuperação ondas vida 05:00, 10 ondas cada vida recuperação 10:00). Ajustar os parâmetros, reduzindo a faixa de arma laser, e aumentar o poder de metralhadoras pesadas (v0.1.12).
  --2010-12-18 Adicionar uma nova arma "arma a laser" (v0.1.8.0).
  --2010-12-12 Pause imagem recurso versão desenvolvimento do ramo, continuar a otimizar, desenvolver a versão círculo (v0.1.7.0).
  --2010-11-28 Primeira versão recurso de imagem (v0.2.1.3267).
  --2010-11-23 Lançamento [Círculo Edition (v0.1.6.2970)] (http://oldj.net/article/html5-td-circle-version/).
  --2010-11-14 Online lançou a primeira versão.
  --2010-11-11 Comece a escrever este jogo.


 Plano de Desenvolvimento：
----------

 - Adicionar uma nova arma, "canhão", características: explodir quando atingido por um monstro, fazendo com que a superfície de ataque.
  - Adicione um editor de níveis.
  - Adicionar a função de salvar seu progresso.
