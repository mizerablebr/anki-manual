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

    Língua Francesa: Bonjour
    Língua Portuguesa: Olá
    Página: 12

No Anki essa informação relacionada é chamada de 'nota' e cada fragmento de informação é chamado de 'campo'. Então podemos dizer que esse tipo de nota tem três campos: Língua francesa, Língua portuguesa e Página.

Para adicionar e editar campos, pressione o botão “Campos…​” quando estiver adicionando ou editando notas. Para mais informações sobre campos, por favor consulte a seção [Personalização de campos](editing.md#customizing-fields).

### Tipos de Cartões

Para que o Anki possa criar cartões baseados em nossas anotações, nós precisamos fornecer um diagrama descrevendo quais campos devem ser exibidos no anverso ou no verso de cada cartão. Esse diagrama é chamado 'tipo de cartão'. Cada tipo de nota pode ter um ou mais tipo de cartão; quando você adiciona uma nota o Anki irá criar um cartão para cada tipo de cartão.

Cada tipo de cartão tem dois 'modelos', um para a pergunta e outro para a resposta. No exemplo de Língua Francesa acima, nós queremos que o cartão de reconhecimento se pareça com isso:

    P: Bonjour
    R: Olá
       Página #12

Para fazer isso, nós podemos configurar o modelo de pergunta e resposta assim:

    P: {{Língua Francesa}}
    R: {{Língua Portuguesa}}<br>
       Página #{{Página}}

Ao circundar um nome de campo com caves duplas nós informamos ao Anki que ele deve substituir aquela seção com a informação do campo. Qualquer coisa que não esteja circundada por chaves duplas permanece como está em cada cartão (por exemplo, nós não precisamos digitar “Página \#” no campo Página quando estamos adicionando material – isso é adicionado automaticamente em todo cartão.) &lt;br&gt; é um código especial que avisa ao Anki que ele deve ir para a próxima linha; mais detalhes estão disponíveis na seção [modelos](templates/intro.md).

Os modelos de produção de cartão funcionam funcionam de uma forma semelhante:

    P: {{Língua Portuguesa}}
    R: {{Língua Francesa}}<br>
       Página #{{Página}}

Uma vez que um tipo de cartão tenha sido criado, toda vez que você adicionar uma nova nota, um cartão será criado baseado no tipo de cartão. Tipos de cartão tornam mais fácil manter a formação dos seus cartões consistente e pode diminuir bastante o esforço necessário para adicionar informações. Eles também significam que o Anki pode garantir que cartões relacionados não irão aparecer muito próximo uns dos outros, e eles permitem que você corrija um erro de digitação ou erro de fato apenas uma vez e todos os cartões relacionados serão atualizados de uma vez.

Para adicionar ou editar tipos de cartão, pressione o botão “Cartões…​” enquanto estiver adicionando ou editando uma nota. Para mais informações sobre tipos de cartão, por favor verifique a seção [Cartões e Modelos](templates/intro.md).

### Tipos de Notas

Anki permite que você crie diferentes tipos de notas para diferentes materiais. Cada tipo de nota possui seu próprio conjunto de campos e tipos de carta. É recomendado criar um tipo de nota separado para cada grande tópico que esteja estudando. No exemplo de Língua Francesa acima, nós devemos criar para ele um tipo de nota chamado “Língua Francesa”. Se quisermos aprender sobre capitais, nós poderíamos criar também para isso um tipo de nota separado, com campos como “País” e “Capital”.

Quando o Anki verifica se existem duplicatas, ele apenas compara com outras notas do mesmo tipo. Assim, se você adicionar uma capital chamada “Laranja” usando o tipo de nota capitais, você não verá a mensagem de nota duplicada quando chegar a hora de aprender como falar “Laranja” em Língua Francesa.

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

