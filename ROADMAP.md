# MOODER by Rogue — Roadmap

**Atualizado:** 2026-11-13  
**Nota:** as prioridades abaixo são uma proposta de execução; nenhuma está marcada como concluída sem verificação do código.

## Fase 0 — Auditoria e segurança da versão atual (P0)

- [ ] Inventariar ficheiros, pontos de entrada, módulos e dependências.
- [ ] Confirmar o que existe hoje em Smart Grid, Brand Identity e Apparel Studio.
- [ ] Verificar estado das funcionalidades históricas Moodboard/Event Identity.
- [ ] Identificar fluxos de exportação, backup e armazenamento.
- [ ] Criar backup/tag da versão atual e ambiente/branch de testes.

**Aceitação:** mapa de arquitetura verificado, funcionalidades inventariadas e versão recuperável.

## Fase 1 — UI/UX transversal e navegação (P1)

- [ ] Definir tokens de cor, tipografia, espaçamento, botões e cabeçalhos.
- [ ] Aplicar os quatro títulos oficiais acordados.
- [ ] Implementar navegação Home/Return em todos os módulos relevantes.
- [ ] Verificar consistência em desktop e mobile.

**Aceitação:** navegação e cabeçalhos coerentes, sem quebrar funcionalidades existentes.

## Fase 2 — Smart Grid (P1)

- [ ] Auditar interface atual e pontos de fricção.
- [ ] Melhorar organização de controlos e feedback visual.
- [ ] Testar Color Palette em slots estreitos e Event Showcase.
- [ ] Validar extração automática de cores, contraste e edição manual, quando presentes.

**Aceitação:** fluxos principais intuitivos e exportações preservadas.

## Fase 3 — Apparel Studio (P1)

- [ ] Inventariar mockups e formatos disponíveis.
- [ ] Melhorar realismo e consistência dos mockups.
- [ ] Rever acabamentos e detalhes técnicos.
- [ ] Comparar PDF/exportação atual com os requisitos e ficheiros de referência.
- [ ] Testar resultados e prevenir regressões.

**Aceitação:** mockups e fichas técnicas validados contra requisitos concretos.

## Fase 4 — Brand Identity (P2)

- [ ] Verificar a versão e funcionalidades atuais.
- [ ] Integrar a linguagem visual partilhada sem perder capacidades existentes.
- [ ] Validar editor, direção fotográfica, paleta e exportação onde aplicável.

**Aceitação:** experiência consistente e funções históricas preservadas ou explicitamente substituídas.

## Fase 5 — Exportações e integração (P2)

- [ ] Mapear exportações de cada módulo.
- [ ] Verificar dependências do Export Center.
- [ ] Remover o Export Center separado **apenas se** não houver perda funcional.
- [ ] Testar exportação, backup, recuperação e publicação GitHub Pages.

**Aceitação:** cada ferramenta exporta corretamente e não existem links ou funcionalidades órfãs.

## Prioridades imediatas

1. Auditoria do repositório.
2. Design system e navegação.
3. UX do Smart Grid.
4. Mockups, acabamentos e PDF do Apparel Studio.

## Não assumir como concluído

A documentação histórica da V8 Beta refere limitações em CMYK, sangria, multiprojeto/IndexedDB e PDF raster. O estado atual de cada uma é **por verificar**; só devem entrar no backlog definitivo depois da auditoria.
