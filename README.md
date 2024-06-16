# 📚 Módulo 2: Trabalhando com repositórios do GitHub

| [![GitHub4Women](https://github.com/lirazootech/GitHub4Women-Modulo2/blob/282127ae204294c01e7fcbd75d8339638d2dec91/GitHub4Women.png)](https://www.maismulheres.tech/) |
|:--:|
| Este repositório foi criado para praticar e aplicar os conhecimentos adquiridos durante o curso GitHub4Women sobre repositórios e conceitos básicos de Git e GitHub. |

# 🎯 Conceito e abordagem:

A atividade visa consolidar o conhecimento apresentado em sala de aula, abordando os seguintes tópicos:

- Criação de repositório
- Adição de arquivos
- Adição de branch
- Clone de repositório

## 🤖 Tecnologias Utilizadas:

Para realização dessa atividade, eu utilizei algumas tecnologias:

- GitHub: Plataforma destina ao desenvolvimento de software, colaboração e segurança. Por ela foi possível realizar a comunicação e a colaboração em tempo real nas alterações feitas no repositório, commits e solicitações pull.

- Git: Sistema de controle de versão distribuído que me possibilitou efetuar mudanças no repositório, commits e solicitações pull através da linha de comando usando o Git Bash.

- Power Shell: Utilizei para automação rápida de tarefas e processos, o PowerShell consiste em um shell de linha de comando, uma linguagem de script e uma estrutura de gerenciamento de configurações.

## 🧐 Processo de Criação

Inicialmente foi criado um novo repositório através da plataforma do GitHub, e as seguinte informações foram configuradas:

1. Repository Owner
2. Repository Name
3. Description
4. Definição da visibilidade do repositório: público ou privado

Onde:

- Repository Owner é a escolha do perfil escolhido para criação do novo repositório.
- Repository Name é o nome do repositório a ser criado, é importante que o nome seja autodescritivo e único.
- Description é a solicitação de uma descrição sobre do que se trata o repositório que está sendo criado, uma breve introdução.
- A definição de visibilidade do repositório de ve ser escolhido entre as opções público ou privado. Público deixará o repositório visivel no seu perfil do GitHub.

Em seguida na seção "Initialize this repository with" foi possível adicionar itens como os arquivos README.md, gitignore e o licenciamento. Então adicionei um "README file" selecionei "none" para o .gitignore e escolhi a licença "MIT License". Dessa forma o meu repositório foi criado"

Foi solicitado a adição de um arquivo ao repositório através da interface do GitHub, então adicionei um novo arquivo de imagem via Upload de arquivos. Em toda e qualquer alteração feita ao longo do desenvolvimento um commit deve ser feito com um resumo e uma descrição estendida da alteração.

Sendo assim, usando a interface nos campos “Commit summary” que é onde devemos inserir o resumo do commit e o campo “Optional extended description” onde devemos inserir detalhes adicionais do commit, se houver realizei o primeiro commit do repositório.

### Obs: O commit da alteração foi realizado em uma nova branch, além de criar uma nova branch com o arquivo selecionado, criei também um pull request, ao mesmo tempo no meu repositório.

*Como boa prática, não devemos fazer alterações direto na “main”, por tanto a criação de uma nova branch se fez necessário!*
|:--:|

O mesmo foi feito através da linha de comando utilizando o Git Bash!

Adicionando arquivos através da linha de comando:

*Requisitos:*

- Um repositório já criado no GitHub.com
- Software Git Bash já instalado na máquina (Download aqui)
- Prompt de Comando Power Shell

Já no Git Bash via linha de comando, fui até a minha pasta local e executei o comando git clone para clonar o meu repositório localmente.

Em seguida criei um novo arquivo e o adicionei através da linha de comando, como já havia sido dito, como boa prática não é interessante fazer alterações direto na "main", então executei o comando 'git checkout -b <nomeBranchNova>' para criar uma nova branch.

Criei o novo arquivo de texto como solicitado com o comando 'touch <nomeDoArquivo.txt>' e adicionei as atualizações com o comando 'git Add .' em seguida, executei o comando 'git commit -m "<Com a descrição da alteração>"'.

E finalmente finalizei meu commit fazendo um push com o comando 'git push --set-upstream origin <nomeDaMinhaBranchLocalJáCriada>'.

*Diferente da inserção de arquivos através da interface do GitHub, o commit feito via linha de comando não há uma criação automática de um pull request. Sendo assim, foi necessário retornar a página do meu repositório no navegador e criar um pull request diretamente na interface do GitHub.*
|:--:|

## 🚀 Resultados

A utilização da interface do GitHub acelera o processo de criação e desenvolvimento, com uma interface amigável possibilita uma organização visual pouco poluída, além de deixar disponível informações importantes do processo de desenvolvimento para um melhor controle de versão.

O Sistema Git se tornou fundamental para que eu pudesse fazer todo o controle de versão a partir da minha máquina sem perder as informaçoes do meu repositório já criado, mesclando as alterações e registrando todo esse processo, sem necessáriamente precisar utilizar a interface no meu navegador durante o desenvolvimento da atividade.

| [![Microsoft](https://github.com/lirazootech/GitHub4Women-Modulo2/blob/069ae05de973dca5391bc9b6efc8389c71abc934/Microsoft.png)]() |
|:--:|
| [![maismulheres.tech](https://github.com/lirazootech/GitHub4Women-Modulo2/blob/069ae05de973dca5391bc9b6efc8389c71abc934/maismulheres.tech.png)](https://www.maismulheres.tech/) |
| Este curso é oferecido pela Microsoft em parceria com a WoMakersCODE através da plataforma maismulheres.tech com o objetivo de capacitar e inserir mais mulheres na tecnologia. Ao final do curso, após avaliação as participantes concorrem à premiação do voucher para a certificação GitHub Foundations. |

Copyright © 2024. Feito com 🧡 por <a href="https://github.com/lirazootech/" target="_blank">lirazootech</a> .
