# Samack Scanner - Leitor e Gerador de Código de Barras e QR Code

Este repositório contém a versão web e online do aplicativo **Samack Scanner**, pronta para ser hospedada diretamente via **GitHub Pages**.

## 🌐 Acesse Online
Uma vez configurado o GitHub Pages no seu repositório, o leitor e gerador estarão acessíveis publicamente através de qualquer navegador móvel ou desktop com suporte a câmera.

## 🚀 Principais Recursos da Versão Web

- **Leitor por Câmera (Scanner)**: Integração com CameraX equivalente em JavaScript usando a biblioteca `html5-qrcode` para leitura instantânea na câmera traseira ou frontal.
- **Leitor de Imagem Local**: Permite carregar uma imagem ou foto da galeria do dispositivo para decodificação.
- **Gerador de 11+ Simbologias**: Criação dinâmica client-side em alta definição usando a biblioteca `bwip-js`. Formatos suportados:
  - QR Code
  - Code 128
  - EAN-13 / EAN-8
  - UPC-A / UPC-E
  - ISBN
  - Code 39
  - Codabar
  - ITF
  - Postnet
- **Visualização Lateral de Tela Cheia**: Clique na imagem gerada para abri-la em tela cheia com fundo branco puro, rotacionada lateralmente em 90 graus (ideal para leitura de checkout físico).
- **Ações Inteligentes**: Detecção de dados como conexões Wi-Fi, códigos PIX copia e cola, links HTTP, e-mails, telefones e SMS para exibição de botões de atalho.
- **Histórico Local Persistente**: Salva e organiza todos os códigos escaneados ou gerados localmente utilizando `localStorage` do navegador. Permite buscar, filtrar, favoritar e exportar dados em formatos **CSV** e **JSON**.
- **Painel de Configurações**: Controle rápido do bipe de som (usando AudioContext nativo do navegador), vibração e cooldown de repetição de scanner.
- **Design Premium**: Visual dark moderno, responsivo para celulares e desktops, com suporte a troca de temas (Claro/Escuro).

---

## 🛠️ Como ativar o GitHub Pages para este projeto

Para colocar este site no ar de forma totalmente gratuita, siga os passos abaixo no GitHub:

1. Crie um novo repositório no seu GitHub (ex: `samack-scanner`).
2. Envie o conteúdo desta pasta `github` para o repositório.
3. No painel do seu repositório no GitHub, vá em **Settings** (Configurações).
4. No menu lateral esquerdo, clique em **Pages**.
5. Em **Build and deployment** -> **Source**, selecione **Deploy from a branch**.
6. Em **Branch**, selecione a branch principal (`main` ou `master`) e a pasta raiz (`/` root). Clique em **Save**.
7. O GitHub gerará o link oficial para você (ex: `https://seu-usuario.github.io/samack-scanner/`).

---
Criado por **Samack** - 2026.
