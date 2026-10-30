# Simulador de Gerador de Imagens

Projeto da disciplina de Introdução a Computação: Uma plataforma web e interativa desenvolvida para explorar a geração de imagens, permitindo aos usuários visualizar galerias de imagens, entender o funcionamento da tecnologia, testar a geração de imagens e entrar em contato.

---

## Sobre o Projeto

O **Gerador de Imagens** é um site multipágina focado em proporcionar uma experiência fluida de interface para criação e navegação visual. O projeto é resultado da disciplina de Introdução a Computação e visa o aprendizado e aplicação dos conceitos de HTML, CSS, Versionamento e IHC.

### Funcionalidades
- **Página Inicial (`index.html`):** Apresentação do projeto, destaques e chamada para ação (*CTA*).
- **Gerador (`gerar.html`):** Interface interativa para digitação de prompts e geração visual (Fase de simulação).
- **Galeria (`galeria.html`):** Exposição de imagens geradas com exemplos de prompts utilizados.
- **Sobre (`sobre.html`):** Informações conceituais sobre a tecnologia e os objetivos do projeto.
- **Contato (`contato.html`):** Formulário interativo para dúvidas e feedback.
- **Design Responsivo:** Adaptação completa para dispositivos móveis, tablets e desktops.

---

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica de todas as páginas.
- **CSS3:** Estilização moderna com Flexbox, CSS Grid e variáveis.
- **Design Responsivo:** Arquivo CSS dedicado (`responsivo.css`) para suporte a telas de diferentes resoluções.

---

## Estrutura de Arquivos

```text
projeto-gerador-imagens-ia/
├── assets/                 # Imagens do projeto, fundos e galeria
├── estilos/
│   ├── estilo.css          # Estilos globais e componentes
│   └── responsivo.css      # Regras de media queries
├── index.html              # Página Inicial
├── sobre.html              # Página Sobre
├── galeria.html            # Galeria de Imagens
├── gerar.html              # Interface do Gerador
├── contato.html            # Formulário de Contato
└── README.md               # Documentação do projeto
