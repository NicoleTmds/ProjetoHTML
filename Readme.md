Este projeto servirá de base para testar as funções e compreender o funcionamento e estrutura das linguagens HTML e CSS;

Código padrão html com comentários: 
#atalho: < html:5 >

<!DOCTYPE html>

<html lang="pt-br"> (Define a linguagem do site)

<head> (O head providencia informações gerais do documento. Ele não pode ser visualizado pelos usuários)
    <meta charset="UTF-8"> (Tipo de caractere padrão web)
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> (Garante a compatibilidade do site com a internetexplorer)
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> (Garante certa adaptação da tela para diferentes dispositivos)
    <meta name="description" content="Projeto HTML para entender a linguagem"> (Descrição do site)
    <meta name="keywords" content="programacao,html,css,javascript"> (Palavras-chave)
    <meta name="author" content="Nicole Tamarindo"> (Define o Autor do site)
    <title>ProjetoHTML</title>
</head>

<body> (Estrutura geral do site)

#Titulos são classificados pela importância do texto no site.
#Só pode ter um h1/Titulo principal no site. Os demais titulos(h2/h3/h4...) Podem ser repetidos.
#Atalho para conteúdo aleatório: < p>lorem >
#Caso queira múltiplicar de forma rápida: p*"Quantidade"

<h1>Titulo 1</h1>

<p> Primeiro paragrafo</p>

<h2>Titulo 2</h2>

<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A aut fuga nam commodi reprehenderit saepe rerum, alias harum sapiente excepturi ab perspiciatis officia rem, sunt quisquam corporis unde laborum iste!</p>

<h2>Titulo 2/2</h2>
<h3>Titulo 3</h3>
<h4>Titulo 4</h4>
<h5>Titulo 5</h5>
<h6>Titulo 6</h6>

</body>

</html>

Formatação de texto(Tags): 
    <b></b> (Deixa o trecho em negrito);
    <strong></strong> (Negrito/Determina frases com maior enfase/importantes);
    <hr></hr> (Separa linhas de seção/Linha de divisão)
    <br></br> (Quebra de linha/Pula uma linha)
    <i></i> (Deixa em itálico)
    <u></u> (Deixa sublinhado)
    <small></small> (Texto pequeno)
    <del></del> (Riscado/Deletado)
    <sup></sup> (Superior ex:Número exponencial)
    <sub></sub> (Inferior)
    <mark></mark> (Marcação/destaca o texto)
    <!-- (Comentário)

Como adicionar links (URL ABSOLUTA):
    <a href="url do site">Mensagem que vai aparecer na tela</a>
    ex: <a href="Google.com">Ir para o site</a>

Para o link ser aberto em uma nova aba inserir o <target="_blank">
    ex: <a href="Google.com" target="_blank">Ir para o site</a>

Como direcionar o usuário para uma página/arquivo dentro do próprio projeto:
    <a href="nome do arquivo">Mensagem que vai aparecer na tela</a>
    ex: <a href="sobre.html">Sobre nós</a>
    
(Inverso):
    ex: <a href="index.html">Voltar para a página inicial</a>
    
Como navegar entre páginas/arquivos dentro de pastas:
    <a href="nome da pasta/nome do arquivo">Mensagem que vai aparecer na tela</a>
    ex: <a href="equipe/dimitri.html">Dimitri</a>
    
(Inverso): Se somente colocarmos o nome do arquivo ex:index.html, ele vai ser procurado dentro da pasta em que estamos ex:equipe. Portanto é preciso adicionar o <../>, para voltar uma pasta atrás.
    ex: <a href="../index.html">Voltar para principal</a>
Caso precise voltar duas pastas:
    ex: <a href="../../index.html">Voltar para principal</a>
E assim por diante.

Adicionando imagens da internet:
    <img src="url da imagem" width="xxx"(largura) height="xxx"(altura) alt=Descrição da imagem(Para pessoas com deficiência)>

Adicionando imagens do próprio projeto(Dowloads):
    <img src="pasta/nome do arquivo" height="300"(altura)>
    ex: <img src="img/carro.jpg" width="300"(altura)>

 
