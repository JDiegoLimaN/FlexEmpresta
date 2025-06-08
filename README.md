🏦 FlexEmpresta - Modelagem de Dados
Projeto de modelagem de dados para a empresa FlexEmpresta, especializada em concessão de empréstimos. O objetivo é estruturar os dados existentes em planilhas para um modelo relacional bem definido, facilitando a gestão de clientes, empréstimos, contas bancárias e departamentos. 

📚 Sobre o Projeto
A FlexEmpresta é uma empresa que disponibiliza empréstimos para pessoas físicas. Atualmente, seus dados são armazenados em planilhas desorganizadas, dificultando a localização, padronização e análise das informações. Com o crescimento da base de clientes, tornou-se essencial organizar esses dados em um modelo estruturado e escalável.

Este projeto tem como objetivo principal:

Estruturar os dados da empresa em um modelo conceitual (MER);
Padronizar as informações;
Preparar os dados para uso em sistemas de BI ou banco de dados relacional.
🗂️ Conteúdo do Repositório
Arquivos Principais:
Planilha Original.xlsx: Dados brutos fornecidos pela empresa.
Planilha Final.xlsx: Dados organizados e tratados para modelagem.
Levantamento de requisitos.pdf: Documento com os requisitos funcionais e técnicos do projeto.
image.png: Modelo Entidade-Relacionamento (MER) final do projeto.
🧱 Modelo Conceitual (MER)
O modelo foi criado com base no levantamento de requisitos e nas planilhas fornecidas. Ele contempla as seguintes entidades principais:

✅ Entidades Fortes
Clientes
Colaboradores
Departamento
🔗 Entidades Fracas
ScoreCredito (depende de Cliente)
Conta (depende de Cliente)
ClienteConta (entidade associativa entre Cliente e Conta)
Empréstimo (depende de Cliente)
Pagamento (depende de Empréstimo)
🔄 Relacionamentos Importantes
Um cliente pode ter vários scores de crédito e várias contas (incluindo contas conjuntas).
Cada empréstimo está associado a um único cliente e pode ter múltiplos pagamentos.
Um departamento deve ser gerenciado por um colaborador e precisa ter pelo menos dois colaboradores atuando nele.
🛠️ Objetivos do Projeto
Tornar a base de dados mais acessível;
Facilitar a localização de informações cadastradas;
Padronizar o armazenamento de dados;
Permitir a geração de relatórios para tomada de decisão;
Apoiar futuras implementações tecnológicas e expansão do negócio.
📊 Uso dos Dados
Os dados serão utilizados para:

Geração de relatórios gerenciais;
Conhecimento detalhado dos clientes;
Controle de inadimplência;
Histórico de empréstimos e pagamentos.
🚀 Expectativas Futuras
Utilização de novas ferramentas tecnológicas (SGBDs, BI);
Abertura de filiais;
Inclusão de novos tipos de serviços e empréstimos;
Integração com sistemas automatizados.
📁 Estrutura Recomendada do Projeto


flexempresta-modelagem/
├── Planilha Original.xlsx
├── Planilha Final.xlsx
├── Levantamento de requisitos.pdf
├── image.png
└── README.md
🤝 Colaboração
Se você quiser contribuir com este projeto ou sugerir melhorias, fique à vontade para abrir uma issue ou enviar um pull request!
