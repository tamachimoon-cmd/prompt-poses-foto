# Prompt Poses Foto

Coleção curada de **105 prompts reutilizáveis para fotografia de estúdio com modelos adultos**, cobrindo retrato beauty, editorial, corpo inteiro, movimento, iluminação clássica e experimental, modificadores ópticos, composição, direção de pose, captura em espectros alternativos e linguagem de lentes.

Os prompts seguem uma estrutura consistente: finalidade, modelo e figurino, pose, enquadramento, iluminação, lente, textura, fundo e restrições anatômicas.

## Conteúdo

- [`PROMPTS.md`](PROMPTS.md): índice consolidado e conteúdo integral dos prompts 101–105.
- [`prompts.json`](prompts.json): catálogo estruturado com IDs 1–105 e conteúdo integral dos cinco prompts mais recentes.
- [`prompts/archive-through-100.json`](prompts/archive-through-100.json): cópia exata do catálogo detalhado anterior, preservando os dados estruturados dos prompts 76–100 sem depender apenas do histórico de commits.
- [`prompts/2026-08-03.md`](prompts/2026-08-03.md): prompts 11–15.
- [`prompts/2026-08-04.md`](prompts/2026-08-04.md): prompts 16–20.
- [`prompts/2026-08-07.md`](prompts/2026-08-07.md): prompts 26–30.
- [`REFERENCIAS.md`](REFERENCIAS.md): metodologia e fontes consultadas.

Os IDs e títulos anteriores permanecem no catálogo principal. Os detalhes estruturados do catálogo anterior até o ID 100 também são preservados no arquivo de histórico permanente acima; os cinco prompts mais recentes ficam incorporados integralmente em `PROMPTS.md` e `prompts.json`.

## Novos estilos adicionados

101. SA Control 100 mm com bubble bokeh e beauty de textura preservada
102. Sweet Spot 80 mm deslocado para o olho com campo de foco curvo
103. Zone Plate Obscura 50 mm com glow difrativo e pose gráfica imóvel
104. Flash congelado com LED contínuo em meia exposição e gesto fantasma cromático
105. Contraluz duplo com braços elevados como rebatedores naturais do rosto

## Fórmula-base

```text
[finalidade] + [modelo adulto e figurino] + [pose e olhar] +
[enquadramento] + [iluminação e fundo] + [lente ou técnica de captura] +
[textura e acabamento] + [restrições]
```

## Notas práticas

- Descreva função, posição, direção, tamanho aparente e percurso da luz.
- Em óticas extremas, especifique o que fica no centro e o que pode sofrer expansão de perspectiva.
- Em óticas de aberração controlável, diferencie alteração do bokeh de difusão global do sujeito.
- Em foco seletivo por campo curvo, indique exatamente qual olho ou detalhe ocupa a ilha de nitidez.
- Em zone plate e camera obscura, trate glow e artefatos como consequência óptica e mantenha o sujeito imóvel quando a exposição exigir.
- Ao combinar flash e luz contínua, determine explicitamente qual parte fica congelada e qual elemento pode registrar trilhas.
- Se a pose participar do desenho de luz, descreva a função mecânica dos braços, mãos ou figurino como superfícies refletoras.
- Para movimento rápido, diferencie velocidade do obturador de duração efetiva do flash.
- Em técnicas espectrais, descreva mecanismo físico, filtros e cuidados de segurança, sem confundir fluorescência UV com infravermelho ou visão térmica.
- Em técnicas compostas, deixe claro o que precisa permanecer imóvel e quais planos devem terminar nítidos.
- Para caústicas e reflexos, descreva o percurso físico da luz e impeça a IA de converter o efeito em gobo ou projeção.
- Quando pele e produto exigirem acabamentos distintos, separe as funções das fontes e controle spill.
- Em bokeh criativo, diferencie a geometria da pupila/abertura de filtros de difração, aberração esférica e padrões projetados.
- Prefira olhos nítidos quando o rosto estiver no quadro e mãos com função clara.
- Configurações de câmera funcionam como vocabulário visual; não garantem simulação física exata.
- Respeite consentimento, direitos de imagem e regras da plataforma.

## Licenciamento

Os textos dos prompts são originais e podem ser adaptados livremente. Marcas e ferramentas citadas pertencem aos respectivos proprietários.
