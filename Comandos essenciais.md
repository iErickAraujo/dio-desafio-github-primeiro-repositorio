## Comandos essenciais:

- `git init`: Este comando dá origem a um repositório novo, local ou remoto, ou reinicializa um repositório já existente.
- `git clone [url do repositório no github]`: Este comando clona o código de um repositório para sua manipulação em outro ambiente.
- `git add [nome do arquivo]` ou `git add .`: Adiciona o arquivo ou todos na área de preparação.
- `git commit -m "Descrição do commit"`: Este comando move os arquivos da state area para um repositório local. É importante sempre descrever os seus commits, pois quando for necessário buscar alguma alteração podemos facilmente identificar através da mensagem.
- `git commit -sm "sua mensagem"`: Este comando cria um commit com a mensagem fornecida e adiciona uma linha de signoff ao final da mensagem do commit. A opção `-s` ou `--signoff` é usada para adicionar uma linha ao final da mensagem do commit, que certifica que o committer tem o direito de enviar este trabalho sob a mesma licença e concorda com uma Declaração de Origem do Desenvolvedor. A opção `-m` é usada para fornecer uma mensagem de log para o commit.
- `git status`: Mostra o status da área de trabalho/área de preparação.
- `git log`: Apresenta todo o histórico de commits existentes.
- `git reflog`: Apresenta um histórico mais detalhado dos commits.
- `git branch -v`: Apresenta o último commit de cada branch.
