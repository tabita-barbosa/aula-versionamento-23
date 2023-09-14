## minas versionamento

1. A tarefa hoje será fazer um fork (que é a cópia de um repositório no seu github), e depois vamos clonar o nosso fork.
git clone nosso-link

2. vamos atualizar o fork.
a. colocar o repositorio da aula como nossa fonte de atualizacao
git remote add upstream url-do-repo-original
b. puxar as atualizacoes do repositorio 
git pull upstream

3. vamos criar uma branch com seu nome
git checkout -b "seu-nome" 

4. vamos criar um arquivo txt no nosso clone, no nosso computador
echo "texto do nosso primeiro arquivo no github" > seuNome.txt

5. vamos salvar e commitar esse texto.
git add .
git commit -m "meu primeiro commit"

6. vamos enviar esse texto para o repositório que a gente clonou.
git push origin sua-branch

7. vamos criar um PR (pull request - pedido de inserção) para o repositório original - da professora.
