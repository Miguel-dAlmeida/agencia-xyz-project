# __Módulo DevQuest - Projeto Agência XYZ__

## __Sumário__

- [Apresentação](#apresentação)
- [Explicação do Projeto](#explicação-do-projeto)
- [Gif e URL da Página](#gif-e-url-da-página)
- [Ferramentas e Tecnologias Utilizadas](#ferramentas-e-tecnologias-utilizadas)
- [Principais Recursos e Abordagens](#principais-recursos-e-abordagens)
- [Aprendizado Adquirido](#aprendizado-adquirido)
- [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Agradecimentos e Conclusão](#agradecimentos-e-conclusão)

## __Apresentação__
Muito prazer, meu nome é Mário Miguel, e eu sou um aspirante a Desenvolvedor Web. Este projeto faz parte da minha jornada no curso de Formação de Desenvolvedor Web Fullstack _(DevQuest - Dev em Dobro)_. O projeto __Agência XYZ__ integra o módulo __*"Projeto Landing Page com Flex e Grid"*__. É importante destacar que o layout não foi desenvolvido exclusivamente por mim. 

Neste módulo, o foco foi aprender todo o processo de criação de uma Landing Page do zero, trabalhando de forma guiada junto ao professor. Assim, embora eu tenha participado ativamente do desenvolvimento, codificando em conjunto, este projeto não se trata de um exercício ou desafio prático individual.

## __Explicação do Projeto__

Este projeto se trata de uma Landing Page desenvolvida para uma agência fictícia chamada "Agência XYZ". A página é composta por seções bem definidas: __About__ (Sobre), __Services__ (Serviços), __Projects__ (Projetos) e __Contact__ (Contato).

O design se destaca por ser moderno, visualmente atraente e composto por imagens de alta qualidade e cores vibrantes que amplificam a experiência do usuário.

Outro ponto relevante é a responsividade da página. Todo o layout foi cuidadosamente ajustado para funcionar de maneira fluida em diferentes dispositivos, desde desktops até smartphones. Um exemplo disso é a transição do menu principal, que, em telas menores (como celulares), é substituído por um menu __*"Hambúrguer"*__ funcional, exibido apenas após a interação do usuário.

## __Gif e URL da Página__
<div>
  <img src="./src/images/gif_pagina_agenciaxyz.gif" alt="Gif do resultado final da página" >
</div>

### [GitHub Pages](https://miguel-dalmeida.github.io/agencia-xyz-project/) 


## __Ferramentas e Tecnologias Utilizadas__
<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Markdown" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/markdown/markdown-original.svg" />
</div>

## __Principais Recursos e Abordagens__

- **Tags semânticas**: Utilização de tags _HTML5_ semânticas como `<header>`, `<footer>`, `<section>`, entre outras, para garantir uma melhor estruturação do conteúdo e facilitar a acessibilidade e a indexação por mecanismos de busca.
- **Div's estilizatórias**: Uso de `<div>` como contêineres para organizar e estruturar o layout da página, proporcionando maior facilidade na aplicação de estilos com _CSS_ (principalmente no que diz respeito ao posicionamento dos elementos).
- **Desktop First**: A abordagem inicial foi a criação do layout com foco em dispositivos desktop, seguido de ajustes para telas menores utilizando media queries.
- **Unidade de medida relativa (rem)**: Garantia de escabilidade dentro do projeto (com essa abordagem, um ponto de alteração reflete em toda a página)
- **CSS Grid**: Utilização de _CSS Grid_ para estruturar o layout da página, permitindo um controle preciso sobre o posicionamento de elementos (formato de grade).
- **CSS Flexbox**: Aplicação do _Flexbox_ para a disposição e alinhamento de elementos, especialmente em áreas como o menu e o footer.
- **Propriedade `background`**: Implementação de imagens de fundo altamente personalizáveis.
- **Propriedades `animation` e `transition`**: Uso de animações e transições CSS para dar dinamismo ao layout, com destaque para o efeito de movimentação da seta no cabeçalho e a interação com os links do menu.
- **Media Queries**: Aplicação de media queries para garantir que o layout se adapte adequadamente a diferentes tamanhos de tela.
- **Pseudo-classes e Pseudo-elementos**: Utilização de pseudo-classes como `:hover` e pseudo-elementos como `::before` e `::after`.
- **Prefixo `-webkit-`**: Inclusão de prefixos como `-webkit-` em propriedades CSS para garantir compatibilidade com versões antigas de navegadores como o Safari e navegadores Android desatualizados.
- **Menu "Hambúrguer"**: Implementação de um menu "hambúrguer" para telas de smartphones e dispositivos móveis.
- **Ícones do FontAwesome**: Importação de ícones do FontAwesome.
- **Fontes do Google Fonts**: Inclusão de fontes do Google Fonts, como a fonte _Roboto_.
- **Resets CSS**: O uso de um arquivo de _Reset CSS_ para normalizar a aparência dos elementos.

## __Aprendizado Adquirido__

### **Novos Conhecimentos**
Durante o desenvolvimento deste projeto, adquiri diversos conhecimentos técnicos. Os tópicos explorados foram:

- **Propriedade outline**: Aprendi que a propriedade _CSS_ `outline` adiciona um contorno ao redor de elementos sem afetar o layout (_"bordas flutuantes"_), muito utilizada para destacar elementos como inputs em foco.  
- **Codificação do Menu Hambúrguer**: Um tipo de menu super condizente com celulares e tablets. 
- **Seletor ~ (irmão geral)**: Entendi como selecionar elementos subsequentes de um mesmo nível hierárquico.  
- **Dois Métodos de Criação via CSS**: Comparei abordagens distintas para criar elementos com `content`, uma usando conteúdo explícito e outra combinando com `background`.  
- **Prefixo "webkit-" em CSS3**: Estudei o uso de prefixos como `-webkit-`, necessários para compatibilidade com navegadores antigos.  
- **Prefixos -moz-, -o- e -ms-**: Explorei as variações específicas de navegadores como Firefox, Opera e Internet Explorer para garantir suporte multiplataforma.
- **Guia Completo: Propriedade animation**: Aprendi a criar animações fluidas, como a seta animada na seção _Hero_, utilizando a propriedade `animation`.  
- **Imagens com `<img>` ou `background`**: Compreendi quando utilizar imagens no conteúdo ou como plano de fundo, baseando-se na necessidade do layout e na semântica da página.  
- **Subordinação de Elementos no Grid**: Aprofundei no comportamento de elementos filhos em layouts baseados em CSS Grid.  
- **Navegação “Índice”**: Aprendi a criar uma navegação entre as principais seções do site, melhorando a experiência do usuário.

### **Revisão e Consolidação**
Além dos novos aprendizados, também reforcei conteúdos já aprendidos, de modo a fixá-los melhor. Abaixo, cito os conceitos revisitados:

- **Guia Completo: Propriedade transition**: Reforcei o uso de `transition`. 
- **Propriedade z-index**: Consolidei o conhecimento sobre camadas e o controle de sobreposição no layout.  
- **Interação de `<input>` e `<label>`**: Revi como podemos "linkar" essas tag's (via atributos `id` e `for` com valores idênticos)
- **Pseudo-elementos ::before e ::after**: Aprofundei no uso de pseudo-elementos para criar conteúdo sem alterar o HTML.  
- **Relembrando VW e VH**: Revisitei o uso de unidades de medida relativas à viewport.
- **Estilização de Backgrounds**: Reforcei a aplicação de propriedades como `background-image`, `background-size` e `background-position`.  
- **Alinhamento com margin e auto**: Sanei dúvidas e aprofundei meu entendimento acerca do uso de `margin: auto` para centralizar elementos horizontalmente.  
- **Tipos de Caixas**: Revisei os comportamentos dos modelos de caixa CSS, como `inline`, `block` e `inline-block`.  
- **Propriedade text-align**: Estudei novamente o funcionamento de `text-align: center` para alinhamento horizontal, pois senti que não tinha esse conceito 100% apurado.

### Acesse abaixo a página do Notion com as anotações dos aprendizados obtidos neste múdulo:
[__Notion - Anotações do Módulo Projeto Landing Page com Flex e Grid__](https://gigantic-chef-a6f.notion.site/M-dulo-Projeto-Landing-Page-com-Grid-e-Flex-16ccd10b93ab807ca781e09786ba3535)

## __Desenvolvimento Contínuo__

Com o término deste módulo (_"Projeto Landing Page com Flex e Grid"_), já estou pronto para avançar para o próximo desafio: o __*Quest HTML + CSS Avançado*__. Esse módulo traz uma proposta diferente, pois se trata de um desafio prático. Meu objetivo será recriar, por conta própria, o projeto **"Página de Destino do Huddle com uma Única Seção Introdutória"**, disponível no Frontend Mentor.

A ideia é aplicar tudo o que aprendi até agora sobre _HTML_ e _CSS_ para desenvolver a página, e, ao final, comparar meu código com a solução fornecida pelo curso.

Estou animado para essa experiência, já que será uma ótima chance de testar na prática os conhecimentos que aprendi até agora. No fim das contas, tenho para mim que o aprendizado de programação realmente se consolida quando colocamos a _"mão na massa"_. 

## __Agradecimentos e Conclusão__

É muito gratificante saber que você chegou até aqui. Meu sincero agradecimento por dedicar seu tempo a explorar este projeto e acompanhar minha jornada por meio deste diário técnico. Este projeto representou uma excelente oportunidade para aprender novos conceitos, técnicas e, ao mesmo tempo, revisar e aprimorar habilidades que já faziam parte do meu repertório.  

Esses aprendizados certamente terão um impacto positivo nos meus futuros projetos, facilitando o processo de desenvolvimento. Sei que ainda há muito a explorar e aperfeiçoar, mas cada passo concluído me aproxima do meu objetivo: __conquistar uma vaga como desenvolvedor web júnior e trilhar meu caminho rumo à excelência na programação.__  

  <div style="margin-bottom: 20px;">
    <a style="padding-right: 3px;" href="https://www.linkedin.com/in/mariomigueldealmeida/" target="_blank"><img
        src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"
        target="_blank"></a>
    <a href="mailto:mariomigueldealmeida@gmail.com"><img
        src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"
        target="_blank"></a>
  </div>

<div>
  <img src="https://i.imgur.com/kwfpJJn.gif" alt="Imagem representando união e parceria" width="100%">
</div>