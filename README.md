# diojs
 Programação para internet com JavaScript - Digital Innovation One

 Qual a melhor definição para o DOM (Document Object Model) no contexto de páginas de internet?
DOM é o modelo de padrão e interface que define propriedades, métodos e eventos de elementos.


Analise o código abaixo e responda a alternativa correta;
/*
var lista  = [nome: “rosa” , “cravo” , “tulipa”, “margarida”]
console.log(lista[2]);
*/
Qual o resultado do comando acima?
Não vai aparecer no console, pois é um comentário.



Veja o código abaixo:
var lista = [“Alemanha”, “Inglaterra”, “Escócia”]/
lista.push(“Polônia”);
lista.pop(“Inglaterra”);
Como ficará a listagem desse comando?
O comando não pode ser executado, pois o comando que inicia um comentário está faltando um caractere.


Dia 1º de Abril é o Dia da Mentira. Imagine que hoje seja esse dia (ou por sorte seja mesmo), qual código abaixo retornaria uma string com o dia e o mês(numérico) corretamente no console?
console.log("Hoje é " + d.getDate() + "/" + (d.getMonth()+1));



Analise o código abaixo:
Alert (“Digital Innovation One:” + formacoes)
Assinale a alternativa correta:
O sinal "+" antes de uma string concatena. Antes de inteiros, ele soma.


Considere a variável count de valor 0. Ela passará pelo laço de repetição com "while(count < 5)" imprimindo no console a sequência de números "0, 1, 2, 3, 4, 5". Sendo assim, qual comando abaixo usando "for" seria compatível com este comando "while"?
for(count=0; count <= 5; count++)

A história da chapeuzinho vermelho é umas das histórias mais conhecidas no mundo e possui inúmeras adaptações, mas a história básica cita que a protagonista, chamada de "Chapeuzinho Vermelho", tem um trajeto da sua casa até a casa do Vovó expresso na seguinte variável chamada trajeto:
["mãe", "floresta", "avó"]. 
Qual alternativa abaixo está correta?
O comando trajeto.join(" > ") retorna a string "mãe > floresta > avó".

Considere que você possua o arquivo index.html e você precisa inserir um arquivo de JavaScript chamado "heroi.js" que está em uma pasta chamada "personagens". Qual das alternativas abaixo faria isso da forma correta?
<script src="personagens/heroi.js" type="text/javascript"></script>

Uma ferramenta que não é exclusiva do navegador Google Chrome é a visualização da estrutura da página, os arquivos carregados, mensagens do desenvolvedor, debug e entre outras funções. Quanto a funcionalidade de gerar mensagens do desenvolvedor, considere que uma variável contém o valor "Simplicity is the ultimate sophistication.", uma segunda variável contém o valor "Leonardo da Vinci:". No caso se precisar escrever no console a primeira varíavel, depois a segunda e acrescentar, de forma válida, o seguinte trecho "1425-1519", qual alternativa abaixo está correta?
console.log(var1 + var2 + 1425 + "-" + 1519);



__________


Você está programando a tela de um jogo. Existem 3 opções de personagens para você escolher e eles são de raças diferentes, sendo um humano, um elfo e um orc. Sempre que você selecionar um personagem, uma tag <p> deve escrever os poderes específicos de cada raça. Sendo assim, avalie as alternativas abaixo e selecione a mais coerente para essa funcionalidade:
<select onchange="mostrarPoderes(this)"><option value="Humano"></option><option value="Elfo"></option><option value="Orc"></option></select>


I- O comando  window.open abre a página em outra janela.
II – O comando window.location.href abre a página em outra aba. 
III – O redirecionamento permite que o usuário saia da página atual e vá para outra, seja através da aba ou da janela. 
Apenas I e III está corretas.


Você precisa criar uma tela na qual possua uma espécie de vitrine com vários objetos, cada objeto é um jogo de tabuleiro. A imagem do objeto é a capa da embalagem do jogo. Ao passar o mouse, a pessoa consegue ver o verso da embalagem, mas ao tirar o mouse volta para a capa da embalagem. Ao clicar, a pessoa pode ver fotos do conteúdo do jogo. Sendo assim, qual opção abaixo é mais adequada para o desenvolvimento da vitrine?
<button id="eldritch_horror" onclick="detalhes(this)" onmouseover="mousesobre(this)" onmouseout="mousefora(this)">Eldritch Horror</button>

Assinale a alternativa que melhor define a ideia de parâmetros de uma função.
Os parâmetros de uma função são passados durante a chamada da função, podendo cada uma trazer valores de string, inteiro, arrays e entre outros.

Qual a função do evento OnMouseOver?
Definir a ação quando o usuário passa o mouse sobre o elemento.

Se tratando de funções, assinale a alternativa errada:
Valores podem ser passados para uma função, que retorna uma variável.


Assinale a alternativa que melhor define a diferença entre variável global e local.
A variável local é declarada dentro de uma função, enquanto a variável global é declarada fora da função e pode ser usada dentro da função.


Na estrutura HTML você observa o seguinte comando:
<body onload="carregou()">
Qual alternativa abaixo representa a melhor possibilidade?
A função "carregou" será chamada assim que a página web for carregada, mas seu conteúdo pode ser diverso.


Qual o objetivo do evento onChange?
É disparado quando o valor de um elemento é mudado, como em radiobuttons e checkboxes por exemplo.


Você tem uma página de web com vários bichos de pelúcia e quer presentear alguém com um personagem do desenho animado "Ursinhos Carinhosos". Para isso você usa o seguinte código JavaScript:
document.getElementById("selecionado").innerHTML = "Escolheu: " + nome_personagem.
Qual alternativa abaixo apresenta uma tag HTML com parâmetros corretos e que se relaciona corretamente a declaração JavaScript?
<button id="coração_valente" onclick="selecionou()">Coração Valente</button>