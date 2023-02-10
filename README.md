# Git e GitHub - Anotações

Olá! Esses são meus estudos de Git e Github.

---------------------------------------------------------------------------

- O que é Git? Git é um sistema de versionamento de arquivos. Por que usamos ele?

    Como exemplo posso usar um projeto de um cliente que teve muitas alterações. De forma tradicional, iriamos "zipar" e ir enviando para o cliente, conforme ele vai pedindo alterações nós vamos criando mais e mais pastas zipadas. Caso o cliente fale que quer algo que você utilizou na primeira versão, porém que já foi excluido da sua versão atual, para achar esse item, teria que abrir pasta por pasta atrás do item. Sem contar quando existem mais de uma pessoa trabalhando nesse mesmo projeto tendo que fazer alterações.

    Com o git é diferente. Quando o cliente aprova uma versão, ele não gera um zip, ele faz um commit em um repositório local. E várias pessoas podem também fazer esses commits. Após finalizar um commit você faz um push para um repositório remoto. Assim todos que fazem parte do projeto conseguem ver as suas alterações.

-Vantagens:

    * Controle de histórico

    * Trabalho em equipe

    * Ramificação do projeto

    * Segurança

    * Organização

---------------------------------------------------------------------------

- O que é GitHub? GitHub é uma plataforma (software) para hospedagem de arquivo git que trabalha como um repositório remoto.

---------------------------------------------------------------------------

-Vantagens:

    * Repositórios ilimitados

    * Hospedagem de código-fonte

    * Características de rede social

    * GitHub Pages integrado

    * Colaboração

    * Forks

---------------------------------------------------------------------------

# Vocabulário

 - Branch: são ramificações do projeto. Podemos usar como um esboço que não altera a branch master(ou main). São utilizados para separar alterações grandes ou novas funcionalidades do projeto.

 - Commit: é um grupo de alterações no código. Toda vez que você quiser "salvar" as alterações feitas por você no repositório, você commita essas mudanças.

 - Push: envia o código para o repositório online.

 - Merge: é a união de duas branches. Normalmente, merges são feitos na branch master. 

 - Pull: é uma atualização do repositório local. É feito um merge do repositório online com o local para que os conflitos sejam resolvidos e seja possível enviar o código (sem conflitos) para o repositório online por meio de um push.

 - Fork: é como um clone, porém dentro do github. Isso quer dizer que o repositório não vai ser baixado para 
 seu computador, mas será criado um igual na sua conta.

 - Pull request: é um pedido que se faz ao dono do repositório para que este atualize o código dele com o seu código.

 - Clone: funciona como uma branch de um repositório online em um repositório local. Ou seja, quando se deseja trabalhar em um repositório hospedado no github, clona-se esse repositório para o seu computador, trabalha-se nele, e então é pedida a permissão para atualizar as alterações online.

---------------------------------------------------------------------------

# Comandos Básicos Git Bash

 - git --version (vê a versão do Git)
 - git init (inicializa um repositório git, já entra em uma branch master)
 - git add (adiciona uma alteração no diretório ativo à área de staging)
 - git add . (adiciona todas as alterações de uma vez à área de staging)
 - git commit -m "..." (faz um commit)
 - git branch -M "..." (altera o nome da branch)
 - git push origin "nome da branch" (coloca suas alterações no repositório do GitHub)
 - git checkout "nome da branch" (entra na branch escolhida)
 - git merge "nome da branch" (junta a branch escolhina na atual (main))

---------------------------------------------------------------------------

