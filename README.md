## EchoAI – Transcrição de Áudio com Whisper

Ferramenta web para transcrição de áudio em português via API Whisper da OpenAI.
Suporta microfone ao vivo, upload de vídeo (.mp4) e áudio (.mp3).

**Stack:** Python · Streamlit · OpenAI Whisper API · PyDub · MoviePy

**Como rodar:**
pip install -r requirements.txt

streamlit run app.py

**⚠️ Dependência externa (FFmpeg)**

Este projeto utiliza o FFmpeg para processamento de áudio e extração de trilhas de vídeo.

Linux: geralmente já instalado no sistema
Windows / macOS: é necessário instalar manualmente

Após o download, adicione o executável ffmpeg.exe na pasta do projeto ou no PATH do sistema.
