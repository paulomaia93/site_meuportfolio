# Portfólio Profissional

Portfólio pessoal de Paulo Estevão Maia, desenvolvido como uma landing page estática em `HTML`, `Tailwind CSS` e `JavaScript`, com foco em apresentação profissional, projetos, competências e canais de contato.

Site publicado em:
[https://paulomaia93.github.io/site_meuportfolio/](https://paulomaia93.github.io/site_meuportfolio/)

## Visão Geral

O projeto foi construído para funcionar como uma vitrine profissional de uma página só, com navegação fluida e conteúdo organizado para recrutadores, clientes e oportunidades da área de dados, BI, automação e desenvolvimento.

Atualmente, o site inclui:

- hero com apresentação profissional, CTAs e links rápidos
- seção `Sobre Mim` com resumo expansível e bloco de entregas
- seção `Perfil Profissional` com abas para experiências, formações e certificados
- seção de projetos com filtros por tecnologia, três cards iniciais e botão `Ver mais` para os demais; inclui oito cases de dados da PEEXL, o site institucional, um gerenciador de tarefas, a solução de gestão empresarial com IA e o portfólio pessoal
- formulário de contato integrado ao `Formspree`
- bloco lateral com e-mail, WhatsApp, LinkedIn, GitHub e localização

## Principais Funcionalidades

- navegação suave entre seções
- destaque automático do item ativo na navbar
- menu mobile com animação de abertura e fechamento
- tooltips em botões e ícones da hero
- tooltip na foto do hero com atraso de exibição
- resumo profissional com botão `Ler mais`
- abas com transição suave no bloco `Perfil Profissional`
- rolagem interna automática em abas longas do perfil
- filtros de projeto por categoria/stack
- detalhes dos cases da PEEXL em janela acessível, sem imagens nesta etapa
- botão `Voltar ao topo`
- formulário com envio assíncrono, loading, validação leve e feedback inline de sucesso/erro

## Stack Utilizada

- `HTML5`
- `Tailwind CSS` via CDN
- `JavaScript` puro
- `Font Awesome`
- `Google Fonts`
- `Formspree` para o formulário de contato

## Estrutura do Projeto

```text
site_meuportfolio/
|-- index.html
|-- README.md
|-- README.legacy.md
|-- Imagens.txt
```

## Formulário de Contato

O formulário envia mensagens para o endpoint do Formspree configurado em:

```html
https://formspree.io/f/xanordvg
```

Comportamento atual:

- envio por `fetch`, sem recarregar a página
- botão com estado `Enviando...`
- mensagem inline de sucesso ou erro
- limpeza do formulário apenas em caso de sucesso
- preservação dos dados digitados em caso de falha
- honeypot `_gotcha` para reduzir spam

Se você for clonar esse projeto para uso próprio, lembre de trocar:

- endpoint do Formspree
- e-mail exibido
- telefone/WhatsApp
- LinkedIn
- GitHub

## Como Executar Localmente

Como o projeto é estático, basta abrir o arquivo `index.html` no navegador.

Se preferir servir localmente por um servidor simples, você pode usar, por exemplo:

```powershell
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Publicação no GitHub Pages

O site pode ser publicado diretamente no GitHub Pages porque depende apenas de arquivos estáticos.

Passos básicos:

1. subir o repositório para o GitHub
2. garantir que o arquivo principal esteja na raiz com o nome `index.html`
3. ativar `Settings > Pages`
4. selecionar a branch principal e a pasta `/root`

Após a publicação, o GitHub gera uma URL no formato:

```text
https://seu-usuario.github.io/seu-repositorio/
```

## Observações

- a estrutura, os dados e a apresentação dos doze projetos estão em `index.html`
- o gerenciador de tarefas não apresenta link para o código privado
- várias imagens são carregadas por links externos
- as 23 imagens dos cases da PEEXL foram organizadas em oito subpastas de `C:\Users\paulo\Downloads\Projetos PEEXL - Portfolio Paulo 2026-10-30`, fora do site; o conteúdo é uma cópia da versão local do site institucional
