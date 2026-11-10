🏁 Desafio Pit Wall — GP de São Paulo de F1

Um projeto prático de front-end desenvolvido para a disciplina de Linguagem de Marcação (LIMA), focado no treino intensivo de HTML5 e CSS3 responsivo.

Professores: André Denani e Raul Lopes

Tema: Página do GP de São Paulo de Fórmula 1

📌 Sobre o Projeto

O Desafio Pit Wall consiste em reproduzir a landing page oficial do GP de São Paulo de F1 utilizando exclusivamente HTML e CSS (sem JavaScript). O objetivo é aplicar conceitos de estruturação de layouts modernos, estilização avançada com variáveis CSS, gradients, tabelas estilizadas, formulários e responsividade completa para dispositivos móveis.

🧰 Tecnologias e Conceitos Utilizados

HTML5: Tags semânticas (<header>, <main>, <section>, <table>, <form>, <footer>).

CSS3 Moderno:

Variáveis CSS (:root e var()): Gerenciamento da paleta de cores (preto, vermelho F1, cinza e cores das equipes).

Flexbox: Alinhamento do topo (topbar), links do menu e cartões numéricos do hero.

CSS Grid (grid-template-columns, auto-fit): Grid responsivo dos cards dos pilotos e leiaute em 2 colunas do formulário.

Gradients Avançados:

linear-gradient com corte seco para a faixa inclinada no Hero.

repeating-linear-gradient para criar a zebra (kerb) da pista.

Sobreposição de Imagem com CSS: background com múltiplas camadas (degradê + imagem url()).

Efeitos de Hover e Transição: Interatividade visual nos links, cards e linhas da tabela.

Responsividade (@media queries): Adaptação completa da página para telas de smartphones (até 768px).

Typography: Importação da fonte Titillium Web via Google Fonts.

📁 Estrutura do Projeto

pit-wall/
├── index.html        # Estrutura semântica da página
├── styles.css        # Estilos, variáveis e responsividade
└── img/
    └── piloto.jpg    # Imagem de fundo da seção Hero


📐 Estrutura de Seções da Página

Header (header.topbar): Logo estilizado, menu de navegação e botão de chamada para ação (CTA).

Hero (section.hero + div.kerb): Título gigante em itálico, estatísticas do circuito, faixa decorativa vermelha inclinada com foto de fundo e zebra da pista.

Grid de Pilotos (section#pilotos): Cards dos pilotos organizados em CSS Grid, utilizando bordas superiores dinâmicas baseadas na cor da equipe (--team) e números em marca d'água (opacity).

Classificação (section#classificacao): Filtros de busca e tabela de classificação estilizada no formato de transmissão de TV.

Ingressos (section#ingressos): Seção dividida em duas colunas (tabela de preços e formulário completo para reserva de ingressos).

Rodapé (footer): Créditos e avisos legais centralizados.

🚀 Desafios Extras (Opcional)

[ ] Adicionar um 5º piloto com uma nova equipe e cor customizada no CSS.

[ ] Alterar as variáveis do :root para criar um tema visual alternativo.

[ ] Experimentar diferentes ângulos na faixa inclinada da seção Hero.

🔧 Como Executar o Projeto

Clone ou baixe este repositório:

git clone https://github.com/seu-usuario/pit-wall.git


Abra a pasta pit-wall no seu editor de código (ex: VS Code).

Abra o arquivo index.html diretamente no seu navegador de preferência ou utilize a extensão Live Server.

📄 Licença e Créditos

Projeto desenvolvido para fins educacionais.

Foto de fundo por Jonathan Borba no Pexels.

Marcas e nomes citados são meramente ilustrativos.
