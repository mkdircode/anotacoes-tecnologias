
# Git

SW (Software) de versionamento de código

### Comandos no terminal

- mkdir => cria pasta
- cd … => volta 1 nível
- mv => move arquivo

## Objetos

Blobs < Trees < Commits

## Ciclo de vida

Repositorio local (RL, máquina local) e Repositorio remoto (RR, o Github)

No ambiente de desenvolvimento do RL tem: working directory e o staging area. As alterações que for fazendo (git add, git mv etc) vão transitar entre working directory e o staging area até que faça o git Commit. Ao fazer o Commit todas as alterações serão salvas, terão seu estado mudado pra Unmodified e enviadas pro RL.

Pra enviar oq está no RL para o RR, arquivo precisa estar comitado (commit)

    

* * *

# Github

> “plataforma de hospedagem de código para controle de versão e colaboração” [hello world no Github](https://docs.github.com/pt/get-started/quickstart/hello-world)

> Repositório: contém todos arquivos que o projeto precisa. No arquivo README contém infs do projeto na sintaxe [Markdown](https://www.markdownguide.org/cheat-sheet/).

## RL => RR

empurrar arq do Repositorio Local p/ o Remoto

1.  na conta do github
    
2.  novo repositorio e dps Criar Repositorio
    
3.  apontar link do repositorio no github (algo do tipo ‘https://github.com/mkdircode/Livro-de-receitas.git’) e colar no git (RL).
    
4.  no git bash, vamos adc a origem `git remote add origin https://github.com/mkdircode/Livro-de-receitas.git`
    
5.  `git remote -v` lista repositorios cadastrados
    
    - origin é um ‘apelido’ pro link colado
    
    - pode dar um `git status` pra verificar se não tem pendência
6.  `git push origin master`
    

## Links úteis

[QuickStart GitHub Docs](https://docs.github.com/pt/get-started/quickstart)

[Glossário Github](https://docs.github.com/pt/get-started/quickstart/github-glossary)