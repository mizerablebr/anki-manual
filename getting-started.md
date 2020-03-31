# Começando

## Vídeos

Para se dubruçar rapidamente no Anki, por favor confira esses vídeos introdutórios. Eles foram produzidos com uma versão anterior do Anki, mas o conceito é o mesmo.

-   [Baralhos compartilhados e Revisando o básico](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on)
    
-   [Mudando a ordem dos Cartões](http://www.youtube.com/watch?v=DnbKwHEQ1mA&yt:cc=on)
    
-   [Estilizando os Cartões](http://www.youtube.com/watch?v=F1j1Zx0mXME&yt:cc=on)

-   [Digitando na Resposta](http://www.youtube.com/watch?v=5tYObQ3ocrw&yt:cc=on)

Se o YouTube está indisponível em seu país, como alternativa você pode [baixar os vídeos](https://apps.ankiweb.net/downloads/archive/screencasts/2.0/).


## Conceitos Chave

### Cartões

O par composto por uma pergunta e uma resposta é chamado de 'cartão'. Isso é baseado em cartões de estudo de papel cujo anverso possui uma pergunta e o verso possui a resposta. No Anki o cartão não se parece propriamente com o cartão físico, e quando você exibe a resposta a pergunta ainda fica visível por padrão. Por exemplo, se você está estudando química básica, você pode ver uma pergunta como esta:

    P: Símbolo químico do oxigênio?

Depois de pensar sobre isso e decidir que a resposta é O, você pressiona o botão exibir resposta e o Anki exibe para você:

    P: Símbolo químico do oxigênio?
    R: O

Depois de confirmar que você está certo, você pode informar ao Anki o quão facilmente recordou e o Anki irá escolher a próxima vez que exibirá para você.

### Baralho

Um 'baralho' é um grupo de cartões. Você pode colocar cartões em baralhos diferentes para estudar partes da sua coleção de cartões ao invés de estudar tudo de uma vez. Cada baralho pode ter configurações distintas, como quantos cartões novos exibir por dia, ou quanto tempo esperar até que os cartões seja exibidos novamente.

Baralhos podem conter outros baralhos, o que lhe permite organizá-los como uma árvore. Anki usa “::” para exibir os diferentes níveis. Um baralho chamado “Chinês::Hanzi” se refere ao baralho “Hanzi”, que faz parte do baralho “Chinês”. Se você selecionar “Hanzi” então apenas os cartões Hanzi serão exibidos; se você selecionar “Chinês” então todos os cartões chineses, inclusive os cartões Hanzi, serão exibidos.

Para colocar um baralho em árvore, você tanto pode nomeá-los com “::” entre cada nível, ou da lista de baralhos arrastar e soltar eles. Baralhos que foram estruturados sob um outro baralho (ou seja, tem ao menos um “::” em seus nomes) são geralmente chamados de 'sub-baralhos', e os baralhos do topo da árvore às vezes são chamados de 'superbaralhos' or 'baralhos pai'.

Anki começa com um baralho chamado “padrão”; qualquer cartão que de alguma forma tenha sido separado de outros baralhos irá para ele. Anki irá esconder o baralho padrão caso não contenha cartões e você tenha adicionado novos baralhos. Alternativamente, você pode renomeá-lo e usá-lo para outros cartões.

Baralhos são melhor utilizados para agrupar categorias amplas de cartões, so invés de tópicos específicos como “verbos alimentares” ou “lição 1”. Para mais informações nesse sentido, por favor consulte a seção [usando baralhos adequadamente](editing.md#using-decks-appropriately).

Para informações sobre como o baralho afeta a ordem de exibição dos cartões, por favor consulte a seção [ordem de exibição](studying.md#display-order).

### Notas & Campos

Ao fazer cartões de estudo, é frequentemente desejável que seja feito mais de um cartão com referência a dada informação. Por exemplo, se você está aprendendo lingua francesa e você aprendeu que  a palavra “bonjour” significa “olá”, você pode querer criar um cartão que exiba “bonjour” e o demande por lembrar “olá”, e um outro cartão que exiba “olá” e requeira que você lembre de “bonjour”. Um cartão está testando sua habilidade em reconhecer a palavra estrangeira e o outro cartão está testando sua habilidade em produzir-la.

Enquanto usa cartões de memória em papel, sua única opção neste caso é tomar nota dessa informação duas vezes, uma para cada cartão. Alguns programas de computador de cartões de estudo tornam sua vida mais fácil ao oferecer uma funcionalidade de girar o anverso e o verso. Isso é um aperfeiçoamento do situação do papel, mas há duas grandes desvantagens:

-   Pelo motivo desses programas não acompanharem sua performance de reconhecimento e produção separadamente, os cartões tenderão a não serem exibidos para você no momento ótimo, significa dizer que você esquecerá mais do que gostaria ou estudará mais do que o necessário.
    
-   Inverter a pergunta e a resposta apenas funciona quando você quer exatamente o mesmo conteúdo em cada lado. Isso significa, por exemplo, que não é possível exibir informação extra no verso de cada cartão.

Anki resolve esses problemas ao permitir que você divida o conteúdo dos seus cartões em pedaços de informação separados. Você pode então dizer ao Anki que pedaço da informação você quer em cada cartão e o Anki irá tomar conta da criação do cartões para você e atualizá-los se você fizer qualquer edição no futuro.

Imagine que nós queiramos estudar o vocabulário francês e nossa vontade é de que o número da página esteja incluído no verso de cada cartão. Nós queremos nossos cartões com a seguinte aparência:

    P: Bonjour
    R: Olá
       Página #12

E:

    P: Olá
    R: Bonjour
       Página #12

Neste exemplo nós temos três fragmentos de informações: uma palavra francesa, seu significado em português e o número da página. Se as colocarmos juntas, elas se parecerão com isso:

    Língua francesa: Bonjour
    Língua Portuguesa: Olá
    Página: 12

No Anki essa informação relacionada é chamada de 'nota' e cada fragmento de informação é chamado de 'campo'. Então podemos dizer que esse tipo de nota tem três campos: Língua francesa, Língua portuguesa e Página.

Para adicionar e editar campos, pressione o botão “Campos…​” quando estiver adicionando ou editando notas. Para mais informações sobre campos, por favor consulte a seção [Personalização de campos](editing.md#customizing-fields).

### Card Types

In order for Anki to create cards based on our notes, we need to give it
a blueprint that says which fields should be displayed on the front or
back of each card. This blueprint is called a 'card type'. Each type of
note can have one or more card types; when you add a note, Anki will
create one card for each card type.

Each card type has two 'templates', one for the question and one for the
answer. In the above French example, we wanted the recognition card to
look like this:

    Q: Bonjour
    A: Hello
       Page #12

To do this, we can set the question and answer templates to:

    Q: {{French}}
    A: {{English}}<br>
       Page #{{Page}}

By surrounding a field name in double curly brackets, we tell Anki to
replace that section with the actual information in the field. Anything
not surrounded by curly brackets remains the same on each card. (For
instance, we don’t have to type “Page \#” into the Page field when
adding material – it’s added automatically to every card.) &lt;br&gt; is
a special code that tells Anki to move to the next line; more details
are available in the [templates](templates/intro.md) section.

The production card templates work in a similar way:

    Q: {{English}}
    A: {{French}}<br>
       Page #{{Page}}

Once a card type has been created, every time you add a new note, a card
will be created based on that card type. Card types make it easy to keep
the formatting of your cards consistent and can greatly reduce the
amount of effort involved in adding information. They also mean Anki can
ensure related cards don’t appear too close to each other, and they
allow you to fix a typing mistake or factual error once and have all the
related cards updated at once.

To add and edit card types, click the “Cards…​” button while adding or
editing notes. For more information on card types, please see the [Cards
and Templates](templates/intro.md) section.

### Note Types

Anki allows you to create different types of notes for different
material. Each type of note has its own set of fields and card types.
It’s a good idea to create a separate note type for each broad topic
you’re studying. In the above French example, we might create a note
type called “French” for that. If we wanted to learn capital cities, we
could create a separate note type for that as well, with fields such as
“Country” and “Capital City”.

When Anki checks for duplicates, it only compares other notes of the
same type. Thus if you add a capital city called “Orange” using the
capital city note type, you won’t see a duplicate message when it comes
time to learn how to say “orange” in French.

When you create a new collection, Anki automatically adds some standard
note types to it. These note types are provided to make Anki easier for
new users, but in the long run it’s recommended you define your own note
types for the content you are learning. The standard note types are as
follows:

Basic  
Has Front and Back fields, and will create one card. Text you enter in
Front will appear on the front of the card, and text you enter in Back
will appear on the back of the card.

Basic (and reversed card)  
Like Basic, but creates two cards for the text you enter: one from
front→back and one from back→front.

Basic (optional reversed card)  
This is a front→back card, and optionally a back→front card. To do this,
it has a third field called “Add Reverse.” If you enter any text into
that field, a reverse card will be created. More information about this
is available in the [Cards and Templates](templates/intro.md) section.

Cloze  
A note type which makes it easy to select text and turn it into a cloze
deletion (e.g., “Man landed on the moon in \[…​\]” → “Man landed on the
moon in 1969”). More information is available in the [cloze
deletion](editing.md#cloze-deletion) section.

To add your own note types and modify existing ones, you can use Tools →
Manage Note Types from the main Anki window.

Notes and note types are common to your whole collection rather than
limited to an individual deck. This means you can use many different
types of notes in a particular deck, or have different cards generated
from a particular note in different decks. When you add notes using the
Add window, you can select what note type to use and what deck to use,
and these choices are completely independent of each other. You can also
change the note type of some notes [after you’ve already created
them](browsing.md).

### Collection

Your 'collection' is all the material stored in Anki – your cards,
notes, decks, note types, deck options, and so on.

## Shared Decks

You can watch [a video about Shared Decks and Review
Basics](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on) on YouTube.

The easiest way to get started with Anki is to download a deck of cards
someone has shared:

1.  Click the “Get Shared” button at the bottom of the deck list.

2.  When you’ve found a deck you’re interested in, click the “Download”
    button to download a deck package.

3.  Double-click on the downloaded package to load it into Anki, or
    File→Import it.

Please note that it’s not currently possible to add shared decks
directly to your AnkiWeb account. You need to import them with the
desktop program, then synchronize to upload them to AnkiWeb.

Creating your own deck is the most effective way to learn a complex
subject. Subjects like languages and the sciences can’t be understood
simply by memorizing facts — they require explanation and context to
learn effectively. Furthermore, inputting the information yourself
forces you to decide what the key points are, leading to a better
understanding.

If you are a language learner, you may be tempted to download a long
list of words and their translations, but this won’t teach you a
language any more than memorizing scientific equations will teach you
astrophysics. To learn properly, you need textbooks, teachers, or
exposure to real-world sentences.

    Do not learn if you do not understand.
    --SuperMemo

Most shared decks are created by people who are learning material
outside of Anki – from textbooks, classes, TV, etc. They select the
interesting points from what they learn and put them into Anki. They
make no effort to add background information or explanations to the
cards, because they already understand the material. So when someone
else downloads their deck and tries to use it, they’ll find it very
difficult as the background information and explanations are missing.

That is not to say shared decks are useless – simply that for complex
subjects, they should be used as a 'supplement' to external material,
not as a 'replacement' for it. If you’re studying textbook ABC and
someone has shared a deck of ideas from ABC, that’s a great way to save
some time. And for simple subjects that are basically a list of facts,
such as capital city names or pub quiz trivia, you probably don’t need
external material. But if you attempt to study complex subjects without
external material, you will probably meet with disappointing results.

