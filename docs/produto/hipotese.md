# Hipótese de valor

> **Acreditamos que** uma agenda online que garante o horário a quem escolhe primeiro, com lembretes automáticos por WhatsApp e e-mail 24 horas antes e confirmação "Sim/Não",
> **para** clínicas de estética com mais de um profissional e seus pacientes,
> **vai gerar** menos faltas e nenhuma marcação duplicada.
> **Saberemos que é verdade quando** a taxa de faltas das clínicas cair e as marcações duplicadas chegarem a zero.

## Como medir

| Métrica | Como se calcula | Linha de base | Meta |
|--|--|--|--|
| Taxa de faltas (métrica principal) | Atendimentos sem comparecimento ÷ atendimentos agendados, por mês | *levantar no discovery* | *definir no checkpoint 02* |
| Marcações duplicadas | Horários do mesmo profissional com mais de um agendamento confirmado | *levantar no discovery* | 0 |
| Confirmação pelo lembrete | Lembretes respondidos com "Sim" ÷ lembretes enviados | — | *definir no checkpoint 02* |

## Como testar

- **Discovery (checkpoint 02):** entrevistar clínicas para levantar a taxa de faltas atual e como a agenda é feita hoje.
- **Protótipo (checkpoint 03):** pacientes e recepcionistas navegam no fluxo de agendamento e de confirmação pelo lembrete.

## IA no produto

A regra 01 do bootcamp exige **IA como parte da proposta de valor**.

**Decisão do POD (16/11/2026):** a IA do produto é um **assistente no WhatsApp para os profissionais da clínica**, que responde a perguntas sobre a agenda do dia, os clientes e os procedimentos. A previsão do risco de falta, proposta no checkpoint 01, foi **descartada**.

> Acreditamos que **um assistente de IA no WhatsApp que responde aos profissionais sobre a agenda do dia, os clientes e os procedimentos**, para profissionais de clínicas de estética, vai gerar menos tempo gasto procurando informação entre um atendimento e outro. Saberemos que é verdade quando *(métrica e meta a definir no AI Canvas)*.

Definido pela PO em 17/11/2026: só o profissional usa o assistente, reconhecido pelo número ou pelo nome, e as respostas trazem apenas nome do cliente, data, horário e procedimento (RN20 a RN22 da [especificação funcional](../specs/especificacao-funcional.md)).
