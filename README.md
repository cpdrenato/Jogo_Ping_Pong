<p align="center">
	<img src="img/Play.png"  height="140" width="100" alt=""/>	
</p>	
		
	

# Jogo em HTML5
- jogo do tipo Pong em HTML5.
- Em Construçao


## icones
- http://www.iconninja.com/tag/play-icon
## Configurar footer
- https://pt.stackoverflow.com/questions/165214/footer-no-final-do-documento
$ html
```sh
$<div class="container body-content">
    @RenderBody()
    <footer class="fixarRodape">
        <hr />
        <p>&copy; @DateTime.Now.Year</p>
    </footer>
$</div>
```
$ css
```sh
$style>
    .fixarRodape {
        bottom: 0;
        position: fixed;
        width: 90%;
        text-align: center;
    }
$</style>
```
## EXEMPLO COM RODAPÉ EM POSIÇÃO ABSOLUTA
```sh
$<div id="wrapper">
  <div class="container body-content">
    <p>
      Conteúdo do corpo do documento!
    </p>
    <p>
      Conteúdo do corpo do documento!
    </p>
    
  </div>
  <footer id="rodape">
    <p>&copy; Tudo o que quiser colocar aqui</p>
  </footer>
$</div>
```
$ css
```sh
	html, body {
	margin: 0;
	padding: 0;
	height: 100%;
	}
	#wrapper{
	min-height: 100%;
	position: relative;
	}
	div.body-content{
	  /** Altura do rodapé tem que ser igual a isso aqui e vice-versa **/
	padding-bottom: 100px;
	}
	footer{
	background: #ffab62;
	width: 100%;
	height: 100px;
	position: absolute;
	bottom: 0;
	left: 0;
	}
````


- Renato Lucena
- 2018