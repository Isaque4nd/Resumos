<<<<<<< HEAD

# DIO | Curso de Git e GitHub

Bootcamp:
[Digital INNOVATION ONE - Bootcamp WEX](https://web.dio.me/track/824331c4-b300-4f76-b29d-ce6c147932bf)

Curso:
[Versionamento de código com Git e GitHub](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/f3cbaa66-efbd-4c25-842e-2069c188c066?back=/track/bootcamp-wex-desenvolvimento-net-e-qa&tab=undefined&moduleId=undefined)

## Documentação 🗂

- [GIT](https://git-scm.com/doc)
- [GitHub](https://docs.github.com/pt)

## Comandos 🖊

```
git init - inicia o repositório criado

git commit - salva as alterações feitas no repositorio local

git commit -m"mensagem-que-desejar" - adiciona um commit e uma mensagem ao mesmo

git commit --amend -m"nova-mensagem" - troca a mensagem adicionada no último commit

git pull - puxa as alterações presentes no repositorio remoto e mescla com as alteracoes presentes no repositorio local

git push - sobe as alterações do repositório local para o remoto

git push -u origin main - sobe as alterações do repositório local para o remoto e faz com que a branch main se torne upstring

cat 'nome-do-arquivo' visualiza as informações contidas no arquivo selecionado

ls - lista pastas e arquivos presentes no repositório

git config --global user.name "seu nome" - altera globalmente o nome de usuário

git config --global user.email seuemail@exemplo.br - configura globalmente o email do usuário

git add 'nome-do-arquivo' - adiciona um arquivo do repositorio na area de preparação

git status - visualiza os arquivos que estão com algumas alterações para serem salvas (commit)

echo 'pasta-ou-arquivo/' > .gitignore - coloca o diretório do repositório na lista de diretórios que serão ignorados na hora de dar o commit

echo > .gitignore - volta a mostrar o diretório do repositório na lista de diretórios na hora de dar o commit

touch 'pasta/.gitkeep' -comando utilizado para adicionar arquivo em diretório vazio, para que ele mesmo vazio apareca na lista de preparacao do git

git add '.' - adicionando o ponto no comando git add, todos os arquivos e diretórios ficarao na lista de prontos para commit

git log - visualiza os commits feitos, com data, autor, codigo hash e descrição

rm -rf 'nome-da-pasta-ou-arquivo - remove algum diretório que não desejávamos ter criado

git restore 'nome-da-pasta-ou-arquivo' - restaura a pasta ou arquivo para uma versão anterior à última alteração (para casos de alteções por engano ou fazer alterações que deixem algo pior e quisermos reverter)

git reset --soft 'codigo-hash-do-commit-selecionado' - apaga os commits feitos depois do commit selecionado

git reset --mixed 'codigo-hash-do-commit-selecionado' - volta os arquivos que foram modificados depois do commit selecionado para a lista de arquivos nao preparados para commit (seria necessario usar o git add . para eles novamente)

git reset --hard 'codigo-hash-do-commit-selecionado' - apaga totalmente os arquivos contidos nos commits feitos depois do selecionado (ficam somente pastas e arquivos salvos até aquele commit)

git restore --staged 'nome-da-pasta-ou-arquivo' - remove a pasta ou arquivo da area de preparacao para commit

git reflog - mostra todas as alteracoes feitas ate mesmo as que nao aparecem no git log

=======
# Resumos
>>>>>>> fab3e42b07e17c4a1dcce4f72ec22b7db058880e
