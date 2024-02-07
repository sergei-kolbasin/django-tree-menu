# django-tree-menu
The repository contains a Django application for creating and managing a tree menu. Use this project to easily create and customize a multi-level menu on your website using Django
***

## PEP 8
Flake8 was used to test the code on PEP8, so you need to select 2 commands before running the application:
1. To use flake8 you need to install it with pip

        <pip install flake8>
 
2. To run flake8 on your code, simply run the command in the terminal, specifying the path to your project or file

        <flake8 path/to/your/code>

## Open with Docker

1. Go to project root path 

        <cd Tree-menu>
  
2. Build an  Dockerfile form 

        <docker build . -t tree-menu>
    
3. Run container

        <docker run -p -t 8000:8000 tree-menu>

## Prettier

If you or your team don’t want to formatting program code, Prettier can do everything itself.
Just download it with npm

        <npm install --save-dev --save-exact prettier>

Before commit run 

         <npx prettier --write>
