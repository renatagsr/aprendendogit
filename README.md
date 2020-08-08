# Aprendendo GIT

## Comando

### Configuração inicial
* No GIT colocar `git --global user.name "Name"`, para configurar que sempre irá ser referente a essa pessoa. Para o email colocar `git --global user.email email`.

### Como criar um repositório localmente

Pasta localizada no GITHUB.
`git init`, cria uma pasta replicável para o GITHUB.

### Como mandar os arquivos para o GITHUB

Para saber mostrar os arquivos que foram modificados no servidor dar `git status`, se estiver em vermelho o arquivo foi modificado porém não está no servidor. Para adicionar essa modificação fazer `git add nome do arquivo`, dessa forma irá parecer em verde se der o `git status`. 
Se fizer `git commit -m "Mensagem"` da próxima vez irá aparecer o que foi modificado nessa adição. 
Para colocar as modificações no GITHUB, após seguir todos esses passo, coloca o comando `git push origin master`.

### Como direcionar o GIT local para o servidor (a primeira vez)

Ir no GITHUB e copiar a segunda parte que aparecer em "code". Esse processo é necessário apenas na primeira vez que é configurado.

### Utilizando códigos de marcação
* Um
    * Dois
        * Três
* Quatro
* [ ] Cinco
