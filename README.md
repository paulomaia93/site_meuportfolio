# site_meuportfolio

Link para acesso ao site: https://paulomaia93.github.io/site_meuportfolio/

Objetivo do Script

O objetivo do script JavaScript embutido no final do arquivo HTML é controlar a interatividade e o comportamento dinâmico do site, sem precisar recarregar a página. Ele melhora a experiência do usuário por meio de animações, navegação fluida, filtros, abas e modais.

Como o Script Funciona (principais funções)

Atualizar o ano no rodapé automaticamente
Insere o ano atual no rodapé usando new Date().getFullYear().
Menu responsivo (mobile)
Controla a exibição do menu em telas menores com o botão de “hambúrguer”.
Controle das Abas ("Habilidades", "Experiência", "Educação", "Certificações")
Alterna entre os conteúdos clicando nas abas, exibindo o conteúdo correspondente e escondendo os demais.
Filtro de Projetos
Permite ao usuário filtrar os projetos por categoria (como "Python", "HTML", "Power BI", etc.), mostrando apenas os relevantes.
Botão "Carregar Mais Projetos"
Exibe gradualmente mais projetos ao clicar no botão, controlando quantos são visíveis.
Botão “Voltar ao Topo”
Exibe um botão flutuante quando a página é rolada para baixo e, ao clicar, leva suavemente ao topo da página.
Formulário de Contato
Intercepta o envio do formulário e exibe uma mensagem de sucesso (sem back-end envolvido).
Scroll suave entre seções
Quando um link do menu é clicado, o scroll até a seção correspondente é feito de forma suave.
Modal de Habilidades
Ao clicar em uma habilidade, um modal (janela sobreposta) aparece com mais detalhes sobre aquela habilidade, com título, tópicos e imagem.

Tecnologias Utilizadas

HTML + CSS (TailwindCSS): estrutura e estilo do site.
JavaScript: lógica de interação e comportamento dinâmico.
Font Awesome: ícones das seções e redes sociais.
CDNs externas: para carregar bibliotecas de forma rápida.

Como Publicar seu Site no GitHub Pages

1. Crie um repositório no GitHub 
    Acesse github.com
    Clique em "New repository"
    Dê um nome ao repositório (por exemplo: meu-portfolio)
    Marque como "Public"
    Clique em "Create repository"

2. Envie os arquivos do seu site
    Você pode fazer isso de duas maneiras:

    Via navegador:
    Clique em "Add file" > "Upload files"
    Selecione os arquivos do seu site (como index.html, imagens, CSS, etc.)
    Clique em "Commit changes"

    Via Git (linha de comando):
    git clone https://github.com/seu-usuario/meu-portfolio.git
    cd meu-portfolio
    git add .
    git commit -m "Publicando site"
    git push origin main

3. Ative o GitHub Pages
    Vá até a aba "Settings" do repositório
    No menu lateral, clique em "Pages"
    Em "Source", selecione a branch main e a pasta / (root)
    Clique em "Save"

4. Acesse o site publicado
    Depois de alguns segundos, o GitHub fornecerá um link como:
    https://seu-usuario.github.io/meu-portfolio/

Observação
O arquivo principal do site deve se chamar index.html e estar diretamente na raiz do repositório, e não dentro de pastas.
