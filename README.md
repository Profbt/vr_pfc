# Paraná Faz Ciência — Interactive Projects Showcase

**A lightweight web showcase for student-created Scratch projects presented at Paraná Faz Ciência.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-vrpfc.vercel.app-22c55e?style=for-the-badge&logo=vercel&logoColor=white)](https://vrpfc.vercel.app/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Scratch](https://img.shields.io/badge/Scratch-4D97FF?style=flat-square&logo=scratch&logoColor=white)

**English** | [Português](#português)

## Overview

This static website presents interactive educational projects developed with Scratch for the Paraná Faz Ciência science event. It brings three activities together in a simple browser-based exhibition:

- **Storytelling:** an interactive narrative created with Scratch.
- **Genius Robot:** a playful logic project that discovers the participant's name.
- **Caesar Cipher:** an introduction to message encryption.

Each activity is embedded directly from Scratch and accompanied by a QR code for mobile access. The project uses only HTML and CSS and does not require authentication, a database, or a backend.

## Technical approach

- Static multi-page HTML structure.
- Shared responsive CSS.
- Scratch projects embedded through iframes.
- QR codes for cross-device access.
- Simple deployment to static hosting.
- No collection or storage of visitor data.

## Run locally

Clone or download the repository and open `index.html` in a modern browser. A local static server can also be used:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Structure

```text
index.html    storytelling project
robo.html     Genius Robot project
cesar.html    Caesar Cipher project
style.css     shared visual layout
img/          visual assets and QR codes
```

## Rights

The source code and original project materials are provided for portfolio viewing and evaluation. No open-source license is granted. Embedded Scratch projects and third-party assets remain subject to their respective owners and terms.

---

<a id="português"></a>

# Paraná Faz Ciência — Mostra de Projetos Interativos

[English](#paraná-faz-ciência--interactive-projects-showcase) | **Português**

🌐 **Aplicação:** [vrpfc.vercel.app](https://vrpfc.vercel.app/)

## Visão geral

Este site estático apresenta projetos educacionais interativos desenvolvidos com Scratch para o evento Paraná Faz Ciência. A mostra reúne três atividades:

- **Storytelling:** narrativa interativa criada com Scratch.
- **Robô Gênio:** projeto lúdico de lógica que descobre o nome do participante.
- **Cifra de César:** introdução à criptografia de mensagens.

Cada atividade é incorporada diretamente do Scratch e acompanhada por um QR Code para acesso em dispositivos móveis. O projeto utiliza somente HTML e CSS e não exige autenticação, banco de dados ou backend.

## Abordagem técnica

- Estrutura estática com múltiplas páginas HTML.
- CSS responsivo compartilhado.
- Projetos Scratch incorporados por iframe.
- QR Codes para acesso em diferentes dispositivos.
- Publicação simples em hospedagem estática.
- Nenhuma coleta ou armazenamento de dados de visitantes.

## Executar localmente

Abra o arquivo `index.html` em um navegador moderno ou execute:

```bash
python3 -m http.server 8080
```

Depois acesse `http://localhost:8080`.

## Estrutura

```text
index.html    projeto de storytelling
robo.html     projeto Robô Gênio
cesar.html    projeto Cifra de César
style.css     identidade visual compartilhada
img/          recursos visuais e QR Codes
```

## Direitos

O código-fonte e os materiais autorais deste projeto são disponibilizados apenas para visualização e avaliação de portfólio. Nenhuma licença de código aberto é concedida. Projetos incorporados do Scratch e recursos de terceiros permanecem sujeitos aos direitos e termos de seus respectivos autores.
