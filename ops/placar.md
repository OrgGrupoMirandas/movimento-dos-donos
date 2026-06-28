# Placar do Movimento — Operacional

> ## Familias que plantaram a semente ate hoje: `_____ / 100.000`
> Label publico do placar. Criterio UNICO = contrato de consorcio fechado (a semente plantada). Nao confundir com "familia livre" — o placar conta a decisao, nao a contemplacao.

## Criterio oficial

Uma familia entra no placar quando **fecha contrato de consorcio imobiliario pela Yes Consorcio**.
Esse e o momento em que a familia escolheu o caminho — plantou a semente.
Criterio UNICO: contrato fechado. Contemplacao e aquisicao do imovel sao bonus de nivel, NAO sao o criterio de contagem.

## Niveis de progresso

| Nivel | Evento | Conta no placar? | Fonte |
|-------|--------|------------------|-------|
| Semente | Contrato fechado | SIM — marco oficial | Bitrix deal ganho cat 0 |
| Raiz | Carta contemplada | Bonus (sobe nivel do Dono) | CS / administradora |
| Arvore | Imovel adquirido | Bonus (case de prova social) | CS / escritura |

## Regras de integridade

1. **1 familia = 1 CPF titular.** Mesma familia com 2 cartas conta 1 vez.
2. **Contagem retroativa:** todo contrato Yes desde o inicio da operacao (2024+).
3. **Atualizacao:** deal ganho no Bitrix cat 0 incrementa automaticamente.
4. **Auditoria trimestral:** cruzar placar vs contratos reais na administradora.
5. **O numero e publico.** Se alguem pedir a lista, ela existe.

## Marcos de celebracao

| Marco | Acao |
|-------|------|
| Cada 100 familias | Post comemorativo (Carla + Ralph) |
| Cada 1.000 familias | Evento de celebracao da tribo |
| 10.000 familias | Marco historico — campanha especial |
| 100.000 familias | Missao cumprida |

## Responsaveis

| Etapa | Dono |
|-------|------|
| Contagem automatica (webhook Bitrix) | Neriton |
| Publicacao de marco | Carla + Ralph |
| Auditoria trimestral | Edwards + Midiane |
| Exibicao no site/perfil | Ralph |

## Implementacao tecnica — a construir

- [ ] Webhook Bitrix: deal ganho cat 0 → incrementa contador
- [ ] API/endpoint publico para consultar o numero atual
- [ ] Widget para site (codigo31.anthonymiranda.com.br)
- [ ] Integracao com IG bio (atualizacao manual mensal)
- [ ] Dashboard interno com breakdown por mes/closer
