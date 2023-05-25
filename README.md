<h1 align="center"> Tag-main-HTML </h1>

## 🔗 Índice
* [🎯 Objetivo](#-objetivo)
* [📝 Uso básico da tag main](#-Uso-básico-da-tag-main)
* [⚠️ Importância e benefícios do uso da tag](#-Importância-e-benefícios-do-uso-tag-main)
* [📍 Considerações de uso da tag main](#-Considerações-de-uso-tag-main)
* [📋 Requisitos funcionais](#-requisitos-funcionais)
* [📍 Requisitos não-funcionais](#-requisitos-não-funcionais)
* [🔧 Tecnologias utilizadas](#-tecnologias-utilizadas)
*  [✅ Conclusão](#-conclusão)


## 🎯 Objetivo
O objetivo da tag main em HTML é identificar e envolver o conteúdo principal de uma página ou seção de um documento. Ela foi introduzida na especificação do HTML5 para fornecer uma estrutura semântica clara e ajudar a melhorar a acessibilidade, usabilidade e SEO de um site ou aplicação web.


## 📝 Uso básico da tag main
A tag main é posicionada dentro do elemento body e é usada para envolver o conteúdo principal da página. Aqui está um exemplo básico de como usar a tag main:
![Capturar_2023_05_25_06_02_23_521](https://github.com/andersoncode55/Tag-main/assets/61977421/fef3db14-0dac-4a61-aa40-fb5ec410ccc2)
<body>
  <header>
    <!-- conteúdo do cabeçalho -->
  </header>

  <main>
    <section>
      <h2>Seção 1</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean consectetur commodo risus, eu eleifend eros lobortis ac.</p>
     </section>
  </main>

  <footer>
    <!-- conteúdo do rodapé -->
  </footer>
</body>
No exemplo acima, a tag main envolve o conteúdo principal da página, que pode incluir títulos, parágrafos, imagens, formulários e outros elementos relevantes para o contexto da página.
<hr>


## ⚠️ Importância e benefícios do uso da tag main
O uso da tag main traz alguns benefícios importantes para a estruturação semântica do conteúdo de uma página:
<ol>
  <li>Clareza semântica: A tag main fornece uma estrutura semântica para identificar o conteúdo principal da página. Isso facilita a compreensão do conteúdo tanto pelos desenvolvedores quanto pelos mecanismos de busca.</li>
  <li>Acessibilidade: Ao identificar explicitamente o conteúdo principal da página, a tag main ajuda os usuários que dependem de tecnologias assistivas a navegarem mais facilmente pelo conteúdo relevante.</li>
  <li>SEO: Os motores de busca, como o Google, dão importância ao conteúdo principal de uma página. O uso adequado da tag main ajuda a destacar esse conteúdo nos resultados de pesquisa.</li>
  <li>Manutenção e estilização: Envolver o conteúdo principal em uma tag main torna mais fácil para os desenvolvedores e designers identificarem e aplicarem estilos específicos a essa área.</li>
</ol>





## 📍 Considerações de uso da tag main
É importante lembrar que a tag main não deve ser usada em mais de uma vez em uma mesma página. Ela deve conter apenas o conteúdo principal da página e não deve incluir cabeçalhos, rodapés, barras laterais ou elementos secundários.

Além disso, em casos em que o conteúdo principal é específico de uma seção dentro de uma página, pode ser apropriado usar a tag main novamente dentro dessa seção para envolver o conteúdo principal local.


## 📋 Requisitos funcionais
Aqui estão alguns exemplos de requisitos funcionais que podem ser aplicados à tag main em HTML:
<ol>
  <li>Identificar o conteúdo principal: A tag main deve ser capaz de envolver e identificar o conteúdo principal de uma página ou seção específica de um documento HTML.</li>
  <li>Suportar elementos de marcação: A tag main deve permitir a inclusão de diferentes elementos de marcação dentro dela, como títulos, parágrafos, imagens, listas e outros elementos HTML para representar o conteúdo principal.</li>
  <li>Ser aninhada adequadamente: A tag main deve ser utilizada de forma correta, evitando o aninhamento inadequado dentro de outras tags estruturais, como header, footer ou nav.</li>
  <li>Ser compatível com diferentes navegadores: A tag main deve ser suportada pelos principais navegadores web, como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, garantindo a consistência e acessibilidade do conteúdo principal em diferentes plataformas.</li>
  <li>Permitir múltiplos usos em um documento: A tag main deve permitir a sua utilização em diferentes partes de um documento HTML, quando necessário, para identificar o conteúdo principal de seções específicas.</li>
  <li>Ser semanticamente correta: A tag main deve seguir as melhores práticas de semântica web, garantindo que o conteúdo envolvido por ela seja representado de forma adequada e compreensível pelos navegadores, mecanismos de busca e tecnologias assistivas.</li>
  <li>Suportar acessibilidade: A tag main deve ser utilizada de forma a garantir a acessibilidade do conteúdo principal, fornecendo informações claras e significativas para usuários com deficiências visuais ou que dependem de tecnologias assistivas.</li>
  <li>Ser facilmente estilizável: A tag main deve ser flexível e permitir a aplicação de estilos CSS para personalizar a aparência do conteúdo principal, garantindo uma boa experiência de usuário.</li>
  <li>Ser documentada: O uso da tag <main> deve ser adequadamente documentado, incluindo informações sobre seu propósito, sintaxe correta, exemplos de uso e possíveis considerações adicionais.</li>
</ol>



## 📍 Requisitos não-funcionais
Aqui estão alguns exemplos de requisitos não-funcionais que podem ser aplicados à tag main em HTML:
<ol>
  <li>Performance: A tag main deve ter um desempenho adequado, garantindo um carregamento rápido do conteúdo principal da página e uma resposta ágil durante a interação do usuário.</li>
  <li>Responsividade: A tag main deve ser responsiva, ou seja, adaptar-se a diferentes tamanhos de tela e dispositivos, oferecendo uma experiência de visualização e interação otimizada em smartphones, tablets e desktops.</li>
  <li>Compatibilidade com navegadores: A tag main deve ser compatível com uma ampla gama de navegadores web, incluindo versões antigas e recentes, para garantir que o conteúdo principal seja exibido corretamente em todos eles.</li>
  <li>Acessibilidade: A tag main deve atender aos padrões de acessibilidade da Web, permitindo que usuários com deficiências visuais ou outros tipos de deficiência possam acessar e interagir com o conteúdo principal de forma eficaz, por meio de tecnologias assistivas.</li>
  <li>Segurança: A tag <main> deve ser implementada de forma segura, evitando vulnerabilidades de segurança que possam comprometer a integridade do conteúdo principal ou abrir brechas para ataques maliciosos.</li>
  <li>Manutenibilidade: A tag main deve ser fácil de manter e atualizar, com um código HTML limpo, bem estruturado e documentado, facilitando a compreensão e a realização de modificações futuras.</li>
  <li>Internacionalização: A tag main deve suportar a internacionalização, permitindo a adaptação do conteúdo principal para diferentes idiomas e regiões, quando aplicável.</li>
  <li>Conformidade com padrões: A tag main deve estar em conformidade com as especificações e padrões do HTML estabelecidos pelo W3C (World Wide Web Consortium) para garantir a interoperabilidade e a compatibilidade com outras tecnologias web.</li>
  <li>Eficiência de código: O uso da tag <main> deve resultar em um código HTML eficiente, sem redundâncias desnecessárias, facilitando a análise, a manutenção e o desempenho geral da página.</li>
</ol>

Lembre-se de que esses são apenas exemplos de requisitos não-funcionais que podem ser aplicados à tag main. É importante adaptar e personalizar esses requisitos de acordo com as necessidades e especificações do seu projeto web.




## ✅ Conclusão
A tag main é um elemento HTML usado para identificar e envolver o conteúdo principal de uma página ou seção de um documento. Seu uso adequado traz benefícios em termos de semântica, acessibilidade, SEO e estilização. Ao utilizar a tag main, você fornece uma estrutura clara e organizada para o conteúdo principal do seu site ou aplicação web.











