<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finvest - Sua Empresa de Investimentos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        header nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            background: url('investments-hero.jpg') no-repeat center center/cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 3em;
        }
        .section {
            padding: 20px;
            margin: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
        }
        .service-item {
            flex: 1;
            margin: 10px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
        }
        .contact-form button {
            padding: 10px 20px;
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <img src="finvest-logo.png" alt="Finvest Logo">
        </div>
        <nav>
            <a href="#home">Home</a>
            <a href="#sobre-nos">Sobre Nós</a>
            <a href="#servicos">Serviços</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <div>
            <h1>Bem-vindo à Finvest</h1>
            <p>Sua parceira em investimentos inteligentes</p>
            <a href="#sobre-nos" style="background: #fff; color: #333; padding: 10px 20px; text-decoration: none;">Saiba Mais</a>
        </div>
    </section>

    <section id="sobre-nos" class="section">
        <h2>Sobre Nós</h2>
        <p>A Finvest é uma empresa dedicada a oferecer as melhores soluções em investimentos para nossos clientes. Fundada por especialistas do setor financeiro, nossa missão é ajudar você a alcançar seus objetivos financeiros de maneira inteligente e segura.</p>
        <h3>Nossa Equipe</h3>
        <p>Conheça os profissionais que fazem a Finvest:</p>
        <div class="team">
            <div class="team-member">
                <img src="team-member1.jpg" alt="Membro da Equipe 1">
                <p>João Silva - CEO</p>
            </div>
            <div class="team-member">
                <img src="team-member2.jpg" alt="Membro da Equipe 2">
                <p>Maria Souza - CFO</p>
            </div>
            <!-- Adicione mais membros da equipe conforme necessário -->
        </div>
    </section>

    <section id="servicos" class="section">
        <h2>Serviços</h2>
        <div class="services">
            <div class="service-item">
                <h3>Consultoria Financeira</h3>
                <p>Oferecemos serviços de consultoria financeira para ajudá-lo a planejar e gerenciar seus investimentos de forma eficiente.</p>
            </div>
            <div class="service-item">
                <h3>Análise de Investimentos</h3>
                <p>Nossa equipe realiza análises detalhadas de investimentos para garantir os melhores retornos para nossos clientes.</p>
            </div>
            <div class="service-item">
                <h3>Educação Financeira</h3>
                <p>Oferecemos cursos e workshops para educar nossos clientes sobre finanças pessoais e investimentos.</p>
            </div>
        </div>
    </section>

    <section id="contato" class="section">
        <h2>Contato</h2>
        <div class="contact-form">
            <form action="submit_form.php" method="post">
                <input type="text" name="nome" placeholder="Seu Nome" required>
                <input type="email" name="email" placeholder="Seu E-mail" required>
                <input type="text" name="assunto" placeholder="Assunto" required>
                <textarea name="mensagem" rows="5" placeholder="Sua Mensagem" required></textarea>
                <button type="submit">Enviar</button>
            </form>
            <div>
                <p>Endereço: Rua dos Investidores, 123, São Paulo, SP</p>
                <p>Telefone: (11) 1234-5678</p>
                <p>Email: contato@finvest.com</p>
            </div>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finvest - Sua Empresa de Investimentos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        header nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            background: url('investments-hero.jpg') no-repeat center center/cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 3em;
        }
        .section {
            padding: 20px;
            margin: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
        }
        .service-item {
            flex: 1;
            margin: 10px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
        }
        .contact-form button {
            padding: 10px 20px;
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <img src="finvest-logo.png" alt="Finvest Logo">
        </div>
        <nav>
            <a href="#home">Home</a>
            <a href="#sobre-nos">Sobre Nós</a>
            <a href="#servicos">Serviços</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <div>
            <h1>Bem-vindo à Finvest</h1>
            <p>Sua parceira em investimentos inteligentes</p>
            <a href="#sobre-nos" style="background: #fff; color: #333; padding: 10px 20px; text-decoration: none;">Saiba Mais</a>
        </div>
    </section>

    <section id="sobre-nos" class="section">
        <h2>Sobre Nós</h2>
        <p>A Finvest é uma empresa dedicada a oferecer as melhores soluções em investimentos para nossos clientes. Fundada por especialistas do setor financeiro, nossa missão é ajudar você a alcançar seus objetivos financeiros de maneira inteligente e segura.</p>
        <h3>Nossa Equipe</h3>
        <p>Conheça os profissionais que fazem a Finvest:</p>
        <div class="team">
            <div class="team-member">
                <img src="team-member1.jpg" alt="Membro da Equipe 1">
                <p>João Silva - CEO</p>
            </div>
            <div class="team-member">
                <img src="team-member2.jpg" alt="Membro da Equipe 2">
                <p>Maria Souza - CFO</p>
            </div>
            <!-- Adicione mais membros da equipe conforme necessário -->
        </div>
    </section>

    <section id="servicos" class="section">
        <h2>Serviços</h2>
        <div class="services">
            <div class="service-item">
                <h3>Consultoria Financeira</h3>
                <p>Oferecemos serviços de consultoria financeira para ajudá-lo a planejar e gerenciar seus investimentos de forma eficiente.</p>
            </div>
            <div class="service-item">
                <h3>Análise de Investimentos</h3>
                <p>Nossa equipe realiza análises detalhadas de investimentos para garantir os melhores retornos para nossos clientes.</p>
            </div>
            <div class="service-item">
                <h3>Educação Financeira</h3>
                <p>Oferecemos cursos e workshops para educar nossos clientes sobre finanças pessoais e investimentos.</p>
            </div>
        </div>
    </section>

    <section id="contato" class="section">
        <h2>Contato</h2>
        <div class="contact-form">
            <form action="submit_form.php" method="post">
                <input type="text" name="nome" placeholder="Seu Nome" required>
                <input type="email" name="email" placeholder="Seu E-mail" required>
                <input type="text" name="assunto" placeholder="Assunto" required>
                <textarea name="mensagem" rows="5" placeholder="Sua Mensagem" required></textarea>
                <button type="submit">Enviar</button>
            </form>
            <div>
                <p>Endereço: Rua dos Investidores, 123, São Paulo, SP</p>
                <p>Telefone: (11) 1234-5678</p>
                <p>Email: contato@finvest.com</p>
            </div>
        </div>
    </section>
</body>
</html>
