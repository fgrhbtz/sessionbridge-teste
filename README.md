# SessionBridge — versão de testes

Produção musical a distância: quem hospeda roda a DAW (FL Studio, Ableton...) e o visitante vê a tela, ouve o master em estéreo e assume mouse e teclado quando recebe o controle. Funciona entre Windows e Mac, em qualquer combinação.

## Baixar

Pegue o arquivo do seu sistema na [última versão](../../releases/latest):

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 | `SessionBridge-Setup-0.1.0.exe` |
| Mac com chip Apple (M1 a M4) | `SessionBridge-0.1.0-arm64.dmg` |
| Mac Intel | `SessionBridge-0.1.0-x64.dmg` |
| Manual (3 páginas) | `Manual-SessionBridge.pdf` |

O app ainda não é assinado:
- **Windows:** na tela azul, "Mais informações" › "Executar assim mesmo".
- **Mac:** botão direito no app › Abrir. Detalhes na pág. 3 do manual.

## Como testar (em dupla)

1. Os dois instalam. Quem hospeda coloca o plugin SessionBridge no master da DAW (no Mac, antes clica em "Instalar plugin" no app).
2. Quem hospeda clica em "Hospedar" e manda o código de 6 letras.
3. O outro clica em "Entrar" e digita o código; quem hospeda aceita.
4. Produzam uns 15–20 minutos passando o controle de um para o outro.

A primeira conexão do dia pode levar até 1 minuto (o servidor está acordando).

Este repositório só distribui os instaladores; o código do projeto é privado.
