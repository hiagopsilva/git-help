
<h4 align="center">
  🚀 GitHub help
</h4>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=000000">
</p>

<br>

<p>Readme para ajudar quem é iniciante a como subir projetos para o Github em apenas dois passos.</p>


## Tools
- Prompt de comando - Git bash
- Conta no Github

## Get started

Primeiro passo: Ir no github e criar um novo repositório.
- Pra começar voce vai precisar entrar no site do github e página `Repositories`, do lado direito, clique no botão `new`.

- Nisso vai aparecer uma página para criar um novo repositório, abaixo em `Repository name`, de um nome para o seu repositório (não coloque carácteres especiais, se colocar o site ira alterar para a seta `EX: 'meu*repositorio' -> 'meu-repositorio'` .

- Depois disso clique em `Create repository`.

- Agora copie o link que aparecer para você ao lado dos botões `HTTPS | SSH`, geralmente o link aparece como `https://github.com/SEU USERNAME/NOME DO REPOSITORIO.git` ou clique ao lado direito para copiar o link do repositório ( vamos utilizar esse link daqui a pouco ).

Segundo passo: Iniciar um repositório no git bash.
- Com o git bash aberto no diretório da pasta do projeto, execute o comando ` git init` para iniciar o arquivo git.

-  Após isso precisamos adicionar os arquivos que vamos subir para o git, se você esta executando o seu primeiro commit desse repositório, execute o comando `git add .` ( Não se esqueça do ponto no final e do espaço entre o "add" e o ponto ".").
- Caso voce queira adicionar apenas um arquivo por exemplo o `index.html`, basta colocar o caminho da pasta no lugar do ponto, por exemplo `git add index.html`, ou se o arquivo estiver dentro de uma pasta coloque `git add src/index.html`.

-  Depois disso execute o comando `git commit -m "O NOME DO COMMIT QUE DESEJAR"`, se nesse caso você estiver executando o seu primeiro `commit`, pode colocar a mensagem `Initial commit` ou `Confirmação inicial` em português.

- Certo, agora vamos conectar esse projeto ao repositório, para isso basta executar o comando `git remote add origin E O LINK QUE VOCE COPIOU`, no git bash ele não realiza o CTRL V, para resolver isso basta clicar no botão `Insert` do teclado ou clique com o botão direito do mouse e clique na opção `paste`.

- E para finalizar agora vamos enviar as alterações do projeto para o github, para isso basta executar o comando `git push -u origin master`, se aparecer os campos para colocar o login e a senha não tem problema isso é para confirmar se é você mesmo que esta comitando as alterações. ( Para tirar essa solicitação da senha, é necessário configurar a chave SSH ).

- Caso voce já tenha realizado o seu primeiro commit neste repositório, basta executar o comando `git push`, se é o seu primeiro commmit, realize o passo anterior.


Pronto, agora ficou fácil enviar projetos para o github.

Vlw! 😎

