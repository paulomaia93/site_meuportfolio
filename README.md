# Portfólio Profissional — Paulo Estevão Freitas Maia

Portfólio pessoal estático que reúne apresentação profissional, trajetória, competências, formação, certificados, projetos e canais de contato. A identidade visual usa tema escuro em roxo e azul, com elementos inspirados na linguagem visual da PEEXL sem substituir a identidade pessoal.

## Publicação

O endereço informado no próprio portfólio é [paulomaia93.github.io/site_meuportfolio](https://paulomaia93.github.io/site_meuportfolio/). O site está hospedado no GitHub e publicado pelo GitHub Pages, conforme informação fornecida pelo proprietário. A versão atualmente servida não foi verificada durante esta atualização do README.

O versionamento, os commits, o envio ao GitHub e a publicação são controlados manualmente por Paulo. Alterações locais neste repositório não significam que o site publicado foi atualizado.

## Seções e recursos

- **Home:** apresentação profissional, fotografia, texto de boas-vindas e acessos para projetos e contato.
- **Sobre:** resumo profissional expansível e áreas de atuação/competências.
- **Perfil:** abas para experiências, formação acadêmica, certificados e reconhecimentos.
- **Projetos:** cartões responsivos, moldura de monitor, filtros, três destaques iniciais, botão “Ver mais” e detalhes em modal com galeria.
- **Contato:** formulário Formspree e canais profissionais.
- Navegação responsiva entre Home, Sobre, Perfil, Projetos e Contato; menu para celular e botão “Voltar ao topo”.

### Projetos ativos

O `index.html` contém dez projetos. Os três primeiros destaques, nessa ordem, são:

1. Gestão Empresarial no ChatGPT
2. Destinação de Materiais Obsoletos
3. Site Institucional

Os demais projetos ativos são:

- Meu Portfólio Profissional
- Gerenciador de Tarefas
- Controle Admin. e Orçamentário
- Análise Financeira
- Estoque e Suprimentos
- Desempenho do Emprego Formal (CAGED)
- Gestão e Análise de Vagas

Os filtros organizam projetos por tipo de solução, área de aplicação e tecnologia/ferramenta. Um projeto pode corresponder a mais de um critério; com filtros ativos, a interface apresenta todos os resultados correspondentes e a contagem atualizada. Power BI e DAX são critérios distintos, e DAX avançado é descrito nos detalhes técnicos dos projetos em que está documentado.

Os detalhes dos projetos seguem uma estrutura comum: resumo, implementação técnica, ferramentas e recursos, objetivos, o que foi feito e resultados. Cada projeto mantém seus próprios conteúdos, imagens, avisos de privacidade e links aplicáveis. Os cases premiados mostram um troféu amarelo no cartão e no título do modal.

SIPOC Pecém e Logística Aeris foram retirados da lista ativa. Pastas de imagens desses cases ainda podem existir em `imagens/projetos/`, mas não são referenciadas pelos cartões atuais.

## Imagens e privacidade

Fotografia, fundos, certificados, capas e capturas usadas pelo site são arquivos locais. As capas e galerias ficam organizadas por projeto em `imagens/projetos/`. Alguns projetos usam capturas de páginas; outros usam ilustrações conceituais identificadas como ilustrativas.

Nos projetos privados, as capturas do Gerenciador de Tarefas foram desfocadas para ocultar dados pessoais. Os detalhes aplicáveis informam que os dados foram ocultados em atenção à LGPD e que o acesso aos sistemas não está disponível publicamente. Verifique as imagens e avisos antes de substituir ou adicionar arquivos.

## Tecnologias

- HTML5
- Tailwind CSS via CDN, complementado por CSS próprio
- JavaScript sem framework
- Font Awesome 6.4.0
- Google Fonts: Inter e Hanken Grotesk
- Formspree para envio do formulário de contato

O JavaScript implementa navegação, menu móvel, abas do perfil, filtros de projeto, expansão da lista, galerias, modais e envio assíncrono do formulário.

## Estrutura do repositório

```text
site_meuportfolio/
├── index.html
├── README.md
└── imagens/
    ├── certificados/
    ├── projetos/
    │   └── <pasta-do-projeto>/
    ├── caminho-sobre.png
    ├── fundo-hero.png
    └── retrato-profissional-paulo-estevao.png
```

Os arquivos e nomes efetivos em `imagens/` são a referência para a estrutura atual. Não remova pastas de imagens apenas por não aparecerem na lista ativa de projetos: elas podem ser materiais arquivados.

## Formulário de contato

O formulário envia mensagens para o endpoint Formspree configurado no HTML. O envio é assíncrono, apresenta estado de carregamento e retorno de sucesso ou erro; limpa os campos apenas após sucesso e inclui um campo honeypot contra spam.

Ao reutilizar o projeto, substitua e confira o endpoint, o e-mail, o telefone/WhatsApp e os links profissionais antes de publicar.
