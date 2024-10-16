# Desafio de Projeto de Software: E-ShopHub

## Descrição
Desenvolva uma API em Kotlin para um sistema de e-commerce chamado "E-ShopHub". A API deve permitir aos usuários gerenciar produtos, categorias, carrinho de compras e processar pedidos. A segurança da API deve ser gerenciada através do AWS Cognito e Spring Security. O sistema também deve integrar o Apache Kafka para a comunicação assíncrona.

## Bibliotecas Necessárias
- Kotlin Standard Library
- Spring Boot (versão 2.5.4)
- Spring Security (versão 5.5.1)
- Spring Data JPA (versão 2.5.4)
- Apache Kafka (versão 2.8.0)
- AWS SDK for Java (versão 1.12.42)
- Jackson (versão 2.12.3)

## Requisitos
- **Requisito funcional 1**: O sistema deve permitir a criação, edição e exclusão de produtos.
- **Requisito funcional 2**: O sistema deve permitir a criação, edição e exclusão de categorias de produtos.
- **Requisito funcional 3**: O sistema deve permitir a adição de produtos ao carrinho de compras.
- **Requisito funcional 4**: O sistema deve permitir o processamento de pedidos.
- **Requisito não funcional 1**: A API deve implementar autenticação e autorização usando AWS Cognito e Spring Security.
- **Requisito não funcional 2**: A comunicação de eventos entre componentes do sistema deve ser feita via Apache Kafka.
- **Requisito não funcional 3**: A aplicação deve ser desenvolvida utilizando boas práticas de segurança e seguir as recomendações do OWASP.

## Instruções de Instalação
1. Clone o repositório:
    ```sh
    git clone https://github.com/usuario/eshophub.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd eshophub
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
    ./gradlew bootRun
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
Os desenvolvedores devem submeter seus projetos via pull request para o repositório original.
