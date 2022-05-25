# GitHub Challenge: Decola Tech 3ª Edição

Demo-repo, requisito parcial para conclusão do [Decola Tech Bootcamp](https://www.dio.me/bootcamp/decola-tech-3a-edicao) da plataforma Digital Inovation One (**DIO**), oferecido pela [Avanade](https://www.avanade.com/). O Bootcamp foca em desenvolvimento de __Mobile Apps__.


## Tech stack (for this repo)

- Markdown
- [Bash basic commands](#CLI_commands)
- [GIT CLI basic commands](#Git_commands)
- [GitHub (on browser) basic usage](#GH_Browser)
- [GitHub CLI basic commands](#GH_commands)


## Connections

DIO Site: <https://www.dio.me/>

DIO Site (english): <https://www.dio.me/en>

DIO Site (spanish): <https://www.dio.me/es>

Avanade: https://www.avanade.com/

My e-mail: <juliamizarela@id.uff.br>


## Additional Information on Decola Tech 3ª Edição

[Inscrições abertas](https://www.dio.me/bootcamp/decola-tech-3a-edicao) para o Decola Tech 3ªEdição:
**Até 30/05/2022**


Conteúdo: 
1. HTML5 & CSS3
2. JS 
3. React Native. 


[![Decola Tech 3aEd](https://hermes.digitalinnovation.one/files/assets/330af21c-25c0-47f5-8afd-57cf726b9149.png)](https://www.dio.me/bootcamp/decola-tech-3a-edicao)


## CLI commands used

Repositório Git criado localmente e posteriormente empurrado para remoto no GitHub seguindo a sequência:

<a name="CLI_commands">__Preparação no Bash__</a>
```
cd Scripts/Web          # My scripts are organized loosely by type or language
mkdir DIO               # I'm in more then one bootcamp
mkdir DIO/Decola_Tech_3aEd
cd DIO/Decola_Tech_3aEd
touch README.md
gedit README.md         # Initial edition to this README.md as seen on the "Initial Commit"
```
<a name="Git_commands">__Git commands__</a>
```
git init -b main 	# making sure our initial branch is main, not master
git add *		# stages our README.md
git commit -m "Initial Commit"
```
<a name="GH_commands">__GH commands__</a>
```
gh create repo 	        # Used interactively for convenience (settings: 
                        # use local repo to create remote from this dir, 
                        # make the repo public, 
                        # add the remote connection as origin, 
                        # push the commits from local to remote)
```
<a name="GH_Browser">__Changed this README__, and pushed the "Update README.md" commit right from the browser</a>

__Syncronized local again with git commands, then made this almost recursive change with gedit, and finally pushed to remote__
```
git pull origin main
gedit README.MD
git add *
git commit -m "Added Commands to README"
git push origin main
```
Edição mais uma vez no browser (commit message "README changes on GH browser").
