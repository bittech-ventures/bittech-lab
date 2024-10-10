# bittech-lab
Capacitação em novas tecnologias com aulas teóricas, exercícios práticos e desafios. Os participantes aprenderão conceitos inovadores, aplicarão conhecimentos em situações reais e colaborarão em equipe para resolver problemas complexos, desenvolvendo habilidades técnicas e promovendo a inovação.


# Instruções

É possivel contribuir com este de duas formas:
1. Criando desafios:
   2. Para criar um novo desafio basta incluir um arquivo .md dentro da pasta da linguagem correspondente.
      3. Se quizer fazer para uma linguagem que ainda não tem pasta é só adicionar a pasta seguindo o mesmo padrão das demais.
4. Resolvendo desafios:
   5. Você pode resolver os desafios já existentes.
   6. A resolução do desafio pode ser feito direto nesse repositório ou em outro repositório
      7. Caso opte por colocar o desafio em outro repositório será necessário criar um .md com a descrição de como você resolveu e o link do repositório.


## Passo a Passo

1. **Faça um Fork do Repositório**
   - Vá para a página principal do repositório.
   - Clique no botão "Fork" no canto superior direito.

2. **Clone o Repositório Forked**
   - No seu terminal, clone o repositório usando o comando:
     ```bash
     git clone git@github.com:bittech-ventures/bittech-lab.git
     ```
   - Navegue até o diretório do projeto:
     ```bash
     cd bittech-lab
     ```

3. **Crie uma Nova Branch**
   - Crie uma nova branch para trabalhar na sua solução:
     ```bash
     git checkout -b minha-solucao
     ```

4. **Implemente a Solução**
   - Crie uma pasta com o nome da issue dentro da pasta da linguagem correspondente (ex: `Python/`, `Kotlin/`, `Golang/`).
   - Adicione sua solução na pasta criada.
   - Certifique-se de incluir testes para validar sua implementação.

5. **Commit e Push das Alterações**
   - Adicione os arquivos modificados:
     ```bash
     git add .
     ```
   - Faça o commit das suas alterações:
     ```bash
     git commit -m "Adiciona solução para [descrição da tarefa]"
     ```
   - Envie as alterações para o seu repositório forked:
     ```bash
     git push origin minha-solucao
     ```

6. **Abra um Pull Request**
   - Vá para a página do seu repositório forked no GitHub.
   - Clique no botão "Compare & pull request".
   - Preencha o formulário de pull request com uma descrição detalhada das suas alterações.
   - Clique em "Create pull request".

## Dicas

- Certifique-se de que seu código está bem documentado.
- Verifique se todos os testes passam antes de abrir o pull request.
- Siga as convenções de codificação do projeto.

