# TP: Teste de Software

## Objetivo
Desenvolver e testar um pequeno sistema. Mensurar cobertura. Utilizar CI/CD.

## Sobre o Sistema

Crie um repositório no GitHub para armazenar a seu sistema. O sistema deve ter um nome; não utilize nomes como `tp_teste`.

Desenvolva um sistema de software simples, como uma aplicação de linha de comando, um sistema web ou um aplicativo móvel. O sistema deve incluir funcionalidades mínimas que permitam a interação com o usuário. Nosso objetivo principal é evidenciar como os testes ajudam na manutenção de um sistema de software. Sistema, linguagem de programação e tecnologias são de livre escolha.

O repositório deve conter um arquivo `README.md` com as seguintes seções:
- Nomes dos membros do grupo.
- Breve explicação sobre os objetivos da ferramenta.
- Breve explicação sobre as tecnologias utilizadas.
- Como executar os testes localmente.

## Especificação

**Implementar 30 testes de unidade**. Implementar pelo menos 30 testes de unidade. Os testes devem seguir boas práticas, como testes através de API públicas, teste de comportamento, bons nomes, testes focados, testes não-complexos, etc. 

**Implementar 5 testes de integração ou de sistema (e2e)**. Os testes de integração ou e2e também devem seguir boas práticas.

**Mensurar cobertura de teste (cobertura ≥ 80%)**. Selecione e utilize alguma ferramenta de cobertura da linguagem escolhida, por exemplo, Coverage.py para Python, Istanbul ou Jest para JavaScript, JaCoCo para Java, etc. A cobertura de testes deve ser ≥ 70%.

**Utilizar CI/CD com GitHub Actions**. Os testes e cobertura devem ser executados automaticamente a cada commit nos sistemas operacionais Linux, MacOS e Windows. Para isso, deve-se configurar e utilizar a ferramenta GitHub Actions. No GitHub, existem diversos exemplos sobre como utilizar o GitHub Actions para várias linguagens. Sugestão: Configure o GitHub Actions desde o início do desenvolvimento para executar os testes automaticamente desde os primeiros commits.

**Publicar os relatórios de cobertura no Codecov através do GitHub Actions**. O grupo deve utilizar o [Codecov GitHub Action](https://github.com/marketplace/actions/codecov) e fazer o upload do relatório de cobertura no Codecov. Na documentação, você encontra [diversos exemplos](https://docs.codecov.com/docs/supported-languages) sobre como utilizar o Codecov GitHub Action para várias linguagens de programação.

## Sobre o Codecov 

Codecov é uma plataforma para publicação online de relatórios de cobertura. Você deve criar uma conta no Codecov e permitir acesso ao GitHub. Exemplos de relatórios de cobertura publicados no Codecov:
VueJS: https://codecov.io/github/vuejs/vue
Django Rest: https://codecov.io/github/encode/django-rest-framework

## Submissão

Submeter via Moodle três links:
- O link do repositório GitHub.
- O link para o último build de sucesso do GitHub Actions, mostrando a execução dos testes (exemplo: https://github.com/Textualize/rich/actions/runs/17610757833).
- O link do Codecov do sistema. Por exemplo: https://codecov.io/github/encode/django-rest-framework
