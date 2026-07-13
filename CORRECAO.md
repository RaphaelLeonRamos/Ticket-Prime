# Correção AV2 — Ticket-Prime (Alphabit/GeekTop)

**Grupo:** Raphael, João Victor, Mauricio, Juarez, Julio, Lian

| # | Item de Avaliação | Nota | Justificativa |
|---|-------------------|:----:|---------------|
| 01 | Padrão AAA nos Testes | 0,0 | Nenhum método com `// Arrange`, `// Act`, `// Assert`; `UnitTest1.cs` tem método vazio (`Test1() {}`) |
| 02 | Nomenclatura e Independência | 0,5 | Nomes como `HashPassword_ShouldReturnDeterministicSha256` seguem estrutura; zero condicionais |
| 03 | Padrões Arquiteturais | 0,0 | `/docs/analise_arquitetura.md` não existe |
| 04 | Violações Arquiteturais | 0,0 | Arquivo não existe |
| 05 | ADR | 0,0 | Pasta `/docs/adrs/` não existe |
| 06 | Dívida Técnica | 0,0 | `/docs/registro_divida_tecnica.md` não existe |
| 07 | Priorização Dívida | 0,0 | Arquivo não existe |
| 08 | Classificação Manutenção | 0,0 | `/docs/fluxo_manutencao.md` não existe |
| 09 | Pipeline de Liberação | 0,0 | Arquivo não existe |
| 10 | Plano de Iteração | 0,0 | `/docs/plano_iteracao.md` não existe |
| 11 | Quadro Kanban e WIP | 0,0 | Arquivo não existe |
| 12 | Matriz de Riscos | 0,0 | 5 riscos em `operacao.md` mas coluna `Estratégia` ausente |
| 13 | Gatilhos de Risco | 0,0 | Coluna Gatilho presente mas estrutura incompleta |
| 14 | Métrica DORA | 0,0 | Métrica sem ficha com 7 campos |
| 15 | Métrica de Qualidade | 0,0 | Segunda métrica não existe |
| 16 | SLO | 0,0 | SLO sem estrutura de ficha (SLI, Fórmula, Fonte, Janela, Alvo) |
| 17 | Error Budget Policy | 0,0 | Sem 3 níveis graduados |
| 18 | Segurança SSDF | 0,5 | Nenhuma credencial hardcoded nos 95 `.cs` |
| 19 | Threat Model e Gates | 0,0 | `/docs/seguranca_ciclo.md` não existe |
| 20 | Topologia Times e DoD | 0,0 | `topologia_times.md` não existe; `release_checklist_final.md` tem 15 itens mas sem topologia |

**Nota Final: 1,0 / 10,0**
