# TAREFA IA26 WEBDESIGN

Esta disciplina tem como foco principal o aprendizado de técnicas e práticas de web design, com ênfase nas linguagens de marcação (HTML), de estilo (CSS) e, de forma introdutória, na linguagem de programação (JavaScript). Ao longo do curso, os estudantes são introduzidos aos conceitos fundamentais que permitem a construção de páginas web estruturadas, organizadas e visualmente agradáveis.

O principal objetivo é capacitar os alunos a criar e estilizar páginas web, compreendendo desde a estrutura básica do conteúdo até a sua apresentação visual. Dessa forma, a disciplina abre caminho para o desenvolvimento de sites e aplicações web mais complexas, que são amplamente utilizadas no mercado de trabalho atual.

Por se tratar de uma disciplina introdutória, ela é projetada para ser acessível a iniciantes, não exigindo conhecimentos prévios em programação ou desenvolvimento web. Mesmo assim, ela desempenha um papel fundamental na formação de futuros profissionais da área, pois estabelece as bases essenciais para a construção de interfaces web modernas.

Além disso, o curso contribui para a compreensão de princípios importantes de design e usabilidade na web, como organização de conteúdo, hierarquia visual, experiência do usuário e boas práticas de desenvolvimento. Esses conhecimentos são indispensáveis para qualquer pessoa que deseja seguir carreira na área de tecnologia e desenvolvimento web.

## Antes do início

- É desejável que os alunos tenham um ambiente de desenvolvimento configurado em suas máquinas, incluindo um editor de código e um navegador web atualizado. Nesta disciplina, utilizaremos o Visual Studio Code como editor de código, por ser gratuito, leve, altamente personalizável e um dos mais utilizados no mercado de desenvolvimento web. Já como navegador web, será utilizado o Google Chrome, devido à sua ampla compatibilidade com tecnologias modernas, ferramentas de desenvolvimento integradas e também por ser um dos navegadores mais populares entre desenvolvedores.

- Ter esse ambiente configurado corretamente é fundamental para garantir uma melhor experiência de aprendizado, permitindo que os alunos escrevam, testem e visualizem seus códigos de forma prática e eficiente durante as atividades da disciplina.


## HTML - HyperText Markup Language (Linguagem de Marcação de Hipertexto)

Como o nome sugere, HTML não é uma linguagem de programação, mas sim uma linguagem de **marcação**. Ele é usado para estruturar o conteúdo de uma página web (como sites); isso comumente é interpretado como uma estrutura visual. No entanto, o HTML é responsável por organizar o conteúdo de uma página web para que possa ser consumido por **todos os tipos de usuários** (incluindo aqueles com deficiências). Portanto, a estrutura do HTML é fundamental para a acessibilidade e usabilidade de um site. O HTML é composto por uma série de elementos, cada um representado por uma tag (etiqueta) que define o tipo de conteúdo e sua função na página. Por exemplo, `<h1>` é usado para títulos principais, aumentando respectivamente conforme os paragrafos seguintes, podendo ter um `<h2>`, `<h3>` e etc.   `<p>` para parágrafos, `<a>` para links, entre outros. O HTML também permite a inclusão de atributos nas tags para fornecer informações adicionais sobre os elementos, como `class`, `id`, `src`, etc.

Antes de seguirmos, imagine um editor de texto como o Microsoft Word ou o Google Docs. Em editores como estes, você costuma selecionar um trecho de texto e aplicar uma formatação, como negrito, itálico ou sublinhado. O HTML é a linguagem que permite marcar o trecho selecionado com uma tag (etiqueta) que indica a formatação desejada, sendo que a sintaxe do HTML é composta por tags (etiquetas) de abertura e fechamento, onde a etiqueta de abertura é escrita entre colchetes angulares `< >` e a etiqueta de fechamento é escrita da mesma forma, mas com uma barra `/` antes do nome da tag. Por exemplo, para criar um parágrafo em HTML, você usaria a tag `<p>` para abrir o parágrafo e `</p>` para fechá-lo. O conteúdo do parágrafo seria colocado entre essas duas tags.


![Animação de seleção](docs/select.gif)

>Na animação acima, o usuário escreve em um editor a frase `lorem ipsum dolor sit amet potentia` e, então, executa algumas seleções de definição de formatação. A seguir, veremos, passo a passo, o equivalente em HTML para cada uma dessas seleções/formatações.

1. O usuário seleciona `lorem ipsum` e aplica a formatação de negrito.
  - Em HTML, o código correspondente seria `<strong>lorem ipsum</strong> dolor sit amet potentia`, onde a tag `<strong>` é usada para indicar que o texto deve ser exibido em negrito. No exemplo, a marcação começa com a tag `<strong>` e termina com a tag de fechamento que vimos antes: `</strong>`, indicando que o texto entre essas duas tags deve ser exibido em negrito.


  2. O usuário seleciona `sit amet` e aplica a formatação de itálico.
  - Em HTML, o código correspondente seria `<strong>lorem ipsum</strong> dolor <em>sit amet</em> potentia`, onde a tag `<em>` é usada para indicar que o texto deve ser exibido em itálico. No exemplo, a marcação começa com a tag `<em>` e termina com a tag de fechamento `</em>`, indicando que o texto entre essas duas tags deve ser exibido em itálico.


  3. O usuário seleciona `ipsum dolor sit` e aplica a cor vermelha.
  - Em HTML, o código correspondente seria `<strong>lorem <span style="color: red;">ipsum dolor sit</span></strong> amet <em>sit amet</em> potentia`, onde a tag `<span>` é usada para aplicar estilos específicos a um trecho de texto, e o atributo `style` é usado para definir a cor do texto como vermelha. No exemplo, a marcação com a tag `<span>` começa antes de 
  `ipsum` e termina após `sit`, indicando que o texto entre essas tags deve ser exibido em vermelho.




> **⚠️ Nota:**
>
> O HTML é uma linguagem de marcação, e seu principal objetivo é estruturar o conteúdo de uma página web. Caso pesquise na internet, notará que existem outras tags para aplicar formatações como negrito e itálico, como `<b>` e `<i>`, respectivamente. No entanto, as tags `<strong>` e `<em>` são consideradas mais semânticas, pois indicam a importância do texto, enquanto as tags `<b>` e `<i>` são puramente de formatação visual. Portanto, é recomendado usar as tags semânticas para melhorar a acessibilidade e a compreensão do conteúdo.
>
> `<strong>` e `<em>` fazem sentido tanto para leitores sem deficiência quanto para leitores com deficiência, pois indicam a importância do texto, enquanto `<b>` e `<i>` são puramente de formatação visual e podem não ser interpretados corretamente por leitores de tela ou outros dispositivos assistivos.



Esta é apenas a sintaxe básica do HTML, mas é importante lembrar que existem muitas outras tags e atributos que podem ser utilizados para construir páginas web muito mais completas, dinâmicas e interativas. À medida que você avança no aprendizado, vai descobrir novos recursos que permitem melhorar tanto a estrutura quanto a apresentação do conteúdo, tornando suas páginas mais organizadas, funcionais e profissionais.

Com o tempo e a prática, você também passará a entender melhor como combinar diferentes elementos HTML de forma eficiente, criando estruturas mais complexas e bem planejadas para atender diferentes necessidades de layout e conteúdo. 

Uma sugestão interessante para aprender HTML de forma mais eficiente é começar desenhando a estrutura de uma página web em um papel ou até mesmo em um quadro. Nesse esboço, você pode identificar os diferentes elementos que compõem a página, como cabeçalho, menus, seções, artigos, imagens e rodapé, além de entender como eles se organizam e se relacionam entre si. Durante esse processo, é importante se questionar constantemente sobre qual tag HTML é mais adequada para representar cada parte do conteúdo.

Depois de planejar a estrutura, o próximo passo é transformar esse rascunho em código HTML. Comece escrevendo a base do documento e, em seguida, utilize as tags corretas para organizar e estruturar todas as informações da página. Esse processo ajuda a desenvolver uma melhor compreensão da lógica por trás do HTML e da importância da semântica no desenvolvimento web.

Vale destacar que a prática é essencial para realmente aprender HTML. Quanto mais você experimentar, errar e testar diferentes abordagens, mais familiarizado ficará com a linguagem. Tente criar diversos tipos de páginas, desde as mais simples até projetos um pouco mais elaborados, explorando diferentes tags, atributos e estruturas. Com o tempo, você ganhará mais confiança e conseguirá desenvolver páginas cada vez mais bem organizadas e profissionais.




- Ao final deste conteúdo, realizaremos um exercício prático com o objetivo de colocar em prática todos os conceitos aprendidos sobre HTML. Nesse momento, você terá a oportunidade de desenvolver uma página web simples, aplicando corretamente as principais tags HTML para estruturar o conteúdo de maneira organizada, semântica e acessível.

- Durante a realização desse exercício, será possível reforçar o entendimento sobre como cada elemento da página deve ser representado no código, escolhendo as tags mais adequadas para títulos, parágrafos, imagens, links e outras partes importantes da estrutura. Além disso, você poderá perceber na prática como a utilização correta da semântica contribui para uma melhor leitura do código, tanto para desenvolvedores quanto para navegadores e tecnologias assistivas.

- Esse exercício também será fundamental para consolidar seu aprendizado sobre a sintaxe do HTML, permitindo que você ganhe mais confiança na escrita do código. Ao experimentar, testar e até cometer pequenos erros durante o processo, você estará evoluindo suas habilidades e desenvolvendo uma compreensão mais sólida da linguagem.


### Estrutura básica de um documento HTML

Outro ponto importante a ser abordado é a estrutura básica de um documento HTML, que representa o alicerce de qualquer página web. Entender essa estrutura é fundamental para que o navegador consiga interpretar corretamente o conteúdo e exibir a página de forma adequada.

Todo documento HTML deve começar com a declaração do tipo de documento < !DOCTYPE html>, que informa ao navegador que o arquivo está utilizando o padrão HTML5, a versão mais atual da linguagem. Essa declaração ajuda a evitar problemas de compatibilidade e garante que os elementos da página sejam renderizados corretamente.

Em seguida, o documento é estruturado em duas partes principais: o < head> e o < body>. Essas duas seções possuem funções diferentes, mas trabalham juntas para formar uma página web completa e funcional.

O < head> é a seção do documento onde são incluídas informações importantes sobre a página, como o título, links para arquivos CSS, scripts JavaScript, meta tags (metainformações), entre outros. Por exemplo, dentro do <head> podemos definir o < title> da página, que aparece na aba do navegador, além de configurar aspectos como a codificação de caracteres e a responsividade da página em diferentes dispositivos. O conteúdo do <head> não é exibido diretamente na página, mas é essencial para o funcionamento, desempenho e aparência da página web.

Já o < body> é a seção do documento onde o conteúdo visível da página é colocado. É aqui que você adiciona os elementos HTML que compõem a estrutura e o conteúdo da página, como títulos, parágrafos, imagens, links, listas, tabelas, formulários, entre outros. Tudo o que o usuário vê e com o qual interage está dentro do < body>. O conteúdo do < body> é o que os usuários visualizam quando acessam a página web, sendo, portanto, a parte mais perceptível e interativa do site.

Compreender bem essa divisão entre < head> e < body> é essencial para desenvolver páginas organizadas, funcionais e bem estruturadas. À medida que você pratica e explora novos elementos, essa base se torna cada vez mais natural no processo de criação de páginas web. 

A estrutura básica de um documento HTML pode ser representada da seguinte forma:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
   <meta charset="UTF-8">
   <title>Título da Página</title>
   <!-- Links para arquivos CSS e scripts JavaScript podem ser adicionados aqui -->
</head>
<body>
   <!-- Conteúdo visível da página é adicionado aqui -->
</body>
</html>
```  

> **⚠️ Nota:**
>
> Todo o código HTML deve ser escrito dentro da tag `<html>`, que é a raiz do documento. O atributo `lang="pt-BR"` indica que o idioma principal do conteúdo da página é o português do Brasil, o que é importante para a acessibilidade e para os mecanismos de busca entenderem o idioma da página. O elemento `<meta charset="UTF-8">` define a codificação de caracteres do documento como UTF-8, garantindo que caracteres acentuados e outros símbolos sejam exibidos corretamente. O elemento `<title>` define o título da página, que é exibido na aba do navegador e nos resultados de busca. 



### Atributos HTML

- Os atributos HTML são utilizados para fornecer informações adicionais sobre os elementos HTML, complementando suas funcionalidades básicas. Eles são escritos dentro da tag de abertura de um elemento e, geralmente, consistem em um nome e um valor, separados por um sinal de igual =. Esses valores costumam ser definidos entre aspas, o que ajuda a garantir uma melhor organização e legibilidade do código.

- Os atributos podem ser usados para definir propriedades específicas de um elemento, como sua aparência, comportamento ou funcionalidade dentro da página. Por meio deles, é possível personalizar a forma como os elementos são exibidos e como interagem com o usuário. Isso torna os atributos uma parte fundamental do HTML, pois permitem maior controle sobre os componentes da página.

Por exemplo, o atributo href é utilizado na tag < a> para especificar o endereço (URL) de destino de um link, permitindo que o usuário seja redirecionado para outra página ao clicar no elemento. Da mesma forma, o atributo src é utilizado na tag < img> para indicar o caminho da imagem que será exibida na página. Sem esses atributos, esses elementos não funcionariam corretamente


Imagine que temos a necessidade de criar um link para o site do Google em uma página web. Para isso, podemos usar a tag `<a>` (âncora) e o atributo `href` para especificar o URL do Google. O código HTML correspondente seria:

```html
<a href="https://www.google.com">Visite o Google</a>
```

O que resultaria em um link clicável com o texto "Visite o Google". Quando o usuário clicar nesse link, ele será redirecionado para a página do Google. O atributo `href` é fundamental para criar links em HTML, e seu valor deve ser um URL válido para garantir que o link funcione corretamente, como é possível ver no resultado abaixo:

[Visite o Google] (https://www.google.com)




### Lista de todas as tags HTML
Nestes links, você pode encontrar uma lista completa de todas as tags HTML, juntamente com suas descrições e exemplos de uso: [MDN Web Docs - Elementos HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element) ou [W3Schools - HTML Tags](https://www.w3schools.com/TAGS/default.asp).



# CSS - Cascading Style Sheets (Folhas de Estilo em Cascata)

O CSS é uma linguagem de estilo utilizada para controlar a aparência e o layout de uma página web. Por meio dele, é possível definir como os elementos HTML serão exibidos na tela, permitindo ajustar aspectos visuais como cores, fontes, tamanhos, margens, espaçamentos, alinhamentos e até animações. Dessa forma, o CSS desempenha um papel fundamental na criação de interfaces mais atraentes e organizadas.

Uma das principais vantagens do CSS é que ele é separado do HTML. Isso significa que você pode manter a estrutura do conteúdo (HTML) independente da apresentação visual (CSS). Essa separação torna o código mais limpo, organizado e fácil de entender, além de facilitar a manutenção e atualização do site. Por exemplo, ao alterar um único arquivo CSS, é possível modificar o estilo de várias páginas ao mesmo tempo, sem precisar editar cada arquivo HTML individualmente.

O CSS também contribui para a padronização do design de um site, garantindo que todos os elementos sigam um mesmo estilo visual. Isso melhora a experiência do usuário e torna a navegação mais agradável e consistente. Além disso, o uso de CSS permite adaptar o layout da página para diferentes dispositivos, como celulares, tablets e computadores, tornando o site responsivo. Veja o exemplo: 

Considere o seguinte código HTML:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
   <meta charset="UTF-8">
   <title>Exemplo de CSS</title>
   <link rel="stylesheet" href="styles.css">
</head>
<body>
   <h1>Olá, Mundo!</h1>
   <p>Este é um exemplo de CSS.</p>
</body>
</html>
```

Neste exemplo, temos um documento HTML básico com um título e um parágrafo. O arquivo CSS externo `styles.css` é vinculado ao documento HTML usando a tag `<link>` no `<head>`. O conteúdo do arquivo `styles.css` pode ser o seguinte:

```css
/* styles.css */
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

h1 {
  color: #333333;
  text-align: center;
}

p {
  color: #666666;
  font-size: 18px;
  margin: 20px;
}
```


> **⚠️ Nota:**
>
> No exemplo acima, o CSS é aplicado ao HTML, pois o arquivo `styles.css` está vinculado ao documento HTML usando a tag `<link>` no `<head>`. O CSS define o estilo para o elemento `<body>`, o título `<h1>` e o parágrafo `<p>`, controlando a aparência da página web. O CSS é uma parte essencial do desenvolvimento web, pois permite que você crie páginas visualmente atraentes e responsivas, melhorando a experiência do usuário.



O resultado do exemplo acima seria uma página web com um fundo cinza claro, um título centralizado em cor escura e um parágrafo com uma cor mais clara, tamanho de fonte maior e margens ao redor do texto. O CSS é uma ferramenta poderosa para personalizar a aparência de uma página web e criar designs únicos e atraentes.

![CSS Aplicado](docs/image-css.png)


Sem o CSS, a página web seria exibida com o estilo padrão do navegador, que pode variar dependendo do navegador e do sistema operacional. Chamamos isso de `user agent stylesheet`, que é o estilo padrão aplicado pelo navegador aos elementos HTML. O CSS permite que você substitua esse estilo padrão e crie uma aparência personalizada para a sua página web, controlando aspectos como cores, fontes, layout, espaçamento, entre outros. Sem o CSS, a página web seria exibida de forma básica e sem formatação, o que pode resultar em uma experiência de usuário menos atraente e menos profissional.

Sem o CSS que escrevemos, teríamos o seguinte resultado:

![Sem CSS](docs/image-css-none.png)



### Sintaxe do CSS

A sintaxe do CSS é composta por regras de estilo, onde cada regra é formada por um seletor e um bloco de declarações. O seletor é usado para selecionar os elementos HTML aos quais as regras de estilo serão aplicadas, enquanto o bloco de declarações define as propriedades de estilo e seus valores. A sintaxe básica do CSS pode ser representada da seguinte forma:

```css
seletor {
  propriedade: valor;
  propriedade: valor;
  /* ... */
}
```

> **⚠️ Nota:**
>
> O seletor pode ser um nome de elemento HTML, uma classe, um ID ou uma combinação desses. As propriedades de estilo são palavras-chave que definem o aspecto visual dos elementos, como `color`, `font-size`, `background-color` etc. Os valores são atribuídos às propriedades para especificar o estilo desejado, como `red`, `16px`, `#f0f0f0` etc. Cada declaração dentro do bloco de declarações deve ser separada por um ponto e vírgula `;`, e o bloco de declarações deve ser encerrado com uma chave `}`.



### Seletores CSS

Os seletores CSS são utilizados para identificar e selecionar os elementos HTML aos quais as regras de estilo serão aplicadas. A lógica dos seletores está diretamente relacionada à estrutura do documento HTML, seguindo a hierarquia dos elementos, o que justifica o nome “cascading” (em cascata), já que os estilos podem se sobrepor e ser aplicados de forma organizada conforme essa hierarquia.

Esses seletores permitem aplicar estilos tanto a elementos específicos quanto a grupos de elementos, com base em diferentes critérios, como tipo de tag, classes, IDs, atributos, entre outros. Dessa forma, é possível ter um controle muito mais preciso sobre a aparência de cada parte da página, tornando o CSS uma ferramenta extremamente flexível e poderosa para o desenvolvimento web.

Considere o seguinte código HTML:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
   <meta charset="UTF-8">
   <title>Exemplo de Seletores CSS</title>
   <link rel="stylesheet" href="styles.css">
</head>
<body>
   <h1 class="titulo">Título Principal</h1>
   <p id="paragrafo1">Este é o primeiro parágrafo.</p>
   <p id="paragrafo2">Este é o segundo parágrafo.</p>
   <a href="#" class="link">Este é um link</a>
</body>
</html>
```

Para aplicar estilos a esses elementos usando CSS, podemos usar diferentes tipos de seletores. Por exemplo: 

1. Seletor de tipo: para selecionar todos os elementos de um determinado tipo, como `<h1>`, `<p>`, `<a>` etc. Exemplo: `h1 { color: blue; }` aplicaria a cor azul a todos os elementos `<h1>` na página.

2. Seletor de classe: para selecionar elementos com uma classe específica. Exemplo: `.titulo { font-size: 24px; }` aplicaria um tamanho de fonte de 24 pixels a todos os elementos com a classe "titulo".

3. Seletor de ID: para selecionar um elemento com um ID específico. Exemplo: `#paragrafo1 { color: red; }` aplicaria a cor vermelha apenas ao elemento com o ID "paragrafo1".

4. Seletor de atributo: para selecionar elementos com um atributo específico ou um valor de atributo específico. Exemplo: `a[href="#"] { text-decoration: none; }` removeria o sublinhado de todos os links que têm um atributo `href` com o valor "#".

5. Pseudo-classes: para selecionar elementos com base em seu estado ou posição na hierarquia do documento. Exemplo: `p:first-child { font-weight: bold; }` aplicaria negrito ao primeiro parágrafo dentro de seu elemento pai.


Como dito, a hierarquia dos elementos HTML é fundamental para entender como os seletores CSS funcionam, pois eles seguem a estrutura do documento para aplicar estilos. Considere um parágrafo que, por sua vez, está dentro de uma seção, que, por sua vez, está dentro do conteúdo principal da página. No HTML, isso seria algo como:

```html
<main>
  <section>
   <p>Este é um parágrafo dentro de uma seção...</p>
  </section>
</main>
```



- Para selecionar e estilizar os parágrafos dentro dessa estrutura, você poderia usar um seletor de descendente como `main section p { color: green; }`, que aplicaria a cor verde a todos os parágrafos que estão dentro de uma seção, que, por sua vez, está dentro do elemento principal `<main>`.

 > **⚠️ Nota:**
>
> Os espaços entre os seletores indicam uma relação de descendência, ou seja, o seletor `main section p` seleciona todos os elementos `<p>` que são descendentes de um elemento `<section>`, que por sua vez é um descendente de um elemento `<main>`. seguindo a hierarquia do documento HTML. Essa forma de escrita permite criar regras de estilo mais específicas e organizadas, já que o CSS “navega” pela estrutura do HTML para encontrar os elementos corretos.

> Esse tipo de seletor é muito útil quando você deseja aplicar estilos apenas a elementos que estão em um contexto específico, evitando que outras partes da página sejam afetadas. Dessa forma, é possível ter um controle maior sobre o design e manter o código mais limpo e bem estruturado, especialmente em páginas mais complexas.

Se, no HTML que usamos de exemplo, tivéssemos um parágrafo fora da seção, como:

```html
<main>
  <section>
   <p>Este é um parágrafo dentro de uma seção...</p>
  </section>
  <p>Este é um parágrafo fora da seção...</p>
</main>
```

O seletor `main section p` aplicaria a cor verde apenas ao parágrafo dentro da seção, enquanto o parágrafo fora da seção não seria afetado por essa regra de estilo. Isso demonstra como os seletores CSS permitem que você controle a aplicação de estilos com base na hierarquia dos elementos HTML, garantindo que apenas os elementos desejados sejam estilizados de acordo com as regras definidas.

Resultando em algo como:

![Seletores CSS](docs/image-css-selectors.png)


### Tipos de Seletores CSS

- Existem vários tipos de seletores CSS que permitem selecionar elementos HTML de diferentes maneiras. Abaixo está uma tabela com alguns dos tipos de seletores mais comuns. Esta tabela tem o intuito de servir como um guia rápido para entender os diferentes tipos de seletores CSS e como eles funcionam. No entanto, existem muitos outros tipos de seletores CSS; abordaremos esses outros tipos em conteúdos futuros. Por enquanto, foque em entender os tipos de seletores mais comuns listados abaixo, pois eles são os mais utilizados e fundamentais para o aprendizado do CSS.

| Tipo de Seletor               | Exemplo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Descrição |
|------------------------------ | -------------------------------- | --------- |
| Seletor de Tipo               | `nome_elemento { }`              | Seleciona todos os elementos de um determinado tipo. Exemplo: `p { color: blue; }` seleciona todos os parágrafos e aplica a cor azul. |
| Seletor de Classe             | `.nome_classe { }`               | Seleciona elementos com uma classe específica. Exemplo: `.titulo { font-size: 24px; }` seleciona todos os elementos com a classe "titulo" e aplica um tamanho de fonte de 24 pixels. |
| Seletor de ID                 | `#nome_id { }`                   | Seleciona um elemento com um ID específico. Exemplo: `#paragrafo1 { color: red; }` seleciona o elemento com o ID "paragrafo1" e aplica a cor vermelha. |
| Seletor de Atributo           | `elemento[atributo="valor"] { }` | Seleciona elementos com um atributo específico ou um valor de atributo específico. Exemplo: `a[href="#"] { text-decoration: none; }` seleciona todos os links que têm um atributo `href` com o valor "#" e remove o sublinhado. |
| Pseudo-classes                | `elemento:pseudo-classe { }`     | Seleciona elementos com base em seu estado ou posição na hierarquia do documento. Exemplo: `p:first-child { font-weight: bold; }` seleciona o primeiro parágrafo dentro de seu elemento pai e aplica negrito. |

Seletores de descendentes, filhos e irmãos:

| Tipo de Seletor               | Exemplo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Descrição |
|------------------------------ | -------------------------------- | --------- |
| Seletor de Descendente        | `elemento1 elemento2 { }`        | Seleciona elementos que são descendentes de um elemento específico. Exemplo: `main section p { color: green; }` seleciona todos os parágrafos que estão dentro de uma seção, que por sua vez está dentro do elemento principal `<main>`, e aplica a cor verde. |
| Seletor de Filho              | `elemento1 > elemento2 { }`      | Seleciona elementos que são filhos diretos de um elemento específico. Exemplo: `main > section { background-color: lightgray; }` seleciona todas as seções que são filhos diretos do elemento principal `<main>` e aplica um fundo cinza claro. |
| Seletor de Irmão Adjacente    | `elemento1 + elemento2 { }`      | Seleciona um elemento que é imediatamente precedido por outro elemento específico. Exemplo: `h1 + p { margin-top: 0; }` seleciona o parágrafo que vem imediatamente após um título `<h1>` e remove a margem superior. |
| Seletor de Irmão Generalizado | `elemento1 ~ elemento2 { }`      | Seleciona elementos que são irmãos de um elemento específico, independentemente de sua posição. Exemplo: `h1 ~ p { color: gray; }` seleciona todos os parágrafos que são irmãos de um título `<h1>` e aplica a cor cinza. |

