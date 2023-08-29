# Web Scraping Amazon



O projeto teve o objetivo de realizar um estudo sobre Web Scraping com ETL, web scraping são técnicas para a coleta de dados diretamente de páginas da web, nesse estudo foi utilizado o site da Amazon, em específico uma página referente à vendas de televisores, ( https://www.amazon.com.br/s?i=electronics&rh=n%3A16243822011%2Cp_72%3A17833786011&content-id=amzn1.sym.578aa6a5-6bfa-4747-975c-cee0f889732e&pd_rd_r=7538e36b-adc4-4bb5-b22c-4244b566357f&pd_rd_w=QzjCE&pd_rd_wg=CzeX1&pf_rd_p=578aa6a5-6bfa-4747-975c-cee0f889732e&pf_rd_r=M5ST1MD384C6WAYW9P0H&qid=1692993545 ) na qual foi realizada a extração do dados, transformação dos dados e carregamento para um arquivo csv padrão.



Os processos de extração, transformação e carregamento dos dados para um arquivo csv externo, foram feitos utilizando a linguagem Python e as seguintes bibliotecas:
<li>Urllib</li> Utilizada para abrir as páginas web.
<li>Pandas</li> Utilizada para manipular os dados.
<li>bs4</li> Utilizada para analisar diretamente os códigos HTML da página.
