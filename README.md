# MERN_checklist
		Full MERN Project Checklist

	☑ create the initial folder and cd inside of it

		mkdir disco-dogs
		cd disco-dogs

	☑ create server.js and initialize our project

		touch server.js
		npm init -y

	☑ install our back-end dependancies

		npm i cors express mongoose

	☑ create our back-end folder structure

		mkdir server
		cd server

		mkdir config controllers models routes
		cd ..
	☑ initialize git repo

		git init
		touch .gitignore

	☑ create our front-end (make sure we're in the same folder as server/

		npx create-react-app client

	☑ install our front-end dependancies
	
		
		cd client
		npm i axios @reach/router
		cd ..
	
	**************************************************************************************************************
	**************************************************************************************************************
	
	Project setup working with boilerplate

		copy the boilerPlate

		rename the backend boilerplate
		extra-extra

		gitbash .. cd extra-extra
		code .

		install node module
			npm i

		git init

		create file
			.gitignore
				.env
				node_modules/

		npx create-react-app client (trubleshoot => removing the ~/Users/.npmrc from the folder helped.)

		cd client

		install the dependency for client-side
			npm i bootstrap @reach/router axios

		App.jsx
		import 'bootstrap/dist/css/bootstrap.min.css';
		import {Router} from @reach/router;


		------------------
		then go and look the wireframe
