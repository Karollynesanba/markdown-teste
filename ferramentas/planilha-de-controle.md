# 08 · Planilha de controle · Seis etapas

[Início](../README.md) / Operação comercial / Planilha

## Objetivo

Registrar cada ação em tempo real, preservando o histórico até o pagamento.

## Responsável e atualização

O **SDR** atualiza imediatamente após cada ligação, mensagem, agendamento, recontato ou confirmação de resultado.

## As seis colunas

| Etapa | Coluna | Preenchimento conforme o PDF |
| --- | --- | --- |
| 1 | **Atendeu?** | **SIM**: seguir a qualificação. **NÃO**: próxima tentativa do LLM. |
| 2 | **Mandou mensagem?** | **SIM**: enviada. **NÃO**: envio pendente. |
| 3 | **Agendou?** | **AGENDOU LIGAÇÃO** ou **AGENDOU MENSAGEM**. Em aberto: recontato ativo. |
| 4 | **Recontato** | **FEITO**: ação do dia realizada. Em aberto: ação ainda pendente hoje. |
| 5 | **Compareceu?** | O PDF mostra **COMPA...** truncado. Conferir a opção completa na planilha. Em aberto: reunião pendente ou ausência a verificar. |
| 6 | **Pagou?** | **PAGOU** após confirmação; registrar ao lado o valor da venda. Em aberto: negociação ou sem conversão. |

## Passo a passo

1. Localizar o lead e conferir a classe.
2. Atualizar a coluna da ação realizada.
3. Registrar a origem do agendamento.
4. Conferir o recontato do dia atual; uma marcação antiga não comprova contato hoje.
5. Verificar o resultado da reunião.
6. Registrar pagamento e valor somente após confirmação.
7. Conferir se o CRM reflete o mesmo estágio.

## Pasta de referência

O PDF indica [Planilhas do Comercial](https://drive.google.com/drive/folders/15cwhiB-dV-vMxrVVmO9mflxxSH43WuWI). O link foi transcrito do material; acesso, estrutura e automações não foram verificados nesta adaptação.

## Campos em aberto

O modelo usa campos vazios para mais de uma situação. Antes de calcular indicadores, distinguir reuniões futuras de no-shows e negociações abertas de oportunidades encerradas. Não interpretar todo campo vazio como resposta negativa.

## Checklist

- [ ] Registrar atendimento e mensagem.
- [ ] Identificar a origem do agendamento.
- [ ] Atualizar o recontato do dia.
- [ ] Conferir presença ou ausência.
- [ ] Confirmar pagamento e valor.
- [ ] Revisar divergências com o CRM.

**Próxima leitura:** [Panorama anual](../indicadores/panorama-anual.md).
