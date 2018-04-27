# Para Inserir um push para o branch master no github pelo http

	# Create a new repository on the command line

	echo "# GD" >>README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/JoyceCarvalho/example.git
	git push -u origin master
	
	# ...or push an existing repository from the command line 
	
	git remote add origin https://github.com/JoyceCarvalho/example.git
	git push -u origin master

	# ...or import code from another repository
	
	You can initialize this repository with code from a Subversion, Mercurial, or TFS project

# Para inserir um push para o branch master no github pelo SSH

	# create a new repository on the command line

	echo "# GD" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin git@github.com:JoyceCarvalho/example.git

	# ...or push an existing repository from the command line

	git remote add origin git@github:JoyceCarvalho/example.git
	git push -u origin master

	# ...or import code from another repository

	You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

