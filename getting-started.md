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

Quando você adiciona uma coleção nova, o Anki automaticamente acrescenta nela alguns tipos de notas padrão. Esses tipos de notas são fornecidos para tornar o Anki mais simples para novos usuários, mas com o passar do tempo é recomendado que você defina seus próprios tipos de nota para o conteúdo que esteja estudando. Os tipos de nota padrão são os seguintes:

Básico  
Possui os campos Frente e Verso e criará um cartão. O texto que for digitado em Frente aparecerá no anverso do cartão, e o texto digitado em Verso aparecerá no verso do cartão.

Básico (e cartão invertido)  
Como o básico, só que cria dois cartões com as informações que você digita: um para 
frente→verso e um para verso→frente.

Básico (cartão invertido opcional)  
Esse é um cartão frente→verso e opcionalmente um cartão verso→frente card. Para tanto ele possui um terceiro campo chamado “Adicionar Invertido”. Se você adicionar qualquer texto naquele campo, um cartão invertido será criado. Para mais informações sobre isso está disponível na seção [Cartões e Modelos](templates/intro.md).

Omissão de Palavras  
Um tipo de nota que torna simples o ato de selecionar um texto e transformá-lo em um teste de omissão de palavras (ex.: “O homem pousou na lua em […​\]” → “O homem pousou na lua em 1969”). Mais informações estão disponíveis na seção [omissão de palavras](editing.md#cloze-deletion).

Para adicionar os seus próprios tipos de nota e modificar os já existentes, você pode usar Ferramentas →
Gerenciar Tipos de Notas na janela principal do Anki.

Ao invés de serem limitadas a um baralho específico, notas e tipos de notas são comuns a todas as suas coleções.  Isso quer dizer que você pode usar vários tipos de notas diferentes e um baralho específico, ou ter cartões diferentes gerados de uma nota particular em baralhos diferentes. Quando você adiciona notas usando a janela Adicionar, você pode selecionar que tipo de nota usar e qual baralho utilizar, sendo que estas opções são completamente independentes entre si. Você também pode mudar o tipo de nota de algumas notas [mesmo após elas já terem sido criadas](browsing.md).

### Coleção

Sua 'coleção' é todo o material armazenado no Anki – seus cartões, notas, baralhos, tipos de notas, opções de baralho, e assim por diante.

## Baralhos Compartilhados

Você pode assistir [um vídeo sobre conceitos básicos em Baralhos Compartilhados e Revisão](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on) no YouTube.

A forma mais fácil de começar a usar o Anki é fazendo o download de um baralho de cartões que alguém tenha compartilhado:

1.  Pressione o botão “Pegar Partilhados” na parte inferior da lista de baralhos.

2.  Quando você encontrar um baralho em que esteja interessado, pressione o botão “Download” para baixar um pacote de baralhos.
    
3.  Dê um duplo-clique no pacote baixado para carregá-lo no Anki ou importe-o em Arquivo→Importar.

Por favor tenha em mente que não é possível adicionar baralhos compartilhados diretamente na sua conta AnkiWeb. Você precisa importá-los com o programa para computador e então sincronizar para carregá-los no AnkiWeb.

Criar o seu próprio baralho é a forma mais eficiente de aprender um assunto mais complexo. Assuntos como línguas e ciências não podem ser aprendidos apenas memorizando fatos — eles demandam explicação e contexto para um aprendizado efetivo. Além disso, digitar você mesmo as informações força você a decidir quais são os tópicos principais, levando-o a uma melhor compreensão.

Se você é um estudante de línguas, você pode se sentir tentado a baixar uma longa lista de palavras com suas respectivas traduções, mas isso não irá lhe ensinar uma língua, da mesma forma que decorar equações científicas são o ensinará astrofísica. Para aprender adequadamente, você precisa de livros texto, professores ou exposição a expressões do mundo real.

    Você não aprende se você não entende.
    --SuperMemo

A maioria dos baralhos compartilhados são criados por pessoas que estão aprendendo com materiais fora do Anki  – de livros texto, aulas, TV, etc. Eles selecionam os pontos de interesse do que eles aprenderam e colocam no Anki. Eles não se esforçam para adicionar informações de antecedentes ou explicações nos cartões porque eles já compreenderam o material. Então quando outra pessoa baixa seus baralhos e tenta utilizá-los eles vão sentir bastante dificuldade já que lhes faltarão as informações de antecedentes e as explicações.

Isso não quer dizer que baralhos compartilhados são imprestáveis – simplesmente que para assuntos complexos eles devem ser utilizados como um 'complemento' para um material externo, não um 'substituto' para ele. Se você está estudando o livro texto ABC e alguém já compartilhou um baralho de ideias do ABC, esta é uma ótima forma de poupar algum tempo. E para assuntos simples que são basicamente uma lista de fatos, como capitais ou perguntas e respostas de curiosidades, você provavelmente não precisa de um material extra. Mas se você tentar estudar um assunto complexo sem um material externo, você provavelmente irá ao encontro de resultados desapontadores.

