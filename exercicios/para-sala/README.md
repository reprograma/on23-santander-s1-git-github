# Exercício de Sala 🏫  

## Criando e deletando pastas e arquivos pelo terminal Git Bash e subindo no github


- Explicação do exercício: Vamos usar o conteúdo estudado em sala para criar uma pasta simples, com um arquivo html e uma imagem. Através do terminal e vamos subir em nosso GitHub.

OBS1: Erros de digitação e formatação dos comandos no git bash podem acarretar em problemas, lembrem de verificar a grafia caso algum comando dê errado. Para relembrar os comandos é só voltar ao material sobre comandos no terminal

OBS2: Caso o arquivo ou pasta tenha algum erro de digitação ou não exista, também ocorrerão erros. Tentem sempre verificar se estão na pasta correta utilizando pwd e se está tentando passar o nome correto dos arquivos e pastas, liste os itens para pegar o nome correto utilizando ls.

- Você deve ter instalado o Git na sua máquina. Na Área de Trabalho (Desktop), clique com o botão direito e selecione Git Bash here

## Comandos que vamos usar:

- pwd: print working directory, mostra o caminho onde você se encontra
- ls: list, lista o conteúdo da pasta atual
- mkdir: make a directory, cria uma nova pasta. Precisa colocar o nome da nova pasta. Ex: mkdir nomePastaNova
- cd: change directory, entrar em uma pasta. Precisa indicar o nome da pasta que quer entrar. Ex: cd nomePasta
- cd ..: voltar uma pasta acima
- echo: echo, eco que cria um arquivo. Precisa indicar o conteúdo e o nome do arquivo. Ex: echo "oi" > index.html Nos utilizamos o Touch
- touch: touch, comando que cria um arquivo. Precisa indicar o conteúdo e o nome do arquivo. Ex: touch index.html
- rm: remove, deleta um arquivo. Precisa indicar o nome do arquivo. Ex: rm index.html
- rm -r ou rm --recursive: deleta uma pasta. Precisa indicar o nome da pasta e deletar recursivamente. Ex: rm -r nomeDaPasta


Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz uma pasta nova usando o gitbash
- [ ] criei um arquivo dentro dela
- [ ] inicializei esse arquivo e configurei minha autoria
- [ ] criei um repositório no github
- [ ] adicionei as mudanças no meu git e fiz o meu primeiro commit
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)


### Rastreando seu projeto localmente e subindo para o GitHub

Seus dados devem estar previamente configurados no Git da sua máquina.
Verifique se seu **user.name** e **user.email** estão configurados:
- `git config --list`

Comandos para rastrear localmente um projeto:
- Entrar no Git Bash clicando com o botão direito do mouse de dentro da sua pasta (*Git Bash here*) ou navegando pelo Git Bash até a pasta desejada (`cd nomeDaPasta`).
- `git init`: iniciar o rastreamento dessa pasta
- `git add <nome do arquivo>` ou `git add --all` ou `git add .`: adicionar os arquivos na área de preparação
- `git commit -m "Mensagem de bom senso"`: adicionar a mensagem do que foi feito nesse(s) arquivo(s) adicionado(s)

Enviar o seu repositório local para um site de hospedagem de repositórios (ex: [GitHub](https://github.com)):
- Criar um repositório novo no site do GitHub https://github.com/new
- Voltar para o Git Bash dentro da pasta
- `git remote add origin https://github.com/<seuLogin>/<seuRepositorio>.git`: adicionando o endereço do repositório remoto
- `git push -u origin main`: enviando o que está no Git local para o GitHub

**Observação**
Caso precise mudar o endereço do seu repositorio online é só dar
`git remote --set-url origin novaURL`

