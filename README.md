# Competição GOAT: Quem é o melhor jogador?
Este é um projeto de análise de dados utilizando os com dados do Kaggle dos gols dos jogadores Cristiano Ronaldo e Lionel Messi.<br>
No futebol o termo GOAT (em inglês: Greatest Of All Time), ou seja, o melhor de todos os tempos, tem sido usado por décadas pela imprensa estadunidense para se referir a um atleta que marca uma determinada era.
Nesta competição será realizada uma análise exploratória dos dados de gols e títulos dos jogadores e serão atribuídos pontos. As regras da competição serão as seguintes:

1) Contagem de pontos:<br>

Para cada TÍTULO ganho serão contabilizados:<br>

 * 1 ponto por Título,<br>
 * 5 pontos, caso o Título seja Individual<br>
 
 
Para cada GOL realizado serão contabilizados:<br>

 * 1 ponto por gol em rodadas de grupo,<br>
 * 2 pontos por gol em rodadas dos 16 melhores,<br>
 * 3 pontos por gol em quartas de final,<br>
 * 4 pontos por gol em semi-finais,<br>
 * 5 pontos por gol em finais.<br>

2) Definição dos Campeonatos:<br>

Apenas serão contabilizados os gols dos campeonatos em que os dois jogadores participaram.<br>

Quem será o ganhador desta competição?

# Informações
Para realizar esta competição foram utilizados: Python, as bibliotecas Pandas e Matplotlib e a técnica do storytelling.<br>
A biblioteca Pandas será utilizada para importar os dados para o arquivo e, também, para tratar os dados. A biblioteca Matplotlib será utilizada para plotagem dos gráficos dos dados.

Foi realizado um webscrapping para levantamento dos títulos ganhos em 17/03/2023 do site https://www.transfermarkt.pt/.


Desenvolvido com:<br>
<li>Anaconda, https://www.anaconda.com/;</li>
<li>Jupyter</li>
<li>Utilizada linguagem Python 3.9, instaladas bibliotecas Pandas e Matplotlib;</li>
<li>Dados dos gols referentes aos atletas Lionel Messi e Cristiano Ronaldo, https://www.kaggle.com/datasets/ahmedterry/cristiano-ronald-vs-lionel-messi-weekly-updated;</li>
<li>Dados de títulos ganhos por cada jogador do site https://www.transfermarkt.pt/.</li>

Este projeto será uma grande oportunidade para melhorar a análise de dados utilizando as bibliotecas Pandas e Matplotlib do Python.


# Arquivos
O arquivo "GOAT.ipynb" contém todo o conteúdo de análise e tratamento dos dados, é o arquivo onde foi construída toda a competição.
O arquivo "GOAT_COlab" foi criado no Google Colab e foi trancrito para a nuvem para quem não possui Jupyter em seu computador, facilitando a visualização dos dados.
Já o arquivo "GOAT_PBI" é um arquivo em Power BI para análise dos dados (para, quem tiver o desejo, poder visualizar facilmente os dados).

## Acessando o Arquivo GOAT:

1. Anaconda/ Jupyter<br>

Clonar este repositório para o seu Github.<br>
Importar o repositório para uma pasta de seu computador.<br>
Realizar a instalação do programa Anaconda, instalar o Python 3.9 e, dentro de Anaconda Navigator, realizar o download do Jupyter.<br>
Os dados estão disponíveis na pasta 'data' neste repositório, sendo:
    <li> Dados dos gols: cristiano_vs_messi.csv</li>
    <li> Dados de títulos do Cristiano Ronaldo: CR.csv</li>
    <li> Dados de títulos do Lionel Messi: LM.csv</li>

No prompt do Anaconda, realizar o download das bibliotecas Pandas e Matplotlib.<br>
Abrir Jupyter Notebook no Anaconda.<br>
Procurar pela pasta do repositório.<br>
Alterar o nome do caminho dos arquivos na segunda linha na etapa de importação dos dados selecionando o nome do caminho de seu computador.<br>
Apertar em 'RUN'.<br>
Após este passo, o programa irá rodar todos as tabelas e gráficos disponíveis.<br>

<img src="img/tela_GOAT.png" width="50%">

2) Google Colab<br>

Caso não deseje clonar todo esse repositório, também será disponibilizado um arquivo no Google Colab.<br>
Você só precisará clicar no link abaixo e clicar em "Ambiente de execução" e, em seguida, "Executar tudo".<br>

<a class="nav-link" href="https://colab.research.google.com/drive/1_GjkVmAnMNiqW_PWV-j-nzJeb_Pv0ZOb?usp=share_link" target="_blank">Clique aqui para acessar o arquivo!</a><br>


## Acessando o Arquivo GOAT:

1) Power BI<br>
Quer dar uma conferida nos dados utilizados?
Você irá precisar realizar o download do Power BI em seu computador para conseguir visualizar este arquivo...
<a class="nav-link" href="https://github.com/liliansom/GOAT/blob/main/GOAT_PBI.pbix" target="_blank">Clique aqui e faça o download do arquivo Power BI dos dados!</a><br>


<img src="img/Tela_PBI1.png">
<img src="img/Tela_PBI2.png">


# Resultados

<a class="nav-link" href="https://github.com/liliansom/GOAT/blob/main/img/MessiGOAT.jpg" target="_blank">Clique aqui e veja a foto de quem ganhou o título de GOAT nesta competição.</a><br>

# Andamento do projeto:
Entregue.<br>