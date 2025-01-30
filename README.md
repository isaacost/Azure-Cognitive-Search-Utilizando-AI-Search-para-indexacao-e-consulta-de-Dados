# Configurando uma Pesquisa com AI

Este documento fornece um guia passo a passo para configurar uma pesquisa baseada em inteligência artificial, seguindo as diretrizes da Microsoft AI Fundamentals.

## Passo a Passo

### 1. Criar um Serviço de Pesquisa no Azure
1. Acesse o [portal do Azure](https://portal.azure.com/).
2. Pesquise por **Azure Cognitive Search** na barra de pesquisa.
3. Clique em **Criar** e preencha os detalhes necessários:
   - Nome do serviço
   - Grupo de recursos
   - Localização
   - Camada de preços
4. Clique em **Revisar + Criar** e depois em **Criar**.

### 2. Configurar um Índice de Pesquisa
1. No serviço criado, vá até **Índices** e clique em **Novo índice**.
2. Defina os campos do índice com suas respectivas propriedades (ex.: nome, tipo, pesquisável, filtrável).
3. Salve o índice.

### 3. Criar uma Fonte de Dados
1. No serviço de pesquisa, vá até **Fontes de Dados** e clique em **Adicionar fonte de dados**.
2. Escolha o tipo de origem (ex.: Blob Storage, SQL Database, Cosmos DB).
3. Configure as credenciais de acesso à origem dos dados.
4. Salve a fonte de dados.

### 4. Criar e Configurar um Indexador
1. No serviço de pesquisa, vá até **Indexadores** e clique em **Novo indexador**.
2. Associe o indexador à fonte de dados criada.
3. Configure a frequência de indexação.
4. Execute o indexador para preencher o índice com dados.

### 5. Testar a Pesquisa
1. Vá até **Explorador de Pesquisa** no Azure Cognitive Search.
2. Insira termos de pesquisa e teste os resultados.

## Insights e Possibilidades
- **Relevância aprimorada**: Ajuste de scoring e sinônimos para melhorar os resultados.
- **Filtros e Facetas**: Permitem refinar os resultados com base em categorias.
- **Pesquisa Semântica**: Utilização de IA para entender melhor as intenções do usuário.
- **Integração com Chatbots e Assistentes Virtuais**: Melhora a experiência do usuário ao combinar pesquisa com processamento de linguagem natural.

## Ferramentas Beneficiadas
- **E-commerce**: Melhorando a busca por produtos.
- **Plataformas de Suporte**: Facilitando a busca por artigos e documentação.
- **Sistemas de Gestão de Conhecimento**: Organização de grandes volumes de informação.

## Aprendizados
- A configuração de um serviço de pesquisa eficaz depende de um bom modelo de indexação.
- Melhorar a relevância exige ajustes constantes na configuração dos índices.
- A pesquisa baseada em IA pode ser integrada a outras ferramentas para potencializar sua utilidade.

---

Para mais detalhes, consulte a documentação oficial: [Microsoft AI Fundamentals](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).
