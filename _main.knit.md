--- 
title: "Neurohistologia UFTM"
author: "Arthur Corcovia (Hermes)"
date: "2025-01-30"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is a minimal example of using the bookdown package to write a book.
  The HTML output format for this example is bookdown::gitbook,
  set in the _output.yml file.
link-citations: yes
github-repo: rstudio/bookdown-demo
---

# About

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports; for example, a math equation $a^2 + b^2 = c^2$.

## Usage 

Each **bookdown** chapter is an .Rmd file, and each .Rmd file can contain one (and only one) chapter. A chapter *must* start with a first-level heading: `# A good chapter`, and can contain one (and only one) first-level heading.

Use second-level and higher headings within chapters like: `## A short section` or `### An even shorter section`.

The `index.Rmd` file is required, and is also your first book chapter. It will be the homepage when you render the book.

## Render book

You can render the HTML version of this example book without changing anything:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:


```r
bookdown::render_book()
```

To render this example to PDF as a `bookdown::pdf_book`, you'll need to install XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.org/tinytex/>.

## Preview book

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


```r
bookdown::serve_book()
```




<!--chapter:end:index.Rmd-->

# Encéfalo

Do ponto de vista neuroanatômico, o encéfalo corresponde à parte superior e de maior organização citoarquitetural do Sistema Nervoso Central (ou neuroeixo), estando constituído pela união de telencéfalo, diencéfalo, mesencéfalo, ponte, bulbo e cerebelo e delimitado inferiormente pela decussação das pirâmides bulbares, ponto da via corticoespinal fundamental para a projeção de eferências motoras. Funcionalmente, as estruturas encefálicas medeiam uma série de processos fisiológicos responsáveis por integrar as funções vegetativas do organismo e perceber e interpretar aspectos variados da interface entre este e o meio no qual ele se encontra inserido, a exemplo das funções cronobiológicas do núcleo supraquiasmático e da glândula epífise, do controle da fome e da ingestão alimentar determinado pela atividade de núcleos hipotalâmicos, da interpretação da linguagem promovida pela área de Wernicke e da decodificação visual efetuada por áreas secundárias do lobo occipital. Cabe também ressaltar que o encéfalo é responsável pelo controle de funções executivas superiores e pela realização do pensamento crítico complexo por intermédio de intrincados circuitos neuronais ainda não muito bem compreendidos, os quais possuem altas potências de plasticidade e se relacionam à personalidade, à motivação, à memória, ao comportamento e a outros fenômenos misteriosos da Neurofisiologia.

- figura de tomografia computadorizada por tratografia

Nesse sentido, é válido destacar que a consciência - tida como provavelmente a maior incógnita das neurociências - também advém das complexas organizações celulares e bioquímicas dos componentes do encéfalo, com especial destaque para o córtex cerebral. Desde a Antiguidade, múltiplas hipóteses têm sido formuladas a fim de se desvelar os mecanismos biofísicos e filosóficos subjacentes a tal fenômeno central da experiência humana, sendo que a Teoria da Complexidade configura-se atualmente como a proposta mais aceita pela comunidade científica para a explicação da consciência e de suas origens. Esta se originou no campo da Matemática e da Engenharia da Computação e postula que existe uma tendência natural de ocorrerem fenômenos dinâmicos não triviais em extensas redes de elementos interconectados, o que oferece uma base para a explicação de como a consciência poderia emergir a partir de uma circuitaria altamente complexa e organizada de células excitáveis. Nesse âmbito, pode-se citar que empreitadas científicas como o [Projeto Conectoma Humano](https://www.humanconnectome.org/), que visa ao mapeamento de todo o conjunto de sinapses existentes no Sistema Nervoso, são fundamentais não só para o aprimoramento da prática clínica como também para uma melhor compreensão da Biologia Celular e da Bioquímica que regem a Histofisiologia de um dos sistemas mais enigmáticos do organismo humano.

- boxe comentando sobre o projeto EyeWire e outras iniciativas de ciência cidadã

## Tecido Nervoso

Conforme proposto pelo neuroanatomista espanhol Santiago Ramón y Cajal, o tipo celular característico do Sistema Nervoso consiste numa célula altamente especializada estacionada mitoticamente na fase G~0~ e condutora de impulsos elétricos, por meio dos quais pode induzir a excitação de outras células: **o neurônio**.

Entretanto, deve-se ressaltar que, para que este cumpra corretamente seus papéis fisiológicos, faz-se necessária a presença de células de sustentação responsáveis por nutrirem, protegerem e mielinizarem os neurônios: **as células da glia**. Há estudos que apontam que essas células de características estromais são cerca de três vezes mais numerosas que os próprios neurônios e que, assim como eles, também apresentam padrões morfológicos extremamente específicos, que abrangem desde células com prolongamentos bastante ramificados a células de caráter epitelial cúbico simples com microvilosidades em suas membranas apicais.

No que tange à histogênese das populações celulares do tecido nervoso, é importante salientar que tanto os neurônios quanto as células da glia possuem **origem embrionária neuroectodérmica**, diferenciando-se a partir de precursores presentes nas zonas ventricular, intermediária e cortical do tubo neural por meio da ação de morfógenos como o fator de transcrição $SOX9$, o fator nuclear $I/A$, a glicoproteína $Wnt$ e a proteína sinalizadora $SHH$ (*sonic hedgehog*). Cabe mencionar, todavia, que as células da micróglia constituem uma importante exceção a esse padrão, originando-se de células mesenquimais precursoras eritromieloides encontradas no saco vitelínico. As células da micróglia apresentam em suas superfícies receptores para quimiocinas e outras moléculas inflamatórias, o que demonstra que elas possuem importantes funções no desenrolar da resposta imune inata e adaptativa no tecido nervoso. Nesse quesito, cabe dizer que a micróglia constitui parte do chamado Sistema Fagocítico Mononuclear, assim como as células de Kupffer, os osteoclastos e os macrófagos, compartilhando parte significativa de seu proteoma com essas células, a exemplo da proteína transmembrânica 19 $(TMEM19)$, do purinorreceptor P2Y $(P2RY12)$ e da proteína Sal-símile 1 $(SALL1)$

- boxe emrbiológico relembrando do processo de formação do tubo neural

### Neurônios {.unnumbered}

Na microscopia de luz, o componente mais reconhecível da morfologia neuronal básica é compreendido por uma região dilatada denominada **soma**, **pericário** ou **corpo celular**, na qual é possível observar um núcleo claro com predomínio de eucromatina e nucléolos evidentes situado adjacente a uma área intensamente basofílica conhecida como **ergastoplasma** ou **corpúsculo de Nissl**, nome que se dá para o retículo endoplasmático rugoso nessa população celular. Essas características ultraestrutruais indicam que essas células apresentam intensa atividade de síntese proteica, o que faz sentido de um ponto de vista fisiológico, haja vista que a comunicação entre dois neurônios se dá predominantemente através da liberação de mediadores químicos em regiões do meio extracelular conhecidas como fendas sinápticas. Do ponto de vista bioquímico, essas moléculas sinalizadoras muitas vezes são aminoácidos, a exemplo da glicina e do glutamato, ou derivados de aminoácidos, como a acetilcolina e a dopamina, o que justificaria a síntese de componentes proteicos aumentada nos neurônios. Ademais, vale relembrar que, tal como os cardiomiócitos e outras células mitoticamente inativas, os neurônios apresentam grânulos de lipofuscina em seus citoplasmas, identificáveis por meio de técnicas imunohistoquímicas.

- fotomicrografia de um corpo celular neuronal identificando os principais elementos grifados

No processo de condução do impulso nervoso, corpo celular recebe potenciais excitatórios e inibitórios provenientes de pequenos prolongamentos similares aos galhos de uma árvore, denominadas **dendritos** (do grego; *"dendron"*, *galhos*), nos quais é possível encontrar especializações de membrana conhecidas como espículas dendríticas, que possuem a função de aumentar a superfície de contato nas sinapses axoespinhosas. Após o pericário efetuar somações espaciais e temporais dos estímulos recebidos por meio dos prolongamentos dendríticos, estes são transmitidos para um grande prolongamento cilíndrico único denominado **axônio**, o qual se prende ao corpo celular por meio de uma região livre de ergastoplasma denominada **cone de implantação**. A abertura de canais de Na^+^ voltagem-dependentes nessa região possibilita a ocorrência de um evento elétrico no qual se observa uma onda de despolarização viajando unidirecionalmente ao longo do protoplasma axonal em direção ao terminal sináptico, fenômeno conhecido como potencial de ação. Quando esse potencial de ação chega no terminal sináptico, ele promove a abertura de canais de Ca^2+^ voltagem-dependentes na membrana dessa região, permitindo a entrada de íons Ca^2+^ para o citoplasma neuronal, promovendo, por conseguinte, a exocitose de vesículas de secreção contendo neurotransmissores, os quais são liberados para a fenda sináptica.

- boxe bioquímico sobre as vias de biossíntese dos neurotransmissores a partir dos aminoácidos

É interessante notar que as morfologias celulares dos neurônios podem variar drasticamente de acordo com o órgão analisado e suas respectivas funções, de forma que podem ser elencados como tipos básicos de neurônios os **unipolares**, os **bipolares**, os **pseudounipolares** e os **multiploares**. Em suma, as características básicas de cada um desses perfis estruturais básicos encontram-se resumidas a seguir.

#### Neurônios unipolares {.unnumbered}

Apresentam um corpo celular do qual parte um único axônio, não possuindo prolongamentos dendríticos. São extremamente raros no organismo humano, podendo ser encontrados no epitélio sensitivo da mucosa olfatória e na retina.

- esquema de um neurônio unipolar e fotomicrografia da mucosa olfatória e da retina

#### Neurônios bipolares {.unnumbered}

Nessas células, o pericário se encontra diretamente interposto entre dois prolongamentos protoplasmáticos, sendo que o sinal recebido pelos dendritos é conduzido até o corpo celular por meio de um prolongamento citoplasmático único formado pela união dos vários dendritos. Ao chegar no corpo celular, o sinal elétrico é então transmitido até o terminal sináptico por meio do axônio. Vale frisar que é possível encontrar neurônios dessa categoria nos gânglios coclear e vestibular, na retina e na mucosa olfatória, estruturas anatômicas envolvidas na captação dos sentidos especiais.

- esquema de um neurônio bipolar e fotomicrografia da mucosa olfatória e da retina

#### Neurônios pseudounipolares {.unnumbered}

Originam-se a princípio como neurônios bipolares, porém, o corpo celular se desloca lateralmente aos prolongamentos celulares, de forma que estes se fundem num filamento contínuo em relação ao qual o corpo celular se encontra interposto **indiretamente**, através de uma curta ponte de citoplasma. Esses neurônios se encontram intrinsicamente relacionados à percepção sensitiva, podendo ser encontrados, por exemplo, nos gânglios sensitivos de nervos espinais e em alguns gãnglios de nervos cranianos como o trigêmeo (NC V), principal estrutura nervosa relacionada à propriocepção consciente, à sensibilidade vibratória e ao tato epicrítico na face. Dessa forma, ainda é possível pensar essa classe de neurônios como células detentoras de um prolongamento único, o qual se bifurca num prolongamento centrífugo de características dendríticas responsável por captar estímulos da periferia do organismo e num prolongamento centrípeto de natureza axonal dedicado a encaminhar tais estímulos ao Sistema Nervoso Central.

- esquema mostrando o processo de formação dos neurônios pseudounipolares e fotomicrografia dos neurônios dos gânglios das raízes sensitivas dorsais

- boxe clínico acerca do tropismo do herpes zoster por esses gânglios e o aparecimento de lesões segundo dermátomos

#### Neurônios multipolares {.unnumbered}

Apresentam uma morfologia celular típica do que se costuma vir à mente ao se pensar em nerurônios, com o pericário recebendo vários prolongamentos dendríticos e emitindo um único e longo prolongamento axonal. Vale mencionar que, assim como os demais tipos de neurônios previamente abordados, nos neurônios multipolares também é possível observar a presença de neurofilamentos ao longo do axônio, filamentos intermediários do tipo IV que servem como biomarcadores de diversas doenças neurodegenerativas com prognóstico grave, a exemplo da neuropatia axonal gigante, da esclerose lateral amiotrófica e da Doença de Alzheimer. Essa classe de neurônios é a mais numerosa do corpo, sendo possível encontrar uma grande pluralidade morfológica dentre os neurônios que a compõem. Tal pluralidade fica muito evidente ao compararmos neurônios multipolares de diferentes regiões do Sistema Nervoso. Enquanto as células de Betz situadas na camada piramidal interna do córtex motor primário são caracterizadas por seus formatos triangulares, as células de Purkinje do córtex cerebelar são marcadas por possuírem profusas ramificações dendríticas. Por outro lado, os neurônios parvocelulares dos núcleos hipotalâmicos responsáveis pela secreção de hormônios hipofisiotróficos são facilmente noticiáveis por conta das dimensões reduzidas do corpo celular. 

- fotomicrografias das categorias de neurônios supramencionadas

É importante destacar que, levando-se em consideração a extensão dos axônios dos neurônios multipolares, eles podem ainda ser separados em dois subtipos:

-   **Golgi tipo I:** apresentam axônios longos que se estendem para além dos limites da árvore dendrítica.
-   **Golgi tipo II:** seus axônios são muito curtos e não extrapolam os limites da região ocupada pelos prolongamentos dendríticos. Podem ainda ser isentas de axônios.

- fotomicrografia de material de córtex cerebral corado pela prata, traçando uma diferenciação clara entre neurônios de Golgi tipo I e neurônios de Golgi tipo II

- boxe embriológico sobre a maturação da barreira hematoencefálica e a relevância de se considerar esse fenômeno para a compreensão da fisiopatologia do Kernicterus

### Células da Glia {.unnumbered}

No que concerne às **células da glia** (também conhecidas como **gliócitos**) e suas amplas variedades histofuncionais, é possível notar que essas populações celulares possuem as capacidades necessárias para promover mecanismos de **suporte às atividades de condução nervosa desempenhadas pelos neurônios**, direta ou indiretamente. Nesse contexto, a fagocitose de potenciais patógenos, a produção de líquido cerebroespinal (importante fluido corporal que banha o Sistema Nervoso Central e o protege de choques mecânicos) e a realização da drenagem glinfática durante o sono podem ser elencadas como algumas das múltiplas funções desempenhadas pelos gliócitos a fim de se resguardar a homeostase do tecido nervoso. Apesar das células da glia apresentarem características morfológicas altamente diversificadas, todas elas possuem uma origem embrionária neuroectodérmica em comum, à exceção das células de micróglia.

- boxe farmacológico sobre as células da glia e o desenvolvimento de fármacos que atuem sobre neuromoduladores liberados por elas

Sob uma perspectiva patológica, é relevante destacar que, enquanto os neurônios apresentam baixas capacidades regenerativas e se encontram permanentemente estacionados na fase G~0~ do ciclo celular fora das esparsas regiões correspondentes a nichos neuronais (como o córtex entorrinal da formação hipocampal), as células da glia são mitoticamente ativas e podem se proliferar descontroladamente mediante processos neoplásicos, originando tumores conhecidos como **gliomas**, que, por sua vez, abrangem glioblastomas, astrocitomas, oligodendromas, Schwannomas, ependimomas, dentre outras espécies de neoplasias. Ademais, frente a processos de morte celular dos neurônios (o que pode se dar de forma mais pronunciada na Síndrome de Wernicke-Korsakoff e na Doença de Tay-Sachs), as células da glia passam a ocupar o lugar das células nervosas lesionadas, limpando restos celulares e preenchendo o tecido danificado nesse processo, de maneira análoga ao que é observado na fibrose do miocárdio após episódios isquêmicos desencadeados por obstruções das artérias coronárias. A esse processo, dá-se o nome de **gliose**.

- boxe sobre a biologia celular do processo de gliose

Para a devida compreensão acerca das populações celulares que compõem as células de glia e suas respectivas características funcionais, é necessário termos em mente alguns pontos-chave, dos quais trataremos logo a seguir.

#### Astrócitos {.unnumbered}

Do grego, o nome dessa população celular se traduz literalmente como "células-estrela", o que reflete suas geometrias altamente ramificadas e fractalizadas. Embriologicamente, temos que os astrócitos se originam dos glioblastos que migram para a placa cortical do tubo neural mediante a histogênese do tecido nervoso. São células com núcleos grandes, ovoides e de baixa afinidade tintorial pela coloração HE e emitem um grande número de prolongamentos citoplasmáticos, os quais acabam em regiões dilatadas denominadas **pés terminais**, responsáveis por estabelecerem conexões entre os vasos sanguíneos que vascularizam o Sistema Nervoso e seus neurônios. Os pés terminais que contatam a lâmina basal dos capilares presentes no interior do tecido nervoso também são chamados de pés vasculares e contribuem para a formação da **barreira hematoencefálica**, uma barreira capilar de caráter protetivo que impede que substâncias neurotóxicas se impregnem no tecido nervoso causando lesões irreversíveis. Além disso, existem evidências de que essas células desempenham papéis potencialmente relevantes na regulação da concentração iônica do meio extracelular, na sinaptogênese, na absorção de excesssos de neurotransmissores, na produção de compostos neuromoduladores e no acoplamento metabólico de vias de glicólise neuronais. Nesse último aspecto, é interessante mencionar que se sabe que os astrócitos se encontram metabolicamente interligados por meio de junções comunicantes, de modo que não seria improvável que essas especializações de membrana também estivessem presentes na interface astrócito-neurônio, permitindo o fluxo de metabólitos entre os citoplasmas dessas células. Outras funções importantes desempenhadas pela população celular em enfoque são a **drenagem glinfática** e a formação da **glia limitante**, uma zona com altas densidades de pés astrocitários que se estende ao longo das fronteiras entre compartimentos ocupados por líquor cefalorraquidiano (como os ventrículos cerebrais) e os compartimentos preenchidos por fluido intersticial (como o parênquima cerebral).

- boxe anatômico sobre a glia limitante e sua importância funcional

Os astrócitos podem ser caracterizados como **astrócitos fibrosos**, predominantes em regiões de substância branca e detentores de longos prolongamentos que pouco se ramificam, ou **astrócitos protoplasmáticos**, situados preferencialmente em áreas de substância cinzenta e identificáveis por meio de seus prolongamentos curtos, porém muito ramificados.

- fotomicrografia mostrando diferença entre astrócitos fibrosos e protoplasmáticos

Em técnicas de imunohistoquímica, os astrócitos podem ser marcados fazendo-se uso de anticorpos direcionados contra a proteína ácida fibrilar glial $(GFAP)$, um filamento intermediário do tipo III que pode ser alvo de autoanticorpos em astrocitopatias.

- imagens de TC em diferentes séries mostrando um caso de astrocitopatia por autoimunidade contra GFAP1

#### Micróglia {.unnumbered}

Foram inicialmente descritas em 1919 pelo pesquisador espanhol Pio del Rio-Hortega, motivo pelo qual também são conhecidas pelo epônimo "células de Hortega". Não compartilham uma origem embriológica em comum com as demais células da glia e os neurônios, mas sim com as células do **Sistema Fagocítico Mononuclear**, sendo originadas a partir de células precursoras eritromieloides situadas no saco vitelínico que migram para o Sistema Nervoso quando este é invadido por componentes vasculares. Apresentam ramificações curtas e irregulares, que tendem a ser emitidas ortogonalmente umas às outras, além de núcleos pequenos, alongados e intensamente corados nas preparações de rotina, o que constrasta nitidamente com as demais células da glia. Em razão de tais diferenças estruturais e embriológicas consideráveis, as outras células da glia também podem ser chamadas coletivamente de macróglia, em contraposição à população celular aqui descrita. Essas células microgliais medeia uma série de funções relacionadas às **imunidades inata e adaptativa** e à **resposta inflamatória**, sendo capazes de fagocitarem, processarem e apresentarem antígenos, liberarem quimiocinas e outros mediadores inflamatórios e removerem restos apoptóticos e fragmentos celulares de áreas de tecido lesadas.

- fotomicrografia de células da neuróglia

Além disso, a micróglia - que compreende aproximadamente 12% de todas as células do encéfalo - também parece estar envolvida na plasticidade neuronal, particularmente na destruição sinapses disfuncionais. É possível que tal característica funcional da micróglia se encontre hiperativa em doenças neurodegenerativas como o Alzheimer e o Parkinson em virtude de um estresse metabólico aumentado sobre o tecido nervoso, explicando em partes os mecanismos fisiopatológios de atrofia neuronal e desestruturação sináptica verificados nesses quadros.

- boxe patológico sobre os possíveis sistemas de eliminação das placas beta-amiloides e de como a micróglia e o sistema glinfático pode ter participação ativa como elementos de neuroproteção

#### Células ependimárias {.unnumbered}

Correspondem a células cúbicas ou cilíndricas dispostas de forma similar a um epitélio simples ao longo de todas as estruturas embriologicamente derivadas do lúmen do tubo neural, como o canal ependimário da medula espinal, o quarto ventrículo, o aqueduto de Sylvius, o terceiro ventrículo e os ventrículos laterais. Essas células têm origem histogenética dos ependimoblastos localizados na zona ventricular do tubo neural, os quais, por sua vez, originam-se a partir de células ventriculares. Morfologicamente, verifica-se a eventual presença de microvilosidades e cílios nos domínios de membrana apicais dessas células, o que se relaciona intrinsicamente às funções de **produção e movimentação do líquido cerebroespinal** desempenhadas por elas, as quais se encontram aderidas umas às outras por meio de junções de adesão. No **plexo coroide**, todavia, essas especializações de membrana são substituídas por junções de oclusão mais coesas, contribuindo para a formação da barreira hematoliquórica, que impede a mistura de substâncias entre os capilares fenestrados da tela coroidea e o líquor circulante no interior dos ventrículos encefálicos.

- boxe anatômico traçando um paralelo biomecânico entre o princípio de Pascal na hidrostática e a função protetiva do LCR contra choques mecânicos

#### Tanicitos {.unnumbered}

Constituem o epêndima conjuntamente às células ependimárias. Apresentam uma morfologia intermediária entre aquelas descritas anteriormente para os astrócitos e as células ependimárias e são embriologicamente derivadas das células da **glia radial** bipolar. Vale apontar que um aspecto estrutural ímpar dessas células é a presença de um prolongamento basal único que atravessa a camada de pés terminais astrocitários da glia limitante para se dilatar próximo a um vaso sanguíneo, formando uma espécie de pé vascular. Estudos recentes propõem que essa população celular misteriosa esteja envolvida em mecanismos de regulação da saciedade e do apetite e no controle da liberação de gonadotrofinas por meio da regulação dos níveis de $GnRH$.

- imagem de imunofluorescência mostrando a morfologia misteriosa dos tanicitos

- boxe embriológico explicando o que é a glia radial e sua importância para a histogênese do tecido nervoso (acompanha a imagem que já coloquei)
![(\#fig:unnamed-chunk-4)As células gliais radiais se prolongam por toda a extensão da parede do tubo neural e são fundamentais para coordenar a migração de diferentes populações celulares durante a histogênese do Sistema Nervoso. VZ: zona ventricular; SVZ zona subventricular; IZ: zona intermediária; CP: placa cortical. [@mirandanegrón2022]](images/neuro-radialglia.jpg) 

#### Células de Schwann e oligodendrócitos {.unnumbered}

Esses tipos celulares são responsáveis por garantir uma condução mais eficiente e célere de impulsos elétricos através dos axônios neuronais por meio da **mielinização de fibras nervosas**, processo que possibilita a condução saltatória dos potenciais de ação por meio dos nós de Ranvier, pequenos intervalos de membrana desnuda interpostos entre as bainhas de mielina, áreas de revestimento lipídico eletrodinamicamente isolante. Essas células costumam apresentar poucas ramificações (conforme já se pode antever pela própria etimologia grega da palavra "oligodendrócito"), as quais são primordiais para a fisiologia da mielinização na medida em que se enrolam repetidamente sobre os axolemas neuronais. Nesse âmbito, é necessário destacar que, ao passo que os **oligodendrócitos** são exclusivos do Sistema Nervoso Central e são capazes de mielinizarem vários axônios ao mesmo tempo, as **células de Schwann** podem ser observadas exclusivamente no Sistema Nervoso Periférico e podem mielinizar, cada uma, apenas um curto segmento de um dado axônio.

- fotomicrografias e esquemas mostrando as diferenças entre as células de Schwann e os oligodendrócitos

Como resultado desses enrolamentos, essas células gliais formam alguns marcos estruturais idetificáveis por meio da microscopia eletrônica de transmissão e muito úteis para o estudo ultraestrutural das doenças desmielinizantes. Estes correspondem ao **mesaxônio externo**, uma esprial de **linhas intraperiódicas** (delimitadas pelo espaço extracelular compreendido entre duas voltas sucessivas do prolongamento mielinizador), uma espiral de **linhas densas principais** (formadas por uma pequena quantidade de citoplasma dos prolongamentos das células mielinizadoras interposta entre dois folhetos internos da estrutura trilaminar de suas membranas plasmáticas, as quais se encontram quase fundidas) e um **mesaxônio interno**.

- eletromicrografia mostrando a ultraestrutura da bainha de mielina

Cabe ressaltar que o processo de mielinização é absurdamente complexo do ponto de vista da Biologia Celular. Resumidamente, seria possível afirmar que, para que a mielina resultante seja viável, são necessárias junções de conexão e de oclusão homotípicas e heterotípicas, proteínas transmembranares responsáveis por compactarem as diversas camadas da espiral formada pelo enrolamento do axônio nos prolongamentos das células mielinizantes (com especial destaque para a proteína zero de mielina e a proteína proteolipídica) e volumes residuais de citoplasma interrompendo a continuidade das linhas densas principais em alguns pontos, correspondendo às **incisuras de Schmidt-Lantermann**.

- boxe mostrando as incisuras de Schmidt-Lantermann e explicando hipóteses acerca de suas possíveis funções

Sob a óptica da Neuropatologia, tem-se que as principais doenças que afetam o processo de mielinização decorrem ou de autoimunidades contra proteínas nele envolvidas (como no caso da esclerose múltipla e da Síndrome de Guillain-Barré) ou de mutações nos genes que as codificam. Para se exemplificar esse último cenário, poderíamos pensar na doença de Charcot-Marie-Tooth ligada ao cromossomo X, onde há um defeito molecular na conexina 32 presente nas junções de comunicação homotípicas presentes nas céulas de Schwann, e na doença de Charcot-Marie-Tooth dos tipos 1B e 2, situação na qual anomalias na proteína zero de mielina levam a prejuízos na compactação das bainhas lipídicas formadas pelos prolongamentos mielinizantes.

![(\#fig:unnamed-chunk-5)A proteína 0 da mielina (P0) é um dos principais agentes moleculares envolvidos na mielogênese da fibras nervosas no Sistema Nervoso Periférico, de modo que anomalias em sua estrutura, as quais podem ocorrer nas doenças de Charchot-Marie-Tooth e de Dejerine-Sottas, desempenham um papéis centrais na etiopatogênese de neuropatias periféricas de natureza genética. Observamos que as proteínas P0 formam homodímeros ao longo das linhas intraperiódicas, sendo cada molécula desses complexos constutuída por três domínios proteicos: uma região semelhante a imunoglobulinas (*Ig-like*) que atua como um zíper, aproximando as membranas plasmáticas adjacentes, um segmento transmembrânico composto por α-hélices e um prolongamento citoplasmático (P0~ct~) rico em resíduos de arginina e lisina. Em faixas de $pH$ fisiológicas, P0~ct~ apresenta carga positiva e teoriza-se que, por conta disso, esse domínio proteico seja capaz de interagir com esteróis, fosfolipídeos e esfingomielinas presentes no folheto interno da membrana plasmática onde se ancora, modificando seu ponto de fusão. Essa interação é importante do ponto de vista biofísico, pois desfavorece ocorrência da fase de gel ordenado na bainha de mielina, o que parece estar diretamente relacionado a manutenção de suas funções. [@raasakka2019]](images/neuro-p0myelin.png) 
- imagens de estrutura proteica terciária computacional mostrando as proteínas zero de mielina ancorando-se entre dois folhetos de membrana plasmática adjacentes 

## Caso Clínico: Raiva

<!--chapter:end:01-intro.Rmd-->

# Cérebro

Anatomicamente, o cérebro pode ser considerado, sem sombra de dúvidas, a estrutura mais importante do Sistema Nervoso Central, podendo ser dividido em 47 áreas de Brodmann relacionadas aos mais diversos aspectos da experiência humana, tais como o processamento auditivo central, a empatia, a sensibilidade térmica e dolorosa, a linguagem, a cognição lógico-matemática, a personalidade e a memória. Além disso, temos também inúmeras estruturas subcorticais e diencefálicas vinculadas a mecanismos de analgesia, ao aprendizado motor e ao controle de funções vegetativas.

<!-- - mapa das áreas de Brodmann junto com legenda explicando as funções das principais delas -->

De uma perspectiva neuroembriológica, tem-se que o cérebro se desenvolve a partir da extremidade cefálica do tubo neural, formada a partir do fechamento do neuróporo rostral durante a quarta semana de desenvolvimento. Esse evento permite a formação de três vesículas encefálicas primárias, as quais correspondem, de rostral a caudalmente, ao **prosencéfalo**, ao mesencéfalo e ao rombencéfalo. Na  quinta semana de desenvolvimento, o prosencéfalo se divide em duas vesículas encefálicas secundárias, correspondentes ao **telencéfalo**, o qual originará os hemisférios cerebrais, e ao **diencéfalo**. Deste são oriundas estruturas do:

-   **tálamo**, o grande _relé_ sensitivo do Sistema Nervoso.
-   **metatálamo**, onde estão abrigados os corpos geniculados essenciais para as vias visual e auditiva. 
-   **epitálamo**, onde se situa a glândula pineal. 
-   **hipotálamo**, principal central de controle vegetativo do organismo.
-   **subtálamo**, fundamental para a frenagem de movimentos através da ativação da via indireta dos núcleos da base.

Nesse âmbito, é interessante mencionar que a **protuberância óptica** se desenvolve a partir do diencéfalo na sexta semana de desenvolvimento embrionário, o que justifica a sintopia mantida entre certas estruturas diencefálicas e os nervos ópticos, o quiasma óptico e os tratos ópticos.

No processo de histogênese do prosencéfalo, distinguem-se duas populações celulares primordiais: os **neuroblastos** e os **glioblastos**. Enquanto estes darão origem às populações celulares progenitoras dos gliócitos integrantes da macróglia (ou seja, os astroblastos e os oligodendroblastos), aqueles se diferenciarão sequencialmente em neuroblastos bipolares, neurblastos unipolares e neurônios. Vale salientar queé possível que aconteçam interconexões entre os processos de neurogênese e gliogênese, dentre as quais a **transformação gliogênica** se configura como mecanismo mais comum de conversão de neuroblastos em glioblastos. Finalmente, é preciso ressaltar que, no prosencéfalo, ocorre a migração dos neurônios originados na zona intermediária do tubo neural para a placa cortical, explicando a organização tecidual dos hemisféricos cerebrais num córtex composto por substância cinzenta, onde podem ser visualizados corpos celulares de neurônios, e num centro sensorial composto predominantemente por prolongamentos axônicos de tais neurônios corticais.

<!-- - esquema mostrando as diferentes zonas hitogenéticas do tubo neural. -->

No que tange à citoarquitetura dos circuitos neuronais complexos encontrados no córtex cerebral, vale mencionar que esta apresenta variações significativas conforme o grau de desenvolvimento filogenético da espécie estudada e a região cortical analisada. No entanto, é válido afirmar que, para todas as espécies, observa-se uma **organização laminar** das camadas de células do córtex cerebral, de modo que, usualmente, o córtex se encontra dividido em 6 camadas distintas. Quanto à classificação filogenética dessas regiões cerebrais, vislumbra-se uma subdivisão das áreas corticais em:

-   **arquicórtex**, típico da formação hipocampal.
-   **paleocórtex**, característico do rinencéfalo e de áreas olfativas.
-   **neocórtex**, presente ao longo de 95% de toda a extensão cortical, correspondendo ao território compreendido pelo isocórtex.

<!-- - mapa filogenético do cérebro de diferentes espécies de mamíferos e animais em geral. -->

Por outro lado, sob uma perspectiva citoarquitetural, o córtex cerebral pode ser classificado como:

-   **isocórtex**, quando estão presentes todas as camadas corticais, que são, de exterior para interior: a camada plexiforme ou molecular, a camada granular externa, a camada das células piramidais, a camada granular interna, a camada ganglionar e a camada das células multiformes.
-   **alocórtex**, no qual ao menos uma das seus camadas supramencionadas se faz ausente.

<!-- - corte histológico impregnado por prata mostrando a organização das camadas do isocórtex. -->

O isocórtex ainda pode ser segmentado em três categorias, o que reflete o alto grau de especialização de diferentes áreas corticais para a efetuação dos mais variados tipos de tarefas e funções. Essas subcategorias são definidas com base no predomínio diferencial de uma camada cortical específica sobre as outras e compreendem as seguintes classificações:

-   **isocórtex homotípico**, encontrado em áreas de associação e caracterizado por possuir estratos de espessuras similares entre si.
-   **isocórtex heterotípico agranular**, observado em áreas motoras primárias e secundárias e organizado de tal maneira que se nota um claro predomínio das camadas compostas por células piramidais sobre os demais estratos corticais.
-   **isocórtex heterotípico granular**, verificado em áreas sensitivas, nas quais existe uma dominância das camadas granulares sobre as outras.

Todavia, é preciso ressalvar que a boa visualização dessas camadas corticais e, por conseguinte, a classificação das áreas observadas de acordo com suas características citoarquiteturais e filogenéticas, só podem ser atingidas mediante o  emprego de técnicas refinadas de imunofluorescência, as quais possibilitam a marcação dos tipos celulares típicos de cada estrato cortical de acordo com as proteínas expressas especificamente por cada um deles. Nesse contexto, é possível mencionar as seguintes populações celulares para cada lâmina do córtex cerebral:

-   **Camada molecular**: nesse estrato cortical, há o predomínio de **prolongamentos axonais e dendríticos** de neurônios subjacentes, não sendo possível encontrar uma grande quantidade de células. Entretanto, ocasionalmente se pode deparar com gliócitos e **células horizontais de Cajal** (também denominadas células de Cajal-Retzius), neurônios glutamatérgicos e $GABA$érgicos fundamentais na mediação do processo de corticogênese via secreção de reelina, uma proteína sinalizadora morfogenética.

<!-- - boxe com um esquema de sinalização celular mostrando a função da reelina e a importância dela para a embriologia. -->

-   **Camada granular externa**: essa camada se encontra composta por densas aglomerações de **células piramidais** e **células granulares**. Enquanto estas correspondem a neurônios multipolares do tipo II de Golgi e também são conhecidas como **células estreladas**, aquelas correspondem a neurônios multipolares do tipo I de Golgi e são os principais tipos de neurônios disparados na ativação do trato corticoespinal e na cognição.

-   **Camada das células piramidais (ou piramidal externa)**: nessa lâmina do córtex cerebral, nota-se um significativo predomínio de **células piramidais** com pericários de tamanho médio. Vale salientar que, como uma regra geral para essa população celular, observa-se que seus corpos celulares aumentam progressivamente de tamanho conforme mais profundamente se vai adentrando no córtex cerebral. Além dessas células, também se pode encontrar ocasionalmente **células de Martinotti**, pequenas células poligonais de prolongamentos dendríticos curtos relacionadas à inibição das atividades das células piramidais adjacentes, podendo, dessa maneira, desempenharem funções relevantes no controle motor.

-   **Camada granular interna**: esse estrato do córtex cerebral é constituído primariamente por **células estreladas** e é tido como a primeira camada cortical a receber aferências talâmicas, sendo, portanto, responsável por retransmiti-las às demais regiões do córtex. Em cortes do giro estriado (área 17 de Brodmann, também conhecida como área visual primária), é possível observar de modo nítido neurônios constituintes da via visual estabelecendo conexões com as células granulares da camada granular interna por meio das **fibras geniculocalcarinas**, as quais formam a Estria de Gennari, faixa esbranquiçada facilmente reconhecível à examinação macroscópica.

<!-- - imagem de macroscopia mostrando a Estria de Gennari. -->

-   **Camada granular (ou piramidal interna)**: nessa região do plano estratimérico do córtex cerebral, pode-se visualizar grandes quantidades de **células piramidais** com somas de dimensões amplas e quantias consideráveis de células estreladas e de Martinotti. No giro pré-central, correspondente à área motora primária, essa camada abriga as **células de Betz**, os maiores neurônios de todo o Sistema Nervoso e as principais ativadoras de motoneurônios \u03B1 inferiores, estabelecendo sinapses excitatórias glutamatérgicas com estes e projetando-se por meio dos tratos corticoespinais lateral e anterior.

-   **Camada das células multiformes**: apresenta uma gama variada de populações celulares, abrigando células piramidais pequenas, células de Martinotti, células estreladas e **células fusiformes**. Estas apresentam morfologia alongada, porém, diferentemente das células horizontais de Cajal, dispõem-se perpendicularmente à superfície do córtex cerebral. As células fusiformes encontram-se funcionalmente relacionadas ao envio de impulsos neuronais para outras áreas corticais e para o tálamo.

Assim como outras estruturas do neuroeixo, o cérebro se encontra revestido por uma série de folhetos de tecido conjuntivo responsáveis por, dentre outras funções, fornecer proteção mecânica ao tecido nervoso, permitir a nutrição de seus componentes e promover a drenagem sanguínea do encéfalo por meio dos seios venosos. Tais membranas conjuntivas correspondem às meninges e, do ponto de vista estratimérico, elas correspondem, da mais externa para a mais interna, à **dura-máter**, à **aracnoide-máter** e à **pia-máter**.

A dura-máter se encontra aderida ao periósteo dos ossos da calota craniana no encéfalo e forma pregas responsáveis por compartimentalizarem a parte cefálica do paquímero dorsal do corpo, tais como a **foice do cérebro**, o **tentório do cerebelo** e a **foice do cerebelo**. Além disso, essa meninge é composta por um folheto externo e um folheto interno, os quais podem se separar em determinadas regiões para formarem importantes **seios venosos**, como os seios sigmoides, os seios transversos, o seio sagital superior e o seio sagital inferior, fundamentais para a drenagem venosa do parênquima encefálico.

Internamente à dura-máter, pode-se encontrar a aracnoide-máter, a qual é dividida numa parte mais externa que fica aderida à dura-máter e contribui para a formação de uma camada meníngea protetora espessa (a **paquimeninge**) e numa parte trabecular que se aprofunda em direção ao **espaço subaracnoideo**, principal reservatório de líquor cefalorraquidiano no Sistema Nervoso Central. De uma perspectiva histológica, pode-se dizer que a aracnoide-máter é composta fundamentalmente de tecido conjuntivo denso e **células meningoteliais** revestindo o espaço subaracnoideo.

<!-- - boxe explicando as funções das membranas serosas e do mesotélio e falando das células meningoteliais como possível quarto mesotélio do corpo. -->

Ainda mais internamente à aracnoide-máter, pode-se visualizar a pia-máter, o folheto meníngeo **mais delicado e vascularizado**, que se encontra intimamente aderida ao tecido nervoso e revestida por células meningoteliais de origem embrionária mesenquimatosa. Pelo espaço subaracnoideo transitam artérias dedicadas à irrigação de estruturas cerebrais e esses vasos adentram o parênquima encefálico por meio de canais revestidos por pia-máter e preenchidos por um delgado espaço fisicamente contíguo ao espaço subaracnoideo, denominado espaço perivascular ou **espaço de Virchow-Robbin**.

<!-- - diagrama (imagem de livro de Histologia ou Anatomia) mostrando a estrutura do espaço de Virchow-Robbin -->

<!-- ## Caso Clínico: Meningoencefalite criptocócica -->

<!--chapter:end:02-A.Rmd-->

# Cerebelo

De uma perspectiva neuroanatômica, o cerebelo (cuja etimologia latina significa _pequeno cérebro_) corresponde a um órgão do compartimento infratentorial especializado em mecanismos de **coordenação motora**, **aprendizado motor** e **correção dos movimentos corporais**, conectando-se com estruturas tais como o tálamo, o complexo olivar inferior bulbar, o córtex motor, o aparellho vestibular e a medula espinal. Morfologicamente, o cerebelo se situa posteriormente ao quarto ventrículo e se conecta com o tronco encefálico por meio de três pares de pedúnculos cerebelares (superior, médio e inferior), por onde trafegam vias e tratos neuronais responsáveis pelas mais variadas funções desse componente do Sistema Nervoso, que vão desde o planejamento motor junto às áreas 5 e 7 de Brodmann até papéis límicos relacionados à linguagem e à emoção.

Assim como o cérebro, o cerebelo tabmém apresenta uma camada cortical compreendida por substância cinzenta e uma camada medular composta primordialmente por substância branca, as quais correspondem, respectivamente, ao **córtex cerebelar** e ao **corpo medular do cerebelo** (denominado também _árvore da vida_ por apresentar uma geometria similar àquela observada nos galhos de uma árvore frondosa). Podem ser encontradas esturturas compostas por substância cinzenta mergulhadas no corpo medular, coletivamente referidas como **núcleos profundos do cerebelo**. Estes abrangem os núcleos **denteado**, **interpósito** (formado pela união dos núcleos **globoso** e **emboliforme**) e **fastigial**. Do ponto de vista da divisão longitudinal do cerebelo, cada núcleo se encontra relacionado a funções e vias específicas da motricidade, o que é de grande relevância clínica para a avaliação de quadros de lesões cerebelares no exame físico.

<!-- - boxe mostrando técnicas de avaliação das vias cerebelares no exame físico neurológico -->

Nesse âmbito, convém salientar que a **zona verminiana**, composta por uma estrutura altamente segmentada situada ao longo do plano sagital mediano e detentora de um formato parecido com o de uma minhoca (o que justifica seu nome). Essa região se relaciona primariamente com o **núcleo do fastígio**, estabelecendo conexões com o sistema vestibular por meio da via fastígio-vestibular, essencial para o ajuste de movimentos mediante alterações nas velocidades lineares e angulares do corpo.

Por outro lado, a **zona paraverminiana**, compreendida por boa parte dos hemisérios cerebelares, relaciona-se ao **núcleo denteado** e medeia processos vinculados à intercomunicação cérebro-cerebelo para o planejamento motor por intermédio da via eferente dento-tálamo-cortical e da via aferente córtico-ponto-cerebelar. 

É necessário apontar que, assim como se pôde perceber para a classificação das regiões do córtex cerebral, o cerebelo também possui uma divisão filogenética, a qual guarda fortes correlações com os aspectos fisiológicos de cada uma de suas regiões. Destarte, é possível subdividir essa estrutura nervosa em:

-   **arquicerebelo**: funcionalmente correlacionado com o vestibulocerebelo e constituído anatomicamente pelo lobo flóculo-nodular.
-   **paleocerebelo**: fisiologicamente relacionado ao espinocerebelo.
-   **neocerebelo**: vinculado ao cerebrocerebelo do ponto de vista funcional.

No que diz respeito à anatomia microscópica desse órgão, pode-se afirmar que seu plano estratimérico básico se caracteriza pela presença de uma camada cortical externa de substância cinzenta e uma camada medular interna de substância branca, sendo que o córtex cerebelar pode ser subdividido em três estratos, os quais correspondem, de mais exterior para mais interior, a uma **camada molecular**, uma camada de **células de Purkinje** e uma camada de **células granulosas**.

De modo análogo ao que é observado para a camada molecular do córtex cerebral, a camada molecular cerebelar é relativamente pobre em corpos celulares, porém **rica em prolongamentos neuronais**. Estes incluem os prolongamentos dendríticos extremamente ramificados das células de Purkinje e os prolongamentos axônicos das células granulosas, os quais se encontram sinapticamente acoplados. Dessa forma, a ativação das células granulares por meio de **fibras musgosas** provenientes de estruturas extracerebelares promove, consequentemente, a ativação das células de Purkinje. Essa circuitaria neuronal altamente regulada constitui um dos principais aspectos da citoarquitetura cerebelar que possibilitam o aprendizado motor por meio de ativações e silenciamentos sucessivos dos neurônios situados nos núcleos profundos do cerebelo, responsáveis por dispararem as vias eferentes previamente descritas. Dentre as raras populações celulares que possuem seus pericários situados na camada molecular do córtex cerebelar, pode-se elencar as **células estreladas** e as **células em cesta**. Estas últimas podem ser classificadas como neurônios multipolares do tipo II de Golgi, configurando-se como células inibitórias $GABA$érgicas que promovem a coordenaçãomotora ao inibirem as células de Purkinje e, consequentemente, suprimirem a inibição destas sobre os núcleos cerebelares profundos.

Já a camada de **células de Purkinje** é composta primariamente por neurônios multipolares do tipo I de Golgi com grandes corpos celulares e uma profusa ramificação dendrítica direcionada para a camada molecular. Essas células são umas das maiores de todo o organismo humano e exercem ação inibitória sobre os neurônios dos núcleos profundos do cerebelo por meio da liberação de $GABA$ na fenda sináptica compreendida entre essas células ativadoras das vias cerebelares eferentes e os terminais axonais das células de Purkinje. Dessa forma, ocorre um influxo de íons Cl^-^ para o meio intracelular dos neurônios de tais núcleos, hiperpolarizando-os. As células de Pukinje são ativadas principalmente por meio da ação das **fibras trepadeiras**, que se originam do **núcleo olivar inferior** e emitem prolongamentos axônicos que parecem se entrelaçar helicoidalmente ao redor das fibras nervosas representadas pelos axônios das células de Purkinje, de modo similar ao que é constatado para as plantas epífitas, que parecem se enrolar ao redor dos troncos das árvores com as quais estabelecem relações ecológicas desarmônicas.

Por fim, cabe salientar que a **camada granulosa** do córtex cerebelar é composta primordialmente por **células granulosas**, neurônios multipolares do tipo Golgi I que emitem extensos prolongamentos axônicos retilíneos e amielínicos para a camada molecular do córtex cerebelar, e **células de Golgi**, as quais correspondem a interneurônios inibitórios $GABA$érgicos ativados pelas fibras musgosas e responsáveis por suprimirem as atividades das células granulosas. Teoriza-se que o papel das células de Golgi no contexto das intrincada circuitaria neural cerebelar esteja voltado à **plasticidade neuronal** no córtex cerebelar e ao rearranjo espaço-temporal dos níveis de atividade das células granulosas e de suas conexões sinápticas.

<!-- - boxe de biologia celular explicando os mecanismos moleculares subjacentes à plasticidade neuronal. -->

<!-- - boxe fisiológico explicando os papéis desempenhados pelas fibras musgosas e a neuroanatomia delas. -->


<!--chapter:end:02-AB.Rmd-->

# Plexo Coroide

Sob uma óptica histológica, pode-se asserir que a população celular mais representativa das regiões nas quais se faz presente o plexo coroide corresponde às **células ependimárias**, embriologicamente derivadas das células ventriculares que povoam a zona ventricular do tubo neural durante o processo de histogênese do tecido nervoso. Além de tais células, também é possível encontrar **tanicitos** em algumas regiões específicas do sistema ventricular encefálico, os quais correspondem a células derivadas da glia radial bipolar detentoras de uma morfologia intermediária entre os astrócitos e as células ependimárias. Dessa forma, é válido frisar que as células ependimárias e os tanicitos constituem os principais componentes neuroepiteliais do epêndima, imprescindível para a produção e a movimentação do líquido cefalorraquidiano.

<!-- - boxe de Biologia Celular mostrando imagens de imunofluorescência das células ependimárias e dos tanicitos e explicando as diferenças de morfologia, com enfoque para a morfologia estranha dos tanicitos. -->

<!-- - boxe anatômico mostrando os componentes do sistema ventricular do Sistema Nervoso, ou seja, desde as cisternas até os ventrículos em si e os aquedutos que os conectam. -->

<!-- - esquema de histogênese do tecido nervoso explicado por zonas do tubo neural (pode ser aquela do Kierszenbaum) -->

Como já se pode inferir a partir das populações celulares gliocíticas descritas acima, o plexo coroide (ou corioide) corresponde a uma associação de **estruturas circumventriculares** e um **epêndima** de características epitelioides que abriga células especializadas na produção do líquor a partir do plasma sanguíneo. Nesse sentido, é pertinente lembrar que os chamados _órgãos circumventriculares_ são regiões do Sistema Nervoso Central nas quais se observam descontinuidades da barreira hematoencefálica e, dessa forma, representam áreas de fluxo de substâncias facilitado entre o meio intravascular e o tecido nervoso. Do ponto de vista ultraestrutural, o plexo coroide constitui-se essencialmente pela interface entre uma rede de capilares fenestrados com diafragma situada no interior de uma massa de tecido conjuntivo frouxo e o epêndima sobrejacente.

<!-- - mostrar fotomicrografia lâmina de plexo coroide indicando os componentes histológicos de suas estruturas. -->

Assim, pode-se dizer que o plexo coroide está presente nas paredes do terceiro e do quarto ventrículos, onde uma película fina de **pia-máter** altamente vascularizada denominada **tela coroide** oferece o aporte sanguíneo necessário para a produção de líquor e, nas fissuras coroides dos ventrículos laterais, situadas nas seções mediais desses componentes do sistema ventricular encefálico, entre o fórnice e o tálamo. Nessas regiões verifica-se, além da intensa produção de líquor, um incisivo e perene **monitoramento imunológico** por parte de macrófagos, linfócitos e células dendríticas encontradas no tecido conjuntivo frouxo que sustenta o plexo coroide.

<!-- - boxe fisiológico versando sobre a importância das células do Sistema Imunológico inclusas no plexo coroide. -->

Ultraestruturalmente, as células ependimárias apresentam grandes quantidades de **mitocôndrias** e múltiplas **invaginações basais** de seus domínios de membrana basolaterais, fatores que as caracterizam como células detentoras de intensa atividade metabólica e elevadas taxas de transporte ativo ocorrendo por bombas proteicas incrustadas na membrana plasmática. Ademais, a presneça de **microvilosidades** e eventuais **cílios** em seus domínios de membrana apicais é significativa do ponto de vista histofisiológico, haja vista que as células em questão também efetuam a absorção e a circulação do líquor. Finalmente, é interessante apontar a existência de uma resistente **barreira hematoliquórica** constituída por junções de oclusão e interdigitações estabelecidas entre células ependimárias adjacentes. Tais especializações laterias de membrana são, pois, fundamentais para se evitar a passagem direta de moléculas do sangue para o líquido cefalorraquidiano.

<!-- - boxe ultraestrutural mostrando eletromicrografia de transmissão do epênima, evidenciando os capilares fenestrados com diafragma que circulam pelo estroma e a Biologia Estrutural das barreiras hematoencefálica (fazer comparativo com outro corte, porque ela não vai estar presente aqui) e hematoliquórica. -->

<!--chapter:end:02-AC.Rmd-->

# Medula Espinal

De uma perspectiva neuroanatômica, a medula espinal se constitui como um grande **_conduit_ neuronal** central responsável por integrar o encéfalo com os compontnes do Sistema Nervoso Periférico. Isso possibilita, por exemplo, que o núcleo rubro medeie o controle ultrapreciso da musculatura intrínseca da mão por meio do trato rubroespinal, e que o sistema límbico receba e processe informações aferentes de dor crônica captadas por fibras nociceptivas amielínicas do tipo C na periferia do corpo e transmitidas ao prosencéfalo pro meio da **via paleoespinotalâmica**.  

<!-- - boxe clínico sobre a relevância da via paleoespinotalâmica na patogenia da depressão. -->

Convém, entretanto, frisar que as características fisiológicas da medula espinal vão muito além do que aquelas que se poderia esperar de um simples cilindro constituído puramente por prolongamentos axônicos responsáveis por carregarem _inputs_ oriundos dos tecidos periféricos e _outputs_ para estes dirigidos. Desse modo, verifica-se que a medula espinal também está envolvida no controle das funções vegetativas do organismo por meio dos **núcleos intermédio-laterais** toracolombares e dos **núcleos intermédio-mediais** sacrais, em mecanismos de analgesia mediados pela **Substãncia Gelatinosa de Rolando** e até mesmo em arcos reflexos altamente intrincados, com a ativação e a inibição de grupamentos musculares inteiros. Nesse âmbito, é interessante ressaltar que o fenômeno da modulação negativa da dor por meio de estímulos táteis, explicado pela **Teoria da Comporta da Dor**, ocorre ao nível da medula espinal e hodiernamente é alvo de múltiplos estudos que visam à invenção de novos tratamentos farmacológicos da dor crônica.

<!-- - boxe farmacológico sobre o sistema opioide endógeno, a fisiologia da teoria da comporta da dor e atividades do cotidiano que liberam opioides endógenos. -->

Macroscopicamente, a medula espinal apresenta como limite superior a **decussação das pirâmides** e como limite inferior o **ligamento coccígeo**, originado a partir da parte dural do **filamento terminal**, emitido a partir do **cone medular**. A medula espinal apresenta uma organização metamérica, que, no entanto, é díspar daquela observada para a coluna vertebral, estojo ósseo que delimita a parte caudal do paquímero dorsal e abriga a estrutura nervosa em questão. Isso se dá em decorrência das taxas de crescimento diferenciais observadas para essas duas estruturas durante o processo de organogênese, de tal forma que é válido afirmar que um determinado segmento vertebral abriga estruturas nervosas referentes ao metâmero espinal dois níveis inferiores a ele. Assim, na seção do canal vertebral compreendida pela vértebra T$V$, é possível encontrar o segmento medular T7. 

<!-- - esquema mostrando as taxas de crescimento diferencial da medula e da coluna vertebral. -->

<!-- - desenho mostrando a anatomia mmacroscópica da medula espinal. -->

Diferentemente do que se verifica para o encéfalo, a medula apresenta uma estratimeria na qual a **substância branca** composta majoritariamente por células da glia e prolongamentos axônicos ascendentes e descendentes se encontram na **periferia** do tubo e a **substância cinzenta**, compreendida por gliócitos e corpos celulares de neurônios, encontra-se numa posição **central**. Isso se dá naturalmente mediante o processo de histogênese do órgão em questão, o qual se desenvolve a partir do tubo neural, cujo lúmen se oblitera quase completamente nesse processo. É interessante apontar que a divisão clássica da substância cinzenta do _H_ medular num **corno ventral eferente motor** e um **corno dorsal aferente sensitivo** possui fundamentação embriológica. Ao passo que este é oriundo de uma estrutura denominada **placa alar**, a qual se forma por meio das células constituintes da parede dorsal do tubo neural e se diferencia em estruturas nervosas sensitivas por meio da ação do morfógeno $Wnt$, aquele é originado a partir da **placa basal**, que se desenvolve a partir da parede ventral do tubo neural e se diferencia em neurônios motores inferiores através da indução morfogenética efetuada pela proteína $SHH$ em suas células. Nesse sentido, pode-se lembrar que, diferentemente do que se observa na medula de um indivíduo que já completou seu desenvolvimento embrionário, a medula primitiva apresenta sulcos laterais responsáveis por demarcar o limite entre as placas alares e as placas basais, denominados **sulcos limitantes**.

<!-- - boxe embriológico sobre a ação morfogenética das proteínas $SHH$ e $Wnt$ e seus papéis na organogênese. -->

<!-- - esquema ilustrando o processo de desenvolvimento supradescrito. -->

Outro aspecto anatômico no qual se pode notar claras diferenças entre as organizações macroscópicas e mesoscópicas do encéfalo e da medula espinal se dá na organização dos folhetos meníngeos, uma vez que, na medula, a dura-máter não se encontra aderida ao periósteo das vértebras, apresentando-se relativamente solta no interior do canal vertebral, formando o **saco dural**, uma estrutura fibrosa de **tecido conjuntivo denso** responsável por fornecer proteção mecânica à medula. Externamente ao saco dural, é possível observar a presença de tecido conjuntivo frouxo, tecido adiposo unnilocular e elementos neurovasculares preenchendo o **espaço epidural**. Vale salientar que, dentre as estruturas vasculares que podem ser encontradas nessa região, tem-se o **plexo venoso de Batson**, o qual promove a drenagem sanguínea da medula espinal e se conecta com veias das cavidades torácica e abdominopélvica. Tais conexões explicam o porquê de certos tipos de neoplasias, como o câncer de próstata, efetuarem metástases hematogênicas parao Sistema Nervoso Central.

<!-- - boxe anatômico e clínico destacando os diferentes espaços delimitados pelos folhetos meníngeos e a relevância deles na Anestesiologia. -->

Microscopicamente, é possível subdividir a substância cinzenta da medula espinal, que se dispõe num formato parecido com uma letra _H_ ou com uma borboleta (ganhando, por isso, a denominação de _H_ medular), em uma série de **lâminas** ou **núcleos** conhecidos como **lâminas de Rexed**. Cada uma dessas lâminas desempenha papéis específicos na modulação das atividades dos tratos espinais que trafegam pela substância branca e nas funções motoras e sensitivas desempenhadas pelo neuroeixo em sua interface de integração com o restante do organismo por meio do Sistema Nervoso Periférico. É interessante ressaltar que a proporção entre as áreas ocupadas pela substância cinzenta e pela substância branca aumenta craniocaudalmente, de forma que a medula espinal sacral possui um predomínio de substância cinzenta e a medula espinal cervical, de substância branca.

<!-- - Boxe embriológico e fisiológico sobre a biologia do desenvolvimento das lâminas de Rexed e as funções de cada uma delas. -->

<!--chapter:end:02-AD.Rmd-->

# Nervos

A partir de uma óptica neuroanatômico, é válido afirmar que os nervos são as principais estruturas que compõem o **Sistema Nervoso Periférico** e, por isso, funcionam como _fios_ que abrigam importantes circuitos neuronais responsáveis pela comunicação entre o Sistema Nervoso Central e as demais regiões do corpo. Isso possibilita que o Sistema Nervoso como um todo atue, ao lado do Sistema Endócrino, como uma rede de integração entre os múltiplos órgãos das várias regiões do corpo.

<!-- - boxe traçando um paralelo entre a estrutura de um computador e a morfofisiologia do sistema nervoso. -->

<!-- - boxe sobre os chamados _sistemas de integração_ e a importância deles para a manutenção da homeostase, se possível falar de como sua fisiologia pode ser modelada pela Biologia de Sistemas do ponto de vista matemático. -->

Ao todo, possuímos **12 pares de nervos cranianos** e **31 pares de nervos espinais**. Enquanto estes se originam a partir da substância cinzenta do _H_ medular, aqueles se originam de núcleos imersos na substância branca do **tronco encefálico**, a exemplo do nervo vago (NC X), o qual se origina parcialmente do núcleo dorsal motor do nervo vago, e do nervo oculomotor (NC III), que possui seu componente autonômico oriundo do núcleo de Edinger-Westphal, ou de **projeções telencefálicas** e **diencefálicas**, como se observa para o nervo olfatório (NC I) e o nervo óptico (NC II), respectivamente.

<!-- - boxe clínico sobre a avaliação dos nervos cranianos no exame físico neurológico. -->

De forma geral, pode-se dizer que todo nervo possui um componente **aferente sensitivo** e um componente **eferente motor** e, do ponto de vista histológico, compõe-se por conjuntos de prolongamentos axônicos revestidos por membranas protetivas de tecido conjuntivo e fibras colágenas. Tais prolongamentos podem ou não estar mielinizados e isso dependerá da atividade das **células de Schwann**, os principais gliócitos do Sistema Nervoso Periférico. Essas células apresentam **núcleos sinuosos e alongados** que parecem acompanhar as trajetórias percorridas pelos prolongamentos nervosos. 

<!-- - eletromicrografia das células de Schwann. -->

Os nervos usualmente podem ser encontrados em estreita associação com elementos vasculares tais como as veias de médio calibre e as artérias musculares constituintes dos **feixes vásculo-nervosos**, e se encontram compartimentalizados em **feixes** e **fascículos** nervosos por meio das membranas conjuntivas supramencionadas. Estas correspondem ao **epineuro**, ao **perineuro** e ao  **endoneuro**.

Nesse âmbito, é possível mencionar que, enquanto o **epineuro** une vários fascículos nervosos em um só nervo e é composto primordialmente por **tecido conjuntivo denso**, o **perineuro**  delimita os fascículos nervosos e corresponde a uma bainha conjuntiva constituída por uma série de fibroblastos modificados com formato achatado entremeados por fibras colágenas. Existe ainda o **endoneuro**, que corresponde a uma delicada película de **tecido conjuntivo frouxo** que reveste fibras nervosas individuais. 

<!-- - esquema mostrando a estrutura dos folhetos de revestimento dos nervos ao lado de uma fotomicrografia legendada deles. -->

Entre os fascículos nervosos, pode-se observar, no interior das bainhas conjuntivas supradescritas, **vasos sanguíneos** responsáveis pela vascularização do tecido nervoso periférico. Vale salientar que os nervos configuram-se como estruturas de notável relevância clínica no exame físico neurológico, podendo ser lesados por uma miríade de afecções com as mais variadas etiologias, como a hanseníase, a neuropatia diabética e a esclerose múltipla.

<!-- - boxe microbiológico sobre a hanseníase e os mecanismos de virulência subjacentes aos danos causados em ramos nervosos sensitivos pelo _Mycobacterium leprae_. -->

<!--chapter:end:02-AE.Rmd-->

# Gânglios

## Gânglios Sensitivos

As fibras sensitivas constituintes dos nervos espinais apresentam seus somas situados em dilatações localizadas na **raiz dorsal** de seus nervos, em estruturas conhecidas como **gânglios sensitivos das raízes dorsais**. Esses neurônios pseudounipolares transmitem informações sensitivas ao Sistema Nervoso Central por meio das vias **coluna dorsal-lemnisco medial**, responsável pela condução de informações relacionadas ao tato epicrítico, à sensibilidade vibratória e à propriocepção consciente de todo o corpo com exceção da cabeça e do pescoço, e **anterolateral**, a qual conduz informações relacionadas ao tato protopático, à propriocepção inconsciente, à nocicepção e à termocepção. 

<!-- - Boxe fisiológico e farmacológico sobre os anestésicos locais e a fisiologia das células nociceptivas. -->

<!-- - Boxe histórico sobre a Lei de Hilton e a Lei da Energia Específica dos Nervos. -->

Como característica histológica peculiar dos gânglios sensitivos, é possível mencionar a presença de gliócitos especializados, denominados **células satélites**, "contornando" e sustentando os corpos celulares e os neuritos dos neurônios sensitivos. Ao emitirem um prolongamento centrípeto em direção à medula espinal e um prolongamento centrífugo em direção à periferia do organismo, os gânglios sensitivos proporcionam a integração somatossensorial entre diferentes regiões do corpo, o que é de especial importância para a defesa do organismo e para a mediação de **arcos reflexos**.

<!-- - boxe fisiológico sobre a Fisiologia dos arcos reflexos e as manobras de testagem de reflexos mais relevantes no exame físico neurológico. -->

## Gânglios Autonômicos

Essas estruturas integram a **divisão visceral** do Sistema Nervoso e são fundamentais para o controle das funções vegetaticas, estabelecendo conexões com os gânglios pré-vertebrais simpáticos, os gânglios das cadeias paravertebrais e  os núcleos intermédio-mediais da medula espinal. Nesse sentido, vale salientar que, nas lâminas observadas, verifica-se a presença dessas estruturas no **Sistema Nervoso Entérico**, onde formam o **plexo mioentérico** (ou de **Auerbach**), situado entre as camadas musculares circular interna e longitudinal externa do intestino e envolvido na regulação da motilidade destas, e o **plexo submucoso** (ou de **Meissner**), localizado na camada submucosa e essencial para o controle da motilidade do estrato muscular da mucosa e para o controle quimioceptivo e mecanoceptivo da peristalse.

<!-- - Boxe de biologia celular versando sobre a importância do SNE na patogenia de doenças psíquicas e sobre as principais funções dele. -->

Ainda se pode vislumbrar a presneça de pequenos gânglios autonômicos em meio ao tecido conjuntivo presente nas trabéculas da **glãndula submandibular**, onde medeia suas atividades secretórias conectando-se com fibras provenientes do nervo facial.

## Aplicação Clínica

O vírus causador da _Herpes zoster_ tende a se alojar nos gânglios sensitivos das raízes dorsais dos nervos espinais quando se converte em seu estado latente após uma primoinfecção. Assim, mediante episódios de imunossupressão intensa, esse patógeno pode voltar à sua forma ativa e proporcionar o aparecimento de feridas máculo-papulares e vesiculares que se distribuem metamericamente na superfície do corpo, obedecendo os padrões de delimitação dos **dermátomos**. Cabe ressaltar que essas lesões podem ser desencadeadas por estresse emocional severo e podem ulcerar se deixadas sem tratamento, o que favorece a ocorrência de infecções secundárias.

<!-- - Boxe anatômico e embriológico sobre os dermátomos e os gradientes morfogenéticos que estão por trás de sua origem no desenvolvimento. -->

<!--chapter:end:02-AF.Rmd-->

# Mecanorreceptores

## Corpúsculos de Vater-Paccini

Os corpúsculos de Vater-Paccini correspondem a estruturas nervosas encapsuladas por **lamelas concêntricas** de tecido conjuntivo e responsáveis pela detecção de informações relacionadas à **sensibilidade vibratória** e à **pressão** exercida em **camadas profundas** da derme reticular e na hipoderme, onde tais estruturas componentes do Sistema Somatossensorial são mais numerosas. Por possuírem um complexo revestimento de fibras colágenas entremeadas por fluido intersticial, esses receptores são sensíveis até mesmo às mais sutis variações da pressão aplicada sobre a superfície da pele, encontrando-se distribuídos em abundância por regiões do tegumento recobertas por pele espessa e sujeitas a atritos e forças friccionais intensas e constantes, a exemplo da palma da mão e da superfície plantar do pé. 

Convém, todavia, salientar que essas terminações nervosas mecanorreceptoras não são exclusivas do Sistema Tegumentar, podendo também ser visualizadas em vísceras secretoras como o **pâncreas**, em **articulações** e no **periósteo** que reveste os componentes ósseos do esqueleto. Não se sabe ao certo os papéis fisiológicos efetuados pelos corpúsculos de Vater-Paccini nestes locais, especialmente no que concerne à população desses mecanorreceptores encontrada nas trabéculas conjuntivas do pâncreas. Entretanto, é teorizado que eles possam estar envolvidos no controle central da secreção realizada por essa importante glândula anfícrina retroperitoneal por meio da detecção de variações na pressão hidrostática no interior dos ductos secretores ao decorrer da ejeção do suco pancreático para a porção descendente do duodeno.

<!-- - boxe fisiológico sobre a a viscerocepão e o papel dos mecanorreceptores nisso tudo. -->

De um ponto de vista neurofisiológico, é possível afirmar que as informações captadas pelos corpúsculos de Paccini chegam ao **córtex somatossensorial primário**, correspondente ao **giro pós-central** (áreas 1, 2 e 3 de Brodmann), por meio da via **coluna dorsal-lemnisco medial**. Nesse âmbito, observa-se que o primeiro neurônio da via, cuja terminação nervosa periférica forma o corpúsculo de Paccini, possui seu pericário situado nos **gânglios sensitivos das raízes dorsais** dos nervos espinais e, ao adentrar na medula, envia um longo prolongamento axônico para o **tálamo** por meio do **funículo posterior** da substância branca medular. Particularmente, verifica-se que há um expressivo direcionamento das fibras nervosas para núcleos talâmicos responsáveis pela retransmissão das informações referentes à sensibilidade vibratória, à propriocepção consciente e ao tato epicrítico, merecendo destaque os núcleos **ventral póstero-lateral** e **ventral póstero-medial**.

<!-- - esquema mostrando a via da coluna dorsal-lemnisco medial -->

Ao chegar nesses centros talâmicos, o impulso nervoso é retransmitido para a **camada IV (granular interna)** do córtex somatossensorial primário, onde obedece um padrão de distribuição **somatotópico**

<!-- - boxe embriológico e anatômico falando sobre os mapas corticais para somatotopia e tonotopia e a origem desses mapas do ponto de vista da biologia do desenvolvimento. -->

<!--chapter:end:02-AG.Rmd-->

# Botões Gustativos

Histologicamente, essas **estruturas neuroepiteliais** formam pequenos aglomerados elipsoides de células incrustadas no epitélio pavimentoso estratificado não-queratinizado característico da mucosa de revestimento especializada da língua, podendo ser encontrados nas superfícies das papilas **fungiformes**, **foliáceas** e **circunvaladas** (a exceção são as papilas filiformes, que cumprem funções mais relacionadas à fricção do alimento com a superfície lingual do que à sensibilidade espacial gustatória). Nessas estruturas neuroepiteliais, é possível distinguir a existência de três populações celulares:

- As células **basais**, que funcionam como células-tronco e se encontram destinadas à reposição contínua das células gustativas.

- Já as **células gustativas** são especializadas na detecção de sabores por meio do reconhecimento de moléculas solúveis dispersas na saliva e se degradam muito rapidamente quando comparadas a outras populações celulares, haja vista suas meias-vidas estimadas de 5 a 10 dias. Cabe ressaltar que essas células são providas de abundantes microvilos apicais que usualmente dispõem de grandes quantidades de receptores metebotrópicos dedicados à percepção dos sabores liberados pela comida e à transdução de sinais elétricos por estes proporcionados. 

<!-- - boxe de biologia molecular sobre proteínas da família TRPV e de seus papeis na detecção de sabores -->

- Por fim, as **células sustentaculares** são responsáveis pela sustentação das populações celulares supramencionadas, atuando como um componente estromal dos botões gustativos.

Nesse âmbito, também é válido mencionar que as células gustativas receptoras se encontram divididas em **3 subtipos** principais, cada qual dedicado à percepção de diferentes modalidades gustativas. Assim, tem-se que, ao passo que as células gustativas do **tipo I** se encontram especializadas na captação de informações relativas ao sabor salgado, as células gustativas do **tipo II** estão voltadas à detecção do doce, do _umami_ (sabor característico de alimentos ricos em glutamato, tais como o peixe cru, os cogumelos e alguns tipos de queijo) e do amargo por meio de receptores metabotrópicos denominados **transducinas**. Finalmente, tem-se que as células gustatórias do **tipo III** possuem propriedades características de células excitáveis, sendo capazes de conduzir potenciais de ação e desempenharem respostas elétricas vinculadas aos sabores azedo e salgado por intermédio de despolarizações proporcionadas pela entrada de cátions (Na^+^ e Ca^2+^) através de canais iônicos voltagem-dependentes situados nos polos apicais de tais células.

<!-- - boxe de notícia sobre a descoberta do sabor umami e a culinária japonesa. -->

Quando as moléculas responsáveis pela percepção do sabor se dissolvem na saliva e adentram nos **poros gustativos**, pequenas aberturas por meio das quais o domínio de membrana apical das células gustativas se abre na cavidade oral, ocorre, portanto, o disparo de cascatas de sinalização intracelulares responsáveis por promoverem a **exocitose de ATP** para a região de contato entre o botão gustativo e ramos nervosos especiais dos nervos facial (NC VII), vago (NC X) e glossofaríngeo (NC IX). Dessa forma, mediante a ativação dessas estruturas nervosas, a informação gustativa é carreada até o **córtex gustativo primário**, localizado nos giros da ínsula posteriores, por meio de uma trajetória nervosa que passa pelo **núcleo do trato solitário (NTS)**.

<!-- - boxe de notícias falando sobre o sabor umami. -->


<!--chapter:end:02-AH.Rmd-->

# Drogas de Abuso

Do ponto de vista do Código Penal Brasileiro, as drogas de abuso podem ser classificadas em lícitas (a exemplo do álcool e da nicotina, substâncias que apresentam alto potencial dependogênico em função da comercialização disseminada e da maior aceitação social para com sua utilização, que pregressamente era vista até mesmo como distintivo de _status_ econômico) e ilícitas (grupo que inclui a maconha, o ácido lisérgico, as anfetaminas, o MDMA, o _skank_, os inalantes, as _club drugs_ e inúmeras outras substâncias que constituem problemas de saúde pública de proporções geopolíticas ao se considerar o impasse do tráfico internacional de drogas e o surgimento de extensas cenas de uso intinerantes que moldam o cenário das grandes metrópoles, como a _Cracolândia_ paulistana e a _Skid Row_ em Los Angeles). Vla salientar que inúmeras substâncias originalmente planejadas como fármacos passaram a apresentar um caráter de droga de abuso como consequência de fenômenos relacionados à medicalização da vida moderna e à automedicação, haja vista a incidência crescente de síndromes de abstinência ocasionadas pela retirada de benzodiazepínicos e drogas-Z em indivíduos que realizavam uso cotidiano desses medicamentos para dormir. Nesse sentido, tem-se observado que, seguindo as recomendações de agências reguladoras como a _CDC_, muitos entes federados estadunidenses vêm aplicando restrições cada vez mais duras sobre a distruibuição e a fabricação de opioides potentes como o fentanil, o qual, embora possa apresentar um emprego muito valioso na forma de adesivos transdérmicos para o manejo da dor em pacientes em Cuidados Paliativos, tem contribuído para a epidemia de abuso de opioides que assola o país desde o final da década de 90. Sob o ponto de vista farmacodinâmico, pode-se categorizar as drogas de abuso de acordo com suas principais ações sobre os sistemas de neurotransmissão, embora devemos sempre ter em mente que, mesmo dentre as drogas de uma determinada categoria, existe grande heterogeneidade quanto a seus mecanismos de ação, os quais nem sempre são muito bem entendidos. Assim, seria possível traçar a seguinte classificação para as drogas de abuso:

- **Álcool:** presente em diferentes títulos em diferentes bebidas destiladas ou fermentadas, como o uísque, a cerveja, o rum, o saquê, o corote, a cachaça e o vinho.

- **Nicotina:** agonista total de receptores ionotrópicos de acetilcolina, primeiramente extraída da planta _Nicotiana tabacum_, pode ser encontrada em cigarros, charutos, essências para narguilês e nos _e-líquidos_ utilizados em _vapes_ (cigarros eletrônicos).

- **Derivados da maconha:** incluem o _skank_, uma espécie de "maconha sintética" e o haxixe, um exsudato resinoso extraído das glândulas presentes nos tricomas do terço superior de plantas femininas da espécie _Cannabis sativa_. Seus efeitos sobre o sistema de recompensa e outras áreas do córtex cerebral se dão pelas substâncias tetrahidrocanabidiol (THC), relacionado à euforia e às alucinações relatadas durante o uso, e canabidiol, amplamente pesquisado em razão de seus efeitos terapêuticos putativos para quadros de epilepsia, êmese induzida por medicamentos e doenças neurodegenerativas.

- **Hipnóticos e Sedativos:** destacam-se nesse grupo substâncias corriqueiramente utilizadas como fármacos, como o clonazepam (um benzodiazepínico), o zolpidem (um hipnótico muito potente) e o fenobarbital (barbitúrico utilizado para tratamento de epilepsias refratárias). Compartilham o mecanismo de ação comum de atuarem como moduladores alostéricos positivos de receptores $GABA_A$,assim como o álcool, sendo que quadros de intoxicação por essas substâncias podem levar ao óbito por parada respiratória na medida em que ocorre supressão importante de centros vegetativos bulbares, o que pode ser revertido com o uso do antídoto flumazenil.

- **Opioides:** essa classe farmacológica foi um marco na história da Anestesiologia e compreende uma série de alcaloides naturais extraídos da papoula ( _Papaver somniferum_ ), como a morfina, a codeína e a tebaína, e opioides sintéticos fabricados por meio da introdução ou da modificação de grupos funcionais dessas substâncias, a exemplo da heroína, da petidina, do fentanil, do tramadol e da metadona. Atuam em receptores opioides $\mu$, $\delta$ e $\kappa$ promovendo modulação da dor e inibição de interneurônios $GABA_B$ responsáveis por regularem a atividade da via mesolímbica, deixando-a hiperativa.

- **Estimulantes:** englobam substâncias como as anfetaminas, a cocaína, o metilfenidato, a atomoxetina e a efedrina, as quais atuam promovendo extravasamento de neurotransmissores excitatórios - especialmente a norepinefrina e a dopamina - de suas vesículas sinápticas, promovendo também o acúmulo destes no meio extracelular por meio de uma inversão na dinâmica de recaptação e transporte de proteínas de armazenamento vesicular como a $VMAT$ e de recaptação de neurotransmissores, como a $NET$, as quais passam a atuar como bombas de extrusão de neurotransmissores para o meio externo. Para o tratamento dos sintomas das crises de abstinência provocados pela retirada do uso dessas substâncias, podem ser empregados antipsicóticos e $\beta$-bloqueadores.

- **Alucinógenos:** abrigam um amplo rol de substâncias, muitas das quais são utilizadas como enteógenos por comunidades tradicionais e não possuem mecanismos de ação muito bem conhecidos. Nesse sentido, podemos citar como representantes dessa classe o ácido lisérgico (LSD), a psilocibina, a mescalina, o MDMA, o DMT (dimetiltriptamina) e os alcaloides $beta$-carbolínicos encontrados na _ayahuasca_, na harmala e no cipó-mariri.

No que diz respeito às manifestações clínicas e aos sintomas das síndromes de abstinência relativas ao uso de cada uma das classes supramencionadas de drogas de abuso, pode-se dizer que estas são extremamente variadas e, em última instância, dependem não só de mecanismos de _up-regulation_ ou _down-regulation_ de receptores nas membranas neuronais como também de modificações ainda desconhecidas sobre os sistemas de neurotransmissão e neuromodulação. A mesma heterogeneidade pode ser verificada quanto às sensações relatadas mediante o uso dessas substâncias, uma vez que elas diferem significativamente entre si quanto a seus alvos de ação. Dessa forma, noticia-se:

- **Álcool:** constitui a droga de abuso mais consumida atualmente e atua como modulador alostérico positivo de receptores $GABA_A$, facilitando a ligação do ácido $\gamma$-aminobutírico a esse canal iônico operado por ligantes, proporcionando um influxo de íons $Cl^-$ que hiperpolariza a célula, fazendo com que seja mais difícil dela ser disparada. Nesse sentido, pequenas doses de álcool podem proporcionar euforia e comportamento social desinibido na medida em que neurônios de centros superiores responsáveis pela regulação do comportamento são inibidos. Entretanto, à medida que a alcoolemia aumenta (e, por apresentar uma cinética de eliminação de ordem zero, os níveis plasmáticos de etanol costumam variar erraticamente e serem de difícil controle em situações de intoxicação), essa inibição neuronal pode se disseminar para os núcleos da base, o cerebelo e o hipocampo, levando ao aparecimento de ataxia, descoordenação da marcha e amnésia anterógrada (a qual, a nível molecular, pode estar relacionada a subtipos de receptores neuronais que contêm uma subunidade $\alpha_5$).

- **Nicotina:** conforme postula Stephen Stahl, esse agonista total de receptores nicotínicos possui um potencial dependogênico estimado em 32% e atua no Sistema Nervoso Central ativando receptores nicotínicos e promovendo despolarização neuronal, que causa uma sensação de relaxamento e despertar. Em função de sua via de administração se dar pelo fumo (via inalatória), esses efeitos são observados de modo extremamente rápido. Acredita-se que sua atuação em receptores nicotínicos dos subtipos $(\alpha_7)_5$ e $(\alpha_4)_2(\beta_2)_3$ esteja envolvida nos aspectos psicológicos subjacentes a seu uso e à sua dependência.

- **Maconha e seus derivados:** ao atuarem em receptores canabinoides do tipo $CB_1$ distribuídos por grandes extensões do Sistema Nervoso Central de modo análogo a canabinoides endógenos derivados do ácido araquidônico, como a anandamida, o tetrahidrocanabinol (THC) e o canabidiol regulam a atividade de liberação de neurotransmissores por meio de terminais nervosos pré-sinápticos. Em baixas doses, isso parece se relacionar a sensações de relaxamento, tranquilidade e bem-estar, porém, se os níveis dessas substâncias se elevarem, o indivíduo poderá relatar crises psicóticas e alucinações. Vale ressaltar que as substâncias presentes na maconha podem provocar, mediante uso crônico, embotamento afetivo, dificuldades para dormir e em funções sociais, perda da personalidade e de habilidades, além de transtornos psicóticos. Isso é particularmente grave em adolescentes, uma vez que a organização citoarquitetural de suas vias de comunicação encefálicas ainda não se encontra completamente madura e a maconha parece promover proliferação sináptica desordenada, prejudicando o desenvolvimento neuropsicocognitivo.

- **Opioides:** além de atuar de modo similar às dinorfinas e endorfinas produzidas endogenamente durante situações estressantes a partir da clivagem da pré-opiomelanocortina e, por conseguinte, proporcionarem uma intensa analgesiaatuando em receptores na medula e na substância cinzenta periaquedutal, os opioides também parecem ativar a via mesolímbica dando uma sensação de "barato" ao se ligarem a receptores expressos em neurônios $GABA$érgicos moduladores dessa via e diminuir a ativação destes. Assim, ao fazer uso de um opioide potente como o fentanil, um indivíduo pode relatar uma sensação de prazer, relaxamento e bem-estar com cessação de suas dores, efeitos que podem ser seguidos de sonolência. No entanto, em quadros de intoxicação por opioides, os quais podem ser tratados com o uso do antagonista opioide naltrexona em sua forma inalável, é comum que o indivíduo apresente miose, xerostomia, cólicas e prurido. Vale ressaltar, no entanto, que para o tratamento da abstinência por retirada de opioide, recomenda-se utilizar a metadona, um opioide menos potente cuja meia-vida de eliminação longa impede a ocorrência de variações bruscas dos níveis das drogas em uso.

- **Sedativos e Hipnóticos:** como mencionado anteriormente, ao se utilizar um barbitúrico, um benzodiazepínico ou uma droga-Z e as moléculas desses fármacos ocuparem seus sítios alostéricos nos receptores $GABA_A$ (localizados nas regiões de transição entre as subunidades $\alpha$ e $\gamma$ desse canal iônico operado por ligantes), ocorre uma mudança conformacional nesse receptor que favorece a ligação das moléculas de $GABA$ (ácido $\gamma$-aminobutírico) a seus dois sítios ortostéricos situados na transição entre as subunidades $\alpha$ e $\beta$ dessas proteínas. Desse modo, nota-se uma inibição intensa da atividade neuronal, o que, embora seja benéfico para situações como o controle do estado de mal epiléptico (quadro para o qual se costuma administrar uma dose de ataque de 10 miligramas de diazepam intravenoso), pode levar à amnésia anterógrada, ataxia, marcha ebriosa, depressão respiratória e óbito, especialmente se esses medicamentos forem ingeridos junto com o álcool, que também atua potencializando a transmissão $GABA$érgica (vale lembrar que é exatamente esse o princípio da "boa noite Cinderela", droga de estupro que leva flunitrazolam em sua composição). Entretanto, em doses menores, essas drogas tendem a provocar sentimentos de tranquilidade intensa, relaxamento, sonolência e hipotonia muscular.

- **Estimulantes:** em vista de seus mecanismos de ação se centrarem na liberação neurotransmissores excitatórios para o meio extracelular, potencializando a ação destes sobre as sinapses, pode-se elencar como os principais efeitos agudos decorrentes do uso de drogas como a cocaína, a atomoxetina, o metilfenidato, a anfepramona (muito utilizado por caminhoneiros que realizam longas viagens noturnas) e a efedrina sensações de euforia e hipervigilância, acompanhadas de tendências maníaca, alerta extremo, palpitações, tremores, diaforese e midríase (percebe-se que alguns desses sintomas, especialmente aqueles que se manifestam a nível físico, encontram-se relacionados à hiperativação simpática). Essas substâncias possuem alto potencial de causarem dependência e a síndrome de abstinência por sua retirada é marcada por anedonia, desejo intenso de dormir intercalado por períodos de agitação e _craving_ pela droga, os quais podem ser tratados por meio de $\beta$-bloqueadores, fármacos que atuarão controlando os sintomas físicos supramencionados, e antipsicóticos. A tendência de indivíduos que fazem uso de estimulantes do SNC é de que, com o passar do tempo e com o desenvolvimento de tolerância às drogas menos potentes, eles busquem drogas capazes de promover a liberação de monoaminas de modo mais intenso.

- **Alucinógenos:** de um pondo de vista farmacodinâmico, os mecanismos de ação dessas drogas são variados, complexos e ainda incompreendidos, porém em grande parte estes parecem estar relacionados ao estado de humor do indivíduo que as consome, podendo seus efeitos serem fortemente influenciados por este. Dessa maneira, as alucinações visuais, auditivas, cenestésicas, olfativas e gustatórias apresentadas por pessoas que fazem uso de substâncias como o ácido lisérgico podem ser caracterizadas como _good trips_, nas quais o indivíduo se sente espiritualmente elevado e iluminado por forças divinas, ou _bad trips_, nas quais o usuário da droga - que provavelmente já se encontrava ansioso ou deprimido antes do consumo da substância - relata viver um verdadeiro pesadelo acordado, ouvindo vozes aterrorizantes e enxergando monstros. Ademais, um fenômeno pouco compreendido que pode ser causado por essas drogas são os _flashbacks_, períodos nos quais os indivíduos que já as utilizaram experienciam reviver seus momentos de contato com a substância. Em virtude de provocarem uma tolerância brusca e intensa, é raríssimo observar quadros de dependência para essa classe de drogas de abuso. 

<!--chapter:end:02-AI.Rmd-->

# Cross-references {#cross}

Cross-references make it easier for your readers to find and link to elements in your book.

## Chapters and sub-chapters

There are two steps to cross-reference any heading:

1. Label the heading: `# Hello world {#nice-label}`. 
    - Leave the label off if you like the automated heading generated based on your heading title: for example, `# Hello world` = `# Hello world {#hello-world}`.
    - To label an un-numbered heading, use: `# Hello world {-#nice-label}` or `{# Hello world .unnumbered}`.

1. Next, reference the labeled heading anywhere in the text using `\@ref(nice-label)`; for example, please see Chapter \@ref(cross). 
    - If you prefer text as the link instead of a numbered reference use: [any text you want can go here](#cross).

## Captioned figures and tables

Figures and tables *with captions* can also be cross-referenced from elsewhere in your book using `\@ref(fig:chunk-label)` and `\@ref(tab:chunk-label)`, respectively.

See Figure \@ref(fig:nice-fig).


```r
par(mar = c(4, 4, .1, .1))
plot(pressure, type = 'b', pch = 19)
```

\begin{figure}

{\centering \includegraphics[width=0.8\linewidth]{_main_files/figure-latex/nice-fig-1} 

}

\caption{Here is a nice figure!}(\#fig:nice-fig)
\end{figure}

Don't miss Table \@ref(tab:nice-tab).


```r
knitr::kable(
  head(pressure, 10), caption = 'Here is a nice table!',
  booktabs = TRUE
)
```

\begin{table}

\caption{(\#tab:nice-tab)Here is a nice table!}
\centering
\begin{tabular}[t]{rr}
\toprule
temperature & pressure\\
\midrule
0 & 0.0002\\
20 & 0.0012\\
40 & 0.0060\\
60 & 0.0300\\
80 & 0.0900\\
\addlinespace
100 & 0.2700\\
120 & 0.7500\\
140 & 1.8500\\
160 & 4.2000\\
180 & 8.8000\\
\bottomrule
\end{tabular}
\end{table}

<!--chapter:end:02-cross-refs.Rmd-->

# Parts

You can add parts to organize one or more book chapters together. Parts can be inserted at the top of an .Rmd file, before the first-level chapter heading in that same file. 

Add a numbered part: `# (PART) Act one {-}` (followed by `# A chapter`)

Add an unnumbered part: `# (PART\*) Act one {-}` (followed by `# A chapter`)

Add an appendix as a special kind of un-numbered part: `# (APPENDIX) Other stuff {-}` (followed by `# A chapter`). Chapters in an appendix are prepended with letters instead of numbers.




<!--chapter:end:03-parts.Rmd-->

# Footnotes and citations 

## Footnotes

Footnotes are put inside the square brackets after a caret `^[]`. Like this one ^[This is a footnote.]. 

## Citations

Reference items in your bibliography file(s) using `@key`.

For example, we are using the **bookdown** package [@R-bookdown] (check out the last code chunk in index.Rmd to see how this citation key was added) in this sample book, which was built on top of R Markdown and **knitr** [@xie2015] (this citation was added manually in an external file book.bib). 
Note that the `.bib` files need to be listed in the index.Rmd with the YAML `bibliography` key.


The RStudio Visual Markdown Editor can also make it easier to insert citations: <https://rstudio.github.io/visual-markdown-editing/#/citations>

<!--chapter:end:04-citations.Rmd-->

# Blocks

## Equations

Here is an equation.

\begin{equation} 
  f\left(k\right) = \binom{n}{k} p^k\left(1-p\right)^{n-k}
  (\#eq:binom)
\end{equation} 

You may refer to using `\@ref(eq:binom)`, like see Equation \@ref(eq:binom).


## Theorems and proofs

Labeled theorems can be referenced in text using `\@ref(thm:tri)`, for example, check out this smart theorem \@ref(thm:tri).

::: {.theorem #tri}
For a right triangle, if $c$ denotes the *length* of the hypotenuse
and $a$ and $b$ denote the lengths of the **other** two sides, we have
$$a^2 + b^2 = c^2$$
:::

Read more here <https://bookdown.org/yihui/bookdown/markdown-extensions-by-bookdown.html>.

## Callout blocks


The R Markdown Cookbook provides more help on how to use custom blocks to design your own callouts: https://bookdown.org/yihui/rmarkdown-cookbook/custom-blocks.html

<!--chapter:end:05-blocks.Rmd-->

# Sharing your book

## Publishing

HTML books can be published online, see: https://bookdown.org/yihui/bookdown/publishing.html

## 404 pages

By default, users will be directed to a 404 page if they try to access a webpage that cannot be found. If you'd like to customize your 404 page instead of using the default, you may add either a `_404.Rmd` or `_404.md` file to your project root and use code and/or Markdown syntax.

## Metadata for sharing

Bookdown HTML books will provide HTML metadata for social sharing on platforms like Twitter, Facebook, and LinkedIn, using information you provide in the `index.Rmd` YAML. To setup, set the `url` for your book and the path to your `cover-image` file. Your book's `title` and `description` are also used.



This `gitbook` uses the same social sharing data across all chapters in your book- all links shared will look the same.

Specify your book's source repository on GitHub using the `edit` key under the configuration options in the `_output.yml` file, which allows users to suggest an edit by linking to a chapter's source file. 

Read more about the features of this output format here:

https://pkgs.rstudio.com/bookdown/reference/gitbook.html

Or use:


```r
?bookdown::gitbook
```



<!--chapter:end:06-share.Rmd-->



<!--chapter:end:07-references.Rmd-->

