# Programação para internet com HTML5 e CSS3
## HTML5 
* Versão mais recente do HTML
* Estrutura básica

    ```
    <!DOCTYPE html>

    <html>
        <head>

        </head>

        <body>
        </body>
    </html>
    ```   

* Tags

    * Cabeçalho e rodapé
        ```
            <header>
                (...)
            </header>

            <footer>
                (...)
            </footer>
        ```

    * Parágrafo

        ```
        <p>Texto</p>
        ```

    * Títulos

        ```
        <h1>Texto</h1>
        <h2>Texto</h2>
        <h3>Texto</h3>
        <h4>Texto</h4>
        <h5>Texto</h5>
        <h6>Texto</h6>
        ```

    * Listas

        * Lista não ordenada
        
            * O atributo type permite mudar o tipo do marcador (círculo, quadrado ...)

        ```
        <ul type="square">
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item 4</li>
            <li>Item 5</li>
        </ul>
        ```

        * Lista ordenada

        ```
        <ol>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item 4</li>
            <li>Item 5</li>
        </ol>
        ```


    * Barra de navegação com links

        ```
        <nav>
            <ul>
                <li>Link 1</li>
                <li>Link 2</li>
                <li>Link 3</li>
            </ul>
        </nav>
        ```

    * Seções

        ```
        <section id="secao1>
            <p>Conteúdo</p>
        </section>

        <section id="secao2>
            <p>Conteúdo</p>
        </section>

        <section id="secao3>
            <p>Conteúdo</p>
        </section>

        ```

    * Links
        
        * Atributos
            
            * href: destino da página. Pode ser uma URL externa ou para uma seção da página
            * target: define o modo como a página será aberta (em outra guia do navegador ou na mesma aba) 

        ```
        <a href="http://www.google.com/" target="_blank">Google</a>
        <a href="#secao1">Link para seção da página</a>

        ```
 
     * DIVs: estabelecem divisões de conteúdo dentro de uma seção. Podem ser adicionadas imagens, textos ou qualquer outro tipo de conteúdo.
        
        ```
        <div>
            (conteúdo)    
        </div>
        ```

## CSS3

* CSS (Cascading Style Sheets = Folhas de estilo em cascata)
* Permite modificar a aparência de uma página HTML
* Estrutura do CSS
    ```

    elemento {
        atributo1: valor1;
        atributo2: valor2;

        (...)

        atributoN: valorN;
    }

    ```
       
    * Elemento: pode ser uma tag ou seletor de classe/id 

1. Criar pasta 'css' no diretório do projeto e o arquivo de estilos dentro desta pasta
2. Adicionar a referência através da tag HTML ```<link>``` a sua página

    ```
    <html>

        <head>
            <link rel='stylesheet' type='text/css' href='css/style.css'>
        </head>

        <body>
        </body>
        
    </html>
    ```

 3. Propriedades CSS (essencial)

    * background/background-color: cor de fundo do elemento
    * color: cor do texto
    * font-family: tipo da fonte
    * font-size: tamanho do texto
    * margin: margens do texto (top, right, bottom, left --> nesta ordem)
        * margin-top
        * margin-right
        * margin-bottom
        * margin-left        
    * padding: espaçamento interno do elemento (top, right, bottom, left --> nesta ordem)
        * padding-top
        * padding-right
        * padding-bottom
        * padding-left     
    * display: disposição em que os elementos são mostrados
        * inline
        * block
        * inline-block
        * inline-flex
        * flex
        * grid
        * flexbox
