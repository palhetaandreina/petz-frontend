# Ciência da computação (opcional)

- Processador
  - Paralelismo
  - Concorrencia
- Como dados são armazenados (memória ram)

# Git

Como versionar e trabalhar com git

Como nomear um repositorio

- sem acentuação gráfica
- utilizar letras minúsculas
- separar palavaras por traços
- nome do time - nome do projeto notifications-consumidor-eventos

como inicializar um repositorio git:

```sh
# escreve dentro de README.md o texto "# petz-frontend"
echo "# petz-frontend" >> README.md
# inicializa o git na pasta
git init
# salva as alterações feitas no arquivo
# https://www.freecodecamp.org/news/content/images/2023/02/image-180.png
git add README.md
# Agrupa as alterações do arquivo
# -m: mensagem que descreva o que foi modificado
git commit -m "first commit"
# criar uma branch ou renomear e passar o nome da branch
git branch -M main
# o caminho do repositório que os arquivos serão enviados
git remote add origin https://github.com/palhetaandreina/petz-frontend.git
# manda os arquivos comitados local para o repositorio remoto
git push -u origin main
# Se não tiver a branch no repositório remoto, usar esse comando para add
git push --set-upstream origin 'nome-da-branch'
```

- Status
- Stage
- Commit
- Branchs
- Pull/Push
- Merge
- Pull Requests (ou Merge request para gitlab)

# Lógica de programação

- Escopo de variáveis (const, let, var)
- Variáveis
  - Number
  - String
  - Boolean
  - Object
  - Array (JSON)
- Condições
  - switch case
  - if
  - condição ternária
- Operações lógicas
  - &&
  - ||
  - !
- Loops de repetição
  - for
  - for in
  - for of
  - while
  - do while
  - recursividade
- Funções
  - parametros
  - retornos

# Páginas web

- HTML (estruturação do site)
  - URL
- CSS (estilização do site)
  - Preprocessors
    - SASS
    - SCSS
    - LESS
- JS
  - Manipulação de DOM
  - Orientação a objetos
  - Interfaces

# Backend

- Requisições HTTP
  - Protocolos HTTP/HTTPS
  - Metódos
    - GET
    - POST
    - PUT
    - PATCH
    - DELETE
- Como gerar rotas para endoints
- Como tratar formulários
- Status de respostas
- Cookies

# Projeto de conclusão de curso

Aplicação a ser desenvolvida: IFOOD

Stack

- Backend: Nestjs
- Frontend: ReactJs
- Banco de dados: Postgres
  - SELECT
  - INSERT
  - UPDATE
  - DELETE
  - DELETE SOFT
  - Paginação
  - Transactions/Commits
  - ORM
