# Comandos Linux e Git usados no curso

**Neste arquivo irei colocar os comandos utilizados no decorrer do curso de Git e Github, na qual eu participei e resolvi colocar os comandos aqui para que eu possa estar consultando quando for preciso. E colocando aqui, pode também auxiliar alguém.**

# Comandos Linux

- **`ls` (Listar arquivos e diretórios do diretório atual).**

- **`ls -a` (Lista arquivos, diretórios e arquivos ocultos do diretório atual).**

- **`cd` (Acessar um diretório).**

- **`cd ..` (Voltar um diretório).**

- **`cd ../nomepasta` (Volta um diretório e entra em outro).**

- **`touch` (Criar arquivos. Ex: `touch teste.txt`).**

- **`clear` (Limpar a tela).**

- **`rm` (Remover um arquivo. Ex: `rm teste.txt`).**

- **`mkdir` (Cria um diretório).**

- **`rmdir` (Remove um diretório vazio).**

- **`rm -rf` (Remove um diretório e todo o seu conteúdo).**

- **`cat` (Exibe o conteúdo do arquivo. Ex: `cat teste.txt`).**

- **`mv` (Usado para mover arquivos e diretórios de um diretório para outro ou para renomear um arquivo ou diretório. Exemplo de como renomear: `mv nomearq.txt novonome.txt`. Exemplo de como mover: `mv nomearq.txt pastaDestino/`).**



# Comandos Git


- **Saber a versão do git para ver se está instalado: `git --version` .**

- **Lista de configurações dentro do git: `git config --global --list` .**

- **Adicionar nome do usuário no git: `git config --global user.name ”Nome Usuário”` .**

- **Adicionar email do usuário no git: `git config --global user.email email@usuario.com` .**

- **Inicializar um repositório git: `git init` .**

- **Renomear o branch de "master" para "main": `git branch -m master main` .**

- **Configurar para que o git inicie com o branch padrão "main": `git config --global init.defaultBranch main` .**

- **Status completo do repositório: `git status` .**

- **Adicionar arquivo ao stage: `git add nomearquivo` .**

- **Adicionar todos os arquivos ao stage: `git add .` .**

- **Remover arquivo do stage: `git restore --staged nomearquivo` .**

- **Remover arquivos do índice do Git: `git rm --cached nomearquivo` .**

- **Fazer commit: `git commit` .**

- **Fazendo commit com mensagem: `git commit -m “Mensagem descritiva do commit”` .**

- **Adicionar no stage e fazer commit: `git add . && git commit -m “Mensagem descritiva do commit”` .**

- **Histórico de commits: `git log` .**

- **Histórico de commits mais compacto: `git log --oneline` .**

- **Usando checkout para visualizar e voltar em commits anteriores: `git checkout idcommit` .**

- **Voltando para o main: `git checkout main` .**

- **Reverter um commit. Volta a um commit revertendo o que tinha feito antes: `git revert idcommit` .**

- **Voltar a um commit anterior mas permanecendo alterações nos arquivos de commits futuros: `git reset idcommit` .**

- **Voltar a um commit anterior resetando todas as alterações futuras: `git reset idcommit --hard` .**

- **Listar os branchs que estão no repositório: `git branch` .**

- **Criar um novo branch: `git branch nomebranch` .**

- **Mudar de branch: `git checkout nomebranch` .**

- **Criar um branch e já acessá-lo com o checkout: `git checkout -b nomebranch` .**

- **Deletar um branch que já foi fundido(merge) com o branch principal(main): `git branch -d nomebranch` .**

- **Deletar um branch que não foi fundido ao main: `git branch -D nomebranch` .**

- **Para fundir branchs, você tem que estar no branch de destino e puxa o branch que vai fundir: `git merge nomebranch` .**

- **Mostra o alias e o endereço do projeto: `git remote -v` .**

- **Criar alias para o endereço do projeto no github: `git remote add origin enderecoprojeto.git` .**

- **Subir os arquivos do repositório local para o github: `git push origin main` .**

- **Clonar projeto do github: `git clone enderecoprojeto.git` .**

- **Clonar projeto do github renomeando o repositório:  `git clone enderecoprojeto.git novo-nome-projeto` .**

- **Baixar as atualizações do projeto remoto e colocar no repositório local: `git pull origin main` .**

# Alguns links que podem ser úteis
- **Playlist no Youtube, do curso gratuito Git e Github de Tiago Matos:** [Acessar](https://youtube.com/playlist?list=PLcoYAcR89n-qbO7YAVj5S0alABLis_QVU)
- **Caso seja preciso ajuda para gerar a chave ssh:** [Acessar](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- **Site que ajuda a aprender mais sobre o git:** [Acessar](https://learngitbranching.js.org/?locale=pt_BR)
