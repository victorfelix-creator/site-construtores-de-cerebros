# Site de exemplo · Pais e Cuidadores são Construtores de Cérebros

Protótipo do site do programa de parentalidade positiva do CAEN/UFC, inspirado no ParentData (conteúdo para famílias) e no The Human Project (parceiros e impacto).

## Como abrir

Abra `index.html` no navegador, ou sirva a pasta:

```
python -m http.server 8765
```

e acesse http://localhost:8765. A página de parceiros fica em `#parceiros`.

## O que tem

Um arquivo, seis páginas (trocadas pelo `#` do endereço):

- `#inicio`: página curta no modelo do ParentData. Apresentação, 4 dicas em destaque e temas mais buscados, como funciona (componentes Progresso e Card de encontro), números com fonte, citação, quem apoia, chamada para municípios e perguntas frequentes.
- `#sobre`: para quem, onde e como, teoria da mudança, os 11 encontros, história e equipe.
- `#familias`: 12 dicas filtráveis por fase, glossário com busca e cadastro para dica semanal.
- `#pesquisa`: estudos do CAEN/UFC e materiais do projeto.
- `#parceiros`: parceiros agrupados por tipo, no modelo do The Human Project.
- `#apoie`: etapas de implantação e formulário de contato.

O visual segue o design system do Figma: as variáveis CSS têm os mesmos nomes das variáveis do Figma (`--cor-bg-canvas`, `--espaco-4`, `--raio-lg`...), os estilos de texto são as classes `.t-*` e os componentes são `.botao`, `.tag`, `.card`, `.encontro`, `.passo`, `.aviso` e `.campo`. Tema único, claro, como no design system.

## Pendências (marcadas no site como "a confirmar")

- Número de famílias atendidas e lista de CRAS.
- Depoimentos de famílias (com autorização).
- Resumo dos achados da tese (2025) e do TCC de Samira Melo (2025).
- E-mail de contato, redes sociais, política de privacidade (LGPD).
- Gratuidade para as famílias.
- Logotipos oficiais dos parceiros e secretarias municipais parceiras.
- Os formulários ainda não enviam: falta ligar a um serviço (e-mail, planilha ou WhatsApp).

## Fontes do conteúdo

Glossário e Relatos do projeto, dissertação de Camila Guedes Corrêa (2023) e títulos dos trabalhos do CAEN/UFC.
