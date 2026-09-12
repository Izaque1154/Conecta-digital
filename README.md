# Conecta-digital
Projeto para o trabalho da Faculdade:
Conecta Digital

O Conecta Digital é um projeto de plataforma web para uma ONG voltada à inclusão digital. A iniciativa busca ajudar idosos, pessoas de baixa renda, moradores de áreas rurais, pessoas com deficiência e usuários com pouca experiência tecnológica.

Funcionalidades

Apresentação da ONG e de sua missão;

Divulgação de projetos de inclusão e segurança digital;

Informações sobre voluntariado e doações;

Formulário de cadastro para voluntários, doadores e alunos;

Página de demonstração de alertas, badges, toast e modal;

Layout responsivo e recursos básicos de acessibilidade.

Tecnologias utilizadas

HTML5 para a estrutura semântica das páginas;

CSS3 para cores, tipografia, Grid, Flexbox e responsividade;

Imagens em WebP, JPG, PNG e SVG;

Git e GitHub para versionamento;

GitHub Pages para publicação.

Estrutura do projeto

conecta-digital/
├── assets/
│   ├── css/
│   │   └── style.css
│   └── imagens/
├── index.html
├── projetos.html
├── cadastro.html
├── componentes.html
└── README.md

Como executar localmente

Baixe e extraia o arquivo do projeto.

Abra a pasta conecta-digital.

Abra o arquivo index.html em um navegador moderno.

Como alternativa, utilize a extensão Live Server do Visual Studio Code.

O projeto não exige instalação de dependências ou banco de dados.

Acessibilidade

As páginas utilizam elementos semânticos como header, nav, main, section, article e footer. Também foram incluídos textos alternativos nas imagens, identificação dos campos com label, agrupamentos com fieldset e legend, foco visível e navegação por teclado.

O formulário utiliza validações nativas do HTML5, incluindo required, pattern, minlength, maxlength e tipos específicos como email, tel e date.

Responsividade

O layout foi criado com CSS Grid e Flexbox. Imagens flexíveis e ajustes de tamanho permitem o uso em computadores, tablets e celulares.

Versionamento

O projeto segue uma organização inspirada no GitFlow:

main: versão estável e pronta para publicação;

develop: integração das alterações em desenvolvimento;

feature/: criação de novas funcionalidades;

hotfix/: correção de problemas urgentes.

As mensagens seguem o padrão Conventional Commits, por exemplo:

feat: adiciona página de cadastro
fix: corrige navegação e responsividade
docs: adiciona documentação do projeto

As versões utilizam o versionamento semântico MAJOR.MINOR.PATCH, como v1.0.0.

Validação e publicação

O HTML pode ser verificado no W3C Validator e a acessibilidade pode ser avaliada com Lighthouse ou axe DevTools. A versão final pode ser publicada pelo GitHub Pages a partir da branch main.

Autor: Izaque A. Araújo

Projeto acadêmico desenvolvido para aplicar conhecimentos de HTML5, CSS3, acessibilidade, versionamento e publicação web.
