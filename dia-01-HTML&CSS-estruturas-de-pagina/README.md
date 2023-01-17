Versionamento de arquivos
O primeiro passo e ter uma pasta  versionada e criar uma estrutura inicial e fazemos isso utilizando o comando (git init) . O segundo passo é criar uma branch nova com o comando (git branch nome-da-branch) ou (git checkout -b nome da branch).
(git checkout -b nome da branch) voce cria uma nova branch e ja muda de branch para que voce acabou de criar. 

alguns comandos importantes do git. 

(git init)   transforma uma pasta em um repositorio git;
(git add nome-do-arquivo)   adiciona o arquivo especificado em staging * estaging = espaço temporario antes do commit;
(git add .) Adiciona todos os arquivos modificados em staging (espaço temporario antes do commit);
(git status) verifica o status dos arquivos do projeto;
(git commit -m "Mensagem descrevendo a alteraçao") cria um ponto de acesso para a alteração e possui ua mensagem descrevendo quais alterações foram feitas
(git branch) Verifica as branchs existentes e alterna automaticamente para ela
(git checkout -b nome-da-branch) cria uma branch nova a partir da atual e alterna automaticamente para ela
(git checkout nome-da-branch) altera para a branch especificada
(git log) mostra os registros dos commits *alteraçoes realizadas
(git merge nome-da-branch) realiza a mesclagem das alteraçoes branch especificada 

