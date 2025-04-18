# Tese-patentometria-Derwent

As informações abaixo se referem à tese de doutorado de Paula Cotrim de Abrantes elaborada na linha de pesquisa 1, Comunicação, Organização e Gestão da Informação e do Conhecimento, do Programa de Pós-Graduação em Ciência da Informação (PPGCI), do Instituto Brasileiro de Informação em Ciência e Tecnologia (Ibict), do Ministério da Ciência e Tecnologia e Inovação (MCTI), em associação com a Escola de Comunicação (ECO), da Universidade Federal do Rio de Janeiro (UFRJ).

O arquivo “programderwentcores-esse.ipynb” é um programa em Python elaborado com a finalidade de criar o arquivo edges.csv e o arquivo nodes.csv, usados pelo software VOSViewer. Esse programa usa o listascompleto2024esse.txt (arquivo completo dos resultados da Derwent conforme estratégia de busca detalhada nesta pesquisa de doutoramento) e gera os arquivos entrada.txt e entrada_new.txt, no qual cada linha terá o número da patente seguido de asterisco e o depositante. 
O arquivo countries.csv, se necessário, pode ser usado para designar cores diferentes para cada país. Ao rodar a segunda etapa do programa serão gerados os arquivos nodes.csv, com os nomes de todos os depositantes identificados na listascompleto2024esse.txt e o edges.csv, que mostra a quantidade de documentos que possuem depositantes em comum entre dois depositantes. O arquivo nodes.csv foi transformado em nodesajustadoderwent.csv e ajustado conforme os pesos atribuídos aos inventores encontrados no arquivo completo de resultados da Derwent para que esses refletissem corretamente o número de pedidos de patente identificados nos resultados da estratégia de busca realizada nessa base. Tanto o nodes.csv como o edges.csv, quando gerados, ficam no mesmo diretório onde está o programa programderwentcores.ipynb. 
Obs.: Ao rodar esse programa, ao final do processamento, pode aparecer a mensagem "IOPub data rate exceeded. The notebook server will temporarily stop sending output to the client in order to avoid crashing it. To change this limit, set the config variable `--NotebookApp.iopub_data_rate_limit`. 
Current values:
NotebookApp.iopub_data_rate_limit=1000000.0 (bytes/sec)
NotebookApp.rate_limit_window=3.0 (secs)". No entanto, é uma limitação da tela do computador, os dados foram devidamente processados juntamente com seus devidos arquivos. 

Para elaborar o grafo no VOSViewer, basta clicar na aba "file", após "open". Na aba VOSviewer localize o diretório correto, posteriormente, clique em “all documents”, insira o arquivo nodesajustadoderwent.csv e no campo abaixo, o arquivo edges.csv, e clique em “ok”."  

__________________________________________________________________________________________________________________________________________________________________________________________

O arquivo .ipynb é um programa em Python que foi usado para gerar a nuvem de palavras elaborada para esta pesquisa de doutoramento. Esse programa usou o arquivo “nuvem resumo patentes essa tese.ipynb”  onde as palavras escolhidas para constar na nuvem foram estruturadas na ordem: palavra; ranking; frequência, separadas pelo sinal de ponto e vírgula.  

