# 🎤 Assistente Multimodal com Inteligência Artificial

Este projeto implementa um assistente inteligente capaz de interagir com o usuário por meio de voz, utilizando tecnologias modernas de processamento de linguagem natural e síntese de fala.

A solução integra diferentes etapas de processamento, desde a captura de áudio até a geração de respostas em linguagem natural e sua conversão em voz.

---

## 🚀 Funcionalidades

- 🎤 Entrada de áudio via upload ou gravação
- 🔄 Conversão automática de áudio para formato WAV
- 🗣️ Transcrição de voz para texto (Speech-to-Text)
- 🧠 Processamento de linguagem natural com IA
- 💬 Geração de respostas inteligentes
- 🔊 Conversão de texto para voz (Text-to-Speech)
- ▶️ Reprodução do áudio gerado

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **OpenAI Whisper** — reconhecimento de fala
- **OpenAI GPT (gpt-4o-mini)** — processamento de linguagem
- **gTTS (Google Text-to-Speech)** — síntese de voz
- **FFmpeg** — conversão de áudio
- **Google Colab** — ambiente de execução

---

## 🏗️ Arquitetura do Sistema

O sistema segue um pipeline estruturado de processamento:

1. Seleção do tipo de entrada (upload ou gravação)
2. Captura do áudio do usuário
3. Pré-processamento (conversão para WAV)
4. Transcrição do áudio (Speech-to-Text)
5. Processamento com modelo de linguagem
6. Geração da resposta
7. Conversão da resposta em áudio
8. Reprodução do áudio

---

## ▶️ Como Executar

1. Abra o notebook no Google Colab  
2. Execute as células sequencialmente  
3. Insira sua chave da API OpenAI  
4. Escolha o tipo de entrada (upload ou gravação)  
5. Interaja com o assistente  

---

## ⚠️ Observações Importantes

- Recomenda-se o uso de arquivos `.wav` para melhor desempenho  
- Alguns navegadores podem bloquear reprodução automática de áudio  
- Em caso de falha na reprodução, o áudio pode ser baixado e executado localmente  

---

## 📊 Diferenciais do Projeto

- Integração de múltiplas tecnologias de IA
- Pipeline completo de processamento de voz
- Tratamento de dados (pré-processamento de áudio)
- Estrutura modular e organizada
- Aplicação prática de IA em contexto real

---

## 🔮 Possíveis Melhorias

- Suporte a entrada por imagem (OCR)
- Interface web interativa (Streamlit ou Flask)
- Histórico de conversas
- Suporte multilíngue
- Deploy em nuvem

---

## 👨‍💻 Autor

**André Reis**

---

## 📎 Licença

Este projeto é de uso educacional e demonstrativo.
