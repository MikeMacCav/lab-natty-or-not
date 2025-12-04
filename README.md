# 🎥 Projeto Natty or Not — Avatar IA falando com minha própria voz

## 📒 Descrição
Este projeto foi desenvolvido como parte do desafio **"Natty or Not"** da DIO, cujo objetivo é explorar o uso de **IAs Generativas** para criar conteúdos realistas.  
Criei um vídeo de apresentação usando:

- Uma **foto minha** transformada em vídeo com animação facial por IA.
- Um **clone da minha própria voz**, gerada a partir de um áudio de referência.

O objetivo foi produzir um resultado que parecesse o mais natural possível, simulando um vídeo real gravado por mim.

---

## 🤖 Tecnologias Utilizadas

### 🗣️ **Clonagem de Voz**
- **VoicV (voicv.com)**  
  Utilizado para clonar minha voz a partir de um sample de áudio pessoal.

### 👤 **Criação de Avatar em Vídeo**
- **HeyGen (app.heygen.com)**  
  Ferramenta usada para animar minha foto e sincronizar com o áudio gerado.

### 🛠️ **Ferramentas adicionais**
- Editor local para ajustes no áudio e vídeo (Windows Movie Maker).
- Git/GitHub para versionamento do projeto.

---

## 🧐 Processo de Criação

1. **Escolha da Foto**  
   – Selecionei uma imagem minha com boa iluminação e fundo limpo.  
   – Ajustei o enquadramento para ficar ideal para lipsync.

2. **Clonagem da Voz**  
   – Gravei um áudio curto com boa qualidade.  
   – Enviei para o **VoicV** para gerar um modelo de voz pessoal.  
   – Digitei meu roteiro e gerei o áudio final com a minha voz clonada.

3. **Geração do Vídeo**  
   – Fiz upload da minha foto no **HeyGen**.  
   – Adicionei o áudio criado pelo VoicV.  
   – Renderizei um vídeo com animação facial natural.

4. **Edição Final (Opcional)**  
   – Ajustei volume e equalização.  
   – Adicionei cortes suaves e melhorei o ritmo.

5. **Publicação**  
   – Organizei o projeto no GitHub com boa estrutura e documentação.

---

## 🚀 Resultados

- Um vídeo final onde **um avatar baseado na minha foto fala com minha própria voz clonada**.
- O resultado ficou natural, convincente e coerente com os objetivos do desafio.
- O processo ajudou a reforçar a compreensão sobre IAs generativas modernas:  
  – Clonagem de voz  
  – Talking avatars  
  – Lip sync IA  
  – Multimodalidade  
  – Ética e uso responsável  

📌 O arquivo renderizado final está disponível na pasta `/output/` (ou forneça o link após subir no repositório).

---

## 📁 Estrutura do Repositório

lab-natty-or-not/
│
├── README.md                # Documentação principal
├── roteiro/                 # O roteiro escrito do vídeo
│   └── roteiro.txt
│
├── audio/                   # Áudios usados no projeto
│   ├── sample_original.mp3
│   └── voz_clonada_final.mp3
│
├── imagem/                  # Foto usada no video
│   └── foto_original.png
│
├── output/                  # Resultado final do projeto
│   └── video_final.mp4
│
└── extras/                  # Prints e descrição do processo de criação.
    └── notas_processo.md
