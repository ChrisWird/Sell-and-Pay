<!DOCTYPE html>
<html lang="pt-MZ">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MarketMoz - Marketplace de Marketing Digital em Moçº»bique</title>
    <meta name="description" content="Compre e venda serviços de marketing digital em Moçº»bique.">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; line-height: 1.6; color: #1a1a1a; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        header { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px 0; }
        nav { display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 24px; font-weight: bold; }
        .nav-links a { color: white; text-decoration: none; margin-left: 30px; font-weight: 500; }
        .btn-cta { background: #ff6b6b; color: white; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-weight: bold; }
        .hero { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 80px 0; text-align: center; }
        .hero h1 { font-size: 36px; margin-bottom: 20px; }
        .hero p { font-size: 18px; margin-bottom: 30px; max-width: 600px; margin: 0 auto 30px; }
        .hero-buttons { display: flex; gap: 15px; justify-content: center; flex-wrap: wrap; }
        .btn-primary { background: #ff6b6b; color: white; padding: 14px 28px; border-radius: 8px; text-decoration: none; font-weight: bold; font-size: 16px; display: inline-block; }
        .btn-secondary { background: white; color: #667eea; padding: 14px 28px; border-radius: 8px; text-decoration: none; font-weight: bold; font-size: 16px; display: inline-block; }
        .features { padding: 60px 0; background: #f8f9fa; }
        .features h2 { text-align: center; font-size: 28px; margin-bottom: 40px; }
        .features-grid { display: grid; grid-template-columns: 1fr; gap: 30px; }
        .feature-card { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-align: center; }
        .feature-icon { font-size: 40px; margin-bottom: 15px; }
        .feature-card h3 { font-size: 20px; margin-bottom: 12px; color: #667eea; }
        .feature-card p { color: #666; }
        .how-it-works { padding: 60px 0; }
        .how-it-works h2 { text-align: center; font-size: 28px; margin-bottom: 40px; }
        .steps { display: grid; grid-template-columns: 1fr; gap: 30px; }
        .step { text-align: center; padding: 20px; }
        .step-number { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 20px; font-weight: bold; margin: 0 auto 15px; }
        .step h3 { font-size: 18px; margin-bottom: 8px; }
        .step p { color: #666; font-size: 14px; }
        .email-section { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 60px 0; text-align: center; }
        .email-section h2 { font-size: 28px; margin-bottom: 15px; }
        .email-section p { font-size: 16px; margin-bottom: 30px; }
        .email-form { max-width: 400px; margin: 0 auto; display: flex; flex-direction: column; gap: 12px; padding: 0 20px; }
        .email-form input { padding: 14px; border: none; border-radius: 8px; font-size: 16px; }
        .email-form button { background: #ff6b6b; color: white; padding: 14px; border: none; border-radius: 8px; font-size: 16px; font-weight: bold; cursor: pointer; }
        .success-message { display: none; background: #4caf50; color: white; padding: 15px; border-radius: 8px; margin-top: 20px; }
        footer { background: #1a1a1a; color: white; padding: 30px 0; text-align: center; }
        footer p { color: #999; font-size: 14px; }
        @media (min-width: 768px) { .features-grid, .steps { grid-template-columns: repeat(2, 1fr); } .hero h1 { font-size: 42px; } }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">MarketMoz</div>
                <div class="nav-links">
                    <a href="#features" style="display:none;">Recursos</a>
                    <a href="#contact" class="btn-cta">Entrar na Lista</a>
                </div>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>O Primeiro Marketplace de Marketing Digital de Moçº»bique</h1>
            <p>Compre e venda serviços de marketing digital com segurança. Pagamentos via M-Pesa, e-Mola e transferência bancaria.</p>
            <div class="hero-buttons">
                <a href="#contact" class="btn-primary">Quero Ser um dos Primeiros</a>
                <a href="#how-it-works" class="btn-secondary">Saiba Mais</a>
            </div>
        </div>
    </section>

    <section id="features" class="features">
        <div class="container">
            <h2>Por que usar nosso marketplace?</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🛒</div>
                    <h3>Compre com Segurança</h3>
                    <p>Encontre os melhores profissionais de marketing digital em Moçº»bique.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">💼</div>
                    <h3>Venda Seus Serviços</h3>
                    <p>Crie sua loja gratuita e alcance milhares de clientes.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">💳</div>
                    <h3>Pagamentos Locais</h3>
                    <p>M-Pesa, e-Mola, transferencia bancaria. Tudo em MZN.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">📱</div>
                    <h3>100% Mobile</h3>
                    <p>Use pelo celular, tablet ou computador.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🎯</div>
                    <h3>Foco em Marketing</h3>
                    <p>Redes sociais, SEO, trafego pago, design e muito mais.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🇲🇿</div>
                    <h3>Feito para Moçº»bique</h3>
                    <p>Suporte em portugues e atendimento local.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="how-it-works" class="how-it-works">
        <div class="container">
            <h2>Como Funciona</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Crie Sua Conta</h3>
                    <p>Cadastro gratis em 2 minutos.</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Compre ou Venda</h3>
                    <p>Busque serviços ou crie listagens.</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Pagamento Seguro</h3>
                    <p>Pague com M-Pesa ou transferencia.</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Avalie</h3>
                    <p>Apos concluir, avalie o vendedor.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="email-section">
        <div class="container">
            <h2>Entre na Lista de Espera</h2>
            <p>Seja um dos primeiros! Ganhe 50% de desconto.</p>
            <form id="emailForm" class="email-form" onsubmit="handleSubmit(event)">
                <input type="text" id="name" placeholder="Seu nome" required>
                <input type="email" id="email" placeholder="Seu email" required>
                <input type="tel" id="phone" placeholder="Seu telefone (opcional)">
                <button type="submit">Quero Entrar na Lista!</button>
            </form>
            <div id="successMessage" class="success-message">✓ Obrigado! Você está na lista!</div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2026 MarketMoz - Moçº»bique</p>
            <p>Maputo | Em breve em todo país</p>
        </div>
    </footer>

    <script>
        function handleSubmit(event) {
            event.preventDefault();
            document.getElementById('successMessage').style.display = 'block';
            document.getElementById('emailForm').style.display = 'none';
        }
    </script>
</body>
</html>
