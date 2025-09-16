# Assistente Virtual por Voz

O projeto Sistema de Assistência Virtual por Voz tem como objetivo desenvolver uma solução simples (como prova de conceito), interativa, baseada em Processamento de Linguagem Natural (PLN), capaz de compreender comandos de voz e responder alguns comandos de forma automatizada.

A arquitetura do sistema integra dois módulos principais: speech-to-text, que converte fala em texto, e text-to-speech, que transforma texto em áudio para comunicação com o usuário.

Com essa abordagem, o assistente pode executar ações práticas, como realizar buscas na Wikipedia, abrir o YouTube ou localizar estabelecimentos próximos, oferecendo uma experiência acessível e intuitiva.

O desenvolvimento utilizou as bibliotecas gTTS e speech_recognition, garantindo simplicidade, eficiência e viabilidade de aplicação em cenários reais.


Como funciona:

- O assistente fala para você enviar um arquivo de áudio.

- Você envia um arquivo (.ogg, .mp3, .wav, etc.).

- Ele converte para WAV, compatível com speech_recognition.

- O assistente reconhece a fala em português e executa comandos: YouTube, Pesquisa na Wikipedia, Contar piada, Informar hora, tocar música e Sair do assistente

- O assistente responde em voz usando gTTS.

Arquivos antigos são apagados, mantendo o notebook limpo.
