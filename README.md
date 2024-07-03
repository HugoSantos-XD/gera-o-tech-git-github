## Objetivo:
Familiarizar os alunos com o Git e GitHub, desde a criação de uma conta até a realização de operações básicas em um repositório.

## Instruções:

### 1. Criação de Conta no GitHub

Acesse o site GitHub.
Clique em "Sign up" (Inscrever-se).
Siga as instruções para criar uma nova conta. Anote seu nome de usuário e senha.

### 2. Instalação do Git
Acesse o site Git.
Baixe e instale a versão mais recente do Git para o seu sistema operacional (Windows, macOS ou Linux).
Após a instalação, abra o terminal (Prompt de Comando no Windows, Terminal no macOS/Linux).
Verifique a instalação digitando git --version. Deverá aparecer a versão do Git instalada.

### 3. Configuração Inicial do Git
No terminal, configure seu nome de usuário e e-mail com os seguintes comandos (substitua "Seu Nome" e "seu-email@example.com" com suas informações):
git config --global user.name "Seu Nome" git config --global user.email "seu-email@example.com"

### 4. Criação de um Repositório no GitHub
* Faça login na sua conta do GitHub.
* Clique em "New" (Novo) no canto superior direito da página para criar um novo repositório.
* Preencha os campos:
    - Repository name: Escolha um nome para o seu repositório.
    - Description: Adicione uma descrição breve (opcional).
    - Public/Private: Escolha se o repositório será público ou privado.
    - Marque a opção "Initialize this repository with a README" (Inicializar este repositório com um README).
* Clique em "Create repository" (Criar repositório).

### 5. Clonando o Repositório para seu Computador

* No seu repositório recém-criado no GitHub, clique no botão "Code" (Código) e copie a URL.
* No terminal, navegue até o diretório onde deseja clonar o repositório.
* Digite o comando para clonar o repositório:
git clone URL_DO_REPOSITORIO
* Substitua "URL_DO_REPOSITORIO" pela URL que você copiou.
  
### 6. Realizando uma Alteração e Enviando para o GitHub

* Navegue até o diretório do repositório clonado no seu computador.
* Crie um novo arquivo chamado meu_arquivo.txt e adicione algum texto dentro dele.
* Salve o arquivo e, no terminal, adicione o arquivo ao repositório:
git add meu_arquivo.txt
* Faça um commit das alterações:
git commit -m "Adiciona meu_arquivo.txt"
* Envie (push) as alterações para o GitHub:
git push origin main
