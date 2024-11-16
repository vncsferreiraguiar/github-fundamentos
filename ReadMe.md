# Git e Git Hub

Aprendendo os recursos do Git e Git Hub.

## Comandos

### Iniciais
1.1 pwd: mostra o diretório atual  
1.2 ls: o que tem no diretório atual  
1.3 clear: limpa tela  
1.4 cd: mover para uma pasta  
1.5 git init . : Iniciar o versionamento com git na pasta atual (.)  
1.6 ls -a : mostra todas as pastas inclusive ocultas  
1.7 git add: prepara o arquivo para fazer o checkpoint (commit)  
1.8 git config --global user.name "Seu Nome": para definir seu nome como responsavel pelo commit  
1.9 git config --global user.email "SeuEmail": para definir o email do responsavel pelo commit  
1.10 git commit -m : "commita" o arquivo e permite deixar uma mensagem  
1.11 git status: mostra o que tem para ser commitado  
1.12 git log: mostra o histórico  
1.13 git add . : pega todos os arquivos em untracked e coloca como unstage  
1.14 git reset: retorna os arquivos para untracked  

### Conceito de branch:  
Possibilita criar uma cópia de um arquivo e trabalhar nesta cópia, uma vez que, esteja satisfeito com a copia-lo em cima do arquivo original.  
1.15 git branch: retorna a branch atual  
1.16 git checkout -b <nome da branch (nova)> : cria uma nova branch  
1.17 git merge <nome da branch (nova)>: junta as mudanças da nova branch com a master (main). [Detalhe: você precisa estar na branch master(main).]  
1.18 git branch -D <nome da branch>: deleta a branch (Faz isso após executar o merge)  


### Git Hub
1.19 git clone <link https do repositório criado no GitHub (nuvem)>: acessa localmente o repositório criado no GitHub  
1.20 git push <origin brench_remoto>: empurra do local para o remoto
1.21 git pull <main>: Incorpora alterações de um repositório remoto no ramo local
