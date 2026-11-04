Expatriados de Sofá: A Solidão e o Trabalho Remoto Internacional

Atividade Prática Avaliativa: Front-End & Copilotagem com IA

Tema Central: O Futuro do Trabalho e as Características Socioemocionais da Geração Atual

Docente Responsável: Prof. Diego Marques de Carvalho

Curso: Análise e Desenvolvimento de Sistemas (ADS)

📌 1. Visão Geral e Proposta do Projeto

O Expatriados de Sofá é uma plataforma web informativa e interativa desenvolvida para investigar o impacto psicológico e socioemocional do trabalho remoto internacional em jovens desenvolvedores brasileiros (Geração Z).

Embora o modelo de trabalho assíncrono e transfronteiriço traga atrativos como remuneração em moeda forte (dólar/euro) e flexibilidade geográfica, ele também impõe custos silenciosos: a perda de ancoragem comunitária, a dissolução das fronteiras entre vida pessoal e profissional (culture always-on) e a exposição a índices elevados de solidão digital.

🔗 Deploy e Produção

Live Demo (GitHub Pages): https://rrenatodevs.github.io/Projeto-em-Dupla/

📂 2. Estrutura de Arquivos e Diretórios

Projeto-em-Dupla/
├── index.html            # Página inicial (Hero, Dados Estatísticos, Quiz e Gráfico)
├── transparencia.html    # Detalhamento de fontes, metodologia e limites dos dados
├── contato.html          # Formulário acadêmico e perfis dos desenvolvedores
├── css/
│   └── style.css         # Design System autoral (Variáveis, Grid, Dark Mode)
├── js/
│   └── app.js            # Lógica JS Vanilla (Chart.js, Quiz, LocalStorage, DOM)
├── img/                  # Assets visuais e ícones da aplicação
├── AUDITORIA_IA.md       # Dossiê crítico de copilotagem e engenharia de prompts
└── README.md             # Documentação técnica oficial do repositório


🛠️ 3. Arquitetura de Software e Contratos de Dados

A aplicação segue uma arquitetura SPA parcial com páginas estáticas interligadas, desacoplando rigorosamente a camada de estrutura (HTML5 Semântico), estilização (CSS3 autoral com variáveis no :root) e comportamento dinâmico (JavaScript Vanilla).

Esquema de Dados do Quiz (Simulador de Sobrecarga Cognitiva)

A lógica da autoavaliação processa os dados de entrada do usuário através de um objeto estático de diagnósticos:

{
  "pontuacaoTotal": "number (intervalo de 3 a 9)",
  "categorias": {
    "saudavel": { "min": 8, "classe": "resultado-bom", "titulo": "Equilíbrio saudável 🌱" },
    "alerta": { "min": 5, "classe": "resultado-medio", "titulo": "Alerta de isolamento médio ⚠️" },
    "risco": { "min": 0, "classe": "resultado-risco", "titulo": "Perfil: expatriado de sofá em risco 🚨" }
  }
}


Dataset de Visualização de Dados (Chart.js)

{
  "labels": ["100% Remoto", "Híbrido", "Presencial"],
  "metric": "Percentual de trabalhadores que relatam solidão diária",
  "data": [25, 21, 16],
  "source": "Gallup (2024)"
}


📦 4. Declaração de Dependências e CDN

A aplicação consome apenas dependências consolidadas via CDN para garantir rápida taxa de carregamento (LCP) e suporte cross-browser:

Dependência

Versão / CDN

Justificativa Técnica

Bootstrap

v5.0.2 (CSS & JS Bundle)

Sistema de layout responsivo (grid 12 colunas) e acessibilidade de menus colapsáveis.

Chart.js

v4.4.3 (UMD)

Biblioteca leve e responsiva para renderização de gráficos dinâmicos via <canvas>.

Google Fonts

Montserrat (400, 500, 600, 700, 800)

Padronização tipográfica limpa para legibilidade e identidade visual moderna.

🤝 5. Matriz de Colaboração e Commits Semânticos

O desenvolvimento foi distribuído equitativamente entre os dois colaboradores, utilizando o padrão Conventional Commits:

feat: para inclusão de novas páginas, componentes interativos e gráficos.

style: para estilização de temas, design system CSS e ajustes responsivos.

fix: para correções de bugs em JavaScript ou validações de acessibilidade.

docs: para atualização do README.md e do logbook AUDITORIA_IA.md.

Tabela de Divisão de Responsabilidades

Contribuidor

Módulo / Escopo Principal

Renato (@rrenatodevs)

Arquitetura HTML5, Design System (style.css), integração do Bootstrap.

Alexsander (@alexsander1997ribeiro)

Desenvolvimento da lógica em JavaScript (app.js), integrações com Chart.js e documentação.

📚 6. Referências Bibliográficas

Gallup (2024). State of the Global Workplace Report 2024. Disponível em: gallup.com.

Organização Mundial da Saúde - OMS (2025). Commission on Social Connection. Disponível em: who.int.

Buffer (2023). State of Remote Work 2023. Disponível em: buffer.com.

Husky / Diário do Comércio (2024). Perfil do Trabalhador Remoto Brasileiro para o Exterior. Disponível em: diariodocomercio.com.br.
