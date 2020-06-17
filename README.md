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
 
     * DIVs: estabelecem divisões de conteúdo dentro de uma seção. Podem ser adicionadas imagens ou textos.
        
        ```
        <div>
            (conteúdo)    
        </div>
        ```
 