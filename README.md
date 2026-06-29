## EchoAI – Transcrição de Áudio com Whisper

Ferramenta web para transcrição de áudio em português via API Whisper da OpenAI.
Suporta microfone ao vivo, upload de vídeo (.mp4) e áudio (.mp3).

**Stack:** Python · Streamlit · OpenAI Whisper API · PyDub · MoviePy

**Como rodar:**
pip install -r requirements.txt

streamlit run app.py

**⚠️ Dependência externa (FFmpeg)**

Este projeto utiliza o **FFmpeg.exe** para processamento de áudio e extração de trilhas de vídeo.

no Linux: geralmente já vem instalado no sistema.
no Windows / macOS: é necessário que vc faça a instalação manualmente.

Após o download, é preciso adicionar o executável ffmpeg.exe na pasta do projeto ou no PATH do sistema.
