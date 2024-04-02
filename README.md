<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header</title>
    <!-- Adicione links para CSS aqui, se necessário -->
</head>

<body>
    <header>
        <div class="container">
            <div class="logo">

                <!-- Substitua o caminho da imagem pela sua logo -->
                <img src="petlogo.png" alt="Logo da PetShop">
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Página Inicial</a></li>
                    <li><a href="products.html">Produtos</a></li>
                    <li><a href="services.html">Serviços</a></li>
                    <li><a href="contact.html">Contato</a></li>
                    <!-- Adicione mais links conforme necessário -->
                </ul>
            </nav>
            <div class="user-area">
                <form action="cadastro_usuario.php" method="post">

                    <input type="email" name="email" placeholder="E-mail">
                    <input type="password" name="senha" placeholder="Senha">
                    <button type="submit">Entrar</button>
                </form>
            </div>
        </div>
    </header>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produtos e Serviços</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <div class="container">
        <h2>Produtos</h2>
        <!-- Adicione um carrossel de produtos aqui -->

        <h2>Serviços</h2>
        <!-- Adicione um carrossel de serviços aqui -->

        <!-- Adicione descrição e valor para cada produto e serviço -->
    </div>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Cliente</title>
</head>

<body>
    <form action="cadastro_cliente.php" method="post">
        <input type="text" name="nome" placeholder="Nome">
        <input type="text" name="endereco" placeholder="Endereço">
        <input type="tel" name="telefone" placeholder="Telefone">
        <input type="email" name="email" placeholder="E-mail">
        <button type="submit">Cadastrar Cliente</button>
    </form>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Pet</title>
</head>

<body>
    <form action="cadastro_pet.php" method="post">
        <input type="text" name="nome" placeholder="Nome do Pet">
        <input type="text" name="tipo" placeholder="Tipo do Pet">
        <input type="text" name="raca" placeholder="Raça do Pet">
        <input type="text" name="temperamento" placeholder="Temperamento do Pet">
        <button type="submit">Cadastrar Pet</button>
    </form>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escolha do Serviço</title>
</head>

<body>
    <h2>Escolha do Serviço</h2>
    <form action="agendamento_servico.php" method="post">
        <input type="checkbox" name="servico" value="banho"> Banho<br>
        <input type="checkbox" name="servico" value="tosa"> Tosa<br>
        <!-- Adicione mais opções de serviços -->
        <label for="data">Data do Agendamento:</label>
        <input type="date" id="data" name="data">
        <label for="tele-busca">Opção para Tele-busca:</label>
        <input type="checkbox" id="tele-busca" name="tele-busca">
        <button type="submit">Agendar</button>
    </form>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rodapé</title>
    <!-- Adicione links para CSS aqui, se necessário -->
</head>

<body>
    <footer>
        <div class="container">
            <div class="footer-info">


                <!-- Adicione mais links conforme necessário -->
                </ul>
                </nav>
            </div>
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Página Inicial</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <section class="promo-section">
            <h2>Promoção da Semana</h2>
            <!-- Destaque os produtos em promoção -->
        </section>

        <section class="quick-access">
            <h2>Acesso Rápido</h2>
            <!-- Adicione links para os produtos e serviços -->
        </section>
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Produtos</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <h2>Nossos Produtos</h2>
        <!-- Lista de produtos disponíveis para compra com opções de filtro -->
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Detalhes do Produto</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <!-- Apresentação detalhada do produto selecionado -->
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Serviços</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <h2>Nossos Serviços</h2>
        <!-- Descrição dos serviços oferecidos com opção para agendamento -->
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Cadastro do Cliente</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <h2>Cadastro do Cliente</h2>
        <!-- Formulário para inserção de informações pessoais, de contato e de pet -->
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Carrinho de Compras</title>
    <!-- Adicione links para CSS e Bootstrap aqui, se necessário -->
</head>

<body>
    <header>
        <!-- Inclua o cabeçalho com o logo e links de navegação -->
    </header>

    <div class="container">
        <h2>Carrinho de Compras</h2>
        <!-- Exibição dos itens selecionados para compra com opção para finalizar a compra ou continuar comprando -->
    </div>

    <footer>
        <!-- Inclua o rodapé com informações legais e links de navegação -->
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Página Inicial</title>
    <!-- Adicione links para CSS e JavaScript aqui, se necessário -->
</head>

<body>

    <!-- Todo o conteúdo da página será adicionado aqui -->

</body>

</html>
<header>
    <div class="container">

        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Produtos</a></li>
                <li><a href="services.html">Serviços</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </div>
</header>
<section class="promo-section">
    <div class="container">
        <h2>Promoção da Semana</h2>
        <p>Descrição da promoção...</p>
        <a href="promo_details.html" class="btn">Ver Mais</a>
    </div>
</section>

<section class="quick-access">
    <div class="container">
        <h2>Acesso Rápido</h2>
        <!-- Adicione links rápidos para produtos ou serviços -->
    </div>
</section>
<footer>
    <div class="container">
        <p>© 2024 PetCare. Todos os direitos reservados.</p>
        <p>Contato: contato@petcare.com</p>
        <nav>
            <ul>
                <li><a href="privacy_policy.html">Política de Privacidade</a></li>
                <li><a href="terms_of_service.html">Termos de Serviço</a></li>
            </ul>
        </nav>
    </div>
</footer>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Página Inicial</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>



</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetCare - Página Inicial</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
        <h1>Cabeçalho</h1>
    </header>

    <script src="script.js"></script>
</body>

</html>
<div class="container">
    <h2>Nossos Produtos</h2>
    <div class="produtos-grid">
        <!-- Iterar sobre a lista de produtos e exibir cada um deles -->
        <!-- Substitua 'caminho_para_imagem' pelo caminho real das imagens -->
        <!-- Você também pode adicionar um link para a página de detalhes do produto -->
        <!-- por exemplo, <a href="product_details.html?id=1"> -->
        <!-- para permitir que os usuários visualizem mais detalhes do produto -->
        <!-- ou adicionem o produto ao carrinho -->
        {% for produto in produtos %}
        <div class="produto">
            <img src="{{ produto.imagem }}" alt="{{ produto.nome }}">
            <h3>{{ produto.nome }}</h3>
            <p class="preco">R$ {{ produto.preco.toFixed(2) }}</p>
        </div>
        {% endfor %}
    </div>
</div>
