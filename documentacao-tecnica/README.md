# Projeto 4: Documentação - HTML :page_facing_up:

## Disponível em:

- [Site](https://elizabethvelozo.github.io/fcc-design-responsivo-para-a-web/documentacao-tecnica/documentacao-html.html)

## Descrição

- Criar uma página de documentação técnica.

## Requisitos

História de usuário   | Descrição
:--------------------:|-----------
**1**  | Deve haver um elemento `main` com um `id="main-doc"`, que contém o conteúdo principal da página (documentação técnica).
**2**  | Dentro do elemento `#main-doc`, deve haver várias seções (`section`), cada uma com a classe `main-section`. Deve haver um mínimo de 5.
**3**  | O primeiro elemento de cada `.main-section` deve ser um elemento de cabeçalho (`header`) que contém o texto que descreve o tópico desta seção.
**4**  | Cada `section` com a classe `main-section` também deve ter um id que corresponda ao texto de cada `header` contido dentro dela. Os espaços existentes devem ser substituídos por sublinhados (por exemplo, a `section` que contém o cabeçalho "JavaScript e Java" deve ter um `id="JavaScript_and_Java"`).
**5**  | Os elementos `.main-section` devem conter, juntos, pelo menos 10 elementos `p` no total (não 10 para cada elemento).
**6**  | Os elementos `.main-section` devem conter, juntos, pelo menos 5 elementos `code` no total (não 5 para cada elemento).
**7**  | Os elementos `.main-section` devem conter, juntos, pelo menos 5 elementos `li` no total (não 5 para cada elemento).
**8**  | Deve haver uma barra de navegação (`nav`) com um `id="navbar"`.
**9**  | O o elemento de barra de navegação (nav) deve conter um elemento `header` que contém o texto que descreve o tópico da documentação técnica.
**10** | Além disso, a barra de navegação (nav) deve conter elementos de âncora (`a`) com a classe `nav-link`. Deve haver um para cada elemento com a classe `main-section`.
**11** | O elemento `header` na barra de navegação deve aparecer antes de qualquer elemento de âncora (`a`).
**11** | Cada elemento com a classe `nav-link` deve conter um texto que corresponda ao texto do `header` dentro de cada `section` (exemplo: se você tem uma seção/cabeçalho "Olá mundo", sua barra de navegação deve ter um elemento que contém o texto "Olá mundo").
**13** | Quando um elemento da barra de navegação for clicado, a página deve navegar para a seção correspondente ao elemento `main-doc` (exemplo: se eu clicar em um elemento `nav-link` que contém o texto "Olá mundo", a página deve navegar para o elemento `section` que tem esse id e contém o `header` correspondente.
**14** | Em dispositivos com tamanho regular (laptops, desktops), o elemento com `id="navbar"` deve ser mostrado no lado esquerdo da tela e deve sempre estar visível para o usuário.
**15** | A página deve ter pelo menos uma media query.