pt-BR

Nomenclaturas:
	Repositorio = Pasta
	Versão
	Branches = pequenas alterações que podem ser juntadas para formar uma nova versão
	Merge = juntar os branches em um versão
	Remote = Adiciona um repositorio remoto ex: link de um repositorio no GitHub
	Push = ( enviar uma versão )
	Pull = ( puxar uma versão )

--------------------------------------//-------------------------------------------
Comandos GIT
Git bash 
	
	git ( inicia um git a partir da pagina)
  
  	git add ( adiciona o arquivo a area staging (antes do commit) )
	git add Read.md
	git add .  (adiciona todos os arquivos ao staging)
  	
	git status ( vê os arquivos aguardando para serem commitados)
  
	git commit (comita os arquivos presentes no staging)
	git commit -m "Nome do commit"
  
  Renomear para "main"
	git branch -M "main"

git fetch
git merge

Ir para a pasta main (principal)
	git checkout "pasta"


--------------------------------------//-------------------------------------------
Comandos para usar com Github

	git remote add origin "Link do repositorio no git hub"

	git push -u origin main (primeira vez)

	git push origin "main" < nome da pasta: master, main ou branch>
	
	git clone "link da pasta no github"

--------------------------------------//-------------------------------------------
Criando uma Branch

	git checkout -b "nome da branch"
		-b  manda para a pasta da branch
