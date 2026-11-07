# Gears of War 3 — Dublagem PT-BR (COGBox)

A campanha inteira de **Gears of War 3** dublada em português do Brasil, para quem joga pelo [COGBox](https://github.com/Shagg88/COGBox).

O jogo já tem texto oficial em português. Este pacote adiciona **as vozes**: cinemáticas, diálogos, rádio e falas de combate.

> Projeto de fã, sem fins lucrativos e sem ligação com a Microsoft, a The Coalition ou a Epic Games. Você precisa ter o jogo original.

## O que vem no pacote

- **Campanha dublada:** diálogos, cinemáticas, falas de rádio e falas de combate (mais de 6.000 falas), com vozes diferentes para os personagens principais e para os NPCs.
- **9 vídeos pré-renderizados dublados** (aberturas, finais e flashbacks). A voz original fica bem baixa por baixo da dublagem, e música, efeitos e gritos continuam os originais.
- **Gritos e risadas sem palavras** continuam com o áudio original do jogo.
- **DualSense (opcional, sem DSX):** gatilhos adaptáveis por arma, rádio e motosserra no alto-falante do controle. É uma opção do instalador.
- **Instalador com desinstalação:** nada do COGBox é substituído.

## Download

Baixe o `.zip` mais recente na página de [**Releases**](https://github.com/Gears3PTBR/Gears3DublagemPTBr/releases/latest).

**Novidades da v1.2:** DualSense sem DSX e sem app, como opção do instalador, e a cena da morte do Prescott com as falas refeitas. Já tem a v1.1? Rode o instalador da v1.2 por cima, sem desinstalar antes.

## Requisitos

- COGBox **0.3.7 ou mais novo**, com o Gears of War 3 adicionado.
- Windows 10 ou 11.
- Cerca de 2,5 GB livres no disco (os vídeos originais ganham cópia de segurança).

## Como instalar

1. Extraia o `.zip` **dentro da pasta do COGBox** (a que tem o `CogBox.exe`).
2. Feche o jogo e abra o `Instalador.exe` da pasta extraída.
3. Confira a pasta do COGBox, marque o DualSense se quiser e clique em **INSTALAR**.
4. Jogue pelo COGBox normalmente, com o jogo em **português ou em inglês**. Em outros idiomas o jogo usa outras vozes, e a dublagem não toca nas falas.

## Como desinstalar

Abra o `Instalador.exe` de novo e clique em **Desinstalar**. Tudo volta a ser como era.

## Quando o COGBox atualizar

A dublagem é um plugin que fica ao lado do COGBox e não depende da versão dele. Se uma atualização apagar a pasta do jogo e a dublagem sumir, rode o `Instalador.exe` de novo.

Se já existir outro mod com `version.dll`, o instalador **não sobrescreve** o arquivo dele: avisa e para. Tire ou renomeie o arquivo e rode de novo.

## O que o instalador faz

- Nada é baixado nem enviado pela internet.
- Cria a pasta `dublagem-ptbr` dentro de `Gears3` com as falas e coloca em cada `port-*` o plugin (`version.dll` e `gears2-ptbr.ini`; o nome é esse mesmo, vem do plugin da [dublagem do Gears 2](https://github.com/Gears2-PTBR/Gears2-PTBR)).
- Os vídeos dublados são refeitos a partir dos **seus** vídeos originais (o pacote traz só os patches), e os risos e gritos originais encaixados em algumas falas e os sons da motosserra são tirados do **seu** próprio jogo. Nenhum arquivo do jogo é distribuído aqui.

## DualSense (opcional)

Marque **Instalar também o DualSense** antes de clicar em **INSTALAR**. Já instalou sem ele? Abra o `Instalador.exe` de novo e clique em **Só o DualSense**: o resto fica como está.

**Não tem programa para abrir.** O DualSense é parte do plugin e liga sozinho quando o jogo abre, sem DSX e sem emulação de controle de Xbox. Se você usava a versão antiga, feche o DSX e o app antigo do DualSense, porque eles disputam o controle.

- **Gatilhos:** mudam com a arma na mão.
- **Rádio e motosserra no controle:** só com o **cabo USB**. Com som na TV ou caixa, saem no controle; com fone, o controle fica mudo.
- **Ajustes:** dê dois cliques em `DualSenseConfig.exe`, na pasta do COGBox. Lá você marca qual saída de som é a TV ou caixa e ajusta os volumes. Não precisa deixar aberto, e o que você muda vale na hora, mesmo com o jogo aberto.

Testado com cabo USB no COGBox 0.4.5. O controle precisa ser reconhecido pelo COGBox sem o DSX, o que depende de uma versão recente dele. Por Bluetooth os gatilhos usam outro formato de envio e ainda não foram testados.

## Co-op online (opcional, por System Link)

Não faz parte da dublagem, mas funciona junto: o COGBox 0.4.5 ou mais novo tem System Link, e já jogamos a campanha em dupla pela internet com o [Radmin VPN](https://www.radmin-vpn.com/).

1. Os dois entram na mesma rede do Radmin e conferem que se enxergam (`ping`).
2. No launcher do COGBox, marque **System Link - LAN play** (`--net_system_link=true`) nos dois PCs. A versão do COGBox precisa ser a mesma.
3. Em cada PC, crie o arquivo `Gears3\port-tu6\gow3.toml` com o IP do **outro** jogador no Radmin:
   ```toml
   net_peer_ip = "26.x.x.x"
   ```
4. Em cada PC, defina um nome diferente no `CogBox.ini`:
   ```ini
   [Profile]
   Gamertag=SeuNome
   ```
5. Abra o jogo, um cria o grupo e o outro entra.

Se não aparecer o grupo, mande o `gow3.log` mais recente (pasta `Gears3\logs`) numa issue.

## As vozes

As vozes foram geradas com a [ElevenLabs](https://elevenlabs.io), usando vozes criadas para o projeto ou da biblioteca dela. **Nenhuma é cópia da voz dos atores originais.** As falas foram adaptadas para caber no tempo das falas originais, e o tom segue o do jogo (inclusive nos palavrões). O jogo é para maiores de 18 anos, e a dublagem também.

## Problemas e sugestões

Abra uma [issue](https://github.com/Gears3PTBR/Gears3DublagemPTBr/issues). Se for uma fala específica, diga o capítulo, o personagem e o trecho que você ouviu.

## Curtiu?

Me paga um café pra incentivar o trabalho! Pix: `hfgamez59@gmail.com`. Qualquer valor ajuda, e se não der, tudo bem.

## Créditos

- Dublagem, adaptação, instalador e app DualSense: **HubertFer**.
- [COGBox](https://github.com/Shagg88/COGBox) por Shagg88, que faz o Gears of War rodar nativo no PC.

Gears of War é marca da Microsoft / The Coalition / Epic Games.
