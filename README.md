# MOODER by Rogue — Documentação do projeto

> **Estado:** documentação consolidada em 13/11/2026 a partir de três README históricos e de decisões de produto comunicadas pelo responsável. **Não constitui auditoria ao código atual.**

## Visão

MOODER by Rogue é uma plataforma de ferramentas criativas. A organização de produto pretendida inclui Home, Smart Grid, Brand Identity e Apparel Studio. O objetivo de desenvolvimento é uma experiência visual e de navegação consistente entre os módulos.

## Referências históricas confirmadas nos README

### Logo Pack Studio Foundation V7.3

O README desta versão regista: roda cromática opcional, recolhida por defeito; reposição da secção de Direção Fotográfica e do upload de referência; manutenção do editor e do PDF dinâmico. Refere alterações sobre V7.2.

### MOODER V8.0 Beta — instruções históricas de publicação

O README V8 indica que os ficheiros do ZIP eram publicados na raiz do repositório GitHub Pages, preservando a pasta `mockups`; `workspace.html` abria o novo espaço de trabalho e `index.html` mantinha o Brand Identity Foundation V7.6.

Funcionalidades declaradas **nessa beta**: Moodboard com canvas, imagens, texto, blocos de cor, arrastar e grelha; Event Identity com seis formatos editáveis; exportações PNG/PDF e ZIP dos dois novos módulos; backup `.mooder`; armazenamento local.

Limitações declaradas **nessa beta**: exportação separada do Brand Identity; ausência de gestão multiprojeto/IndexedDB, templates avançados, sangria e CMYK real; PDF rasterizado por página; backup `.mooder` limitado a Moodboard e Event Identity. Estas limitações **não foram verificadas na versão atual**.

### Atualização da paleta automática V8.0

O README de atualização descreve alterações apenas a `smart-grid.js` e `workspace.css`: alinhamento da Color Palette em espaços estreitos (incluindo Event Showcase), extração de cores principal/secundária a partir de logótipos PNG/JPG/WebP/SVG, contraste preto/branco automático e possibilidade de edição manual. A extração baseia-se em pixels visíveis e pode requerer ajustes manuais. O documento afirma que não altera o Brand Identity antigo.

## Estrutura de produto pretendida (a validar no código)

- **Home:** entrada e navegação principal.
- **Smart Grid:** composições e ferramentas de grelha.
- **Brand Identity:** ferramentas de identidade visual.
- **Apparel Studio:** mockups e preparação de peças de vestuário, incluindo acabamentos e exportação.

A existência, localização e maturidade atuais destes módulos exigem inspeção do repositório.

## Direção de desenvolvimento acordada

- Uniformizar UI/UX, estilos e componentes entre os módulos.
- Incluir navegação de regresso à Home.
- Adotar títulos: `MOODER by Rogue`, `MOODER SMART GRID by Rogue`, `MOODER Brand Identity by Rogue`, `MOODER Apparel Studio by Rogue`.
- Melhorar usabilidade do Smart Grid.
- Melhorar mockups, acabamentos e detalhe das exportações do Apparel Studio.
- Avaliar remoção do Export Center independente, mantendo exportações em cada módulo.

Estas são **decisões/requisitos**, não funcionalidades declaradas como implementadas.

## Instalação e execução

**Não validado:** o código-fonte e os comandos de instalação não foram disponibilizados para esta revisão. O README histórico V8 aponta para `workspace.html` e `index.html` em GitHub Pages; não é seguro inferir que continuam a ser os pontos de entrada atuais.

Antes de publicar, verificar estrutura do repositório, dependências, pontos de entrada, caminhos relativos e GitHub Pages. Fazer backup e testar numa branch de staging.

## Documentação adicional

- [`PROJECT_CONTEXT.md`](PROJECT_CONTEXT.md): contexto, evidências e decisões.
- [`ROADMAP.md`](ROADMAP.md): prioridades e critérios de aceitação.
- [`CHANGELOG.md`](CHANGELOG.md): histórico documentado e alterações futuras.

## Fontes desta consolidação

`README(1).md` (V7.3), `README-V8.txt` (V8.0 Beta), `README-ATUALIZACAO.txt` (correção da paleta) e requisitos de produto discutidos no projeto. Os originais devem ser preservados como histórico.
