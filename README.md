# dio-resumo-do-lab-armazenamento

## Resumo da Aula
Nesta aula, exploramos diversos tópicos relacionados ao armazenamento e migração no Microsoft Azure. A seguir, um resumo dos principais pontos abordados:

### 1. Criação de Conta de Armazenamento
- **Configurações**:
  - **Assinatura e Grupos de Recursos**: Seleção da assinatura e do grupo de recursos apropriado.
  - **Nome**: O nome da conta de armazenamento deve ser único, com 3 a 24 caracteres, podendo conter apenas letras minúsculas e números.
  - **Região**: Escolha da região onde os dados serão armazenados.
  - **Desempenho**: Opções entre **Standard** e **Premium**.
  - **Redundância**: Definição do modelo de redundância, incluindo:
    - **LRS** (Locally-Redundant Storage)
    - **GRS** (Geo-Redundant Storage)
    - **ZRS** (Zone-Redundant Storage)
    - **GZRS** (Geo-Zone-Redundant Storage)

### 2. Tipos de Armazenamento
- **Blobs e Compartilhamento de Arquivos**: Aprendemos a armazenar dados como blobs e a compartilhar arquivos dentro da conta de armazenamento.
- **Camadas de Armazenamento e Replicação**: Discussão sobre os modelos de camadas e as opções de replicação para otimizar custos e segurança.

### 3. Fila de Mensagens, Tabelas e Políticas de Acesso
- **Adição de Filas e Tabelas**: Foi demonstrado como adicionar filas de mensagens e tabelas à conta de armazenamento.
- **Políticas de Acesso**: Configuração de políticas de acesso para controlar permissões.

### 4. Migração para o Azure
- **Criação de Projetos de Teste de Migração**: Aprendemos a criar um projeto de teste de migração, focando nas seguintes opções:
  - **Servidores**
  - **Bancos de Dados**
  - **Aplicativos Web**
  - **Data Box**: Solução para transferir grandes quantidades de dados.

### 5. Ferramentas e Configurações
- **AzCopy**: Ferramenta para a transferência de dados entre o local e o Azure.
- **Criação de Containers e Tokens de Acesso Compartilhado (SAS)**: Demonstramos como criar containers e gerar tokens de acesso compartilhado para alterar permissões de acesso.

## Conclusão
A aula ofereceu uma visão completa sobre o gerenciamento de contas de armazenamento no Azure, abordando desde a criação e configuração até migrações e controle de acesso. Foi fundamental para entender as melhores práticas e como otimizar o uso dos recursos de armazenamento no Azure.
