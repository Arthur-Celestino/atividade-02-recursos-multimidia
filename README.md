# 🎬 Atividade 02 - Recursos Multimídia

### Professor Genivaldo Carlos da Silva - 30/09/2026

Projeto desenvolvido para a disciplina de **Recursos Multimídia**, utilizando HTML5, vídeo, áudio e legendas no formato WebVTT.

## 📚 Sobre o projeto

A atividade consiste na criação de um player de vídeo HTML5 com suporte a duas faixas de legendas:

- 🇧🇷 Português (Brasil)
- 🇺🇸 English

O projeto também utiliza uma trilha de áudio externa sincronizada com o vídeo através de JavaScript. :contentReference[oaicite:2]{index=2}

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- WebVTT
- Elementos `<video>` e `<audio>`

## 🎥 Recursos do projeto

O player possui:

- Reprodução de vídeo;
- Trilha de áudio externa;
- Legendas em português;
- Legendas em inglês;
- Seleção do idioma pelo menu do player;
- Botão para reproduzir e pausar com áudio;
- Sincronização entre vídeo e áudio;
- Controle de volume;
- Controle de velocidade;
- Suporte à busca durante o vídeo. :contentReference[oaicite:3]{index=3}

## 💬 Legendas

As legendas foram criadas utilizando arquivos `.vtt`.

### Português

O arquivo contém mensagens como:

> Bem-vindo a demonstração de recursos multimídia.

### English

A segunda faixa apresenta a tradução das legendas para inglês.

Os arquivos utilizam o formato **WebVTT**, com marcações de tempo para sincronizar o texto com o vídeo. :contentReference[oaicite:4]{index=4}

## 📁 Estrutura do projeto

```text
📦 atividade-02-recursos-multimidia
│
├── 📄 index.html
├── 📄 README.md
│
├── 📁 legendas
│   ├── legendas-pt.vtt
│   └── subtitles-en.vtt
│
├── 📁 video
│   └── praia.mp4
│
└── 📁 midia
    └── trilha-que-nem-mare.mp3
