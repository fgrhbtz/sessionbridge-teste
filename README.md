# SessionBridge — versão de testes 0.2

Produção musical a distância: quem hospeda roda a DAW (FL Studio, Ableton...) e quem visita vê a tela, ouve o master em estéreo, conversa por voz e chat e assume mouse e teclado quando recebe o controle. Funciona entre Windows e Mac, em qualquer combinação.

**Guia completo para produtores (o que é, instalação, primeira sessão e o que testar):** https://fgrhbtz.github.io/sessionbridge-teste/

## Baixar

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 | [SessionBridge-Setup.exe](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-Setup.exe) |
| Mac com chip Apple (M1 a M4) | [SessionBridge-mac-arm64.dmg](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-mac-arm64.dmg) |
| Mac Intel | [SessionBridge-mac-x64.dmg](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-mac-x64.dmg) |
| Manual (3 páginas) | [Manual-SessionBridge.pdf](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/Manual-SessionBridge.pdf) |

Os dois produtores precisam estar na **mesma versão**.

O app ainda não é assinado:
- **Windows:** na tela azul, "Mais informações" › "Executar assim mesmo".
- **Mac:** botão direito no app › Abrir. No macOS 15: Ajustes do Sistema › Privacidade e Segurança › "Abrir Mesmo Assim".

## Como testar (em dupla)

1. Os dois instalam. Quem hospeda coloca o plugin SessionBridge no master da DAW (no Mac, antes clica em "Instalar plugin" no app).
2. Quem hospeda clica em "Hospedar" e manda o código de 6 letras.
3. O outro clica em "Entrar" e digita o código; quem hospeda aceita.
4. Liguem o microfone ("Ligar microfone"), de preferência com fone de ouvido, e produzam uns 15–20 minutos passando o controle de um para o outro.

A primeira conexão do dia pode levar até 1 minuto (o servidor está acordando).

## Novidades da 0.2

- Conversa por voz entre os dois produtores, com redução de eco e ruído, separada do master.
- Chat de texto no app.
- Mac: botão "Instalar plugin" no próprio app.

Este repositório só distribui os instaladores e o guia; o código do projeto é privado.
