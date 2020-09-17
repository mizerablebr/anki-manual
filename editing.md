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
cartões serão adicionados. Se você quiser adicionar cartões à um novo baralho,
você precisa clicar no nome do baralho atualmente selecionado, e, então,
pressionar o botão "Adicionar".

Em baixo do tipo de nota, você verá alguns botões e uma área chamada "Frente" e
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
para adicionar essa nota à sua coleção. Após isso, um cartão também será criado,
e colocado no baralho que você selecionou. Se você quiser editar um cartão já
adicionado, pode clicar no botão "Histórico" para procurá-lo. O cartão
selecionado abrirá no [navegador](browsing.md).

O Anki verifica o primeiro campo por valores que sejam únicos. Dessa forma, ele irá
te avisar caso você adicione dois cartões com o campo Frente contendo o texto
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
[este artigo](http://www.supermemo.com/articles/20rules.htm) no site do
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

Adding a Note Type
------------------

While basic note types are sufficient for simple cards with only a word
or phrase on each side, as soon as you find yourself wanting to include
more than one piece of information on the front or back, it’s better to
split that information up into more fields.

You may find yourself thinking "but I only want one card, so why can’t I
just include the audio, a picture, a hint and the translation in the
Front field?" If you’d prefer to do that, that’s fine. But the
disadvantage of that approach is that all the information is stuck
together. If you wanted to sort your cards by the hint, you wouldn’t be
able to do that as it’s mixed in with the other content. You also
wouldn’t be able to do things like move the audio from the front to the
back, except by laboriously copying and pasting it for every note. By
keeping content in separate fields, you make it much easier to adjust
the layout of your cards in the future.

To create a new type of note, choose Tools → Manage Note Types from the
main Anki window. Then click “Add” to add a new type of note. You’ll now
see another screen that gives you a choice of note types to base the new
type on. “Add” means to base the newly created type on one that comes
with Anki. “Clone” means to base the newly created type on one that is
already in your collection. For instance, if you’d created a French
vocab type already, you might want to clone that when creating a German
vocab type.

After choosing OK, you’ll be asked to name the new type. The subject
material you’re studying is a good choice here – things like “Japanese”,
”Trivia”, and so on. Once you’ve chosen a name, close the Note Types
window, and you’ll return to the adding window.

Customizing Fields
------------------

To customize fields, click the “Fields…​” button when adding or editing
a note, or while the note type is selected in the Manage Note Types
window.

You can add, remove, or rename fields by clicking the appropriate
buttons. To change the order in which the fields appear in this dialog
and the add notes dialog, you can use the reposition button, which asks
for the numerical position you want the field to have. So if you want to
change a field to be the new first field, enter “1”.

Do not use 'Tags', 'Type', 'Deck', 'Card', or 'FrontSide' as field
names, as they are [special fields](templates/fields.md#special-fields) and will not work
properly.

The options at the bottom of the screen allow you to edit various
properties of the fields to be used when adding and editing the cards.
This is 'not' where you customize what appears on your cards when
reviewing; for that, please see [templates](templates/intro.md).

**Editing Font** allows you to customize the font and size used when
editing notes. This is useful if you want to make unimportant
information smaller, or increase the size of foreign characters which
are hard to read. The changes you make here do not affect how cards
appear when reviewing: to do that, please see the
[templates](templates/intro.md) section. If you have enabled the “type in the
answer” function, however, the text you type will use the font size
defined here. (For information about how to change the actual font face
when typing the answer, please see the [checking your
answer](templates/fields.md#checking-your-answer) section.)

**Sort by this field…​** tells Anki to show this field in the Sort Field
column of the browser. You can use this to sort cards by that field.
Only one field can be the sort field at once.

When **Remember last input…​** is checked, Anki will not clear out this
field’s content after a note is added. If you find yourself entering the
same content into multiple notes, you may find this useful.

**Reverse text direction** is useful if you are studying languages that
display text from right to left (RTL), such as Arabic or Hebrew. This
setting currently only controls editing; to make sure the text displays
correctly during review, you’ll need to adjust your
[template](templates/styling.md).

After you’ve added fields, you’ll probably want to add them to the front
or back of your cards. For more information on that, please see the
[templates](templates/intro.md) section.

Changing Deck / Note Type
-------------------------

While adding, you can click on the top left button to change note type,
and the top right button to change deck. The window that opens up will
not only allow you to select a deck or note type, but also to add new
decks or manage your note types.

Using Decks Appropriately
-------------------------

Decks are designed to divide your content up into broad categories that
you wish to study separately, such as English, Geography, and so on. You
may be tempted to create lots of little decks to keep your content
organized, such as “my geography book chapter 1”, or “food verbs”, but
this is not recommended, for the following reasons:

-   Lots of little decks mean you end up reviewing cards in a
    recognizable order. Whether it’s because you’re clicking on each
    deck in turn (which is slow) or you’ve added a number of decks under
    a single parent deck, you’ll end up seeing all the “chapter 1” or
    “food verb” cards together. This makes it easier to answer the
    cards, as you can guess them from the context, which leads to weaker
    memories. When you need to recall the word or phrase outside Anki,
    you won’t have the luxury of being shown related content first!

-   Anki was not designed to handle many decks (more than several
    dozen), and it will slow down as you add more – especially if you’re
    studying on a mobile client. A few extra decks is not going to make
    a noticeable difference, but if you have many decks the delays will
    start to add up.

Instead of creating lots of little decks, it’s a better idea to use tags
and/or fields to classify your content. Instead of creating a “food
verbs” decks for example, you could add those cards to your main
language study deck, and tag the cards with “food” and “verb”. Each card
can have multiple tags, which means you can do things like search for
all verbs, or all food-related vocabulary, or all verbs that are related
to food.

For those who like to stay very organized, you can add fields to your
notes to classify your content, such as “book”, “page”, and so on. Anki
supports searching in specific fields, which means you can do a search
for “book:'my book' page:63” and immediately find what you’re looking
for.

Anki’s [custom study and filtered deck](filtered-decks.md) features make this
especially powerful, as you can create temporary decks out of search
terms. This allows you to review your content mixed together in a single
deck most of the time (for optimum memory), but also create temporary
decks when you need to focus on particular material, such as before a
test. The general rule is that if you always want to be able to study
some content separately, it should be in a normal deck, and if you only
occasionally need to be able to study it separately (for a test, when
under a backlog, etc), tags/fields and filtered decks are better.

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
