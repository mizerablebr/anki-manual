Preferências
============

O menu de preferências está disponível a partir do menu Ferramentas no
Windows/Linux, ou no menu Anki caso seja um Mac.

Básico
------

A primeira opção de seleção vertical controla em qual idioma estará a interface
do Anki. Após selecionar um idioma, será necessário reiniciar o aplicativo para
que as mudanças tenham efeito.

Por padrão o Anki cola imagens da área de transferência como arquivos JPG, para
salvar espaço em disco. Caso deseje colá-las como PNG é possível ativar a opção
**Colar imagens da área de transferência como PNG**. Imagens em PNG suportam
plano de fundo transparente e são imagens sem perda de definição, mas geralmente
resultam em arquivos de tamanho maior.

Quando o **modo noturno*** estiver habilitado, o Anki mostrará o texto dos
cartões em branco e o fundo em preto. Alguns modelos de cartões talvez precisem
ser modificados para funcionar corretamente com essa opção habilitada. Por
favor, veja [estilo modo noturno](templates/styling.md#night-mode) para mais
informações.

Quando estiver usando o modo escuro em um Mac, versões recentes do Anki irão
automaticamente mudar para o modo noturno. Se você quiser forçar o Anki a usar o
modo claro enquanto estiver usando o modo escuro no restante do seu sistema
operacional, por favor instale a versão 2.1.21beta3 ou superior do Anki, e
instale a versão "-alternate" ao invés da "-standard".

O agendador do **agendador 2.1 do Anki** está documentado
[aqui](https://anki.tenderapp.com/kb/anki-ecosystem/experiment-scheduling-changes-in-anki-21).

A segunda opção de seleção vertical controla como os tipos de notas e os
baralhos interagem. O padrão de "Ao criar, o padrão é o baralho atual" significa
que o Anki irá salvar o último tipo de nota usado para cada baralho e
selecioná-lo novamente a próxima vez que você escolher o baralho (e, além disso,
a janela de adicionar cartões abrirá com o baralho atualmente selecionado). A
outra opção, "Mudar baralho dependendo do tipo de nota", salva o último baralho
utilizado para cada tipo de nota (e, ao abrir a janela de adicionar cartões,
selecionará o último tipo de nota utilizado). Esta opção pode ser mais
conveniente caso você sempre use um único tipo de nota para cada baralho.

Agendamento
-----------

A opção de seleção vertical da aba agendamento controla quando novos cartões
serão mostrados: antes, depois ou misturados com os cartões de revisão.

A opção **Novo dia começa às** controla quando o Anki deve começar a mostrar os
cartões do próximo dia. A configuração padrão é 4 horas além da meia noite
(04:00 da manhã). Essa configuração assegura que, se você estiver estudando por
volta da meia noite, você não terá a carga de trabalho de dois dias em uma única
sessão de estudos. Se você fica acordado até muito tarde ou acorda muito cedo,
talvez queira ajustar esse horário para um que melhor se ajuste ao horário que
você costuma dormir.

A opção **Aprender além do limite** diz ao Anki como se comportar quando não
houver mais nada para estudar no baralho atual exceto cartões em aprendizagem. A
configuração padrão de 20 minutos diz ao Anki que cartões devem ser mostrados
mais cedo caso possuam um intervalo menor do que 20 minutos. Se você selecionar
o valor 0 (zero) para essa opção, o Anki sempre esperará o intervalo completo do
cartão, mostrando a tela de parabéns até que os cartões restantes estejam
prontos para serem revisados.

**Tempo limite** é uma técnica para te ajudar a permanecer focado, dividindo um
longo tempo de atividade (digamos, uma sessão de estudos de 30 minutos) em
blocos menores. Se você configurar um valor diferente de zero para essa opção, o
Anki irá, periodicamente, mostrar quantos cartões você conseguiu estudar durante
o tempo limite especificado.

Rede
----

A aba de rede contém opções relacionadas à sincronização com a AnkiWeb. 

- Quando estiver logado, o botão **desautorizar** irá deslogá-lo.
- Quando a opção "Na próxima sincronização, obrigar mudanças em uma única
  direção" estiver habilitada, a proxima sincronização irá pergutá-lo se você
  deseja fazer upload ou download. Isso é útil caso você tenha feito alguma
  mudança acidentalmente e deseja sobrescrevê-la com uma versão mais antiga que
  está salva na AnkiWeb

