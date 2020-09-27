Adicionando/Editando
===============

Adicionando Cartões e Notas
----------------------

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
------------------

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
------------------

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
-------------------------

Enquanto estiver adicionando cartões, você pode clicar no botão localizado no
canto superior esquerdo para mudar o tipo de nota, e no botão do canto superior
direito para mudar o baralho. A janela que que abrirá não apenas permite que
você selecione o baralho ou tipo de nota como também permite adicionar novos
baralhos e gerenciar suas notas atuais.

Usando Baralhos de forma apropriada
-------------------------

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

Features
--------

The editor is shown when [adding notes](editing.md), [editing a
note](studying.md) during reviews, or [browsing](browsing.md).

On the top left are two buttons, which open the [fields](editing.md#customizing-fields) and
[cards](templates/intro.md) windows.

On the right are buttons that control formatting. Bold, italic and
underline work like they do in a word processing program. The next two
buttons allow you to subscript or superscript text, which is useful for
chemical compounds like H<sub>2</sub>O or simple math equations like
x<sup>2</sup>.

The Fx button clears any formatting in the currently selected text. This
includes colours, bold, etc.

The next two buttons allow you to change text colour.

The \[…​\] button is visible when a cloze note type is selected.

You can use the paperclip button to select audio, images and videos from
your computer’s hard drive to attach to your notes. Alternatively, you
can copy the media onto your computer’s clipboard (for instance, by
right-clicking an image on the web and choosing 'Copy Image') and paste
it into the field that you want to place it in. For more information
about media, please see the [media](media.md) section.

The microphone icon allows you to record from your computer’s microphone
and attach the recording to the note.

The last button shows more advanced features, such as editing the
underlying HTML of a field, and shortcuts to add MathJax or
[LaTeX](math.md) to your notes.

Most of the buttons have shortcut keys. You can hover the mouse cursor
over a button to see its shortcut.

When pasting text, Anki will strip most formatting by default. If you
hold down the shift key while pasting, Anki will preserve more
formatting.

Cloze Deletion
--------------

'Cloze deletion' is the process of hiding one or more words in a
sentence. For example, if you have the sentence:

    Canberra was founded in 1913.

…​and you create a cloze deletion on “1913”, then the sentence would
become:

    Canberra was founded in [...].

Sometimes sections that have been removed in this fashion are said to be
'occluded'.

For more information on why you might want to use cloze deletion, see
rule number 5 [here](http://www.supermemo.com/articles/20rules.htm).

Anki provides a special cloze deletion type of note, to make creating
clozes easy. To create a cloze deletion note, select the Cloze note
type, and type some text into the "Text" field. Then drag the mouse over
the text you want to hide to select it, and click the \[…​\] button.
Anki will replace the text with:

    Canberra was founded in {{c1::1913}}.

The “c1” part means that you’ve created one cloze deletion on the
sentence. You can create more than one deletion if you’d like. For
example, if you select Canberra and click \[…​\] again, the text will
now look like:

    {{c2::Canberra}} was founded in {{c1::1913}}.

When you add the above note, Anki will create two cards. The first card
will show:

    Canberra was founded in [...].

…​on the question, with the full sentence on the answer. The other card
will have the following on the question:

    [...] was founded in 1913.

You can also elide multiple sections on the same card. In the above
example, if you change c2 to c1, only one card would be created, with
both Canberra and 1913 hidden. If you hold down alt (option on a Mac)
while creating a cloze, Anki will automatically use the same number
instead of incrementing it.

Cloze deletions don’t need to fall on word boundaries, so if you select
“anberra” rather than “Canberra” in the above example, the question
would appear as “C\[…​\] was founded in 1913”, giving you a hint.

You can also give yourself hints that don’t match the text. If you
replace the original sentence with:

    Canberra::city was founded in 1913

…​and then press \[…​\] after selecting "Canberra::city", Anki will
treat the text after the two colons as a hint, changing the text into:

    {{c1::Canberra::city}} was founded in 1913

When the card comes up for review, it will appear as:

    [city] was founded in 1913.

For information on testing your ability to type in a cloze deletion
correctly, please see the section on [typing answers](templates/fields.md#checking-your-answer).

Please note that overlapping clozes are not supported. For example, the
following field is invalid:

    {{c1::Canberra was {{c2::founded}}}} in 1913

If you need to create clozes from overlapping text, add another Text
field to your cloze, add it to the [template](templates/intro.md), and then when
creating notes, paste the text into two separate fields, like so:

    Text1 field: {{c1::Canberra was founded}} in 1913

    Text2 field: {{c2::Canberra}} was founded in 1913

The default cloze note type has a second field called Extra, that is
shown on the answer side of each card. It can be used for adding some
usage notes or extra information.

The cloze note type is treated specially by Anki, and cannot be created
based on a regular note type. If you wish to customize it, please make
sure to clone the existing Cloze type instead of another type of note.
Things like formatting can be customized, but it is not possible to add
extra card templates to the cloze note type.


Inputting Foreign Characters and Accents
----------------------------------------

All modern computers have built in support for typing accents and
foreign characters, and multiple ways to go about it. The method we
recommend is using a keyboard layout for the language you want to learn.

Languages with a separate script like Japanese, Chinese, Thai and so on
have their own layouts specifically for that language.

European languages that use accents may have their own layout, but can
often by typed on a generic "international keyboard" layout. These work
by typing the accent, then the character you want accented - eg an
apostrophe (') then the letter a (a) gives á.

To add the international keyboard on Windows machines, please see
<https://support.microsoft.com/en-au/kb/306560>

To add it on Macs, please see
<http://www.macworld.com/article/1147039/os-x/accentinput.html>

Keyboards for a specific language are added in a similar way, but we can
not cover them all here. For more information, please try searching
Google for "input Japanese on a mac", "type Chinese on Windows 10", and
so on.

If you’re learning a right to left language, there are lots of other
things to consider. Please see [this
page](http://dotancohen.com/howto/rtl_right_to_left.html) for more
information.

The toolkit Anki is built on has trouble dealing with a few input
methods, such as holding down keys to select accented characters on Mac
OS X, and typing characters by holding down the alt key and typing a
numeric code on Windows.
