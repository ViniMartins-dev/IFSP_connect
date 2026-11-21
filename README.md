# IFSP Connect

**Autor:** Vinícius Martins Pereira

**Curso:** Engenharia de Controle e Automação

**Colaboração:** Eduardo Luciano Martinez ajudou na criação do conteúdo das páginas.

## Objetivo

O IFSP Connect é um website fictício criado para apresentar informações sobre o IFSP, seus cursos, eventos e notícias. O projeto também tem como objetivo acompanhar minha evolução durante o curso de Desenvolvimento Front-End.

## Páginas

| Página | Arquivo | Conteúdo |
|---|---|---|
| Home | `index.html` | Apresentação do projeto, últimas notícias e objetivo do sistema |
| Cursos | `paginas/cursos.html` | Tabelas de cursos técnicos, técnicos integrados, superiores e pós-graduação |
| Eventos | `paginas/eventos.html` | Cards de eventos, prazos e processos seletivos do IFSP |
| Professores | `paginas/professores.html` | Cards do corpo docente com titulação e link para o currículo Lattes |
| Projeto Integrador | `paginas/projeto.html` | Projeto LUXIF exibido em um iframe que ocupa o espaço entre header e footer |
| Multimídia | `paginas/multimidia.html` | Vídeo institucional e podcast |
| Contato | `paginas/contato.html` | Canais de contato, canais oficiais e perguntas frequentes |
| Cadastro | `paginas/cadastro.html` | Formulário completo de cadastro de usuários |
| Sobre | `paginas/sobre.html` | Sobre o projeto e as tecnologias (fora do menu) |

O menu e o rodapé ficam em `paginas/header.html` e `paginas/footer.html` e são carregados em todas as páginas por meio de `<iframe>`.

## Estrutura do projeto

```
├── index.html
├── paginas/       páginas do site, incluindo header.html e footer.html
├── css/           estilo.css (site), header.css e footer.css
├── imagens/       logos e imagens dos eventos
├── video/         vídeo institucional
├── audio/         podcast
└── README.md
```

## CSS

O arquivo `css/estilo.css` usa variáveis no `:root` (cores, fontes e alturas do header e do footer) e é dividido em seções: base, estrutura da página, Projeto Integrador, cards, professores, tabelas, formulário e multimídia.

## Como executar

Não há instalação. Abra o `index.html` no navegador ou use a extensão Live Server do VS Code. Como o menu e o rodapé usam iframes, o ideal é abrir por um servidor local.

## Tecnologias utilizadas

- HTML
- CSS