# Desafio de Projeto de Software em Kotlin

## Descrição
Desenvolva uma aplicação em Kotlin que simule um sistema de gerenciamento de tarefas. O sistema deve permitir que os usuários criem, editem, visualizem e excluam tarefas. Cada tarefa deve ter um título, descrição, data de vencimento e status (pendente, em progresso, concluída).

## Bibliotecas Necessárias
- Kotlin Standard Library
- kotlinx.coroutines (versão 1.5.2)
- Ktor (versão 1.6.3)
- Exposed (versão 0.34.1)

## Requisitos
- **Requisito funcional 1**: O sistema deve permitir a criação de novas tarefas com título, descrição, data de vencimento e status.
- **Requisito funcional 2**: O sistema deve permitir a edição de tarefas existentes.
- **Requisito funcional 3**: O sistema deve permitir a visualização de todas as tarefas em uma lista.
- **Requisito funcional 4**: O sistema deve permitir a exclusão de tarefas.
- **Requisito não funcional 1**: A aplicação deve ser desenvolvida utilizando o framework Ktor para a criação do servidor web.
- **Requisito não funcional 2**: O sistema deve utilizar o banco de dados SQLite para armazenamento das tarefas.

## Instruções de Instalação
1. Clone o repositório:
    ```sh
    git clone https://github.com/usuario/gerenciador-de-tarefas.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd gerenciador-de-tarefas
    ```
3. Instale as dependências:
    ```sh
    ./gradlew build
    ```
4. Configure as variáveis de ambiente:
    ```sh
    cp .env.example .env
    ```

## Instruções de Execução
1. Para iniciar o servidor:
    ```sh
    ./gradlew run
    ```
2. Para rodar os testes:
    ```sh
    ./gradlew test
    ```

## Critérios de Avaliação
- **Funcionalidade**: O software atende a todos os requisitos funcionais?
- **Qualidade do Código**: O código é limpo, bem organizado e segue as melhores práticas de desenvolvimento?
- **Documentação**: A documentação é clara e completa, facilitando a compreensão e execução do projeto?
- **Testes**: O projeto inclui testes abrangentes que garantem a funcionalidade correta do sistema?

## Prazo de Entrega
Informe a data e hora limite para a submissão do projeto.

## Submissão
Os desenvolvedores devem submeter seus projetos via pull request para o repositório original ou para um repposiório pessoal, mas precisa criar um arquivo .md com a resolução e o link para o repositório que contenha a resolução do desafio.

