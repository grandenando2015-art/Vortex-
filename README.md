<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VORTEX da Internet | Ofertas Exclusivas</title>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: #0b0c10;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 16px;
        }

        .container {
            width: 100%;
            max-width: 480px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        /* Logotipo Oficial */
        .logo-container {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 12px;
        }

        .logo-ring {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            background: linear-gradient(135deg, #1f2833, #0b0c10);
            border: 2px solid #45f3ff;
            box-shadow: 0 0 20px rgba(69, 243, 255, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 15px;
        }

        .logo-ring svg {
            width: 100%;
            height: 100%;
        }

        .brand-title {
            font-size: 1.8rem;
            font-weight: 900;
            letter-spacing: 2px;
            background: linear-gradient(90deg, #ffffff, #c5c6c7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .brand-subtitle {
            font-size: 0.9rem;
            color: #66fcf1;
            font-weight: 600;
            letter-spacing: 1px;
            margin-top: -8px;
        }

        /* Carrossel de Banners */
        .carousel-card {
            width: 100%;
            background: #1f2833;
            border-radius: 16px;
            padding: 20px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.5);
            border: 1px solid #2c3540;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .carousel-card::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0;
            height: 4px;
            background: linear-gradient(90deg, #45f3ff, #ff4b4b, #ffbe2e);
        }

        .banner-title {
            font-size: 1.2rem;
            font-weight: 800;
            color: #ffffff;
            margin-bottom: 8px;
        }

        .banner-desc {
            font-size: 0.85rem;
            color: #c5c6c7;
            margin-bottom: 16px;
        }

        .store-badges {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin-bottom: 15px;
        }

        .badge {
            background: #0b0c10;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 700;
            border: 1px solid #333;
        }

        .badge.shopee { color: #ff5722; border-color: #ff5722; }
        .badge.ml { color: #ffe600; border-color: #ffe600; }
        .badge.shein { color: #ffffff; border-color: #ffffff; }

        /* Lista de Links */
        .links-container {
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        .btn-link {
            width: 100%;
            padding: 16px 20px;
            border-radius: 12px;
            font-size: 1rem;
            font-weight: 700;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            transition: all 0.2s ease;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
        }

        .btn-link:active {
            transform: scale(0.98);
        }

        .btn-primary {
            background: linear-gradient(135deg, #25d366, #128c7e);
            color: #ffffff;
            border: none;
        }

        .btn-secondary {
            background: #1f2833;
            color: #45f3ff;
            border: 1px solid #45f3ff;
        }

        /* Área do ADM no rodapé */
        .admin-footer {
            margin-top: 40px;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            border-top: 1px solid #222;
            padding-top: 20px;
            padding-bottom: 30px;
        }

        .admin-toggle-btn {
            background: transparent;
            border: none;
            color: #555;
            font-size: 0.8rem;
            cursor: pointer;
            text-decoration: underline;
        }

        .admin-box {
            display: none;
            width: 100%;
            max-width: 320px;
            margin-top: 15px;
            background: #15181e;
            padding: 15px;
            border-radius: 10px;
            border: 1px solid #333;
        }

        .admin-box input {
            width: 100%;
            padding: 10px;
            border-radius: 6px;
            border: 1px solid #333;
            background: #0b0c10;
            color: #fff;
            margin-bottom: 10px;
            outline: none;
        }

        .admin-box button {
            width: 100%;
            padding: 10px;
            border-radius: 6px;
            border: none;
            background: #45f3ff;
            color: #0b0c10;
            font-weight: 700;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logotipo Oficial Vortex -->
        <div class="logo-container">
            <div class="logo-ring">
                <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 10 C 30 10, 10 30, 10 50 C 10 70, 30 90, 50 90 C 70 90, 90 70, 90 50 C 90 30, 70 10, 50 10" stroke="#45f3ff" stroke-width="4" stroke-dasharray="120" stroke-dashoffset="30"/>
                    <path d="M50 22 C 38 22, 22 38, 22 50 C 22 62, 38 78, 50 78 C 62 78, 78 62, 78 50 C 78 38, 62 22, 50 22" stroke="#ffffff" stroke-width="3"/>
                    <circle cx="50" cy="50" r="10" fill="#45f3ff"/>
                </svg>
            </div>
            <h1 class="brand-title">VORTEX</h1>
            <span class="brand-subtitle">DA INTERNET</span>
        </div>

        <!-- Banner com Destaques -->
        <div class="carousel-card">
            <div class="banner-title">AS MELHORES OFERTAS!</div>
            <div class="banner-desc">Achadinhos diários com cupons imperdíveis</div>
            <div class="store-badges">
                <span class="badge shopee">Shopee</span>
                <span class="badge ml">Mercado Livre</span>
                <span class="badge shein">Shein</span>
            </div>
        </div>

        <!-- Botões de Ação para o WhatsApp -->
        <div class="links-container">
            <!-- Abre direto o convite do Grupo do WhatsApp -->
            <a href="https://chat.whatsapp.com/KPIeiQKPlZo9iV3Cq7pdr6?s=cl&p=a&iam=2" class="btn-link btn-primary" target="_blank">
                <i data-lucide="message-square"></i>
                ENTRAR NO GRUPO DE OFERTAS
            </a>

            <!-- Abre o aplicativo do WhatsApp na conversa direta -->
            <a href="https://api.whatsapp.com/send?phone=5535997169043&text=Ol%C3%A1%21%20Quero%20entrar%20no%20grupo%20de%20ofertas." class="btn-link btn-secondary" target="_blank">
                <i data-lucide="phone-call"></i>
                Falar com o Administrador
            </a>
        </div>

        <!-- Rodapé do ADM -->
        <div class="admin-footer">
            <button class="admin-toggle-btn" onclick="toggleAdmin()">Área Restrita (ADM)</button>
            <div id="adminBox" class="admin-box">
                <input type="password" id="adminPass" placeholder="Digite a senha">
                <button onclick="checkAdmin()">Acessar Painel</button>
            </div>
        </div>
    </div>

    <script>
        // Inicializar ícones Lucide
        lucide.createIcons();

        function toggleAdmin() {
            const box = document.getElementById('adminBox');
            box.style.display = box.style.display === 'block' ? 'none' : 'block';
        }

        function checkAdmin() {
            const pass = document.getElementById('adminPass').value;
            // Senha configurada: vortex2036
            if (pass === 'vortex2036') {
                alert('Acesso permitido!');
            } else {
                alert('Senha incorreta!');
            }
        }
    </script>
</body>
</html>
