# php version of goproxy
can be made a deploy to **Heroku**

## create project on Heroku
Just do it with ur browser , open ` heroku.com ` and create a NEW project.  

## add heroku buildpack
Go to ur heroku project - ` setting ` , add a buildpack named ` heroku/php ` .  

## link this github repo for deploy
Fork this repo to ur Github Account.  
Go to heroku project - ` deploy ` , choose ` link to Github ` and search for this repo .  
Scroll to the lower part of page to press ` deploy ` button .  

## your server ready
Wait for the deploy to be completed , and you get a php server with domain name.  
You can get ur domain name by clicking ` Open App ` button or find it in [ heroku project - ` setting ` ] .  

## Another method 
Do it with Heroku CLI .  
[Ref link](https://blog.csdn.net/goen88/article/details/50609454)  
Remenber to download the ` .php & .js files ` to your php root path .  
