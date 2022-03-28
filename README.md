Olá, esse é meu mini projeto que é um botão flutuante na parte inferior direita ou esqueda da tela. Ele é muito simples de ser implementado, e você pode colocá-lo em uma parte separada do seu HTML, e vai funcionar normalmente. Você só vai precisar usar o link do css e do js, e usar as classes determinadas, mas é muito simples. 



a estrutura necessária para o funcionamento do botão, é: 
```
<div class="settings-menu" onclick="menuSettingsButton()">
            <i class="fa-solid fa-bars"></i>
            <div class="menu-itens">
                <div class="menu-item">
                    <a href="#">
                        <i class="fa-solid fa-user"></i>
                    </a>
                    
                </div>
                <div class="menu-item">
                    <a href="#">
                        <i class="fa-solid fa-gear"></i>
                    </a>
                </div>
                <div class="menu-item">
                    <a href="#">
                        <i class="fa-solid fa-plus"></i>
                    </a>
                </div>
            </div>
        </div>
```

todas as tags "<i class="">" são editáveis. Você pode escolher o ícone que quiser.
As divs com a class "menu-item", podem ser multiplicadas, você pode por o quanto for necessário, porem, para não quebrar o funcionamento visual, você tera que definir um tamanho maior, ou menor, caso queira, utilizando uma tag de script, da maneira a seguir:
  
```
  <script>
    createMenuSettingsButton(200) //
  </script>
```
  Você pode escolher o número que desejar, recomendo que experimente e teste.
  Nos parametros, você coloca o numero que desejar. Isso vai definir o height da div "menu-itens", fazendo com que caiba mais ou menos a quantidade de categorias que deseja dentro do seu botão.

