# Projeto de Simulado
## Introdução
Este projeto utiliza a inteligência artificial do Google AI Studio para elaborar questões de múltipla escolha e criar um sistema de simulado para concursos públicos na área de tecnologia da informação. O objetivo é auxiliar candidatos a se prepararem para provas, fornecendo uma ferramenta interativa e eficaz para testar seus conhecimentos.
### Fase 1: Elaboração das Questões
Definição do Conteúdo: O ponto de partida foi um documento extenso contendo os conhecimentos específicos exigidos em concursos da área de TI. Esse documento foi cuidadosamente analisado e dividido em cinco eixos temáticos principais:
Gestão Governamental e Governança Pública
Políticas Públicas
Gerência e Suporte da Tecnologia da Informação
Desenvolvimento de Software
Apoio à Decisão, Inteligência Artificial e Métodos Quantitativos
Criação das Questões: Com base no conteúdo de cada eixo temático, foram elaboradas 50 questões de múltipla escolha, 10 para cada tema. Cada questão possui cinco alternativas, com apenas uma correta.
Balanceamento das Alternativas: Para garantir a imparcialidade e a qualidade do simulado, as alternativas corretas foram distribuídas de forma equilibrada, com 10 acertos para cada alternativa (A, B, C, D e E).
### Fase 2: Criação do DataFrame e Arquivo CSV
Organização dos Dados: As questões, alternativas e gabaritos foram organizados em um dicionário Python, estruturado por tema.
Criação do DataFrame: Utilizando a biblioteca pandas, o dicionário foi convertido em um DataFrame, uma estrutura tabular que facilita a manipulação e análise dos dados.
Exportação para CSV: O DataFrame foi exportado para um arquivo CSV ("questoes_simulado.csv"), um formato universal que permite a fácil leitura e importação dos dados em diversas aplicações.
### Fase 3: Desenvolvimento do Simulado
Leitura do DataFrame: A aplicação do simulado, escrita em Python, inicia lendo o arquivo CSV e carregando os dados em um DataFrame pandas.
Interface com o Usuário: O usuário escolhe um dos cinco temas disponíveis, e o sistema filtra as questões correspondentes.
Apresentação das Questões: As questões do tema escolhido são apresentadas ao usuário em ordem aleatória.
Registro das Respostas: O sistema registra as respostas do usuário e verifica se estão corretas.
Feedback e Resultados: Ao final do simulado, o usuário recebe feedback sobre seu desempenho, incluindo a quantidade de acertos, a porcentagem de acerto e uma mensagem de encorajamento ou incentivo para continuar estudando.
### Fase 4: Publicação no GitHub
Criação do Repositório: Um repositório no GitHub ("projeto-simulado") foi criado para hospedar o código-fonte do projeto.
Organização dos Arquivos: O repositório contém os seguintes arquivos:
#### README.md: Este arquivo, com a descrição detalhada do projeto.
#### questoes_simulado.csv: O arquivo CSV com as questões, alternativas e gabaritos.
#### simulado.ipynb: O código-fonte do simulado em formato Jupyter Notebook.
#### cadastro_questao.ipynb: Um notebook auxiliar para cadastrar novas questões no DataFrame.
#### CNPU - Conhecimentos Específicos.txt: O documento original com o conteúdo programático.
### Próximos Passos
Aprimoramento da Interface: Criar uma interface gráfica mais amigável e interativa para o usuário.
Expansão do Banco de Questões: Adicionar mais questões ao sistema, abrangendo outros concursos e áreas de conhecimento.
Implementação de Recursos Adicionais: Incluir funcionalidades como histórico de desempenho, ranking de usuários, personalização do simulado, entre outros.
### Conclusão
Este projeto demonstra como a inteligência artificial pode ser utilizada para criar ferramentas educacionais inovadoras. O sistema de simulado desenvolvido é uma ferramenta valiosa para candidatos a concursos públicos na área de TI, auxiliando-os a se prepararem de forma mais eficiente e alcançar melhores resultados.
