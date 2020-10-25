Adicionando/Editando
====================

Adicionando Cartões e Notas
---------------------------

Lembre-se de que vimos na seção [Começando](getting-started.md) que no Anki nós
adicionamos notas ao invés de cartões, e que ele mesmo se encarrega de adicionar
esses cartões para a gente. Clique em 'Adicionar', na janela principal, e a
janela Adicionar Notas irá aparecer.

No canto superior esquerdo desta janela podemos verificar qual tipo de nota
está atualmente selecionada. Se estiver mostrando um outro tipo de nota que não
o tipo "Básico", então você deve ter adicionado algum outro modelo de nota
quando baixou algum baralho compartilhado. O texto abaixo assume que o tipo de
nota "Básico" está selecionado.

No canto superior direito desta janela podemos ver em qual baralho os novos
cartões serão adicionados. Se você quiser adicionar cartões a um novo baralho,
você precisa clicar no nome do baralho atualmente selecionado, e, então,
pressionar o botão "Adicionar".

Embaixo do tipo de nota, você verá alguns botões e uma área chamada "Frente" e
"Verso". Frente e Verso são chamados 'campos', e você pode adicionar, remover ou
renomear estes campos clicando no botão "Campos..." acima.

Abaixo dos campos existe uma outra área, chamada de "Etiquetas". Etiquetas são
rótulos que você pode adicionar às suas notas, dessa forma tanto a tarefa de
organizar a sua coleção quanto encontrar notas específicas fica mais fácil. Você
pode deixar o campo de Etiquetas em branco se desejar, ou adicionar uma ou mais
delas. Etiquetas são separadas por um espaço em branco. Se a área das etiquetas
contêm o seguinte valor:

    vocabulário checar_com_o_professor

…então a nota que você adicionar terá duas etiquetas.

Depois que você tiver adicionado algum texto nos campos Frente e Verso, você
pode clicar no botão "Adicionar" ou apertar Ctrl+Enter (Command+Enter no Mac)
para adicionar essa nota à sua coleção. Após isso, um cartão também será criado
e colocado no baralho que você selecionou. Se você quiser editar um cartão já
adicionado, pode clicar no botão "Histórico" para procurá-lo. O cartão
selecionado abrirá no [navegador](browsing.md).

O Anki verifica o primeiro campo por valores que sejam únicos. Dessa forma, ele
irá avisar caso você adicione dois cartões com o campo Frente contendo o texto
"maçã" (por exemplo). A verificação por unicidade é limitada ao atual tipo de
nota selecionada. Portanto, se você estiver estudando vários idiomas, dois
cartões com o mesmo texto no campo Frente não serão considerados duplicados
desde que você tenha diferentes tipos de notas para cada idioma.

O Anki não checa, automaticamente, por duplicatas em outros campos por razões de
eficiência, mas no navegador existe a função "Encontrar Duplicatas" que você
pode executar de forma periódica.

Para mais informações quanto aos botões que estão entre o tipo de nota e os
campos de texto, por favor veja a seção [editor](editing.md).

Pessoas diferentes gostam de revisar de maneiras diferentes, mas existem alguns
conceitos gerais que devem ser mantidos em mente. Uma excelente introdução é
[este artigo (em Inglês)](http://www.supermemo.com/articles/20rules.htm) no site do
SuperMemo. Em particular:

-   **Mantenha simples**: Quão mais sucintos forem os seus cartões,
    mais fáceis eles serão para revisar. Talvez você seja tentado a
    incluir várias e várias informações adicionais "só para o caso de
    precisar no futuro", mas dessa forma as revisões rapidamente se
    tornarão um fardo.

-   **Não memorize se não entendeu**: Se você estiver estudando um
    idioma, tente evitar longas listas de palavras. A melhor forma de
    aprender um idioma é com o contexto, o que significa ver essas
    palavras sendo usadas em uma frase. Semelhantemente, imagine que
    você está estudando uma matéria de programação. Se você tentar
    memorizar o mundo de acrônimos que existem de uma só vez, achará
    que é muito difícil fazer progresso. Por outro lado, se você for
    no seu ritmo, levando o tempo que for necessário para entender o
    _conceito_ por trás desses acrônimos, o processo de aprendizagem
    se tornará muito mais fácil.

Adicionando um Tipo de Nota
---------------------------

Embora os tipos básicos de notas sejam suficientes para cartões simples com
apenas uma palavra ou frase em cada lado, assim que você se encontrar querendo
incluir mais do que uma informação na frente ou no verso, é melhor separar essas
informações em múltiplos campos de texto.

Talvez você se pegue pensando "mas eu só quero um cartão, então por que
simplesmente não incluo o áudio, uma imagem, uma dica e a tradução no campo
Frente?". Bem, se você prefere fazer dessa maneira, ok. Mas a desvantagem desse
método é que toda a informação está presa no mesmo lugar. Se você quisesse
ordenar seus cartões pela dica, você não seria capaz de fazê-lo por que ela está
misturada a outros conteúdos. Você também não seria capaz de fazer coisas como
mover o áudio da frente para o verso do cartão, exceto pelo laborioso processo
de copiar e colar essa informação para cada nota individualmente. Ao manter as
informações em campos separados, você torna muito mais fácil o processo de
ajustar o modelo dos seus cartões no futuro.

Para criar um novo tipo de nota, selecione, na tela principal do Anki,
Ferramentas → Gerenciar Tipos de Notas. Após isso, clique em "Adicionar" para
adicionar um novo tipo de nota. Você verá agora uma nova tela que apresenta
tipos de notas preexistentes nas quais você pode se basear para criar o novo
modelo desejado. "Adicionar" significa criar um novo tipo de nota com base em
uma já existente por padrão no Anki. "Duplicar" significa criar um novo tipo de
nota com base em uma já existente na sua coleção. Por exemplo, se você já
tivesse criado o tipo de nota "Vocabulário - Francês", você poderia duplicá-lo
caso desejasse, posteriormente, criar o tipo de nota "Vocabulário - Alemão".

Depois de selecionar OK, você será perguntado sobre qual nome deseja dar ao novo
tipo de nota. O assunto da matéria que você está estudando é uma boa escolha
aqui - coisas como "Japonês", "Curiosidades", e assim por diante. Uma vez que
tiver escolhido um nome, feche a janela Tipos de Notas, e você voltará à janela
Adicionar.

Personalizando Campos
---------------------

Para personalizar campos, clique no botão "Campos…" quando estiver na janela de
Adicionar ou Editar uma nota. Você também pode fazê-lo abrindo a janela
Gerenciar Tipos de Notas, escolher a nota que deseja editar e então clicar no
botão "Campos…".

Você pode adicionar, excluir, ou renomear campos clicando nos botões
apropriados. Para mudar a ordem na qual os campos aparecem nessa janela de
diálogo e também na janela de adicionar notas, você pode usar o botão
"Reposicionar", que perguntará em qual posição você deseja que o campo
selecionado esteja. Então, por exemplo, se você quiser que o campo selecionado
seja o primeiro campo da nota, digite "1" e aperte OK.

Não use 'Tags', 'Type', 'Deck', 'Card', ou 'FrontSide' como nome de campos, pois
eles são [campos especiais](templates/fields.md#special-fields) e não
funcionarão corretamente.

As opções na parte inferior da janela permitem que você edite várias
propriedades dos campos que serão usadas quando estiver adicionando ou editando
cartões. Entretanto, este 'não' é o local que você usa para personalizar a
aparência dos seus cartões quando estiver revisando. Para isso, por favor veja
[modelos](templates/intro.md).

**Fonte de Edição** permite que você customize a fonte e tamanho usados quando
estiver editando notas. Isso é útil se você quiser colocar informações não tão
importantes em um tamanho menor, ou se quiser aumentar o tamanho de caracteres
estrangeiros que são difícies de ler. As mudanças que você fizer aqui não
afetarão como os cartões aparecerão enquanto estiver revisando: para fazer isso,
por favor veja a seção [modelos](templates/intro.md). Contudo, se você tiver
habilitado a função de "escrever a resposta", o texto que você escrever usará
sim o tamanho de fonte aqui especificado. (Para informações sobre como mudar a
formatação de texto usada quando estiver escrevendo a resposta, por favor veja
seção [checando a resposta](templates/fields.md#checking-your-answer).)

**Classificar os cartões no Painel por este campo** diz ao Anki para mostrar
este campo na coluna "Classificar Campo" do painel. Você pode usar isso para
ordenar os cartões por campo. Somente um campo por vez pode ser usado para esta
funcionalidade de classificação.

Quando **Não apagar depois de adicionar** estiver selecionado, o Anki não
apagará o conteúdo deste campo após a nota ser adicionada. Se você se pegar
adicionando o mesmo conteúdo em várias notas repetidamente, talvez ache essa
opção útil.

**Direção do texto invertida** é útil se você estiver estudando idiomas que
mostram o texto da direita para esquerda (sigla RTL, do inglês _Right to Left_),
idiomas tais como o Árabe ou Hebraico encaixam-se nessa classificação. Essa
opção atualmente controla apenas a janela de adição e edição de notas; para se
certificar que o texto será mostrado de forma correta durante a revisão, você
terá que ajustar seu [modelo de nota](templates/styling.md).

Depois que você tiver adicionado os campos desejados, provavelmente vai querer
adicioná-los à Frente ou Verso dos seus cartões. Para mais informações quanto a
isso, por favor veja a seção [modelos](templates/intro.md).

Mudando o Baralho / Tipo de Nota
--------------------------------

Enquanto estiver adicionando cartões, você pode clicar no botão localizado no
canto superior esquerdo para mudar o tipo de nota, e no botão do canto superior
direito para mudar o baralho. A janela que que abrirá não apenas permite que
você selecione o baralho ou tipo de nota como também permite adicionar novos
baralhos e gerenciar suas notas atuais.

Usando Baralhos de forma apropriada
-----------------------------------

Os baralhos são projetados para dividir seu conteúdo em categorias amplas que
você deseja estudar separadamente, tais como Inglês, Química, e assim por
diante. Você pode ser tentado a criar muitos baralhos pequenos para manter seu
conteúdo organizado, tais como "meu livro de biologia capítulo 1", ou "países da
África", mas isto não é recomendado, pelas seguintes razões:

-   Ter muitos "mini baralhos" significa que você acaba revisando
    esses cartões em uma ordem previsível. Seja porque você seleciona
    um baralho de cada vez (o que é lento), ou por que você adicionou
    vários baralhos dentro de um único baralho pai, você acaba vendo
    todos os cartões do "capítulo 1" ou "países da África" de uma
    única vez. Isso torna mais fácil de responder os cartões, dado que
    você pode adivinhá-los pelo contexto, o que resulta em memórias
    mais fracas. Quando você precisar se lembrar de uma palavra ou
    frase fora do Anki, você não terá o luxo de ser apresentado à
    conteúdos relacionados antes!
    
-   O Anki não foi projetado para lidar com muitos baralhos (mais de
    algumas dúzias), e ele vai acabar ficando lendo a medida que você
    for adicionando mais - especialmente se você estiver estudando por
    um aplicativo de celular. Uns poucos baralhos extra não farão uma
    diferença perceptível, mas se você tiver muitos baralhos, o ataso
    começará a se mostrar presente.

Ao invés de criar vários pequenos baralhos, é uma ideia melhor usar etiquetas
e/ou campos para classificar seu conteúdo. Por exemplo, ao invés de criar um
baralho de "países da África", você poderia adicionar esses cartões ao seu
baralho principal de geografia, e etiquetar os cartões com "países", "geografia"
e "África". Cada cartão pode ter várias etiquetas, o que significa que você pode
fazer coisas como procurar por todos os países do mundo, todos os conteúdos
relacionados ao continente africano, ou ainda todos os países da África.

Para aqueles que gostam de ser muito organizados, existe a possibilidade de
adicionar campos às suas notas para classificar seu conteúdo, tal como "livro",
"página", e assim por diante. o Anki permite fazer pesquisas em campos
específicos, o que significa que você pode procurar por "livro:'meu livro'
página:63" e imediatamente encontrar o que você estava querendo.

As funcionalidades de [estudo personalizado e baralho
filtrado](filtered-decks.md) do Anki fazem esse tipo de abordagem algo
especialmente poderoso, uma vez que você pode criar um baralho temporário a
partir de pesquisas como a que acabamos de mencionar. Isso permite que você
revise todo seu conteúdo de uma forma misturada em um único baralho na maior
parte do tempo (para otimizar a retenção de memória), mas também permite que
você crie baralhos temporários quando precisar focar em um material em
específico, tal como em situações pré-prova. A regra geral é que se você quer
estudar um conteúdo sempre de forma separada, ele deve estar em um baralho só
dele, e, se você precisa apenas ocasionalmente estudá-lo separadamente (para uma
prova, caso esteja com matéria acumulada), etiquetas/campos e baralhos filtrados
são um método melhor.

Funcionalidades
---------------

O editor é mostrado quando estiver [adicionando notas](editing.md),
[editando-as](studying.md) durante as revisões, ou [navegando pelo
painel](browsing.md).

No canto superior esquerdo existem dois botões, que abrem as janelas de
[campos](editing.md#personalizando-campos) e [cartões](templates/intro.md).

No canto direito estão os botões que controlam a formatação de texto. Negrito,
itálico e sublinhado funcionam da mesma forma que em qualquer outro programa de
processamento de texto. Os próximos dois botões permitem que você coloque o
texto em superscrito ou subscrito, o que é útil para compostos químicos como
H<sub>2</sub>O ou equações matemáticas simples como x<sup>2</sup>.

O botão Fx remove qualquer formatação atualmente presente no texto selecionado.
Isso inclui cores, negrito, etc.

Os próximos dois botões permitem que você mude a cor do texto.

O botão \[…\] permite adicionar omissões de palavras. Note, entretanto, que para
criar cartões que possuem essa funcionalidade, seu modelo de nota selecionado
tem que estar configurado corretamente. Veja a seção de [omissão de
palavras](editing.md#omissão-de-palavras) para mais informações.

Você pode usar o botão com ícone de clipe de papel para selecionar áudios,
imagens e vídeos do disco rígido do seu computador e adicionar às suas notas.
Alternativamente, você pode copiar a mídia para a área de transferência (por
exemplo, clicar com o botão direito em cima de uma imagem em um site da internet
e escolher a opção 'Copiar Imagem') e colar esse conteúdo no campo que quiser.
Para mais informações quanto a mídia, por favor veja a seção [mídia](media.md).

O ícone de microfone permite que você grave áudio usando o microfone do seu
computador e adicione-o à nota atual.

O último botão mostra funcionalidades mais avançadas, tais como editar o HTML
que compõe um campo, e atalhos para adicionar MathJax ou [LaTeX](math.md) às
suas notas.

A maioria dos botões possui atalhos de teclado. Você pode posicionar o cursor do
mouse em cima de um botão para ver qual o atalho atrelado a ele.

Quando você colar textos, o Anki irá, por padrão, remover a maior parte da
formatação. Porém, caso pressione a tecla shift enquanto cola, o Anki preservará
mais da formatação do texto original.

Omissão de Palavras
-------------------

'Omissão de palavras' é o processo de ocultar uma ou mais palavras em uma
sentença. Por exemplo, se você tivesse a seguinte sentença:

    Brasília foi fundada em 21 de Abril de 1960.

…e omitisse o ano em que Brasília foi fundada, então sua sentença ficaria:

    Brasília foi fundada em 21 de Abril de [...].
    
Para mais informações sobre o porquê de se usar omissões de palavras, veja a
regra número 5 [aqui (em
Inglês)](http://www.supermemo.com/articles/20rules.htm).

Para facilitar, o Anki já vêm por padrão com um tipo especial de nota que
permite omitir palavras no formato acima mencionado. Para criar uma nota usando
omissão de palavras, selecione o tipo de nota "Omissão de Palavras", e digite
algum texto no campo chamado "Texto". Após isso, use o mouse para selecionar a
parte do texto que você deseja ocultar, selecione-o e então clique no botão
\[…​\]. O Anki irá substituir o texto usando este formato:

    Brasília foi fundada em 21 de Abril de {{c1::1960}}.
    
A parte "c1" significa que você criou uma omissão de palavras. Você pode criar
mais de uma se desejar. Por exemplo, se você selecionar Brasília e clicar no
botão \[…​\] novamente, o texto agora ficará:

    {{c2::Brasília}} foi fundada em 21 de Abril de {{c1::1960}}.

Quando você adicionar a nota acima, o Anki irá criar dois cartões. O primeiro
cartão irá mostrar:

    Brasília foi fundada em 21 de Abril de [...].
    
…na pergunta, e mostrará a frase completa na resposta. O outro cartão terá a
seguinte pergunta:

    [...] foi fundada em 21 de Abril de 1960.

Também é possível ocultar múltiplas partes da frase no mesmo cartão. No exemplo
acima, se você mudar "c2" por "c1", somente um cartão será criado, com ambos os
textos "Brasília" e "1960" ocultos. Caso você pressione a tecla "Alt" ("Option"
no Mac) enquanto estiver criando uma omissão de palavras, o Anki automaticamente
usará o mesmo número ao invés de incrementá-lo.

Omissões de palavra não precisam abranger a totalidade de uma palavra. Então, se
você selecionar "rasília" ao invés de "Brasília" no exemplo acima, a pergunta
aparecerá como "B\[…\] foi fundada em 21 de Abril de 1960", dando a você uma dica.

Você também pode pode mostrar dicas que não correspondem exatamente ao texto. Se
você trocar a sentença original por:

    Brasília::A capital do Brasil foi fundada em 21 de Abril de 1960.
    
…e então pressionar \[…\] após selecionar "Brasília::A capital do Brasil", o
Anki irá tratar o texto após os dois pontos duplos como uma dica, mudando o
texto para:

    {{c1::Brasília::A capital do Brasil}} foi fundada em 21 de Abril de 1960.

Quando o cartão aparecer para revisão, o texto aparecerá como:

    [A capital do Brasil] foi fundada em 21 de Abril de 1960.

Para informações sobre como testar sua habilidade de digitar omissões de
palavras corretamente, por favor veja a seção [digitando respostas](templates/fields.md#checking-your-answer).

Por favor, note que sobrepor omissões de palavras é um recursos não suportado.
Por exemplo, o seguinte campo é inválido:

    {{c1:Brasília foi fundada em 21 de {{c2::Abril}} de {{c3::1960}}}}.

Se você deseja criar omissões de palavaras de textos que se sobrepõe, adicione
um outro campo de texto ao seu [tipo de nota](templates/intro.md), e, quando
estiver criando as notas, cole o texto em dois campos separados, algo semelhante
a:

    Campo de Texto1: {{c1::Brasília foi fundada}} em 21 de Abril de 1960
    Campo de Texto2: {{c2::Brasília}} foi fundada em 21 de Abril de 1960

O tipo de nota omissão de palavras padrão possui um segundo campo chamado Extra,
que é mostrado no verso de cada cartao. Ele pode ser usado para adicionar
informações adicionais, por exemplo.

O tipo de nota omissão de palavras é tratado de forma especial pelo Anki, e não
pode ser criado com base em um tipo de nota comum. Se você deseja
personalizá-lo, por favor se certifique de clonar o tipo de nota já existente
"omissão de palavras" ao invés dos outros tipos de notas disponíveis.

Inserindo Caracteres Extrangeiros e Acentos
-------------------------------------------

Todos os computadores modernos possuem suporte nativo para inserção de acentos e
caracteres extrangeiros, e múltiplas formas de fazê-lo. O método que recomendamos
é usar o layout de teclado para o idioma que você deseja aprender.

Idiomas com caracteres diferentes como o Japonês, Chinês, Tailandês, e outros
possuem o seu próprio layout específico para essa linguagem.

Idiomas europeus que usam acentos podem ter o seu próprio layout, mas podem
geralmente ser digitados usando um layout de "teclado internacional".

Para adicionar um layout de teclado internacional em computadores Windows, por
favor veja <https://support.microsoft.com/en-au/kb/306560>.

Para adicionar em um Mac OS X, por favor veja
<http://www.macworld.com/article/1147039/os-x/accentinput.html>.

Layouts de teclado para um idioma específico são adicionados de uma maneira
semelhante, mas não temos condição de listar todos aqui. Para mais informações,
por favor tente pesquisar por "digitar em Japonês no Mac", "digitar em Chinês no
Windows 10", e assim por diante.

Se você está aprendendo um idioma que se escreve da direita para a esquerda,
existem várias outras questões a se considerar. Por favor, veja [esta página (em
inglês)](http://dotancohen.com/howto/rtl_right_to_left.html) para mais informações.

O toolkit que o Anki usa possue dificuldade em lidar com alguns métodos de
inserção de caracteres, tais como pressionar teclas para selecionar caracteres
com acento no Mac OS X, ou pressionar a tecla "Alt" e digitar um código
numérico no Windows.
