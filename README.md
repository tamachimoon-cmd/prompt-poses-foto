# Prompt Poses Foto

Coleção curada de **150 prompts reutilizáveis para fotografia de estúdio com modelos adultos**, cobrindo retrato beauty, editorial, corpo inteiro, movimento, iluminação clássica e experimental, modificadores ópticos, composição, direção de pose, captura em espectros alternativos, técnicas computacionais, processos analógicos e linguagem de lentes.

Os prompts seguem uma estrutura consistente: finalidade, modelo e figurino, pose, enquadramento, iluminação, lente ou mecanismo de captura, textura, fundo e restrições anatômicas.

## Conteúdo

- [`PROMPTS.md`](PROMPTS.md): índice consolidado e conteúdo integral dos prompts 146–150.
- [`prompts.json`](prompts.json): catálogo estruturado com IDs 1–150 e conteúdo integral dos cinco prompts mais recentes.
- [`prompts/archive-through-145.json`](prompts/archive-through-145.json): cópia exata do catálogo detalhado anterior, preservando os dados estruturados dos prompts 141–145.
- [`prompts/references-through-145.md`](prompts/references-through-145.md): snapshot integral das referências acumuladas até o ID 145.
- Arquivos históricos anteriores dentro de [`prompts/`](prompts/).
- [`REFERENCIAS.md`](REFERENCIAS.md): metodologia consolidada e fontes atuais desta rodada.

Os IDs e títulos anteriores permanecem no catálogo principal. Os detalhes estruturados até o ID 145 são preservados no arquivo histórico permanente; os cinco prompts mais recentes ficam incorporados integralmente em `PROMPTS.md` e `prompts.json`.

## Novos estilos adicionados

146. Díptico multiespectral VIS–NIR com reflectância alinhada e textura comparável
147. Retrato por câmera de eventos com gesto lateral e nuvem temporal de polaridade
148. Figurino retrorefletivo de microesferas com flash quase coaxial e pele separada
149. Díptico metamérico D50 versus iluminante A com tecidos de mesma aparência inicial
150. Luminescência VIS-excited IR em acessório com retrato de referência visível

## Fórmula-base

```text
[finalidade] + [modelo adulto e figurino] + [pose e olhar] +
[enquadramento] + [iluminação e fundo] + [lente ou técnica de captura] +
[textura e acabamento] + [restrições]
```

## Notas práticas

- Descreva função, posição, direção, tamanho aparente e percurso da luz.
- Em captura multiespectral, separe reflectância VIS/NIR de termografia e mantenha alinhamento entre bandas.
- Em câmera de eventos, diferencie eventos temporais de uma fotografia convencional: pixels estáticos não devem inventar textura no mapa de eventos.
- Em retroreflexão, a geometria fonte–câmera é determinante; ilumine pele e fundo por fontes separadas quando necessário.
- Em metamerismo, fixe câmera, exposição e composição e altere apenas o iluminante para que a mudança de cor tenha causa física legível.
- Em luminescência VIS→IR, deixe claro que a emissão IR vem do material excitado por luz visível, não de calor nem de UV.
- Prefira olhos nítidos quando o rosto estiver no quadro e mãos com função clara.
- Configurações de câmera funcionam como vocabulário visual; não garantem simulação física exata.
- Respeite consentimento, direitos de imagem e regras da plataforma.

## Licenciamento

Os textos dos prompts são originais e podem ser adaptados livremente. Marcas e ferramentas citadas pertencem aos respectivos proprietários.
