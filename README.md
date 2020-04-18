#Terminal personalizada en Windows.
##### Requisitos previos: habilitar Linux subsystem y instalar la consola de ubuntu.


- instalar Hyper.
	https://hyper.is/


- Instalar Zsh. 
		Consola de ubuntu
		sudo apt-get install zsh 

	Link:
	https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH


- Instalar Ohmyzsh.
		Consola de ubuntu
		sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

	Link:
	https://ohmyz.sh/


- Configurar Zsh por defecto en nuestro sistema.
		Consola de ubuntu
		chsh -s /user/bin/zsh -> zsh shell por defecto del sistema


- Cambiar el theme
		Consola de ubuntu
		nano .zshrc
			"Cambiamos la variable ZSH_THEME por el tema de nuestro gusto"
	Link:
	https://github.com/ohmyzsh/ohmyzsh/wiki/Themes


- Iniciar Zsh en Hyper 
		Abriremos Hyper
		Menu>edit>preferences
			Rellenar la propiedad shell con 
				shell: 'C:\\Windows\\System32\\bash.exe',
