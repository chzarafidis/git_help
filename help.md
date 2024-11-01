how-to-integrate-a-github-wiki-into-the-main-project
https://stackoverflow.com/questions/6941688/how-to-integrate-a-github-wiki-into-the-main-project


git clone https://github.com/youName/ProjectName.wiki docs
git submodule add https://github.com/youName/ProjectName.wiki docs
git submodule update --init

This will create a link from the docs folder to your project's Wiki repository on Github
