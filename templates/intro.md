# Modelos de Cartões

Os modelos de cartões contam ao Anki quais campos devem aparecer na frente e no
verso do seu cartão e controlam quais cartões serão gerados quando certos campos têm texto.
Ajustando seus modelos de cartões, você pode alterar o design e o estilo de muitos
dos seus cartões de uma vez só.

Modelos de cartões são explicados em alguns dos vídeos introdutórios (em inglês) a seguir:

-   [Switching Card
    Order](http://www.youtube.com/watch?v=DnbKwHEQ1mA&yt:cc=on)

-   [Styling Cards](http://www.youtube.com/watch?v=F1j1Zx0mXME&yt:cc=on)

-   [Typing in the
    Answer](http://www.youtube.com/watch?v=5tYObQ3ocrw&yt:cc=on)

## The Templates Screen {docsify-ignore}

You can modify card templates by clicking the "Cards..." button inside the
editing screen.

On the top left is the front template, on the bottom left is the back
template, and in between them is the card styling section.

In Anki, templates are written in HTML, which is the language that web
pages are written in. The styling section is CSS, which is the language
used for styling web pages.

On the right is a preview of the front and back of the currently
selected card. If you opened the window while adding notes, the preview
will be based on the text you had typed into the Add Notes window. If
you opened the window while editing a note, the preview will be based on
the content of that note. If you opened the window from Tools → Manage
Note Types, Anki will display each field’s name in parentheses in place
of content.

At the top right of the window is an Options button that gives you
options to rename or reorder the cards, as well as the following two
options:

-   The 'Deck Override' option allows you to change the deck that cards
    generated from the current card type will be placed into. By
    default, cards are placed into the deck you provide in the Add Notes
    window. If you set a deck here, that card type will be placed into
    the deck you specified, instead of the deck listed in the Add Notes
    window. This can be useful if you want to separate cards into
    different decks (for instance, when studying a language, to put
    production cards in one deck and recognition cards in another). You
    can check which deck the cards are currently going to by choosing
    Deck Override again.

-   The 'Browser Appearance' option allows you to set different (perhaps
    simplified) templates for display in the Question and Answer columns
    of the browser; see [browser appearance](templates/styling.md#browser-appearance) for more
    information.
