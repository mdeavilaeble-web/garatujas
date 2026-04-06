# TAREFA IA26 WEBDESIGN

Esta disciplina foca na aprendizagem de técnicas e práticas de web design, mas com foco nas linguagens de marcação (HTML), de estilo (CSS) e, brevemente, de programação (JavaScript). O objetivo é capacitar os alunos a criar e estilizar páginas web abrindo caminho para o desenvolvimento de sites e aplicações web mais complexas do futuro no mercado de trabalho. Esta é uma disciplina introdutória e, no entanto, fundamental para a carreira de desenvolvimento web, pois estabelece as bases para a construção de interfaces web e a compreensão dos princípios de design e usabilidade na web. O curso é projetado para ser acessível a iniciantes. 


## Antes do início

É desejável que os alunos tenham um ambiente de desenvolvimento configurado em suas máquinas, incluindo um editor de código e um navegador web atualizado. Nesta disciplina, utilizaremos o Visual Studio Code como editor de código (por ser gratuito e o mais utilizado no mercado) e o Google Chrome como navegador web (pelos mesmos motivos).


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



