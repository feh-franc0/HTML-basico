<h1>HTML BÁSICO</h1>

## 1.Tags (valor semantico)
### Tags de abertura e fechamento,normalmente tem conteudo dentro deles.
    exemplo portugol:
        <nomeTagTitulo>meu titulo</nomeTagTitulo>
        <nomeTagParagrafo>meu paragrafo</nomeTagParagrafo>

    usando tags semanticas HTML:
        <h1>Meu titulo</h1>
        <p>meu paragrafo</p>

### Tag de autofechamento,não recebem conteudo escrito so conteudo que é determinado dependendo da utilizadade da tag
    exemplo portugol:
        <imagem caminho="imagem.png" sobre="img de exemplo">

    usando tags semanticas HTML:
        <img src="imagem.png" alt="minha imagem teste">


### saiba que: 
    <h1>            =>  Tag de abertura
    </h1>           =>  Tag de fechamento
    <img>           =>  Tag de autofechamento

    <h1>texto</h1>  =>  Elemento HTML

---
## 2.Estrutura Básica
### estrutura minima que permitira voce a ter uma estrutura minima para ter um arquivo HTML
    <!DOCTYPE html>
    <html lang="en">
        <head>
            <title>titulo da aba</title>
            <meta charset="UTF-8">
        </head>
        <body>
            aqui estarao as tags HTML...
        </body>
    </html>

---
## 3.Títulos e Parágrafos
### Os Títulos com maior peso semantico são o "h1" para o titulo principal do site e "h2" para sub-titulos do seu site,mas vai de h1 ate h5. 
### A tag para paragrafos a principio não tem peso semantico relevante.
    <h1></h1>   => Valor semantico de titulo principal e unico
    <h2></h2>   => Valor semantico de sub-titulos importantes
    <h3></h3>   => Sub-titulo do h2
    <h4></h4>   => Sub-titulo do h3
    <h5></h5>   => Sub-titulo do h4

---
## 4.Comentarios
### comentarios sao muito importantes para ter um codigo bem explicado e organizado, o comentario não será exebido na tela,sera visto apenas pelas pessoas que iram ver o codigo fonte diretamente

    comentar linha unica:
    <!-- comentario -->

    comentar duas ou mais linhas:
    <!-- <h1>titulo</h1>
    <p>paragrafo</p> -->

---
## 5. Formatação
### a formatação é bem usado para dar peso semantico em Tags paragrafo ou tags span.

    use: <b> para texto em negrito sem semantica </b>
    
    use: <strong> o "strong" é semantico,indica para o google(buscados) que o que é strong é muito importante </strong>
    
    use: <i> texto em italico não semantico </i>
    
    use: <em> deixa em italico,semantico de importancia/enfase </em>
    
    use: <mark> texto marcado semelhante ao marca texto,peso semantico de destaque </mark>
    
    use: <small> deixa a letra pequena </small>
    
    use: <del> serve para deixar o texto riscado, semantica de excluido </del>
    
    use: <s> risca texto sem valor semantico </s>
    
    use: <ins> sublinha o texto, informa que texto foi adicionado, ao contrario do del </ins>
    
    use: <u> sublinha sem ter semantica </u>
    
    use: <sub> deixa a linha um pouco mais abaixo,excelentes para formulas quimicas </sub>
    
    use: <sup> deixa a linha um pouco a cima,excelentes para formulas matematicas </sup>

---
## 6. Links
### usado para redirecionar para alguma outra pagina ou para algum lugar da pagina em que estamos
    <a href="sobre.html"> click para ir para a pag sobre </a>

---
## 7. Imagens
### formas de redimensionar e exibir imagens
    <img src="/caminhoImg(url_da_img) alt="o que é,do que se trata a imagem">
    
    -> Tem como utilizar link de imagens que estejam em outros sites ou link para fotas que estao em seu dispositivo.

    -> Transforma a imagem em um link,podendo clicar na img para ir ao site,usando a tag: 
        <a href="link do site"> <img src="a imagem"> </a>

    -> Pode usar um atributo dentro da tag <img> para modificar o tamanho da imagem.Use o atributo( height=altura / width=largura ):
        <img src="imagem" alt="do que se trata a img" height=300 width=300>

---
## 8. Quebra de linha
### Tag de auto fechamante utilizado para quebrar linha(ir para a linha de baixo)
    <h1>Titulo</h1>
    <span>paragrafo1</span>
    <br>
    <span>paragrafo2</span>

---
## 9. Listas
### temos dois tipos de listas e as duas usam a mesma tag para dados que estaram dentro da lista
    para uma lista não ordenada,utilize a Tag:
        -> <ul></ul>
        ex: 
            <ul>
                <li> item1 </li>
                <li> item2 </li>
                <li> item2 </li>
            </ul>


    para uma lista ordenada,utilize a Tag:
        -> <ol></ol>
        ex:
            <ol>
                <li> item1 </li>
                <li> item2 </li>
                <li> item2 </li>
            </ol>


    para ambos os tipos de lista,usamos a tag "li" para adicionar 'itens na lista':
        -> <li></li>

---
## 10. Tabelas
### muito usado para mostrar dados e organizar informações
    Para começar a criar uma tabela use a tag:
        -> <table></table>

    Para criar linhas da tabela,use a tag: 
        -> <tr></tr>

    Para o nome/coluna do cabeçalho da tabela,use:
        -> <th></th>

    Para colocar os dados/preenche-colunas da tabela,use:
        -> <td></td>
    
    E voce pode continuar usando e botando os dados usando: '<tr></tr>' para linhas na tabela e '<td></td>' para dados na tabela.


    Codigo HTML:

        <table>
            <tr>
                <th>Nome</th>
                <th>Telefone</th>
            </tr>
            <tr>
                <td>Fabio castro</td>
                <td>1234-5678</td>
            </tr>
            <tr>
                <td>Joao Pedro</td>
                <td>5858-9191</td>
            </tr>
        </table>
