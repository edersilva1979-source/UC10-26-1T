# Exercício Teórico Avaliativo de Git e GitHub

## 1. Objetivo da atividade

Nesta atividade avaliativa, nós vamos testar os principais conhecimentos estudados durante as aulas de Git e GitHub.

O objetivo é demonstrar que sabemos a teoria também:

1. Vamos Acessar o link que leva ao Form de avaliação teorica
2. Somente após concluir a teorica, vamos fazer a prática
3. link: https://forms.gle/T2RtwGHEE9FerjNZ9


# Exercício Prático Avaliativo de Git e GitHub

## 1. Objetivo da atividade

Nesta atividade avaliativa, nós vamos colocar em prática os principais conhecimentos estudados durante as aulas de Git e GitHub.

O objetivo é demonstrar que sabemos trabalhar com:

1. Repositório Git local
2. Controle de versões
3. Commits
4. Branches
5. Merge
6. Repositório remoto no GitHub
7. Push
8. Tags
9. Releases
10. Exclusão de branches
11. Documentação de um projeto

Ao final da atividade, cada aluno deverá possuir um projeto organizado localmente e publicado corretamente no GitHub.

# 2. Regras gerais da avaliação

A atividade deverá ser realizada individualmente.

O aluno deverá seguir a sequência apresentada neste documento.

O histórico de commits será utilizado como parte da avaliação. Portanto, não basta que os arquivos estejam disponíveis no GitHub. Será necessário demonstrar que o processo foi realizado corretamente.

O projeto deverá possuir exatamente 6 commits principais, conforme determinado nesta atividade.

Como o projeto também deverá possuir README.md e LICENSE, esses dois arquivos serão adicionados juntos em um mesmo commit.

# 3. Parte 1. Criar o repositório local

Crie uma pasta para o projeto com o nome:

```text
avaliacao
```

Dentro dessa pasta, crie um novo repositório Git local.

Ao concluir essa etapa, a pasta deverá estar sendo controlada pelo Git.

# 4. Parte 2. Criar os arquivos iniciais

Crie os seguintes arquivos dentro do projeto:

```text
Index.html
.gitignore
CHANGELOG.md
LICENSE
README.md
```

Observe atentamente os nomes dos arquivos.

## 4.1 Arquivo Index.html

O arquivo Index.html deverá possuir uma estrutura HTML válida.

Exemplo de informações que poderão aparecer na página:

```text
Avaliação Prática de Git e GitHub

Nome do aluno

Turma

Data da atividade
```

Não deixe o arquivo vazio.

## 4.2 Arquivo .gitignore

O arquivo .gitignore deverá estar preenchido corretamente.

O objetivo desse arquivo é impedir que arquivos desnecessários sejam enviados para o repositório.

Exemplo:

```gitignore
.vscode/
.idea/
*.log
temp/
dist/
```

O aluno poderá acrescentar outras configurações que considerar necessárias.

O arquivo não poderá estar vazio.

# 5. Arquivo CHANGELOG.md

O arquivo CHANGELOG.md deverá registrar as versões do projeto.

Inicialmente, poderá conter uma estrutura semelhante a esta:

```markdown
# Changelog

## Versão 1.0.0

Cadastro inicial de clientes.

## Versão 1.1.0

Cadastro inicial de produtos.
```

O conteúdo poderá ser atualizado durante o desenvolvimento da atividade.

# 6. Arquivo LICENSE

O arquivo LICENSE deverá possuir o texto de uma licença de software válida.

Para esta atividade, recomendamos utilizar a licença MIT.

O arquivo não poderá possuir apenas o nome da licença.

Ele deverá conter o texto completo da licença escolhida.

Também deverão ser informados o ano e o nome do responsável pelo projeto quando a licença utilizada solicitar essas informações.

# 7. Arquivo README.md

O README.md deverá apresentar o projeto de forma organizada.

Ele deverá possuir, no mínimo:

1. Nome do projeto
2. Descrição
3. Objetivo
4. Tecnologias utilizadas
5. Estrutura do projeto
6. Funcionalidades desenvolvidas
7. Informações sobre as versões
8. Informações sobre a licença
9. Nome do autor

Exemplo de estrutura:

```markdown
# Avaliação Prática de Git e GitHub

## Descrição

Projeto desenvolvido como atividade prática avaliativa da disciplina de Git e GitHub.

## Objetivo

Aplicar os conhecimentos de controle de versão, branches, merge, tags, releases e GitHub.

## Tecnologias

Git

GitHub

HTML

Markdown

## Funcionalidades

Cadastro de clientes

Cadastro de produtos

## Versões

### v1.0.0

Implementação do cadastro de clientes.

### v1.1.0

Implementação do cadastro de produtos.

## Licença

Este projeto utiliza uma licença de software definida no arquivo LICENSE.

## Autor

Nome do aluno
```

# 8. Parte 3. Criar a branch de cliente

A partir da branch principal, crie uma nova branch chamada:

```text
feature/cliente
```

Entre na branch feature/cliente.

Dentro dela, crie o arquivo:

```text
cad_cli.txt
```

O arquivo deverá conter alguma informação relacionada ao cadastro de clientes.

Exemplo:

```text
Cadastro de Clientes

Nome
CPF
Telefone
Email
```

Não deixe o arquivo vazio.

# 9. Parte 4. Criar a branch de produto

Retorne para a branch principal.

A partir dela, crie uma nova branch chamada:

```text
feature/produto
```

Entre na branch feature/produto.

Dentro dela, crie o arquivo:

```text
cad_pro.txt
```

O arquivo deverá conter informações relacionadas ao cadastro de produtos.

Exemplo:

```text
Cadastro de Produtos

Código
Descrição
Categoria
Valor
Estoque
```

Não deixe o arquivo vazio.

# 10. Parte 5. Realizar os commits

O projeto deverá possuir exatamente 6 commits principais.

Os commits deverão ser organizados da seguinte forma:

## Commit 1

Adicionar o arquivo:

```text
Index.html
```

Mensagem sugerida:

```text
Cria página inicial do projeto
```

## Commit 2

Adicionar o arquivo:

```text
.gitignore
```

Mensagem sugerida:

```text
Configura arquivos ignorados pelo Git
```

## Commit 3

Adicionar o arquivo:

```text
CHANGELOG.md
```

Mensagem sugerida:

```text
Adiciona histórico de versões
```

## Commit 4

Adicionar os arquivos:

```text
README.md
LICENSE
```

Mensagem sugerida:

```text
Adiciona documentação e licença do projeto
```

## Commit 5

Na branch:

```text
feature/cliente
```

Adicionar:

```text
cad_cli.txt
```

Mensagem sugerida:

```text
Implementa cadastro de clientes
```

## Commit 6

Na branch:

```text
feature/produto
```

Adicionar:

```text
cad_pro.txt
```

Mensagem sugerida:

```text
Implementa cadastro de produtos
```

# 11. Atenção aos commits

Os seis commits fazem parte da avaliação.

Não realize todos os arquivos em um único commit.

O professor poderá analisar o histórico do Git para conferir a sequência das alterações.

Mensagens como:

```text
alteração
teste
arquivo
commit
ajuste
final
```

devem ser evitadas.

Utilize mensagens que expliquem claramente o que foi realizado.

# 12. Parte 6. Criar o repositório no GitHub

Entre em sua conta no GitHub.

Crie um novo repositório para esta avaliação.

Utilize o nome:

```text
avaliacao
```

Depois de criar o repositório remoto, conecte o repositório Git local ao repositório criado no GitHub.

A branch principal deverá utilizar o nome:

```text
main
```

# 13. Parte 7. Enviar o projeto para o GitHub

Depois de realizar a conexão entre o Git local e o GitHub, envie os arquivos para o repositório remoto.

Confira no GitHub se os seguintes arquivos aparecem corretamente:

```text
Index.html
.gitignore
CHANGELOG.md
LICENSE
README.md
```

Confira também se o histórico de commits está disponível.

# 14. Parte 8. Realizar o merge da feature/cliente

Retorne para a branch:

```text
main
```

Faça o merge da branch:

```text
feature/cliente
```

com a branch principal.

Após o merge, confira se o arquivo:

```text
cad_cli.txt
```

passou a fazer parte da branch main.

Envie as alterações para o GitHub.

# 15. Parte 9. Criar a Tag v1.0.0

Depois que o cadastro de clientes estiver integrado à branch principal, crie a primeira Tag do projeto.

Nome da Tag:

```text
v1.0.0
```

Essa Tag deverá representar a primeira versão oficial da aplicação.

A versão 1.0.0 deverá possuir:

```text
Index.html
.gitignore
CHANGELOG.md
LICENSE
README.md
cad_cli.txt
```

# 16. Parte 10. Enviar a Tag v1.0.0

Depois de criar a Tag localmente, envie a Tag para o GitHub.

Confira na área de Tags do repositório se aparece:

```text
v1.0.0
```

# 17. Parte 11. Criar a Release 1.0.0

No GitHub, crie uma Release utilizando a Tag:

```text
v1.0.0
```

Título sugerido:

```text
Versão 1.0.0
```

Descrição sugerida:

```text
Primeira versão oficial do projeto.

Nesta versão foi implementada a estrutura inicial do projeto e o cadastro de clientes.
```

A Release deverá utilizar a Tag correta.

# 18. Parte 12. Realizar o merge da feature/produto

Na branch principal:

```text
main
```

faça o merge da branch:

```text
feature/produto
```

Após o merge, confira se o arquivo:

```text
cad_pro.txt
```

passou a fazer parte da branch principal.

Envie as alterações necessárias para o GitHub.

# 19. Parte 13. Criar a Tag v1.1.0

Depois da integração do cadastro de produtos, crie uma nova Tag:

```text
v1.1.0
```

Essa versão deverá possuir tanto o cadastro de clientes quanto o cadastro de produtos.

# 20. Parte 14. Enviar a Tag v1.1.0

Envie a Tag:

```text
v1.1.0
```

para o GitHub.

Confira se agora o repositório possui as duas Tags:

```text
v1.0.0
v1.1.0
```

# 21. Parte 15. Criar a Release 1.1.0

No GitHub, crie uma nova Release utilizando a Tag:

```text
v1.1.0
```

Título sugerido:

```text
Versão 1.1.0
```

Descrição sugerida:

```text
Segunda versão oficial do projeto.

Nesta versão foi acrescentado o cadastro de produtos ao sistema.
```

# 22. Parte 16. Excluir as branches utilizadas

Depois que os dois merges estiverem concluídos e as versões estiverem publicadas, exclua as branches que não serão mais necessárias.

Branches:

```text
feature/cliente
feature/produto
```

As branches deverão ser excluídas do repositório local.

Também deverão ser excluídas do GitHub caso tenham sido enviadas para o repositório remoto.

Ao final, a branch principal deverá ser:

```text
main
```

# 23. Estrutura final esperada

Ao final da atividade, a branch main deverá possuir:

```text
avaliacao

Index.html
.gitignore
CHANGELOG.md
LICENSE
README.md
cad_cli.txt
cad_pro.txt
```

# 24. Histórico de versões esperado

O projeto deverá apresentar duas versões oficiais.

## Versão 1.0.0

Deverá representar:

```text
Estrutura inicial do projeto
Documentação
Licença
Cadastro de clientes
```

Tag:

```text
v1.0.0
```

Release:

```text
1.0.0
```

## Versão 1.1.0

Deverá representar:

```text
Estrutura inicial do projeto
Documentação
Licença
Cadastro de clientes
Cadastro de produtos
```

Tag:

```text
v1.1.0
```

Release:

```text
1.1.0
```

# 25. Resultado esperado no GitHub

Ao acessar o repositório do aluno, deverá ser possível encontrar:

1. README.md completo
2. LICENSE preenchido
3. .gitignore configurado
4. CHANGELOG.md
5. Index.html
6. cad_cli.txt
7. cad_pro.txt
8. Histórico de commits organizado
9. Tag v1.0.0
10. Tag v1.1.0
11. Release 1.0.0
12. Release 1.1.0
13. Branch main atualizada
14. Branches feature/cliente e feature/produto removidas

# 26. Critérios de avaliação

A atividade poderá ser avaliada considerando os seguintes critérios.

| Critério | Pontuação |
| :--- | ---: |
| Criação e configuração do repositório Git | 5 pontos |
| Estrutura dos arquivos | 10 pontos |
| README.md completo | 10 pontos |
| LICENSE e .gitignore corretos | 10 pontos |
| Organização dos 6 commits | 15 pontos |
| Criação correta das branches | 10 pontos |
| Conexão e envio para o GitHub | 10 pontos |
| Merge da feature/cliente | 5 pontos |
| Tag e Release 1.0.0 | 5 pontos |
| Merge da feature/produto | 5 pontos |
| Tag e Release 1.1.0 | 5 pontos |
| Exclusão das branches utilizadas | 5 pontos |
| Organização geral do repositório | 5 pontos |
| **Total** | **100 pontos** |

# 27. Penalizações

Poderão resultar em perda de pontos:

1. Arquivos vazios
2. README.md incompleto
3. LICENSE sem o texto da licença
4. .gitignore vazio
5. Commits realizados de forma incorreta
6. Ausência das Tags
7. Ausência das Releases
8. Merge realizado incorretamente
9. Branches não excluídas ao final
10. Arquivos criados diretamente no GitHub quando deveriam fazer parte do fluxo realizado com Git
11. Projeto enviado somente ao final sem demonstrar corretamente o histórico de desenvolvimento

# 28. Conferência antes da entrega

Antes de entregar a atividade, confira:

```text
Repositório Git criado

Repositório GitHub criado

Index.html criado

.gitignore preenchido

CHANGELOG.md preenchido

LICENSE preenchido

README.md completo

feature/cliente criada

cad_cli.txt criado

feature/produto criada

cad_pro.txt criado

6 commits realizados

Merge da feature/cliente realizado

Tag v1.0.0 criada

Tag v1.0.0 enviada ao GitHub

Release 1.0.0 criada

Merge da feature/produto realizado

Tag v1.1.0 criada

Tag v1.1.0 enviada ao GitHub

Release 1.1.0 criada

Branches utilizadas excluídas

Branch main atualizada no GitHub
```

# 29. Entrega

Para realizar a entrega da avaliação, o aluno deverá informar o endereço do repositório público no GitHub.

Exemplo:

```text
https://github.com/usuario/avaliacao
```

O professor poderá analisar não apenas os arquivos finais, mas também:

```text
Commits
Branches
Histórico
Tags
Releases
README
CHANGELOG
LICENSE
.gitignore
```

Portanto, o processo de desenvolvimento faz parte da avaliação.

# 30. Desafio final

Ao concluir esta atividade, nós teremos reproduzido uma parte importante do fluxo utilizado diariamente em projetos profissionais.

Não estaremos avaliando apenas se o arquivo chegou ao GitHub.

Estaremos avaliando se sabemos utilizar corretamente o controle de versões, organizar o histórico do projeto, trabalhar com branches, integrar funcionalidades, criar versões oficiais e documentar o desenvolvimento.

O objetivo final é compreender que Git e GitHub não servem apenas para guardar arquivos.

Eles registram a evolução de um projeto.