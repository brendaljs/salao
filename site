<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Espaço Andrea - Estética Facial e Corporal</title>
    <style>
        :root {
            --bege: #F5F0E6;
            --rosa-claro: #E8C4C4;
            --marrom: #6D4C41;
            --marrom-claro: #A1887F;
            --cinza: #5D5D5D;
        }
        
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bege);
            color: var(--cinza);
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(rgba(109, 76, 65, 0.8), rgba(109, 76, 65, 0.8)), url('https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        
        .logo {
            font-size: 2.5rem;
            margin-bottom: 20px;
            font-weight: 300;
            letter-spacing: 3px;
        }
        
        .slogan {
            font-style: italic;
            font-weight: 300;
            margin-bottom: 30px;
        }
        
        nav {
            background-color: var(--marrom);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        nav li {
            margin: 0 20px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }
        
        nav a:hover {
            color: var(--rosa-claro);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        h1, h2, h3 {
            color: var(--marrom);
            font-weight: 400;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            position: relative;
        }
        
        h2::after {
            content: "";
            display: block;
            width: 80px;
            height: 2px;
            background: var(--rosa-claro);
            margin: 15px auto;
        }
        
        .servicos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .servico-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .servico-card:hover {
            transform: translateY(-10px);
        }
        
        .servico-img {
            height: 200px;
            overflow: hidden;
        }
        
        .servico-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .servico-card:hover .servico-img img {
            transform: scale(1.1);
        }
        
        .servico-content {
            padding: 20px;
        }
        
        .servico-content h3 {
            margin-top: 0;
            color: var(--marrom);
        }
        
        .btn {
            display: inline-block;
            background-color: var(--marrom);
            color: white;
            padding: 10px 20px;
            border-radius: 30px;
            text-decoration: none;
            margin-top: 15px;
            transition: all 0.3s ease;
            border: 1px solid var(--marrom);
        }
        
        .btn:hover {
            background-color: transparent;
            color: var(--marrom);
        }
        
        .sobre {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }
        
        .sobre-img {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .sobre-img img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .contato-info {
            background: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-top: 40px;
        }
        
        .contato-info p {
            margin: 15px 0;
        }
        
        .contato-icon {
            color: var(--marrom);
            margin-right: 10px;
        }
        
        footer {
            background-color: var(--marrom);
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 60px;
        }
        
        .social-links {
            margin: 20px 0;
        }
        
        .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--rosa-claro);
        }
        
        @media (max-width: 768px) {
            .sobre {
                grid-template-columns: 1fr;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 10px 0;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo">ESPAÇO ANDREA</div>
        <div class="slogan">Beleza e cuidado para sua pele</div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Início</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
    
    <section id="inicio" class="container">
        <h2>Bem-vindo ao Espaço Andrea</h2>
        <p>No Espaço Andrea, acreditamos que a verdadeira beleza começa com cuidados especializados. Nossa missão é proporcionar tratamentos estéticos personalizados que realcem sua beleza natural, promovendo autoestima e bem-estar.</p>
        <p>Com técnicas modernas e produtos de alta qualidade, nossa equipe está pronta para oferecer os melhores resultados em estética facial e corporal.</p>
    </section>
    
    <section id="servicos" class="container">
        <h2>Nossos Serviços</h2>
        <div class="servicos-grid">
            <!-- Dermaplaning -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1596704017256-17961a3685a3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Dermaplaning">
                </div>
                <div class="servico-content">
                    <h3>Dermaplaning</h3>
                    <p>Tratamento de esfoliação física que remove células mortas e pelos faciais, deixando a pele mais lisa, luminosa e preparada para absorver ativos.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Microagulhamento -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1570172619644-dfd03ed5d881?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Microagulhamento">
                </div>
                <div class="servico-content">
                    <h3>Microagulhamento</h3>
                    <p>Estimula a produção de colágeno e elastina, melhorando a textura da pele, reduzindo cicatrizes de acne, estrias e sinais de envelhecimento.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Limpeza de Pele -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1526758097130-bab247274f58?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Limpeza de Pele">
                </div>
                <div class="servico-content">
                    <h3>Limpeza de Pele</h3>
                    <p>Profunda e suave, remove impurezas, cravos e células mortas, desobstruindo os poros e prevenindo o aparecimento de acne.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Fototerapia -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Fototerapia">
                </div>
                <div class="servico-content">
                    <h3>Fototerapia</h3>
                    <p>Tratamento com luzes LED que estimulam a regeneração celular, combatendo acne, rosácea, manchas e sinais de envelhecimento.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Brow Lamination -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1595476108010-b4d1f102b1b1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Brow Lamination">
                </div>
                <div class="servico-content">
                    <h3>Brow Lamination</h3>
                    <p>Tratamento que alisa e fixa os pelos das sobrancelhas, dando um efeito de preenchimento e organização por até 6 semanas.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Extensão de Cílios -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1596704017256-17961a3685a3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Extensão de Cílios">
                </div>
                <div class="servico-content">
                    <h3>Extensão de Cílios</h3>
                    <p>Aplicação de fios sintéticos fio a fio, proporcionando um olhar mais marcante e expressivo, com duração de 3 a 4 semanas.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Hidragloss -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1519699047748-de8e457a634e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Hidragloss">
                </div>
                <div class="servico-content">
                    <h3>Hidragloss</h3>
                    <p>Tratamento hidratante intensivo para os lábios, que combina esfoliação, máscara nutritiva e finalização com gloss, deixando-os macios e volumosos.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Remoção de Verrugas -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Remoção de Verrugas">
                </div>
                <div class="servico-content">
                    <h3>Remoção de Verrugas</h3>
                    <p>Procedimento seguro e eficaz para remoção de verrugas utilizando técnicas especializadas, com mínimo desconforto e rápida recuperação.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
            
            <!-- Design de Sobrancelhas -->
            <div class="servico-card">
                <div class="servico-img">
                    <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Design de Sobrancelhas">
                </div>
                <div class="servico-content">
                    <h3>Design de Sobrancelhas</h3>
                    <p>Modelagem personalizada conforme a estrutura facial, realçando a expressão e harmonizando os traços do rosto.</p>
                    <a href="#contato" class="btn">Agendar</a>
                </div>
            </div>
        </div>
    </section>
    
    <section id="sobre" class="container">
        <h2>Sobre o Espaço Andrea</h2>
        <div class="sobre">
            <div class="sobre-img">
                <img src="https://images.unsplash.com/photo-1559599101-f09722fb4948?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Espaço Andrea">
            </div>
            <div>
                <p>O Espaço Andrea nasceu da paixão por estética e bem-estar, com o objetivo de oferecer tratamentos personalizados e resultados visíveis.</p>
                <p>Andrea, profissional com mais de 10 anos de experiência na área, está constantemente se atualizando com as melhores técnicas e produtos do mercado para oferecer o que há de mais moderno em estética facial e corporal.</p>
                <p>Nosso espaço foi cuidadosamente planejado para proporcionar conforto e tranquilidade durante seus tratamentos, em um ambiente acolhedor e profissional.</p>
                <p>Acreditamos que cada cliente é único, por isso desenvolvemos protocolos personalizados que atendam às necessidades específicas de cada pele.</p>
            </div>
        </div>
    </section>
    
    <section id="contato" class="container">
        <h2>Agende seu Horário</h2>
        <div class="contato-info">
            <p><i class="fas fa-map-marker-alt contato-icon"></i> <strong>Endereço:</strong> Rua Cambará, 402 - Diadema/SP</p>
            <p><i class="fas fa-phone contato-icon"></i> <strong>Telefone:</strong> (11) 91074-0330</p>
            <p><i class="fas fa-clock contato-icon"></i> <strong>Horários:</strong> Entre em contato para agendamento</p>
            <p><i class="fas fa-envelope contato-icon"></i> <strong>Email:</strong> contato@espacoandrea.com</p>
            
            <p style="margin-top: 30px;">Para agendar seu horário ou tirar dúvidas sobre nossos serviços, entre em contato por telefone ou WhatsApp.</p>
            <a href="https://wa.me/5511910740330" class="btn" target="_blank"><i class="fab fa-whatsapp"></i> Enviar Mensagem</a>
        </div>
    </section>
    
    <footer>
        <div class="logo" style="color: white; font-size: 1.8rem;">ESPAÇO ANDREA</div>
        <div class="social-links">
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="https://wa.me/5511910740330"><i class="fab fa-whatsapp"></i></a>
        </div>
        <p>&copy; 2023 Espaço Andrea - Todos os direitos reservados</p>
    </footer>
</body>
</html>
