---
data: 2026-06-01
data_resolucao: 2026-06-01
tipo: manutenção corretiva
status: concluído
tags: [TI, SIMPRO, usuarios, acesso, sistema, resolvido]
---

# Manutenção do SIMPRO - Limpeza de Usuários e Restauração de Acesso

## Informacoes do Chamado

| Campo                | Detalhe                          |
|----------------------|----------------------------------|
| **Data Abertura**    | 01/06/2026                       |
| **Data Resolucao**   | 01/06/2026                       |
| **Tecnico**          | Eryck Assis                      |
| **Status**           | ✅ Resolvido                      |
| **Prioridade**       | Alta                             |

## Descricao do Problema

Sistema SIMPRO apresentava problemas de acesso impossibilitando que usuários cadastrados realizassem login e utilizassem o sistema. O acesso bloqueado era causado pela presença de usuários não cadastrados na base de dados.

## Diagnostico

| Verificacao                         | Resultado                                  |
|-------------------------------------|-------------------------------------------|
| Acesso ao SIMPRO pelos usuarios     | Impossibilitado - bloqueado                |
| Analise da base de usuarios         | Usuarios nao cadastrados identificados     |
| Causa raiz                          | Conflito de usuarios nao autorizados       |
| Contato com suporte                 | Sem resposta do suporte                    |
| Necessidade de intervencao urgente  | Sim - mantencao manual necessaria          |

## Solucao Aplicada

- Analise completa da estrutura do sistema SIMPRO
- Identificacao e remocao de usuários não cadastrados
- Restauracao do acesso para usuários legítimos do sistema
- Criacao de novos usuários por setor:
  - **Setor Compra** - novo usuario criado
  - **Setor Faturamento** - novo usuario criado
  - **Setor de Agendamento Prédio -2** - novo usuario criado

## Usuarios Criados/Gerenciados

| Setor                          | Acao Realizada            | Status      |
|--------------------------------|---------------------------|-------------|
| Setor Compra                   | Usuario criado            | ✅ Ativo    |
| Setor Faturamento              | Usuario criado            | ✅ Ativo    |
| Setor de Agendamento Prédio -2 | Usuario criado            | ✅ Ativo    |
| Carla                          | Acesso restaurado (-1)    | ✅ Ativo    |

## Resultado Final

> ✅ Problema RESOLVIDO — usuarios nao cadastrados removidos com sucesso.
> Acesso ao SIMPRO restaurado para todos os usuarios cadastrados.
> Novos usuarios criados para os setores solicitados.
> Sistema funcionando normalmente.

## Proximos Passos

| Acao                                      | Prazo       | Status       |
|-------------------------------------------|-------------|--------------|
| Testar acesso dos novos usuarios          | 01/06/2026  | ✅ Concluido  |
| Confirmar funcionamento do SIMPRO         | 01/06/2026  | ✅ Concluido  |
| Monitorar possivel reincidencia           | Proximas 2 semanas | ⏳ Em andamento |
| Fechar chamado                            | 01/06/2026  | ✅ Concluido  |

## Observacoes

> Manutenção realizada de forma autônoma apos analise completa do sistema.
> Nenhuma resposta recebida do suporte oficial.
> Recomenda-se implementar validação automática de usuarios nao cadastrados.
> Possivel criar rotina mensal de limpeza de usuarios no sistema.
> Todos os setores devem ter acesso normalizado ao SIMPRO.

---

*Chamado aberto em 01/06/2026 — Resolvido em 01/06/2026*
