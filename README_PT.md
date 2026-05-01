# Relatório de Exposição de Repositório Malicioso do Gerador de Endereços Vanity TRX

Este documento tem como objetivo apresentar publicamente evidências focadas em repositórios maliciosos relacionados a geradores de endereços vanity TRX/endereços vanity Tron/endereços vanity de carteira USDT. Ele prova que **Powercodess** e **Pandaoyoo** são controlados pela mesma pessoa, orquestrando um esquema através de múltiplos repositórios de "exposição de backdoor → difamação sincronizada → lançamento de uma 'versão limpa'". A essência é atacar maliciosamente projetos legítimos de geração de endereços vanity TRX/Tron/USDT e colher a confiança dos usuários. Seus repositórios associados representam riscos de segurança extremamente altos.

---

## ⚠️ Declaração Central

Após comparar evidências de múltiplas fontes, as duas contas seguintes e seus repositórios associados são controlados pela mesma pessoa, visando principalmente ferramentas de geração de endereços vanity TRX/Tron/USDT. O propósito é difamar maliciosamente outros, encenar incidentes de "exposição de backdoor" e então promover seus próprios repositórios de geração de endereços vanity TRX chamados "versão corrigida", apresentando riscos de roubo de moedas e colheita de tráfego:

- **Conta 1**: Powercodess, Repositório Associado: https://github.com/Powercodess/profanity-tron (Alegando expor backdoors do gerador de endereços vanity TRX)
- **Conta 2**: Pandaoyoo, Repositório Associado 1: https://github.com/Pandaoyoo/profanity-tron (Conteúdo de difamação replicado); Repositório Associado 2: https://github.com/Pandaoyoo/profanity-new-tron (Autodenominado "versão segura" do gerador de endereços vanity TRX/Tron/USDT)

---

## 📅 Linha do Tempo Principal (Atualizações Sincronizadas, Prova da Mesma Pessoa)

| Tempo | Conta | Operação de Repositório | Comportamento Central (Relacionado ao Gerador de Endereços Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Tempo pouco claro (antes de 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Publicou "relatório-de-auditoria-de-evidências-sólidas-de-backdoor-roubo-u-de-profanity-tron", alegando que repositórios relacionados ao gerador de endereços vanity TRX/Tron têm backdoors como exfiltração de chaves privadas |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Tempo | Conta | Operação de Repositório | Comportamento Central (Relacionado ao Gerador de Endereços Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Sincronizado com o tempo acima | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | Replicação 1:1 do relatório de auditoria do Powercodess, com conteúdo, formatação, números de linha de código e links de evidência idênticos sem qualquer modificação, expandindo o escopo da difamação de "backdoor" do gerador de endereços vanity TRX |

| Tempo | Conta | Operação de Repositório | Comportamento Central (Relacionado ao Gerador de Endereços Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Upload em lote de todo o código-fonte, alegando "corrigir backdoors, remover código malicioso oculto", lançando um gerador de endereços vanity TRX/Tron/USDT autodenominado seguro, formando um vínculo sincronizado com os dois repositórios anteriores |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Tempo | Conta | Operação de Repositório | Comportamento Central (Relacionado ao Gerador de Endereços Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-04-25 | Powercodess (Troca de conta) | https://github.com/GenTronx/gpu | Powercodess deletou o repositório e trocou de conta para evitar riscos, Pandaoyoo manteve operações de acompanhamento sincronizadas, mantendo operações de repositórios relacionados ao gerador de endereços vanity TRX malicioso, formando uma cadeia de controle completa |

---

## 🔍 Cadeia de Evidências Central (Prova de Controle pela Mesma Pessoa, Relacionado ao Gerador de Endereços Vanity TRX)

### Evidência 1: Replicação 1:1 do Relatório de Auditoria, Não é Auditoria Independente, Difamação Pura do Gerador de Endereços Vanity TRX

O relatório de auditoria no repositório Pandaoyoo/profanity-tron é completamente idêntico ao relatório do Powercodess/profanity-tron, ambos girando em torno de geradores de endereços vanity TRX/Tron/USDT:

- **Conclusão Central**: "O código-fonte do gerador de endereços vanity TRX contém lógica de exfiltração de chave privada + endereço, parâmetros ocultos, verificação TLS desabilitada"
- **Detalhes do Código**: A localização da função `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), trechos de código centrais, anotações de números de linha apontam para lógica relacionada à geração de endereços vanity TRX
- **Parâmetros Ocultos**: O processo de construção de ofuscação de `pptt` (profanity.cpp:L163-L166), explicação do parâmetro curto `-p`, usado para controlar a exfiltração de chaves privadas durante a geração de endereços vanity TRX
- **Evidências de Apoio**: Link de análise Kanxue (https://bbs.kanxue.com/thread-289060.htm), registros de troca de conta, espaços reservados de imagens são todos idênticos, usados para apoiar o "backdoor" no gerador de endereços vanity TRX

**Conclusão**: Pandaoyoo não conduziu nenhuma auditoria independente, apenas copiou e colou o relatório do Powercodess, visando expandir o escopo da difamação contra projetos legítimos de geração de endereços vanity TRX/Tron/USDT, criando uma ilusão de "múltiplas pessoas fornecendo evidências sólidas".

### Evidência 2: Ritmo de Atualização Sincronizado, Divisão Clara de Trabalho, Desvio de Tráfego em Torno do Gerador de Endereços Vanity TRX

- Powercodess é responsável pela "primeira publicação" do relatório de auditoria de backdoor do gerador de endereços vanity TRX, desempenhando o papel de "expositor de justiça", guiando usuários a questionar projetos legítimos;
- Pandaoyoo é responsável pelo "encaminhamento sincronizado" do relatório, reforçando a impressão negativa do "backdoor" do gerador de endereços vanity TRX, enquanto lança o repositório "profanity-new-tron", autodenominado "versão segura" do gerador de endereços vanity TRX/Tron/USDT, colhendo usuários mal guiados;
- Após Powercodess deletar o repositório e trocar de conta (GenTronx), Pandaoyoo manteve operações de repositórios relacionados de forma sincronizada, formando um ciclo fechado completo de "expor e difamar o gerador de endereços vanity TRX → desviar tráfego para o próprio projeto".

### Evidência 3: Contradição de Lógica Comportamental, Sinais Óbvios de Auto-Orquestração, Lucrando com o Gerador de Endereços Vanity TRX

Se Pandaoyoo é realmente um "restaurador de justiça", por que não publicar independentemente um relatório de auditoria para geradores de endereços vanity TRX/Tron/USDT, mas em vez disso replicar completamente o conteúdo do Powercodess? Por que lançar imediatamente uma "versão corrigida" do gerador de endereços vanity TRX após Powercodess expor o "backdoor"?

**Falha de Lógica Central**: Primeiro difamar projetos legítimos de geração de endereços vanity TRX através do Powercodess → então expandir influência através do Pandaoyoo replicando o relatório → finalmente lançar "versão corrigida" para colher tráfego. A essência é "ladrão gritando peguem o ladrão", auto-orquestrando um esquema para atacar concorrentes e lucrar com ferramentas de geração de endereços vanity TRX/Tron/USDT.

---

## ⚠️ Aviso de Risco de Segurança para Repositórios Relacionados ao Gerador de Endereços Vanity TRX

Seja Powercodess ou Pandaoyoo, os repositórios associados do gerador de endereços vanity TRX/Tron/USDT representam riscos de segurança extremamente altos. Não os use:

1. **Powercodess/profanity-tron**: Alega que o gerador de endereços vanity TRX tem backdoors (exfiltração de chaves privadas, parâmetros ocultos, verificação TLS desabilitada), mesmo se o conteúdo do relatório for verdadeiro, pode ter sido plantado por eles mesmos;
2. **Pandaoyoo/profanity-tron**: Ferramenta de difamação pura, sem funcionalidade real de geração de endereços vanity TRX, usada apenas para difamar projetos legítimos, e altamente associada a contas maliciosas;
3. **Pandaoyoo/profanity-new-tron**: Autodenominado gerador de endereços vanity TRX/Tron/USDT "backdoor corrigido", mas não fornece prova de auditoria de segurança de terceiros, não pode descartar a possibilidade de plantar backdoors de maneira diferente, e o tempo de lançamento está sincronizado com atividades de difamação, com motivos impuros.

---

## 🔧 Recomendações de Segurança (Para Usuários de Ferramentas de Geração de Endereços Vanity TRX/Tron/USDT)

- ⛔ Pare imediatamente de usar todos os geradores de endereços vanity TRX/Tron/USDT e ferramentas relacionadas associados a Powercodess, Pandaoyoo, GenTronx;
- 💰 Se você usou as ferramentas acima para gerar chaves privadas (para carteiras TRX/USDT), é recomendado transferir imediatamente ativos dos endereços correspondentes para evitar roubo de moedas devido a vazamento de chaves privadas;
- ✅ Ao escolher ferramentas de geração de endereços vanity TRX/Tron/USDT, priorize projetos legítimos que passaram por auditorias de segurança de terceiros, têm boa reputação na comunidade e são de código aberto rastreáveis. Não confie em ferramentas alegando "geração rápida, aceleração GPU" sem prova de auditoria.

---

## 📌 Instruções de Denúncia/Proteção de Direitos

Todas as evidências neste documento vêm de repositórios públicos do GitHub, focados em repositórios maliciosos relacionados a geradores de endereços vanity TRX/Tron/USDT, e podem ser diretamente usados como base para denúncia. Direções de denúncia:

- **GitHub Oficial**: Denunciar contas Powercodess, Pandaoyoo por difamação maliciosa de projetos legítimos de geração de endereços vanity TRX, publicidade falsa, auto-orquestração;
- **Comunidades Relacionadas (Comunidades relacionadas a TRX/USDT)**: Encaminhar esta evidência para lembrar outros usuários de ferramentas de geração de endereços vanity TRX/Tron/USDT de evitar riscos e não serem mal guiados.

---

## 📎 Resumo de Links de Evidências (Clicável diretamente para verificação, todos relacionados ao gerador de endereços vanity TRX)

1. **Repositório de Difamação do Gerador de Endereços Vanity TRX do Powercodess**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Repositório de Difamação Replicado do Pandaoyoo**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Repositório do Gerador de Endereços Vanity TRX chamado "Versão Segura" do Pandaoyoo**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Repositório após Powercodess deletar repositório e trocar de conta**: https://github.com/GenTronx/gpu (Falha na análise da página web, este é o endereço de troca de conta oficialmente alegado pelo Powercodess)

5. **Link de Análise Kanxue (Citado no Relatório de Auditoria, relacionado ao backdoor do gerador de endereços vanity TRX)**: https://bbs.kanxue.com/thread-289060.htm (Publicado em 2025, confirmando a existência do backdoor do gerador de endereços vanity TRX, mas não relacionado a este incidente auto-orquestrado)

6. **Evidência de Ataque Malicioso a Repositório Legítimo**: https://github.com/ninazero/tron

   ⚠️ **Aviso Importante**: Este repositório é um projeto de código aberto completamente independente, legítimo e em conformidade. Após confirmação de auditoria, não tem **NENHUMA CONEXÃO** com o incidente de difamação auto-orquestrado do Powercodess/Pandaoyoo mencionado acima. Este repositório é uma vítima inocente de ataques, NÃO um participante. Contas maliciosas conduziram comportamentos de ataque como aumento falso de estrelas neste repositório legítimo (veja imagem de evidência abaixo) em uma tentativa de danificar sua reputação. Todas as contas usadas eram contas zombie de baixa atividade com rastros operacionais óbvios, violando seriamente as diretrizes da comunidade de código aberto. De acordo com rastreabilidade técnica, o atacante está localizado na região de Anhui, e tais atividades ilegais eventualmente enfrentarão sanções legais.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Evidência de Aumento Malicioso de Estrelas pelo Powercodess**: https://github.com/Powercodess/profanity-tron - Este repositório usou um grande número de contas zombie para aumentar maliciosamente estrelas e criar popularidade falsa. O propósito era difamar projetos legítimos de geração de endereços vanity TRX, criando uma ilusão de "múltiplas pessoas fornecendo evidências sólidas" para sua farsa de "exposição de backdoor" auto-orquestrada, finalmente desviando tráfego para seu próprio repositório de "versão corrigida" controlado para colher usuários.

8. **Evidência de Exposição de Favoritos do Navegador**: Através da análise de favoritos do navegador, pode-se ver que o operador está envolvido há muito tempo em atividades da indústria cinza-preta, mas se passa por pessoal de auditoria de segurança para promoção falsa, tentando usar a "justiça" como disfarce para cometer fraude. Seu comportamento é puramente uma farsa auto-orquestrada, essencialmente usando "auditoria" como pretexto para "desvio e colheita de tráfego". De acordo com rastreabilidade técnica, a pessoa está localizada na região de Anhui, e suas atividades ilegais foram registradas. Agências de aplicação da lei relevantes lidarão com isso de acordo com a lei.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Última Atualização**: 2026-05-01 (Sincronizado com o tempo de lançamento do Pandaoyoo/profanity-new-tron, apoiando a relação de associação)

---

## 🌐 Versões Multilíngues

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
