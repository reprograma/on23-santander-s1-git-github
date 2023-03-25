# Exercício de Casa 🏠 

## INSTAGRAMINHO
## Explicação do exercício: Bora fazer nosso primeiro fork? Vamos fazer nosso proprio login do instagraminho juntas. Aqui tem um passo a passo: 

- Entrar o repositório do projeto que clonamos: Instagraminho
- Copiar o link HTTP que aparece ao clicar no botão verde ***Clicar em fork para criar uma copia desse repositório no seu GitHub***.
- Na sua máquina: abrir o Git Bash clicando com o botão direito do mouse de dentro da pasta onde deseja clonar o repositório (*Git Bash here*), ou navegando pelo Git Bash até a pasta desejada (`cd nomeDaPasta`).
- `git clone https://github.com/<seuuser>/instagraminho-reprograma`
- `cd instagraminho-reprograma`: para entrar na pasta.
- `ls`: para listar o que tem dentro da pasta.

CONTINUAÇÃO, INICIO DO EXERCICIO 5:
- `git checkout -b ex-aula-seuNome`: para ir para uma branch nova chamada ex-aula-seuNome.
- `code .`: para abrir o VSCode nessa pasta.
- Abrir o arquivo `index.html`.
- No VSCode, verificar se está na sua branch pela parte inferior esquerda do VSCode.
- Alterar o código colocando o seu nome em alguma parte que está com o nome da professora.

  Exemplo:

  **Antes:**
    ```
    <p class="not-account">Não é thielenunes?</p>

    ```

  **Depois**
    ```
    <p class="not-account">Não é alunax?</p>

    ```
- Salve a alteração e verifique no navegador se está correto.
- Volte para o Git Bash dentro dessa pasta.
- `git status`: verifique o status do repositório atual.
- `git add --all` ou  `git add .` : adicione todos os arquivos que foram modificados.
- `git commit -m "Mensagem de bom senso"`: adicionando a mensagem do que foi modificado.
- `git remote -v`: verifique se o endereço do repositório remoto. (Neste caso, o endereço do remoto chamado `origin` já veio quando você fez o clone do repositório).
- `git push origin ex-aula-seuNome`: envie para o repositório remoto as alterações da branch `ex-aula-seuNome`, para isso enviei o seu github para professora.
- Verifique no GitHub se sua alteração foi enviada com sucesso. Veja se sua branch está no repositório: https://github.com/thielenunes/instagraminho-reprograma

Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Resolvi o exercício.
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
- [ ] Criei um Pull Request seguindo as orientaçoes que estao nesse [documento](https://github.com/mflilian/repo-example/blob/main/exercicios/para-casa/instrucoes-pull-request.md).

