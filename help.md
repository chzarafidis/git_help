how-to-integrate-a-github-wiki-into-the-main-project
https://stackoverflow.com/questions/6941688/how-to-integrate-a-github-wiki-into-the-main-project


git clone https://github.com/youName/ProjectName.wiki docs
git submodule add https://github.com/youName/ProjectName.wiki docs
git submodule update --init

<<<<<<< HEAD
This will create a link from the docs folder to your project's Wiki repository on Github
=======
This will create a link from the docs folder to your project's Wiki repository on Github
>>>>>>> d68b6d81de666b6d67fab13f11b73e98f3c103c8
