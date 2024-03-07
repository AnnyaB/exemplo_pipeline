# exemplo_pipeline

# **Exercício Prático: Estruturação de Pipelines de CI/CD com GitHub Actions**

**Objetivo:**
Configurar um pipeline de integração e entrega contínua usando GitHub Actions para um projeto simples de software.

**Pré-requisitos:**

- Uma conta no GitHub.
- Conhecimento básico de Git e GitHub.
- Conhecimento em alguma linguagem de programação (como Python, JavaScript, etc.).

**Projeto de Exemplo no github:** 

https://github.com/paulatoledop/exemplo_pipeline

**Passo a Passo:**

1. **Crie um Novo Repositório no GitHub:**
    - Acesse o GitHub e crie um novo repositório público.
    - Clone o repositório em sua máquina local.
2. **Prepare o Projeto:**
    - Crie um projeto simples na linguagem de sua escolha.
    - Adicione um arquivo de teste que possa ser executado para validar as mudanças no código.
3. **Estruture o Código e Testes:**
    - Organize seu projeto em diretórios (por exemplo, **`src`** para código fonte e **`tests`** para testes).
    - Escreva um teste simples que possa ser automatizado.
4. **Crie um Arquivo de Workflow do GitHub Actions:**
    - Na raiz do repositório, crie uma pasta **`.github/workflows`**.
    - Dentro desta pasta, crie um arquivo de workflow YAML, por exemplo **`ci.yml`**.
5. **Defina o Workflow de Integração Contínua:**
    - No arquivo **`ci.yml`**, defina os passos para instalar dependências, executar testes e construir o projeto.
    - Utilize os runners do GitHub Actions para executar o workflow em push ou pull request.
6. **Adicione um Passo de Entrega Contínua:**
    - Após o passo de integração, adicione etapas para empacotar e entregar o código.
    - Por exemplo, adicione passos para deploy em um serviço de hospedagem ou servidor.
7. **Teste o Pipeline:**
    - Faça commit e push das suas mudanças para o repositório no GitHub.
    - Verifique se o GitHub Actions executa o pipeline conforme esperado.
8. **Adicione um Passo de Notificação:**
    - Configure notificações para serem enviadas em caso de falha ou sucesso do pipeline.
9. **Documentação:**
    - Documente o processo em um arquivo **`README.md`**, explicando como o pipeline funciona e como contribuir para o projeto.
10. **Experimente Mudanças:**
    - Faça mudanças no código e nos testes para ver o pipeline em ação.

**Entrega:**

- Submeta o link do seu repositório GitHub com o workflow configurado.

[Passo a Passo - Teste Automatizado](https://www.notion.so/Passo-a-Passo-Teste-Automatizado-f5df027361844f5d82e5fe9470182a78?pvs=21)

[Passo a Passo - Como criar um arquivo .gitignore](https://www.notion.so/Passo-a-Passo-Como-criar-um-arquivo-gitignore-ae6ab86d35ab41b4b6b44d63c132452f?pvs=21)

[Passo a Passo para criar um arquivo de workflow do GitHub Actions](https://www.notion.so/Passo-a-Passo-para-criar-um-arquivo-de-workflow-do-GitHub-Actions-6473c2de3e494a5ba20564f847bc20eb?pvs=21)

[Passo a passo para implementar Entrega Contínua com o Vercel](https://www.notion.so/Passo-a-passo-para-implementar-Entrega-Cont-nua-com-o-Vercel-305d4113ccfa4521a48eb39c665508e5?pvs=21)