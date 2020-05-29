Estudando
========

Quando você tiver encontrado um baralho que goste ou adicionado algumas notas, chegou a hora de começar a estudar.

Baralhos
-----

O estudo no Anki é limitado ao baralho que está atualmente selecionado bem como a qualquer sub-baralho que ele contenha.

Na tela dos baralhos, seus baralhos serão exibidos em uma lista. Nela há duas colunas numéricas: 'pendente' e 'novo'. 'Pendente' é a contagem de cartões em estudo que está aguardando revisão. 'Novo' é o número de cartões novos que estão prontos para serem estudados naquele dia.

Quando você clica em um baralho ele se tornará o 'baralho atual' e o Anki vai mudar para a tela de estudo. Você pode retornar para a lista de baralhos e mudar o baralho atualmente selecionado a qualquer momento clicando em "Baralhos" no topo da janela principal. (Você também pode usar a ação Estudar Baralho no menu para selecionar um novo deck utilizando o teclado, ou você pode pressionar o botão 's' para estudar o baralho atualmente selecionado)

Você pode pressionar o botão de engrenagem no lado direito do baralho para renomeá-lo, apagá-lo, mudar suas opções ou exportá-lo.

Quando um baralho tem sub-baralhos, os cartões destes aparecerão conjuntos [cada baralho por vez](studying.md#display-order).

Visão Geral do Estudo
--------------

Depois de clicar num baralho para estudá-lo, você verá uma tela que demonstra quantos cartões estão pendentes no dia de hoje. Isso é chamado de tela de 'visão geral'.
Os cartões são divididos em três tipos:

-   **Novo** refere-se aos cartões que você baixou ou inseriu, mas que nunca foram estudados antes.
    
-   **Estudando** faz referência aos cartões que foram vistos pela primeira vez recentemente e continuam sendo estudados.
    
-   **A rever** diz respeito aos cartões que foram previamente estudados e agora precisam ser revisados para que você não os esqueça.

Para iniciar uma sessão de estudo, clique no botão **Estudar Agora**. O Anki irá proceder para exibir-lhe cartões até que acabem aqueles a serem exibidos no dia.

Enquanto estiver estudando, você pode retornar à visão geral ao pressionar a tecla “s” no seu teclado.

Questões
---------

Quando um cartão é exibido, apenas a questão é apresentada primeiro. Depois de pensar sobre a resposta, você tanto pode clicar no botão **Mostrar Resposta**, quando pressionar a barra de espaço no teclado. A resposta então será exibida. Está tudo bem se você precisar de algum tempo para lembrar da resposta, mas via de regra se você não puder responder dentro de 10 segundos, provavelmente é melhor você desistir e exibir a resposta do que ficar sofrendo para recordá-la.

Quando a resposta é apresentada, você deve comparar a resposta que você pensou com a resposta que foi exibida e informar ao Anki o qual bem você lembrou. Se você não tem confiança em comparar sua resposta com exatidão, você pode pedir que o Anki [solicite que você digite a resposta](templates/fields.md#checking-your-answer) ao invés de apenas exibir para você.

O número de botões disponíveis para avaliar a resposta depende se o cartão está sendo 'aprendido' ou 'revisado'.

Aprendizagem
--------

Seja aprendendo novos cartões, seja revisando cartões que você tenha esquecido, o Anki irá exibir os cartões uma ou mais vezes para ajudá-lo a memorizá-los. Cada passo desse é chamado de 'etapa de aprendizado'. Por padrão há duas etapas: 1 minuto e 10 minutos. Você pode mudar o número de etapas e o intervalo entre elas nas [opções do baralho](deck-options.md).

Há três botões de classificação quando estiver estudando:

**Errei** move o cartão de volta para a primeira etapa.

**Bom** coloca o cartão na próxima etapa. Se o cartão já estiver na última etapa, então ele será convertido num cartão de revisão (ele é promovido). Por padrão, uma vez que o cartão tenha alcançado o fim das etapas de aprendizagem, o cartão será novamente exibido no próximo dia, e então sucessivamente em intervalos cada vez mais longos (veja a próxima seção).

**Fácil** o cartão é imediatamente convertido em cartão de revisão, mesmo que ainda lhe faltem etapas. Por padrão, o cartão será exibido novamente 4 dias mais tarde, e então em intervalos cada vez mais longos. O botão Fácil não será exibido se você estiver no modo recordação e ele dará o mesmo intervalo que o botão "Bom".

Quando os cartões são vistos pela primeira vez, eles começam na primeira etapa. Isso quer dizer que ao responder  **Bom** a um cartão pela primeira vez, ele será exibido novamente em 10 minutos, e a etapa inicial de um minuto será saltada. Entretanto, de você pressionar Errei o cartão será exibido novamente em 1 minuto.

Você pode usar as teclas 1, 2 e 3 do seu teclado para selecionar um dos botões, onde 1 representa **Errei**. Pressionar a barra de espaço deu teclado irá selecionar **Bom**.

Se não houver cartões a serem exibidos para você, o Anki irá exibir novamente os cartões de aprendizado mesmo que o intervalo deles não tenha decorrido completamente. Se você preferir esperar o intervalo completo de aprendizado, você pode modificar esse comportamento nas [preferências](preferences.md).

Revisando
---------

Quando um cartão foi anteriormente aprendido e está pronto para ser revisado novamente, haverá quatro botões para avaliar sua resposta:

**Errei** marca sua resposta como incorreta e pede ao Anki que exiba o cartão com mais frequência no futuro. O cartão é considerado como 'falha' de memória. Por favor veja a seção [falhas](deck-options.md) para saber mais sobre como os cartões com falha são tratados.

**Difícil** exibe o cartão num período um pouco menor de tempo do que da última vez, e diz ao Anki para exibí-lo mais frequentemente no futuro.

**Bom** informa ao Anki que o último intervalo de tempo foi adequado e a facilidade do cartão não exige ajuste para mais ou para menos. No padrão inicial de facilidade, o cartão será exibido novamente 2,5 vezes mais tarde do que da vez anterior, de modo que caso tenha anteriormente esperado 10 dias para visualizar o cartão, da próxima vez a espera será por volta de 25 dias.

**Fácil** diz ao Anki que você acho o intervalo muito curto. O cartão será agendado para um futuro mais distante do que quando escolhida o botão 'Bom', além de que no futuro o Anki irá agendar o cartão numa frequência menor. Pelo fato de 'Fácil' aumentar rapidamente o intervalo, ele é melhor utilizado apenas nos cartões mais fáceis. Ao invés dele, na maior parte do tempo você deve se encontrar respondendo 'Bom'.

De igual modo como quando estudando os cartões, você pode utilizar os números de 1 a 4 do teclado para selecionar uma resposta. Pressionar a barra de espaço selecionará 'Bom'.

Due Counts
----------

When only the question is shown, Anki shows three numbers like 12 + 34 +
56 at the bottom of the screen. These represent the new cards, cards in
learning, and cards to review. If you’d prefer not to see the numbers,
you can turn them off in Anki’s preferences.

In the old scheduler, the numbers count *reviews* needed to finish all the 
cards in that queue, not the number of *cards*. If you have multiple
steps configured for lapsed cards, the number will increase by more than 
one when you fail a card, since that card needs to be shown several times.

In the new scheduler, the numbers count *cards*, so the number will always
increase by one regardless of the steps remaining.

When the answer is shown, Anki shows an estimate of the next time a card
will be shown above each button. If you’d prefer not to see the
estimates, you can disable them in Anki’s [preferences](preferences.md).

Anki additionally adds a small amount of random variation to the next
due times, in order to prevent cards that were introduced together and
always rated the same from always staying next to each other. This
variation is not shown on the time estimates but will be applied after
selecting the button.

Editing and More
----------------

You can click the **Edit** button in the bottom left to edit the current
note. When you finish editing, you’ll be returned to study. The editing
screen works very similarly to the [add notes](editing.md) screen.

At the bottom right of the review screen is a button labeled **More**.
This button provides some other operations you can do on the current
card or note:

Mark Note  
Adds a “marked” tag to the current note, so it can be easily found in
the browser. This is useful when you want to take some action on the
note at a later date, such as looking up a word when you get home.
Marked cards also show a small star in the upper-right-hand corner
during reviews.

Bury Card / Note  
Hides a card or all of the note’s cards from review until the next day.
(If you want to unbury cards before then, you can click the “unbury”
button on the [deck overview](studying.md#study-overview) screen.) This is useful if
you cannot answer the card at the moment or you want to come back to it
another time. Burying can also [happen automatically](studying.md#siblings-and-burying) for
cards of the same note. If cards were in learning when they are buried,
they are moved back to the new card queue or review queue prior to being
buried.

Suspend Card / Note  
Hides a card or all of the note’s cards from review until they are
manually unsuspended (by clicking the suspend button in the browser).
This is useful if you want to avoid reviewing the note for some time,
but don’t want to delete it. If cards were in learning when they are
suspended, they are moved back to the new card queue or review queue
prior to being suspended.

Delete Note  
Deletes the note and all of its cards.

Options  
Edit the options for the current deck.

Replay Audio  
If the card has audio on the front or back, play it again.

Record Own Voice  
Record from your microphone for the purposes of checking your
pronunciation. This recording is temporary and will go away when you
move to the next card. If you want to add audio to a card permanently,
you can do that in the edit window.

Replay Own Voice  
Replay the previous recording of your voice (presumably after showing
the answer).

Display Order
-------------

Studying will show cards from the selected deck and any decks it
contains. Thus, if you select your “French” deck, the subdecks
“French::Vocab” and “French::My Textbook::Lesson 1” will be shown as
well.

For new cards and reviews, Anki fetches cards from the decks in
alphabetical order. So in the above example, you would get cards first
from “French”, then “My Textbook”, and finally “Vocab”. You can use this
to control the order cards appear in, placing high priority cards in
decks that appear higher in the list. When computers sort text
alphabetically, the “-” character comes before alphabetical characters,
and “\\~” comes after them. So you could call the deck “-Vocab” to make
them appear first, and you could call the other deck “~My Textbook” to
force it to appear after everything else.

New cards and reviews are fetched separately, and Anki won’t wait until
both queues are empty before moving on to the next deck, so it’s
possible you’ll be exposed to new cards from one deck while seeing
reviews from another deck, or vice versa. If you don’t want this, click
directly on the deck you want to study instead of one of the parent
decks.

Since cards in learning are somewhat time-critical, they are fetched
from all decks at once and shown in the order they are due.

To control the order reviews from a given deck appear in, or change new
cards from ordered to random order, please see the [deck
options](deck-options.md). For more fine-grained ordering of new cards, you
can change the order in the [browser](browsing.md).

Siblings and Burying
--------------------

Recall from [the basics](getting-started.md) that Anki can create more than one
card for each thing you input, such as a front→back card and a
back→front card, or two different cloze deletions from the same text.
These related cards are called 'siblings'.

When you answer a card that has siblings, Anki can prevent the card’s
siblings from being shown in the same session by automatically 'burying'
them. Buried cards are hidden from review until the clock rolls over to
a new day or you manually unbury them using the “Unbury” button that’s
visible at the bottom of the [deck overview](studying.md#study-overview) screen. Anki
will bury siblings even if the siblings are not in the same deck (for
instance, if you use the [deck override](templates/intro.md) feature).

You can enable burying from the [deck options](deck-options.md) screen -
there are separate settings for new cards and reviews.

Anki will only bury siblings that are new or review cards. It will not
hide cards in learning, as time is of the essence for those cards. On
the other hand, when you study a learning card, any new/review siblings
will be buried.

Keyboard Shortcuts
------------------

Most of the common operations in Anki have keyboard shortcuts. Most of
them are discoverable in the interface: menu items list their shortcuts
next to them, and hovering the mouse cursor over a button will generally
show its shortcut in a tooltip.

When studying, either space or enter will show the answer. When the
answer is shown, you can use space or enter to select the Good button.
You can use the 1-4 keys to select a specific ease button. Many people
find it convenient to answer most cards with space and keep one finger
on 1 for when they forget.

The "Study Deck" item in the Tools menu allows you to quickly switch to
a deck with the keyboard. You can trigger it with the '/' key. When
opened, it will display all of your decks and show a filter area at the
top. As you type characters, Anki will display only decks matching the
characters you type. You can add a space to separate multiple search
terms, and Anki will show only decks that match all the terms. So “ja 1”
or “on1 ja” would both match a deck called “Japanese::Lesson1”.

Falling Behind
--------------

If you fall behind in your reviews, Anki will prioritize cards that have
been waiting the longest. It does this by taking the the cards that have
been waiting the longest and showing them to you in a random order up
until your daily review limit. This ordering ensures that no cards will
be left waiting indefinitely, but it means that if you introduce new
cards, their reviews won’t appear until you’ve gotten through your
backlog.

If you wish to change the order of the overdue reviews, you can do so by
creating a [filtered deck](filtered-decks.md).

When you answer cards that have been waiting for a while, Anki factors
in that delay when determining the next time a card should be shown.
Please see the section on Anki’s spaced-repetition
[algorithm](faqs.md) for more information.
