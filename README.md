# TTwitter

Um protótipo moderno e responsivo de interface para uma rede social, desenvolvido com **HTML5** e **CSS** puro. O projeto conta com fluxo de navegação entre telas de autenticação (Login e Cadastro) e o feed principal (Home).

---

## Funcionalidades e Telas

* **Tela de Login (`index.html`):**
  * Layout com apresentação da marca e formulário de acesso.
  * Links para recuperação de senha e tela de cadastro.
* **Tela de Cadastro (`cadastro.html`):**
  * Formulário para registro de novos usuários (Nome, E-mail, Data de Nascimento e Senha).
* **Feed Principal / Home (`home.html`):**
  * **Barra de Navegação (Sidebar/Bottom Nav):** Ícones de navegação que se adaptam ao formato da tela.
  * **Header com Busca:** Barra superior com logo clicável (que redireciona de volta ao login) e campo de pesquisa.
  * **Caixa de Publicação:** Área para digitação de novos posts com ícones de anexo/mídia.
  * **Feed de Postagens e Sugestões:** Layout em grade exibindo publicações e barra lateral com sugestões de amizades.

---

## Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo (`<header>`, `<main>`, `<nav>`, `<aside>`, `<section>`, `<article>`).
* **CSS3:** 
  * **CSS Grid & Flexbox:** Para alinhamento preciso e layouts complexos sem necessidade de frameworks externos.
  * **Design Responsivo (Media Queries):** Breakpoint configurado em `700px` para transição fluida entre desktop e mobile.
  * **Variáveis CSS (`:root`):** Paleta de cores consistente, utilizando tons profundos e destaques em ciano.

---

## Estrutura de Arquivos

```text
├── assets/
│   ├── logoTTwitter.png    # Logo principal da plataforma
│   └── fotoTTwitter.png    # Imagem de exemplo para as publicações no feed
├── index.html              # Página inicial / Login
├── cadastro.html           # Página de criação de conta
├── home.html               # Página do feed / linha do tempo
├── style.css               # Folha de estilos global e regras responsivas
└── README.md               # Documentação do projeto
```


## Como Executar o Projeto

1. Clone esse repositório em sua máquina.
2. Certifique-se de que a pasta `assets/` contém as imagens necessárias (`logoTTwitter.png` e `fotoTTwitter.png`).
3. Dê um duplo clique no arquivo **`index.html`** para abri-lo no seu navegador web.

---

## Como Testar o Modo Mobile

O projeto foi construído sob o conceito de design responsivo. Para visualizar como a interface se comporta em telas de smartphones diretamente no computador, você pode utilizar o **Modo de Simulação de Dispositivos** do seu navegador:

### Passo a Passo no Navegador (Chrome / Edge / Firefox):

1. Com qualquer página do projeto aberta no navegador (`index.html`, `cadastro.html` ou `home.html`), abra as **Ferramentas de Desenvolvedor (DevTools)**:
   * Pressione **`F12`** (ou **`Ctrl + Shift + I`** no Windows/Linux | **`Cmd + Option + I`** no macOS).
2. Ative a barra de ferramentas do dispositivo móvel pressionando o atalho:
   * **`Ctrl + Shift + M`** *(Windows / Linux)*
   * **`Cmd + Shift + M`** *(macOS)*
3. Na barra superior que aparecerá dentro da tela da página:
   * Escolha um modelo de smartphone predefinido **OU**
   * Ajuste manualmente a largura da tela para um valor **abaixo de 700px** para ativar as regras responsivas do CSS.
