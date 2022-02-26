# Git e GitHub - Tutorial

### Comandos do Git

- git init - Inicia um repositório dentro da pasta em que está atualmente;
- ls - Listagem de tudo que está dentro da pasta atual;
- cd [nome-da-pasta] - Vai para a pasta destinada;
- mkdir [nome-da-pasta] - Cria uma pasta dentro do diretório;
- ls -a - Mostra itens ocultos;
- cd .. - Volta para a pasta que você estava anteriormente;
- git config --global user.email "seuemail@email.com" - Define um email para seu git de forma global;
- git config --global user.name seunickname - Define um nickname para seu git de forma global;
- git add [nome do arquivo ou " * " para adicionar tudo] - Informa que algo foi adicionado ou mudou no repositório;
- git commit -m "Comentário" - Salva as alterações do repositório com um comentário;
- git config --list - Lista todas as informações sobre o repositório atual;
- git status - Apresenta o estado atual do repositório e se algo precisa ser "commitado";
- git config --global --unset user.algo - Com a palavra-chave escolhida após o ponto como name, por exemplo, o git reseta o que havia sido definido antes;
- seta para cima - Reescreve o último comando digitado e confirmado;
- git add --all - Commita todas as mudanças, até mesmo exclusões ou renomeações de arquivos;

### Observações

**1 -** A pasta .git após criar o repositório com git init é uma pasta oculta. Para ver as pastas ocultas em seu explorador de arquivos, basta clicar em _**Exibir > Itens ocultos**_;

**2 -** Um arquivo Markdown utiliza formatação baseada em HTML. Por exemplo, usar uma única hashtag antes de um texto transforma ele em um texto de tag h1 (E assim sucessivamente até o h6). Usar dois " * " antes e depois de textos os transforma em negrito. Usar " _ " no começo e fim dos textos transforma-os em itálico. E por aí vai, são diversos comandos;

**3 - ** Arquivos README.md geralmente vêm em repositórios explicando a história e os motivos pela criação deles;

**4 -** Quando der o erro "Another Git process seems to be running in this repository", basta excluir o arquivo **_index.lock_** da pasta **_.git-**;

### Passo a passo para fazer Push de um repositório para o Github

1. Renomeie o arquivo **_master_** para **_main_** indo na sua pasta .git > refs > head; 

2. Escreva no terminal git remote add origin link-do-repositório;

3. Escreva no terminal git branch -M main;

4. Escreva no terminal git push -u origin main;

   

