<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" /> <!-- Define a codificação de caracteres como UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1" /> <!-- Configura a visualização para dispositivos móveis -->
    <title>Divisória Ondulada Dramática</title> <!-- Título da página -->
    <style>
        /* Reset */
        *, *::before, *::after { box-sizing: border-box; } /* Define o box-sizing para todos os elementos */
        html, body { 
            margin: 0; /* Remove margens padrão */
            padding: 0; /* Remove preenchimento padrão */
            height: 100%; /* Define a altura do corpo como 100% da altura da janela */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Define a fonte da página */
            background: #fffbe6; /* Define a cor de fundo da página */
            color: #5a3300; /* Define a cor do texto */
        }

        /* Seção superior com degrade mel */
        .section-top {
            position: relative; /* Permite posicionar elementos filhos de forma absoluta */
            background: linear-gradient(180deg, #f6d365 20%, #fda085 80%, #f5a623 100%); /* Define um fundo em degradê */
            color: #5a3300; /* Cor do texto */
            padding: 6rem 1rem 0 1rem; /* Preenchimento da seção */
            text-align: center; /* Centraliza o texto */
            min-height: 450px; /* Altura mínima da seção */
            overflow: visible; /* Permite que o conteúdo transborde */
        }
        .section-top h1 {
            font-size: 3rem; /* Tamanho da fonte do título */
            font-weight: 900; /* Peso da fonte do título */
            margin-bottom: 0.6rem; /* Margem inferior do título */
            text-shadow: 1px 1px 0 rgba(255, 255, 255, 0.4); /* Sombra do texto */
        }
        .section-top p {
            font-size: 1.2rem; /* Tamanho da fonte do parágrafo */
            max-width: 600px; /* Largura máxima do parágrafo */
            margin: 0 auto 2rem; /* Margens do parágrafo */
            font-weight: 600; /* Peso da fonte do parágrafo */
            text-shadow: 1px 1px 0 rgba(255, 255, 255, 0.4); /* Sombra do texto */
        }

        /* Divisória ondulada dramática */
        .wave-divider {
            position: absolute; /* Permite posicionar a divisória em relação à seção superior */
            bottom: 0; left: 0; /* Posiciona a divisória na parte inferior esquerda */
            width: 100%; /* Largura total da divisória */
            height: 220px; /* Altura da divisória */
            overflow: visible; /* Permite que o conteúdo transborde */
            line-height: 0; /* Remove a altura da linha */
        }
        .wave-divider svg {
            display: block; /* Exibe o SVG como um bloco */
            width: 100%; /* Largura total do SVG */
            height: 220px; /* Altura do SVG */
        }
        .wave-path {
            fill: url(#gradiente-honey); /* Preenche a forma com o gradiente definido */
        }

        /* Seção inferior com cor clara */
        .section-bottom {
            background-color: #fff5e6; /* Cor de fundo da seção inferior */
            color: #886d00; /* Cor do texto da seção inferior */
            padding: 4rem 1rem 6rem; /* Preenchimento da seção inferior */
            text-align: center; /* Centraliza o texto */
            font-weight: 600; /* Peso da fonte da seção inferior */
            min-height: 350px; /* Altura mínima da seção inferior */
        }
        .section-bottom h2 {
            font-weight: 800; /* Peso da fonte do título da seção inferior */
            font-size: 2.25rem; /* Tamanho da fonte do título da seção inferior */
            margin-bottom: 1rem; /* Margem inferior do título da seção inferior */
        }
        .section-bottom p {
            max-width: 600px; /* Largura máxima do parágrafo da seção inferior */
            margin: 0 auto; /* Centraliza o parágrafo */
            font-size: 1.15rem; /* Tamanho da fonte do parágrafo da seção inferior */
            line-height: 1.6; /* Altura da linha do parágrafo */
        }
    </style>
</head>
<body>
    <section class="section-top" aria-label="Seção superior com fundo em degrade mel">
        <h1>Mel Caindo</h1> <!-- Título da seção superior -->
        <p>Divisória ondulada com curvas dramáticas e marcantes para uma transição visual impactante.</p> <!-- Descrição da seção superior -->
        <div class="wave-divider" aria-hidden="true"> <!-- Divisória ondulada -->
            <svg viewBox="0 0 1440 220" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Divisória ondulada dramática mel">
                <defs>
                    <linearGradient id="gradiente-honey" x1="0" y1="0" x2="0" y2="1"> <!-- Definição do gradiente -->
                        <stop offset="0%" stop-color="#f7d976"/> <!-- Cor inicial do gradiente -->
                        <stop offset="50%" stop-color="#f5a623"/> <!-- Cor intermediária do gradiente -->
                        <stop offset="100%" stop-color="#fff5e6"/> <!-- Cor final do gradiente -->
                    </linearGradient>
                </defs>
                <path class="wave-path" d="M0,120 C 200,300 600,0 1440,120 L1440,220 L0,220 Z" /> <!-- Caminho da ondulação -->
            </svg>
        </div>
    </section>
    <section class="section-bottom" aria-label="Seção inferior com fundo claro">
        <h2>Seção Inferior com Cor Clara</h2> <!-- Título da seção inferior -->
        <p>Seção inferior com fundo suave contrastando com o tom quente da seção superior, separadas pela divisória ondulada dramática.</p> <!-- Descrição da seção inferior -->
    </section>
</body>
</html>

