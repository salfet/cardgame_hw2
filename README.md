# cardgame_hw2
#Pug
doctype html 
html(lang ="ru-RU")
    head
        meta(charset='UTF-8')
        meta(name='viewport' content='width=device-width, initial-scale=1.0')
        <link rel="stylesheet" href="style.css">
       

    title Первая страница

    body
  
        div(class= "container")
            include modules/divGame
        script(src='index.js')
