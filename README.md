# PROJETO

## 💡 Processo de Ideação
Na área da Publicidade e Propaganda, as ideias precisam de uma vitrine, pois seus designs são seus produtos. Este projeto surge como resposta a essa necessidade, fazendo um espaço digital exclusivo para uma profissional da área. O site foi idealizado para ser o principal palco de suas criações, facilitando o compartilhamento de seu esforço e visão criativa com o mercado.

## 📌 Título do Projeto
Portifólio profissional.

## 👥 Integrantes do Grupo
- Guilherme Miyamoto Bragatto(10736124)
- Pedro Henrique Lopes Sabainsk (10735777)
- Joaquim Marcondes (10736261)
  
## 📝 Proposta Sintetizada do Projeto 
Desenvolver uma plataforma digital para consolidar a marca pessoal de uma publicitária, apresentando sua identidade, competências e portfólio de maneira profissional.

## 🖼️ Protótipo Inicial
Imagens do check-in 2
<div align="left">
  <img src="./Imagens/imagem_home.png" height="160em" alt="Imagem home" />
  <img src="./Imagens/imagem_pagina_meuportifolio.png" height="160em" alt="Imagem meu portifólio" />
  <img src="./Imagens/imagem_umapagina_projeto.png" height="160em" alt="Imagem de uma página de produtos" />
  <img src="./Imagens/imagem_contato.png" height="160em" alt="Imagem página de entre em contato" />
</div>

## 🌍 Caráter Extensionista
Pois o projeto entra como solução que atende a uma necessidade real e imediata da comunidade: o desenvolvimento de um portfólio digital para a irmã de um dos integrantes, impactando diretamente sua carreira e capacidade de divulgação profissional.

## 🤝 Colaborador Externo  
- Representante: Beatriz Miyamoto Bragatto (Profissional no mercado de publicidade e propaganda)

## 💻 Explicação do Código (Tutorial)
Tecnologias Utilizadas
- HTML5: Utilizado para a estruturação semântica de todo o conteúdo, garantindo acessibilidade e otimização.
- CSS3: Responsável por toda a estilização visual, interatividade via pseudo-classes e responsividade.
- JavaScript: (A SER IMPLEMENTADO).

Explicações do Código
- Página Inicial (index.html): O layout central foi criado com CSS Grid (display: grid), dividindo a seção em duas colunas (imagem e texto). O destaque visual da foto é um efeito de "brilho neon", usando a propriedade box-shadow, que aplica múltiplas camadas de sombra para simular a luz.
- Página de Portfólio (portifolio.html): A galeria de projetos é a parte de maior importância desta página. Ela foi construída com CSS Grid Layout, usando grid-template-columns: repeat(3, 1fr) para criar uma grade responsiva. A interatividade acontece por conta do efeito de :hover nos cards, que usa o transition para suavizar a mudança de cor da borda e o aparecimento de um box-shadow, destacando o projeto selecionado.
- Páginas de Projeto (projetoX.html): Para o detalhamento de cada projeto, o layout de duas colunas (imagem e descrição) foi feito com CSS Flexbox (display: flex). Usada para alinhar itens em um único eixo. A linha decorativa abaixo do título utiliza a tag (hr) estilizada com box-shadow para replicar o efeito neon da identidade visual.
- Página de Contato (contato.html): O formulário e a seção "Sobre" são colocados lado a lado com Flexbox. A usabilidade do usuário no formulário é aprimorada com a pseudoclasse :focus, que muda a borda e adiciona um brilho ao campo selecionado, para melhor visualização do usuário.
- Responsividade: O site é adaptável a dispositivos móveis através de Media Queries (@media), adaptamos para 3 tipos de tela(600px,768px e 900px). Conforme a largura da tela diminui, a grade de projetos se ajusta de 3 para 2 e depois 1 coluna. Da mesma forma, os layouts Flexbox mudam sua direção de row para column, empilhando os elementos para melhor visualização dependendo do dispositivo.

Conclusão e Aprendizados Adquiridos


