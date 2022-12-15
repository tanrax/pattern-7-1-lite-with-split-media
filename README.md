# Pattern Template 7-1 Lite version with Split Media

An extraordinarily neat architecture that any Web Designer can understand at a glance. Structure with the help of SASS and media queries.

``` txt
sass/                    
|
|– mobile/             
|   |– _header.sass          
|   |– _footer.sass                       
|   |– pages/                
|   |   |– _home.sass        
|   |   |– _contact.sass     
|   |   ... 
|– desktop/             
|   |– _header.sass          
|   |– _footer.sass                       
|   |– pages/                
|   |   |– _home.sass        
|   |   |– _contact.sass     
|   |   ... 
|– _base.sass                    
|– _mixins.sass          
|– _typography.sass      
|– _variables.sass                          
|– vendors/              
|   |– _bootstrap.sass   
|   |– _jquery-ui.sass   
|   ...                  
`– mobile.sass      
`– desktop.sass  
```

# Compile SASS.

## Install

``` bash
yarn global add node-sass
```

## Run

``` bash
node-sass --output-style compressed sass/mobile.sass css/mobile.css
node-sass --output-style compressed sass/desktop.sass css/desktop.css
```
