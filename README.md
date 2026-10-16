<p align="center">
  <img src="assets/icon.png" width="112" alt="Ícone do Limitbar">
</p>

<h1 align="center">Limitbar</h1>

<p align="center">
  <b>Seus limites do Claude, a um olhar de distância.</b><br>
  Sessão 5h · Weekly · Fable · créditos extras — direto na barra de menu do macOS.
</p>

<p align="center">
  <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases/raw/main/Limitbar.dmg"><img alt="Baixar para macOS" src="https://img.shields.io/badge/Baixar_para_macOS-Limitbar.dmg-FF5A32?style=for-the-badge&labelColor=17161A"></a>
  <a href="#planos"><img alt="Planos Free, Lite e Pro" src="https://img.shields.io/badge/Planos-Free_%C2%B7_Lite_%C2%B7_Pro-E8A046?style=for-the-badge&labelColor=17161A"></a>
</p>

<p align="center">
  <img alt="Versão" src="https://img.shields.io/badge/vers%C3%A3o-1.9.0-17161A?style=flat-square">
  <img alt="macOS 13 ou mais novo" src="https://img.shields.io/badge/macOS-13%2B-17161A?style=flat-square">
  <img alt="Apple Silicon e Intel" src="https://img.shields.io/badge/Apple_Silicon_%2B_Intel-universal-17161A?style=flat-square">
  <img alt="Teste grátis de 48 horas" src="https://img.shields.io/badge/teste-48h_grátis-17161A?style=flat-square">
  <img alt="Lite vitalício por US$ 2,99" src="https://img.shields.io/badge/Lite_vitalício-US%24_2%2C99-17161A?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases/tree/main/versions"><b>Todas as versões →</b></a>
  &nbsp;·&nbsp;
  <a href="#planos"><b>Comparar planos →</b></a>
</p>

<p align="center">
  <img src="assets/hero.png" width="880" alt="Limitbar na barra de menu do macOS, com o menu de detalhes aberto mostrando sessão, weekly, Fable e créditos">
</p>

---

## Pare de abrir Configurações › Uso no meio do trabalho

O Limitbar mora na barra de menu e mostra quanto resta de cada limite do Claude, o tempo todo. Passe o mouse para ver quando reseta. Quando um limite chega a **80%** ele fica laranja; em **95%**, vermelho. Você vê o aperto chegando antes de ser cortado no meio de uma tarefa.

## Três jeitos de ler

| Texto | Barrinha | Velocímetro |
|:---:|:---:|:---:|
| <img src="assets/style-text.png" width="270" alt="Estilo texto"> | <img src="assets/style-bar.png" width="270" alt="Estilo barrinha"> | <img src="assets/style-gauge.png" width="270" alt="Estilo velocímetro"> |
| Rótulo pequeno, número grande. Mostra o que **sobra** ou o que já foi **usado**. | Barra fria → quente com o % na ponta. Azul quando está tranquilo, vermelha perto do teto. | Mostrador de 250° com ponteiro, de 0 a 100% usado. |

Troque a qualquer momento pelo menu ou em Configurações.

## O que aparece na barra

| Item | O que é | No hover |
|---|---|---|
| **5h** | Sessão de 5 horas, que começa na sua primeira mensagem | `Reseta em 2h13` |
| **Weekly** | Teto semanal de todos os modelos — Claude, Claude Code e app desktop | `Reseta em 3 dias e 4h20` |
| **Fable** | Teto semanal do Fable, e de outros modelos que o seu plano tiver | `Reseta em 3 dias e 4h20` |
| **Créditos** | Uso extra pago, contra o teto mensal | `US$ 12,00 de US$ 50,00` |

Mostre um, dois ou todos. **⌘T** alterna a exibição, **⌘ + arrastar** reordena. **Clique direito** abre o status do Claude (abaixo).

## Status do Claude

Uma bolinha no canto do item mostra a saúde do Claude em tempo real: **verde** quando está tudo no ar, **amarela/laranja** em degradação e **vermelha** em queda. **Clique direito** abre o painel de status — visão geral, cada serviço (Console, API, Code, Cowork e os demais) com seu estado e o histórico recente de incidentes, além do link para o `status.anthropic.com`.

Lê o status público da Anthropic, sem credencial. Dá para desligar em Configurações.

## Projeção de consumo

Não só quanto já foi — **quando vai acabar**. Cada limite mostra para onde o seu ritmo está levando:

- **“Neste ritmo (12%/h): esgota em 1h20 (15:40)”** — em laranja quando acaba antes do reset;
- **“Sobram ~38% no reset”** — quando dá folga.

Aparece no menu, na dica do item da barra e nas notificações. Funciona já nos primeiros minutos da sessão e fica mais esperta com o histórico (pesa mais o ritmo da última hora na sessão e das últimas 24 h na semana).

## Alertas

Uma notificação do macOS quando um limite passa do **aviso** (80%), do **crítico** (95%) e quando **esgota** — uma vez por subida, sem repetir enquanto o uso oscila perto do limiar.

- **Aviso antecipado:** “Sessão de 5h vai esgotar antes do reset” — antes de bater no limite, pela projeção.
- **Aviso de reset:** passou do crítico? O Limitbar avisa quando o limite renovar.
- **Silenciar** pela notificação (1 h ou até o reset) ou pelo menu (30 min, 1 hora, até amanhã).
- **Som** à sua escolha (o padrão segue o modo Foco), vibração do trackpad (experimental) e limiares ajustáveis.

## Histórico

Cada leitura fica guardada **no seu Mac** por 90 dias. Na aba **Histórico**, escolha a métrica e o período (7, 30 ou 90 dias) e veja o **pico**, a **média**, **quantas vezes passou de 95%** e o **tempo que ficou travado** em 100%. **Exportar CSV** leva tudo para uma planilha.

## Tudo numa janelinha

<p align="center">
  <img src="assets/window-settings.png" width="420" alt="Aba Configurações">
  &nbsp;
  <img src="assets/window-license.png" width="420" alt="Aba Licença">
</p>

- **Configurações** — quais limites mostrar, estilo, % restante ou usado, projeção, intervalo de atualização, abrir no login.
- **Alertas** — notificações, aviso antecipado, aviso de reset, som, limiares.
- **Conta** — e-mail, plano do Claude e de onde veio a leitura, com um terminalzinho que registra cada atualização.
- **Histórico** — pico, média, vezes acima de 95%, tempo travado e CSV.
- **Licença** — o seu plano do Limitbar (Free · Lite · Pro), a key e os Macs. Cole a key e pronto: sem conta.
- **Sobre** — versão, procurar atualizações e links.

---

## Planos

Três planos: **Free**, **Lite** e **Pro**. A key é só a sua identidade — o plano fica no servidor de licenças e chega ao app assinado a cada confirmação. Por isso dá para fazer upgrade, assinar ou cancelar **sem trocar de key**.

> [!NOTE]
> **Na versão atual (1.9) ainda não há divisão por plano.** Com licença ativa, tudo está liberado; sem licença, o app funciona por 48 h e depois pede a key. A aba **Licença** já mostra o seu plano.
> A divisão Free · Lite · Pro abaixo passa a valer na **2.0**.

### Resumo

| | **Free** | **Lite** | **Pro** |
|---|:---:|:---:|:---:|
| **Para quem** | quer só os números na barra | quer o Limitbar completo da série 1.x, pagando uma vez | quer tudo, inclusive o que chega na 2.x |
| **Preço** | grátis | **US$ 2,99**<br><sub>pagamento único</sub> | **US$ 9,99**<br><sub>pagamento único</sub><br>ou **US$ 1,99/mês** |
| **Disponível** | na 2.0 | **agora** — é a licença vitalícia | na 2.0 |
| **Precisa de key** | não | sim | sim |
| **Macs ao mesmo tempo** | — | 1 | **2** |
| **Teste grátis** | — | — | 14 dias (na 2.0) |

### Recurso por recurso

| Recurso | Free | Lite | Pro |
|---|:---:|:---:|:---:|
| Limites na barra — 5h, Weekly, Fable, Créditos | ✓ | ✓ | ✓ |
| Reset no hover · ⌘T · ⌘ + arrastar | ✓ | ✓ | ✓ |
| Três estilos — texto, barrinha, velocímetro | ✓ | ✓ | ✓ |
| Cores de aviso na barra (80% / 95%) | ✓ | ✓ | ✓ |
| Status do Claude — bolinha + painel de incidentes | ✓ | ✓ | ✓ |
| Atualização dentro do app (1 clique) | ✓ | ✓ | ✓ |
| **Histórico** — 7/30/90 dias, pico, média, tempo travado | — | ✓ | ✓ |
| **Exportar CSV** | — | ✓ | ✓ |
| **Alertas** — aviso, crítico, esgotou, reset, silenciar, som | — | ✓ | ✓ |
| **Projeção de consumo** — “esgota em 1h20” | — | ✓ | ✓ |
| **Aviso antecipado** — antes de bater no limite | — | ✓ | ✓ |
| **Recursos novos da série 2.x** | — | — | ✓ |

O **Lite** é tudo o que o Limitbar tem até a 1.8 — e pode atualizar para a 2.x sem perder nada disso. O que for **novo** na 2.x fica no **Pro**.

### Preços

| Opção | Preço | O que você leva | Quando |
|---|---|---|---|
| **Lite vitalício** | US$ 2,99 — uma vez | Lite para sempre · 1 Mac | agora |
| **Pro vitalício** | US$ 9,99 — uma vez | Pro para sempre · 2 Macs | na 2.0 |
| **Pro mensal** | US$ 1,99/mês | Pro enquanto a assinatura estiver em dia · 2 Macs | na 2.0 |
| **Upgrade Lite → Pro** | US$ 6,99 — uma vez | Pro vitalício para quem já tem Lite — inclusive quem comprou na série 1.x | na 2.0 |

### Teste grátis

| | Hoje (1.9) | A partir da 2.0 |
|---|---|---|
| **Duração** | 48 horas | 14 dias |
| **O que libera** | tudo | **Pro** completo |
| **Precisa de key ou cartão** | não | não |
| **Quando acaba** | os números ficam bloqueados até ativar uma key | o app **não trava**: cai para o **Free** e você escolhe se quer Lite ou Pro |

### Regras do jogo

- **Você nunca perde o que comprou.** Vitalício é vitalício — Lite ou Pro.
- **Comprou a licença vitalícia na série 1.x? Você tem Lite vitalício.** Nada a fazer: a aba Licença mostra **Lite · vitalício · série 1**. Na 2.0, o upgrade para o Pro sai por US$ 6,99.
- **Assinatura soma, não substitui.** Tem Lite e assina o Pro? É Pro enquanto a assinatura valer; quando ela acabar, você volta para o Lite — não para o Free.
- **Cancelar não corta na hora.** O Pro mensal vale até o fim do período que você já pagou.
- **Pagamento atrasou?** O Pro continua por **7 dias** enquanto a cobrança é refeita.
- **Mudou de plano?** O app fica sabendo na próxima confirmação — ele reconfere sozinho uma vez por dia, sem você fazer nada.

### Macs

- **Lite:** 1 Mac. **Pro:** 2 Macs ao mesmo tempo.
- **Trocar de Mac:** no antigo, Licença › **Remover licença deste Mac** — a vaga fica livre para o novo. Perdeu o Mac antigo? Fale com o suporte que a gente libera.
- **O plano diminuiu** (por exemplo, a assinatura Pro acabou e você tinha 2 Macs): o Mac ativado **primeiro** continua normalmente; o outro pede para liberar uma vaga ou voltar ao Pro.

### Sem internet

- A licença é confirmada online **uma vez** e depois o app reconfere sozinho uma vez por dia, quando há conexão. Sem internet, funciona normalmente por **até 44 dias**.
- **A partir da 2.0, ficar offline não trava o app:** o que você **comprou** (Lite ou Pro vitalício) continua valendo; o que tem **prazo** (assinatura, cortesia) espera a próxima conexão para ser reconferido.

### Comprar

<!-- TROQUE o link abaixo pelo seu checkout (Lemon Squeezy, Stripe Payment Link, Gumroad…) -->
**[Comprar Lite vitalício — US$ 2,99 →](COLE_AQUI_O_LINK_DO_CHECKOUT)**

Pro vitalício, Pro mensal e upgrade chegam junto com a **2.0**.

A key chega no e-mail da compra. No app (com internet): menu do Limitbar › **Licença…** › cole › **Ativar**.

---

## Instalar em 1 minuto

1. [**Baixe o Limitbar.dmg**](https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases/raw/main/Limitbar.dmg), abra e arraste o Limitbar para **Aplicativos**.
2. Abra o app. O macOS vai bloquear na primeira vez — clique em **OK**.
3. Vá em **Ajustes do Sistema › Privacidade e Segurança**, role até **Segurança** e clique em **Abrir Mesmo Assim** (senha do Mac ou Touch ID).
4. Na janela seguinte, clique em **Abrir**. Pronto: daqui em diante ele abre normalmente.

Quando o macOS pedir acesso ao Keychain, clique em **Sempre permitir** — é assim que o Limitbar lê o login do Claude que já está no seu Mac.

**Atualizar** é um clique: quando sai versão nova, o menu mostra **Nova versão — Baixar e instalar** e o Limitbar baixa, confere (sha256), troca e reinicia sozinho. Sem “Abrir Mesmo Assim” de novo.

<details>
<summary><b>Por que o macOS bloqueia na primeira vez?</b></summary>
<br>
O Limitbar é distribuído fora da App Store. O macOS pede que você aprove uma vez qualquer app baixado dessa forma. Depois da aprovação, ele abre como qualquer outro app.
</details>

## Privacidade

- Usa o login que você **já tem** (app Claude para desktop ou Claude Code). Não pede senha nem API key.
- Credenciais ficam no **Keychain** do seu Mac.
- **Histórico, projeção e alertas são calculados no seu Mac** — percentuais e horários de reset, nada de conteúdo. Nada disso sai dele, e dá para desligar e apagar o histórico quando quiser.
- As chamadas de rede vão para a **Anthropic**, para ler o seu próprio uso. Fora isso, só a checagem diária de atualização e a confirmação da licença: a key, um código do Mac (um hash, não o número de série), o nome do Mac e a versão do app. A resposta traz o seu plano, assinado pelo servidor e conferido no seu Mac. Nada de analytics.

## Perguntas frequentes

<details>
<summary><b>Qual a diferença entre Lite e Pro?</b></summary>
<br>
O <b>Lite</b> é o Limitbar completo da série 1.x — barra, status, histórico, alertas e projeção — para 1 Mac, pagando uma vez. O <b>Pro</b> tem tudo isso, mais os recursos novos da série 2.x, e vale para 2 Macs. Os dois existem como pagamento único; o Pro também tem assinatura mensal.
</details>

<details>
<summary><b>Já comprei a licença vitalícia. O que muda para mim?</b></summary>
<br>
Nada que você precise fazer. A sua licença é <b>Lite vitalício</b>: continua valendo para sempre, inclusive na 2.x, com tudo o que a série 1.x tem. Se quiser o Pro, o upgrade sai por <b>US$ 6,99</b> quando a 2.0 sair.
</details>

<details>
<summary><b>Vitalício ou mensal?</b></summary>
<br>
O <b>Pro vitalício</b> (US$ 9,99) se paga em cerca de 5 meses de assinatura. O <b>mensal</b> (US$ 1,99) é para experimentar sem compromisso ou usar por uma temporada: cancele quando quiser e ele vale até o fim do período pago.
</details>

<details>
<summary><b>O que acontece se eu cancelar a assinatura?</b></summary>
<br>
O Pro continua até o fim do período que você já pagou. Depois, você volta para o plano que tinha comprado — Lite, se tiver, ou Free.
</details>

<details>
<summary><b>O que acontece quando o teste acaba?</b></summary>
<br>
Na versão atual (1.9), depois das 48 horas os números ficam bloqueados e um cadeado aparece na barra; cole a key e tudo volta na hora. A partir da 2.0 o teste vira <b>14 dias de Pro</b>, e quando acaba o app não trava: passa para o Free.
</details>

<details>
<summary><b>Em quantos Macs posso usar?</b></summary>
<br>
<b>Lite:</b> 1 Mac. <b>Pro:</b> 2 Macs ao mesmo tempo. Para trocar de Mac, abra <b>Licença › Remover licença deste Mac</b> no antigo e ative no novo. Perdeu o Mac antigo? Fale com o suporte que a gente libera.
</details>

<details>
<summary><b>Minha key começa com LB1 ou LB2. Faz diferença?</b></summary>
<br>
Não para você. <code>LB1</code> são as keys vendidas na série 1.x (Lite vitalício); <code>LB2</code> são as keys novas, emitidas pelo servidor de licenças. As duas ativam igual — o plano vem do servidor, não da key.
</details>

<details>
<summary><b>É um app oficial da Anthropic?</b></summary>
<br>
Não. O Limitbar é independente. Mostra os mesmos números que você vê em Configurações › Uso do Claude, da sua própria conta.
</details>

<details>
<summary><b>Preciso ter o Claude Code?</b></summary>
<br>
Não. Se você usa o app Claude para desktop, o Limitbar usa essa sessão. Se usa o Claude Code, pode usar esse login. Dá também para colar uma sessionKey manualmente.
</details>

<details>
<summary><b>Funciona com quais planos do Claude?</b></summary>
<br>
Com os planos que mostram limites em Configurações › Uso, como Pro, Max e Team. Limites que o seu plano não tem simplesmente não aparecem.
</details>

---

<p align="center">
  <sub>Feito pela <b>BigHeadStudios</b>.<br>
  Limitbar é um app independente, sem afiliação, patrocínio ou endosso da Anthropic. Claude é marca da Anthropic, PBC.</sub>
</p>
