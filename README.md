# guias-para-iniciantes-github

# Subindo seu projeto pro GitHub – fiz de coração, é facinho e super prático ^^

## Cria o repositório no GitHub
Vai lá no GitHub, clica em "New" pra criar um repositório novo. Pode ser público ou privado, você que manda.
Guarda o nome do repositório e o link, cê vai usar depois.
## Vai na sua pasta no terminal
Abre o terminal (ou prompt de comando), vai até a pasta que você quer subir pro GitHub.
## Inicia o Git (caso ainda não esteja)
Se for a primeira vez mexendo nessa pasta, roda:
comando:
git init
## Adiciona os arquivos pro Git
Agora coloca tudo que tá na pasta dentro do Git com:
comando:
git add . - (Esse ponto aí significa “adiciona tudo”.)
## Faz o primeiro commit (tipo um "salvamento")
Roda isso aqui:
comando:
git commit -m "Primeiro commit" - (Esse texto entre aspas é só uma descrição. Pode colocar o que quiser, tipo “subindo meu projetinho”.)
## Conecta com seu repositório do GitHub
Troca o link aqui pelo do seu repositório real:
comando:
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
## Envia os arquivos pro GitHub
Agora é só mandar com:
comando:
git push -u origin main
Se der erro com main, tenta master no lugar. Depende do seu Git.
## Confirma se deu bom
Vai lá no seu GitHub e vê se tá tudo certinho. Se aparecerem os arquivos, sucesso total. 

Tipo se tiver arquivo que você não quer subir (tipo .env, coisas pessoais...), cria um arquivo chamado .gitignore e coloca o nome desses arquivos lá.
E se quiser organizar melhor, dá pra criar "branches" (tipo versões separadas do projeto) pra testar novas coisas sem bagunçar o principal.
