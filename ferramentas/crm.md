# Comandos e organização do CRM

[Início](../README.md) / Apoio à operação / CRM

## Objetivo

Organizar os cards após cada interação e localizar os materiais de qualificação, agendamento e acompanhamento.

> Os atalhos e movimentações documentam a operação do PDF. Dependem da configuração real do CRM e não são implementados por este repositório.

## Classes e materiais

Selecionar **Forms Classe A**, **Forms Classe B** ou **Forms Classe C**. Consulte os limites em [Classificação de leads](../processos/classificacao-de-leads.md).

O PDF menciona os rótulos legados `FUDIDO` e `FAZEMOS` ao explicar o corte de R$ 20 mil. A sequência operacional usa Forms por classe; confirmar com a administração do CRM se esses rótulos ainda existem antes de utilizá-los.

## Comandos e movimentações

| Situação | Comando ou gatilho citado | Destino ou ação |
| --- | --- | --- |
| Oferta de horário | `/passei horário` | Envia mensagem e move para **Passei Horário** |
| Agendamento confirmado | “Agendado”, “Marcado” ou solicitação de Instagram | Move para **Agendado** |
| Ausência na reunião | `/no show` | Move para **No Show** |
| Não fechou | `/não fechou` | Move para **Não Fechou** |
| Pagamento confirmado | `/pagou` | Move para **Pagou** |
| Saiu da call sem pagar | `/negociação (nome do closer)` | Move para negociação do closer correspondente |
| Confirmação pelo Calendly | `/calendly` | Envia mensagem e **Ficou Claro**; move para **Calendly** |
| Sem capacidade de investimento | Material **Venda 10x** | Move para **Low Ticket**, conforme a automação |

A qualificação também menciona `/passei`. Confirmar o atalho ativo. No comando de negociação, substituir o campo pelo closer responsável conforme o padrão configurado.

## Calendly

A mensagem descrita confirma o horário. Quando há sócio, confirma também sua presença; caso contrário, confirma apenas o horário pré-agendado. Conferir o envio e a movimentação do card.

## Biblioteca de materiais citados

- Forms Classe A, B e C.
- Vídeo da Brenda.
- Áudio **AGENDOU**.
- **Como Faço**.
- **Ativação 1 Hora**.
- **Recorde de Faturamento**.
- **Especialista**.
- **Ficou Claro**.
- **Venda 10x**.

O PDF não inclui links ou conteúdo integral desses materiais. Localizá-los no CRM antes de executar os fluxos.

## Checklist

- [ ] Conferir lead e classe.
- [ ] Usar o comando realmente configurado.
- [ ] Conferir a movimentação do card.
- [ ] Identificar o closer na negociação.
- [ ] Confirmar pagamento antes de usar `/pagou`.
- [ ] Manter a [planilha](planilha-de-controle.md) consistente com o CRM.
