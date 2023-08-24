# Case - AKER - SENAI

Case realizado para o processo seletivo para a Bolsa do Projeto da Aker. <p>

As etapas realizadas foram:

1. Iniciar um repositório no GitHub;
    > O repositório foi desenvolvido de modo privado. Geralmente, insiro um .gitignore que não permite que os dados do problema sejam dispobinilizado no GitHub. Entretanto, por ser um *case*, julguei não ser necessário o controle dos dados. Por isso o *.gitignore* não foi inserido no repositório.

1. Criar um Ambiente Virtual;
    > O ambiente virtual foi desenvolvido para a instalação de todas as bibliotecas que forem necessárias a serem utilizadas. Desse modo, é possível assegurar cada versão da biblioteca que está sendo implementada.

1. Elabore um script em linguagem Python que contemple as etapas a  seguir:

    a. Realização da leitura dos dados, mantendo a formatação padrão disponibilizada no link.

    b. Realize a condução de uma análise exploratória dos dados, acompanhada pela descrição de cada ação tomada e da estratégia empregada.
    > Nessa etapa, foi realizado o tratamento dos dados (dados nulos e tipagem dos dados);
    > Também foi realizada uma análise da quantidade de informação de algumas *features*, com algumas plotagens.
    > Também foi realizada uma análise exploratória descritiva, utilizando o describe para verificar o comportamento das informações.

    c. Realize a implementação do treinamento de um modelo preditivo capaz de antever o cenário dos próximos 6 meses para os campos de interesse (SGMT_ASSISTENCIAL). Como exemplo, pode-se considerar a previsão para a categoria "Ambulatorial + Hospitalar sem obstetrícia" em relação a variáveis como (PORTE_OPERADORA), aberturas e fechamentos, entre outras. A estratégia e abordagem de previsão ficam à sua escolha.
    > Descrever o que foi feito.

    d. Realização da manipulação, organização e processamento dos dados visando a criação de um arquivo
de saída no formato CSV. Esse arquivo será utilizado como entrada para um sistema a ser desenvolvido
no PowerBI. Assegure que o arquivo contenha dados de maneira organizada, suficientes para a
geração de gráficos que facilitem a análise dos cenários históricos e previsões futuras derivadas do
modelo preditivo. As informações relevantes para os gráficos podem ser escolhidas conforme a sua
avaliação.


1. Prossiga desenvolvendo um sistema no PowerBI que receberá dados gerados pelo script da etapa 2. Esse sistema terá a finalidade de analisar a distribuição dos dados e visualizar o comportamento histórico, além de apresentar as previsões feitas para os próximos seis meses.
    > O dashboard requerido foi realizado no *Power BI Desktop*. Desse modo, foi utilizado um pc com Windows para a realização do dash.
    > A entrega foi realizada com o arquivo do *Power BI* e uma cópia em *.pdf*.


1. Garanta que o produto desenvolvido seja disponibilizado no GitHub, seguindo as melhores práticas de fluxo de desenvolvimento utilizando GitFlow.
    > Após cada etapa, o código foi inserido no GitHub com um comentário simples no *commit* informando qual a parte que foi realizada.


1. Ao finalizar, compartilhe também as dificuldades que tenha enfrentado ao executar essa atividade. Além disso,
faça um breve relato sobre a sua experiência com as seguintes áreas e tecnologias:
• Utilização de API Rest com Python (3.x)
• Aprendizado de Máquina (Machine Learning)
• Visão Computacional
• Desenvolvimento Web com HTML, CSS e JavaScript, incluindo React
• Banco de dados relacionais
• Uso de Docker para empacotamento de aplicações
• Integrações via API
• Uso do Git para controle de versões