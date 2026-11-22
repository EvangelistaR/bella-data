# Diário agêntico · checkpoint 02

## 17/11/2026 · Registro da decisão sobre a IA

- **Pedido:** a PO informou a decisão da reunião do POD de 16/11: a IA não será a previsão de falta, e sim um assistente no WhatsApp para os profissionais consultarem agenda do dia, clientes e procedimentos.
- **O que o agente fez:** atualizou `hipotese.md` e o PRD; na especificação, incluiu HU26 (proposta), RN20, PD12–PD14, o item no escopo e a linha no histórico de reuniões.
- **Onde o agente se conteve:** identificação do profissional, dados de cliente liberados no WhatsApp e quem usa o assistente não foram decididos na reunião; ficaram como pendências em vez de regra inventada. A RN20 ("só consulta") foi derivada da palavra "consultar" do pedido: confirmar com o POD.
- **Intervenção do POD:** decisão de produto tomada pelo POD; o agente só registrou.

## 17/11/2026 · Pendências do assistente resolvidas

- **Pedido:** a PO confirmou a RN20 e resolveu PD12 (reconhecimento pelo número ou pelo nome), PD13 (nome, data, horário e procedimento) e PD14 (só o profissional; recepção e administrador pelo sistema).
- **O que o agente fez:** criou RN21 e RN22, reescreveu os critérios da HU26 e marcou PD12–PD14 como resolvidas.
- **Onde o agente interpretou:** retirou "situação da confirmação" da resposta da agenda, porque não está na lista da PD13; trocou o critério "informações do cadastro do procedimento" por "nome, data, horário e procedimento". Apontou à PO o risco de reconhecer o profissional só pelo nome.

## 18/11/2026 · Situação da confirmação no assistente

- **Intervenção do POD:** a PO pediu para incluir a situação da confirmação nas respostas; o agente atualizou RN21, HU26 e PD13.

## 18/11/2026 · Formulário de pesquisa de mercado

- **Pedido:** a PO pediu um formulário de pesquisa para validar o produto com clínicas de estética, como parte do discovery do checkpoint 02.
- **O que o agente fez:** criou `docs/produto/pesquisa-clinicas.md` com 17 perguntas (~5 min), cobrindo: perfil da clínica (1–2), agendamento e faltas (3–7), documentação e contratos (8–10), validação da proposta de valor (11–12), assistente de IA no WhatsApp (13–15) e disposição de adoção (16–17). Incluiu mapeamento de cada pergunta aos artefatos do projeto (métricas, PDs, MoSCoW, AI Canvas, Lean Canvas).
- **Iterações com a PO:** versão inicial tinha 36 perguntas (~20 min); a PO pediu redução para 5 minutos; o agente enxugou para 16 perguntas mantendo cobertura das pendências críticas. Após atualização do repositório com a decisão da IA (branch `checkpoint-02`), o agente revisou o bloco de IA: substituiu a previsão de risco de falta (descartada) pelo assistente no WhatsApp (HU26, RN20–RN22), adicionando a pergunta 13 (como o profissional consulta a agenda hoje) e a pergunta 15 (que informação mais precisa). Total final: 17 perguntas.
- **Onde o agente se conteve:** não alterou `docs/produto/` nem `docs/specs/`; apenas criou o arquivo novo de pesquisa. Não inventou perguntas sobre funcionalidades fora do escopo do MVP.
- **Pendente:** validação do questionário com o POD antes de aplicar nas clínicas.
