<h1 align="center" style="font-weight:bold;">Organização CEAR Dados</h1>
___

**Projetos em desenvolvimento:**
* Projeto Multi-Mapa PB

## Descrição dos repositórios

* [auxiliares](https://github.com/CEARDados/auxiliares)
  * Esse repositório reúne todos os programas auxiliares desenvolvidos, bem como dados da NASA, CRESESB e LABREN.
  
* [mm-web-plataform](https://github.com/CEARDados/mm-web-plataform)
  * Esse repositório reúne todos os arquivos relacionados ao desenvolvimento das telas do dashboard do projeto Mult-Mapa para apresentação à comunidade acadêmica no hall do prédio do CEAR. Os dados apresentados são coletados da estação climática localizada no CEAR e da usina UFPB localizada no Centro de Informática(CI).
  * Inicialmente, o dashboard está hospedado em uma máquina local no bloco KLM. É possível acessar com o endereli [http://150.165.164.130:8050/](http://150.165.164.130:8050/).


* [artigos-projeto-multi-mapa-pb](https://github.com/CEARDados/artigos-projeto-multi-mapa-pb)
  * Esse repositório reúne todos os arquivos desenvolvidos durante o processo de escrita dos trabalhos acadêmicos listados a seguir:
    * Avaliação do Potencial de Geração de Energia Solar e Eólica no Estado da Paraíba com o Uso de Base de Dados Interpolada
* [mmp](https://github.com/CEARDados/mmp)
  * Esse repositório reúne todos os materiais teóricos e práticos para capacitações internas e externa aos integrantes do projeto Multi-Mapa.
  * Além disso, algums dados tratados do estado da Paraíba estão disponibilizados no repositório.
* [mm](https://github.com/CEARDados/mm)
  * Esse repositório reúne todos os arquivos referentes ao desenvolvimento do pacote `json2dash`.
  * **O que é o pacote json2dash?**
    O pacote desenvolvido pelo Projeto Plataforma Multi-Mapa PB busca eliminar parcialmente a necessidade de utilizar programação para a confecção de aplicações web, uma vez que o usuário enviará informações por meio de um arquivo de texto no formato JSON (_JavaScript Object Notation_). As informações fornecidas como entrada são convertidas de forma automática em uma aplicação Dash que pode ser publicada na Internet.

   * **Aplicações utilizando o pacote _json2dash_**

    As seguintes aplicações foram desenvolvidas utilizando o pacote json2dash como dependência e hospedadas na plataforma [Heroku](https://www.heroku.com/).

    * [Grandezas Climáticas da PB](https://dashboard-estado-pb.herokuapp.com/)
        * _Dashboard_ desenvolvido para a análise de grandezas climáticas do estado da Paraíba (PB).
    * [Visualização com Gráficos](https://deploy-json2dash.herokuapp.com/)
        * Exemplo com todos os possíveis gráficos que a função `gera_graph_v02()` retorna.
    * [Teste do componente `graph`](https://json2dash-package-test.herokuapp.com/)
        * Exemplo com o componente graph.
    * [MM](https://multimapa-dev.herokuapp.com/)

    **Obs.:** _Para utilizar o pacote json2dash, acesse o tutorial [primeiros passos com o pacote Json2dash](https://miguel-mmf.github.io/first_steps_json2dash/) e utilize a ferramenta [Schema](https://joseitooliveira.github.io/j2d-schema/) para escrita inteligente do arquivo JSON_.
    ***
  * **Pasta [`Auxiliares`](https://github.com/CEARDados/mm/tree/master/Auxiliares)**

    A pasta `Auxiliares` contém alguns arquivos Jupyter Notebook desenvolvidos para a coleta, o tratamento e a manipulação de dados que serão utilizados pelo restante do grupo para o desenvolvimento de suas atividades.
    ***
  * **Pasta [`Dados`](https://github.com/CEARDados/mm/tree/master/Dados)**

    A pasta `Dados` contém as bases de dados utilizadas para observação e construção de _dashboards_ de dados. Existe nela uma grande quantidade arquivos `.csv`, `.json`, `.xlsx` e `.shp` com informações climatológicas e geográficas das 223 cidades do estado da Paraíba (PB) e informações sobre a geração distribuída no estado.

***
<h6 align="center" style="font-weight:bold;">mm@cear.ufpb.br</h6>