Descrição do Projeto:

Este projeto é uma página web evoluída que combina funcionalidades modernas, como animações e interações dinâmicas, utilizando as tecnologias HTML5, Tailwind CSS e Alpine.js. A página é responsiva e amigável para dispositivos móveis, proporcionando uma experiência de navegação fluida e visualmente atraente. A estrutura da página é dividida em seções principais: Home, Sobre e Contato, cada uma com características e funcionalidades específicas.

Estrutura do Projeto:

Cabeçalho (Header)

O cabeçalho da página possui um fundo roxo (classe bg-purple-700), com texto branco (text-white). Ele contém uma barra de navegação com links para as seções Home, Sobre e Contato, estilizados com transições de cor ao passar o mouse (hover:text-purple-300 transition).
Seção Home

Bem-vindo: Uma mensagem de boas-vindas com texto grande e chamativo.
Carrossel de Imagens: Um carrossel de imagens implementado com Alpine.js, permitindo transições suaves entre imagens.
Seção Sobre

Informações sobre os serviços oferecidos na página, dispostos em um layout de grade (grid grid-cols-1 sm:grid-cols-2 gap-6), com cartões estilizados que ganham sombra ao passar o mouse (hover:shadow-lg transition-shadow).
Seção Contato

Formulário de Contato: Um formulário simples e funcional para que os visitantes possam enviar mensagens. Inclui campos para nome, email e mensagem, todos estilizados com bordas arredondadas e foco em anel roxo (focus:ring-2 focus:ring-purple-500 transition).
Rodapé (Footer)

Contém direitos autorais e links para redes sociais, estilizados com transições de cor (hover:text-purple-300 transition).
JavaScript para Animações

Usa Intersection Observer API para adicionar animações de rolagem, aplicando a classe animate__fadeIn quando as seções entram em visão.
Tecnologias Utilizadas
HTML5: Estrutura semântica da página.
Tailwind CSS: Estilização rápida e eficiente com classes utilitárias.
Alpine.js: Interatividade e manipulação do DOM com um pequeno framework JavaScript.
JavaScript Puro: Para adicionar animações de rolagem
