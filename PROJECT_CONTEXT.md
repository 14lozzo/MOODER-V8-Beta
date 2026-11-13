# MOODER by Rogue — Project Context

**Atualizado:** 2026-11-13  
**Confiança:** contexto funcional parcial; arquitetura técnica ainda não auditada.

## 1. Propósito

Consolidar diferentes ferramentas criativas numa plataforma coerente, com navegação, linguagem visual e exportações consistentes.

## 2. Módulos e terminologia

| Nome | O que está documentado | O que falta confirmar |
| --- | --- | --- |
| Home | Entrada principal desejada | Ficheiro de entrada e implementação atual |
| Smart Grid | Atualização V8.0 da paleta em `smart-grid.js` / `workspace.css` | Conjunto completo de ferramentas e UX atual |
| Brand Identity | Histórico Logo Pack Studio V7.3 e Foundation V7.6 no README V8 | Integração e funcionalidades atuais |
| Apparel Studio | Identificado pelo responsável como parte do MOODER V8; referência à V2.4 | Estrutura de código, mockups, acabamentos e exportação |
| Moodboard | Descrito como funcional na V8 Beta | Presença e estado atual |
| Event Identity | Seis formatos editáveis descritos na V8 Beta | Presença e estado atual |
| Export Center | Remoção como módulo independente proposta | Se existe e que dependências tem |

**Atenção:** os nomes Moodboard/Event Identity dos documentos históricos não devem ser automaticamente equiparados a Smart Grid/Apparel Studio sem verificar o código.

## 3. Evidências técnicas históricas

- O README V8 Beta refere `workspace.html` para o novo espaço de trabalho e `index.html` para Brand Identity Foundation V7.6.
- O README da atualização refere especificamente `smart-grid.js` e `workspace.css`.
- A pasta `mockups` devia ser preservada durante a publicação das versões históricas.
- O README V8 Beta refere exportações PNG/PDF/ZIP, backup `.mooder` e armazenamento local para os módulos ali descritos.
- Não há evidência documental suficiente para identificar framework, bundler, estrutura de componentes, testes automatizados ou pipeline de deploy atual.

## 4. Decisões de produto e design

1. Identidade visual transversal aos módulos.
2. Botão de regresso à Home nas ferramentas.
3. Títulos pretendidos:
   - Home — `MOODER by Rogue`
   - Smart Grid — `MOODER SMART GRID by Rogue`
   - Brand Identity — `MOODER Brand Identity by Rogue`
   - Apparel Studio — `MOODER Apparel Studio by Rogue`
4. Exportação dentro de cada ferramenta; avaliar descontinuação do Export Center separado.
5. UX do Smart Grid mais intuitiva.
6. Melhor qualidade dos mockups e acabamentos do Apparel Studio.

## 5. Regras de implementação

- Inspecionar ficheiros reais antes de editar.
- Evitar reescritas desnecessárias e regressões.
- Preservar dados e compatibilidade de exportação/backup existentes até serem testados.
- Testar as funcionalidades de todos os módulos após mudanças em CSS ou navegação partilhados.
- Não afirmar que uma tarefa está concluída sem confirmação no código e teste.

## 6. Questões em aberto para auditoria

- Qual o ponto de entrada atual e o processo de publicação?
- Quais módulos estão efetivamente presentes e como se relacionam?
- Existe um design system ou CSS partilhado?
- Quais formatos de exportação são suportados atualmente em cada módulo?
- Como são guardados projetos, imagens e backups?
- O Export Center é utilizado por outras funcionalidades?
- Quais os requisitos exatos do PDF técnico e acabamentos do Apparel Studio?

## 7. Fontes

README V7.3, README V8.0 Beta, README da correção de paleta V8.0 e decisões comunicadas pelo responsável. Este ficheiro **não substitui a inspeção do repositório**.
