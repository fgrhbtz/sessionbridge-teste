# SessionBridge — versão de testes 0.4.1

Produção musical a distância: quem hospeda roda a DAW (FL Studio, Ableton...) e recebe até 4 visitantes; quem visita vê a janela da DAW, ouve o master em estéreo, conversa por voz, câmera e chat e assume mouse e teclado quando recebe o controle. Funciona entre Windows e Mac, em qualquer combinação.

**Guia completo para produtores (o que é, instalação, primeira sessão e o que testar):** https://fgrhbtz.github.io/sessionbridge-teste/

## Baixar

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 | [SessionBridge-Setup.exe](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-Setup.exe) |
| Mac com chip Apple (M1 a M4) | [SessionBridge-mac-arm64.dmg](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-mac-arm64.dmg) |
| Mac Intel | [SessionBridge-mac-x64.dmg](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/SessionBridge-mac-x64.dmg) |
| Manual (3 páginas) | [Manual-SessionBridge.pdf](https://github.com/fgrhbtz/sessionbridge-teste/releases/latest/download/Manual-SessionBridge.pdf) |

Todos na sessão devem estar na **mesma versão: 0.4.1**. Quem ainda está na 0.4.0 consegue entrar, mas sem as novidades abaixo; quem está na 0.3 entra sem câmeras e sem a lista de participantes.

O app ainda não é assinado:
- **Windows:** na tela azul, "Mais informações" › "Executar assim mesmo".
- **Mac:** botão direito no app › Abrir. No macOS 15: Ajustes do Sistema › Privacidade e Segurança › "Abrir Mesmo Assim".

## Como testar (em dupla)

1. Os dois instalam. Quem hospeda coloca o plugin SessionBridge no master da DAW (no Mac, antes clica em "Instalar plugin" no app).
2. Quem hospeda clica em "Hospedar" e manda o código de 6 letras.
3. O outro clica em "Entrar" e digita o código; quem hospeda aceita.
4. Liguem o microfone ("Ligar microfone"), de preferência com fone de ouvido, e produzam uns 15–20 minutos passando o controle de um para o outro.

A primeira conexão do dia pode levar até 1 minuto (o servidor está acordando).

## Novidades da 0.4.1

- **Mouse próprio do visitante (Windows):** quem hospeda continua com o mouse livre enquanto o visitante mexe na DAW. Clique, clique direito e teclado do visitante não movem o seu mouse; arrastar, girar knob e rolar usam o seu mouse por um instante e o devolvem no mesmo lugar. Uma seta laranja com o nome do visitante mostra onde ele está. Para voltar ao jeito antigo: "Mouse do visitante" › "Compartilhado". No Mac continua compartilhado.
- **Conexão entre redes que bloqueavam a ligação direta:** quando precisa, a sessão passa por um servidor de apoio (TURN). Se antes não conectava com alguém, tente de novo.
- **Pedido de entrada no widget:** Aceitar e Recusar sem abrir a janela principal.
- **A DAW coberta por outra janela não fica mais preta** para quem visita.
- Avisos claros quando a conexão não fecha, quando cai e quando quem hospeda tira alguém da sala; o chat não duplica mais ao entrar de novo.

## Novidades da 0.4

- **Grupos:** até 4 visitantes na mesma sala, com o mesmo código. Todos veem a DAW e ouvem o master; um controla por vez, e os pedidos de controle entram numa fila. A voz é em grupo e o chat mostra quem escreveu.
- **Câmeras:** cada um pode ligar a câmera e ver os outros em miniatura (começa desligada).
- **Só a DAW:** quem visita vê e comanda só a janela da DAW escolhida por quem hospeda, nunca o resto do computador.
- **Trava do controle:** esbarrar no mouse não tira mais o controle de quem visita; quem hospeda retoma com Ctrl+Shift+Espaço (Control no Mac) ou com "Retomar controle".
- **Widget flutuante:** quem hospeda ganha uma lingueta na borda direita da tela, por cima da DAW, com a sala, o controle, o microfone, a câmera e o "Gravar".
- **Gravar:** grava a janela da DAW e o master num MP4 em Vídeos › SessionBridge.
- **Visual novo:** o app, o widget e o plugin agora seguem a mesma identidade do guia e do manual.
- A sala não cai mais sozinha depois de 15 minutos sem ninguém entrar.

## Novidades da 0.3

- Bloco "Licença" na tela inicial. Nesta versão de testes tudo é liberado; no futuro, com chave de licença o uso é livre e sem chave é 1 hora por dia.

## Novidades da 0.2

- Conversa por voz entre os dois produtores, com redução de eco e ruído, separada do master.
- Chat de texto no app.
- Mac: botão "Instalar plugin" no próprio app.

Este repositório só distribui os instaladores e o guia; o código do projeto é privado.
