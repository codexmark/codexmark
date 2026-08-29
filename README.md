<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Rayner Mesquita — Software Engineer, Systems Builder" />

<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=for-the-badge&logo=linkedin&logoColor=E05B66)](https://www.linkedin.com/in/raynermesquita)
[![Kram](https://img.shields.io/badge/Kram-Public_Beta-7E1722?style=for-the-badge&logo=go&logoColor=white)](https://github.com/codexmark/kram)
[![Site](https://img.shields.io/badge/kram.codexmark.com.br-111111?style=for-the-badge&logo=vercel&logoColor=E05B66)](https://kram.codexmark.com.br)
[![GitHub](https://img.shields.io/badge/@codexmark-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/codexmark)

</div>

## Olá, eu sou o Rayner.

Engenheiro de software e construtor de sistemas com uma trajetória iniciada em **2004**. Gosto de problemas que exigem atravessar camadas: da memória e da rede à arquitetura de produto, da automação à experiência de quem usa.

Hoje concentro meu trabalho na interseção entre **engenharia de sistemas, segurança e inteligência artificial** — criando ferramentas locais, aplicações completas e infraestrutura que permanece compreensível, observável e sob controle.

> **Meu princípio de engenharia:** tecnologia sofisticada só é realmente boa quando continua confiável no mundo real.

## Em foco agora — Kram

Estou construindo o **[Kram](https://github.com/codexmark/kram)**, um runtime *local-first* para agentes de programação, gateway multi-provider de LLMs e workspace de terminal — implementado do zero em **Go**.

Abaixo, sem edição: o provedor primário falha, o circuit breaker abre, o roteador cai para o próximo provedor do combo e o turno termina — tudo visível na própria UI.

<a href="https://kram.codexmark.com.br">
  <img src="./assets/kram-demo.gif" width="100%" alt="Kram em ação: provider primário falha, circuit breaker abre, fallback assume e responde — com o trail de roteamento visível na TUI" />
</a>

**Evidência, não promessa:**
- **93 decisões de arquitetura** documentadas (trade-offs, reversões e limites assumidos) em [`DECISIONS.md`](https://github.com/codexmark/kram/blob/master/DECISIONS.md);
- release bloqueado por gate reproduzível: **piso de 90% de cobertura**, suite com `-race`, cross-build **para 6 plataformas** (Linux, macOS, Windows, Android/Termux) num binário único `CGO_ENABLED=0`;
- turnos sobrevivem à queda do terminal, streams retomam do token onde pararam, e `Ctrl+G` desfaz o que um turno mudou — resiliência como arquitetura, não como retry solto;
- agent loop com ferramentas, permissões e aprovações; **MCP** e **LSP** integrados; memória e sessões locais em SQLite.

**[Site →](https://kram.codexmark.com.br)** · **[Arquitetura →](https://github.com/codexmark/kram#readme)**

## O que eu construo

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>◉ Sistemas & IA</h3>
      Runtimes de agentes, gateways de LLM, ferramentas CLI/TUI, integração MCP/LSP, persistência local e automação de workflows.
    </td>
    <td width="50%" valign="top">
      <h3>◌ Segurança & baixo nível</h3>
      Engenharia reversa, análise de memória, protocolos de rede, anti-cheat, hardening de aplicações, regras de firewall e CompTIA Security+.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>◇ Produtos completos</h3>
      APIs, aplicações web e mobile, autenticação, CRUDs, integrações, bancos relacionais e deploy serverless.
    </td>
    <td width="50%" valign="top">
      <h3>↗ Modernização</h3>
      Evolução de sistemas legados, atualização de stacks, melhorias de segurança, experiência de terminal e arquitetura.
    </td>
  </tr>
</table>

## Stack de trabalho

**Sistemas e backend**

![Go](https://img.shields.io/badge/Go-111111?style=flat-square&logo=go&logoColor=E05B66)
![C](https://img.shields.io/badge/C-111111?style=flat-square&logo=c&logoColor=E05B66)
![C++](https://img.shields.io/badge/C++-111111?style=flat-square&logo=cplusplus&logoColor=E05B66)
![Delphi](https://img.shields.io/badge/Delphi-111111?style=flat-square&logo=delphi&logoColor=E05B66)
![Ruby](https://img.shields.io/badge/Ruby-111111?style=flat-square&logo=ruby&logoColor=E05B66)
![Python](https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=E05B66)

**Dados e infraestrutura**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=flat-square&logo=postgresql&logoColor=E05B66)
![SQLite](https://img.shields.io/badge/SQLite-111111?style=flat-square&logo=sqlite&logoColor=E05B66)
![Linux](https://img.shields.io/badge/Linux-111111?style=flat-square&logo=linux&logoColor=E05B66)

<sub>Também navego por JavaScript/Node, Java/Android, Redis e o que o problema pedir — mas a lista acima é onde moro.</sub>

## Projetos selecionados

| Projeto | O problema | Engenharia |
|---|---|---|
| **[Kram](https://github.com/codexmark/kram)** | Agentes de código locais, observáveis e independentes de provedor | Go · LLM gateway · MCP · LSP · TUI · SQLite |
| **[Req. Codex](https://github.com/codexmark/Req.)** | Elicitação e organização de requisitos com colaboração via Discord | JavaScript · Vercel Functions · Redis/Upstash · autenticação |
| **[MikroTik Firewall Rules](https://github.com/codexmark/BasicMkFirewallrules)** | Hardening de borda contra scans, floods e tráfego inválido | RouterOS · filtros stateful · mitigação de ataques |

## Da curiosidade ofensiva à engenharia defensiva

Minha entrada na programação aconteceu explorando jogos: memória, pacotes, binários e as fronteiras entre cliente e servidor. Com o tempo, transformei esse conhecimento em defesa — desenvolvendo anti-cheats, endurecendo sistemas e projetando controles com uma compreensão prática de como eles podem falhar.

Essa origem ainda define meu jeito de trabalhar: entender o sistema por inteiro, desconfiar de abstrações frágeis e construir mecanismos explícitos de segurança e recuperação.

## Como eu penso engenharia

<p align="center"><code>entender profundamente → reduzir a complexidade → tornar observável → automatizar com controle</code></p>

- **Local-first quando faz sentido:** dados e decisões perto de quem opera o sistema.
- **Confiabilidade antes de espetáculo:** erros visíveis, limitados e recuperáveis.
- **Segurança como arquitetura:** não como uma etapa adicionada no final.
- **Produto de ponta a ponta:** backend, interface, deploy e operação fazem parte do mesmo problema.
- **Aprendizado contínuo:** mais de duas décadas programando e ainda escolhendo desafios que me obrigam a evoluir.

---

<div align="center">

### Vamos construir algo difícil — e fazer funcionar de verdade.

[LinkedIn](https://www.linkedin.com/in/raynermesquita) · [Projetos](https://github.com/codexmark?tab=repositories) · [Kram](https://github.com/codexmark/kram) · [kram.codexmark.com.br](https://kram.codexmark.com.br)

<sub>Porto Velho, Rondônia · Brasil</sub>

</div>