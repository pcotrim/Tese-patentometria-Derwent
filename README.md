# Tese-patentometria-Derwent

As informações abaixo se referem à tese de doutorado de Paula Cotrim de Abrantes elaboradada no Programa de Pós-graduação em Ciência da Informação UFRJ/IBICT

O arquivo programderwentcores.ipynb é um programa em Python para criar o edges.csv e o nodes.csv usados pelo software VOSViewer. O programa programderwentcores.ipynb usa o listas.txt (arquivo completo dos resultados da Derwent conforme estratégia de busca detalhada na tese.) e gera o arquivo entrada e entrada_new.txt (cada linha terá o número da patente seguido de asterisco e o depositante). O arquivo countries.csv é usado para designar cores diferentes para cada país. Ao rodar a segunda etapa do programa serão gerados os arquivos nodes.csv (com os nomes de todos os depositantes identificados na lista.txt) e o edges.csv (mostra a quantidade de documentos que possuem depositantes em comum entre dois depositantes). Do arquivo nodes.csv foi criado o arquivo nodesajustadoderwent.csv, pois seus pesos foram ajustados de acordo com os resultados encontrados no arquivo completo da Derwent. Os arquivos, nodes.csv e edges.csv, quando gerados ficam no mesmo diretório onde está o programa programderwentcores.ipynb. Para elaborar o grafo no VOSViewer, basta clicar na aba "file", após "open". Na aba VOSviewer localize o diretório correto, posteriormente insira o arquivo nodesajustadoderwent.csv e no campo abaixo o arquivo edges.csv e ok.
__________________________________________________________________________________________________________________________________________________________________________________________

O arquivo: nuvem resumo patentes ESSA.ipynb é um programa em Python que foi usado para gerar a nuvem de palavras elaborada para a tese. Esse programa usou o arquivo patentometria-nuvem-2024.txt. Neste arquivo estão as palavras selecionadas a partir do Ponto de Transição de Goffman, sua frequência e o ranking que elas aparecem nos resumos dos pedidos de patente extraídos da Derwent conforme estratégia de busca detalhada na tese de doutoramento de Paula Cotrim de Abrantes.

