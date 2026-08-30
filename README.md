# Prompt Poses Foto

Coleção curada de **145 prompts reutilizáveis para fotografia de estúdio com modelos adultos**, cobrindo retrato beauty, editorial, corpo inteiro, movimento, iluminação clássica e experimental, modificadores ópticos, composição, direção de pose, captura em espectros alternativos, técnicas computacionais, processos analógicos e linguagem de lentes.

Os prompts seguem uma estrutura consistente: finalidade, modelo e figurino, pose, enquadramento, iluminação, lente ou mecanismo de captura, textura, fundo e restrições anatômicas.

## Conteúdo

- [`PROMPTS.md`](PROMPTS.md): índice consolidado e conteúdo integral dos prompts 141–145.
- [`prompts.json`](prompts.json): catálogo estruturado com IDs 1–145 e conteúdo integral dos cinco prompts mais recentes.
- [`prompts/archive-through-140.json`](prompts/archive-through-140.json): cópia exata do catálogo detalhado anterior, preservando os dados estruturados dos prompts 136–140.
- [`prompts/references-through-140.md`](prompts/references-through-140.md): snapshot integral das referências acumuladas até o ID 140.
- Arquivos históricos anteriores dentro de [`prompts/`](prompts/).
- [`REFERENCIAS.md`](REFERENCIAS.md): metodologia consolidada e fontes atuais desta rodada.

Os IDs e títulos anteriores permanecem no catálogo principal. Os detalhes estruturados até o ID 140 são preservados no arquivo histórico permanente; os cinco prompts mais recentes ficam incorporados integralmente em `PROMPTS.md` e `prompts.json`.

## Novos estilos adicionados

141. Light Stage por gradientes esféricos com reflectância facial separada
142. Retrato plenóptico light-field com refoco pós-captura entre mão e olhos
143. Pseudo-telecentricidade com Fresnel frontal e gesto sem mudança aparente de escala
144. Separação polarimétrica difusa-especular em díptico beauty sincronizado
145. Iluminação coaxial por beamsplitter com beauty metálico e sombra quase nula

## Fórmula-base

```text
[finalidade] + [modelo adulto e figurino] + [pose e olhar] +
[enquadramento] + [iluminação e fundo] + [lente ou técnica de captura] +
[textura e acabamento] + [restrições]
```

## Notas práticas

- Descreva função, posição, direção, tamanho aparente e percurso da luz.
- Em captura de reflectância, diferencie a captura técnica multiquadro do retrato final relightado.
- Em light-field, especifique o plano de refoco e mantenha o parallax discreto e coerente.
- Em pseudo-telecentricidade, descreva invariância aproximada de escala com profundidade, não compressão de teleobjetiva.
- Em separação polarimétrica, deixe claro que os painéis são componentes alinhados da mesma captura.
- Em iluminação coaxial, descreva o beamsplitter e o percurso da fonte até o eixo óptico.
- Prefira olhos nítidos quando o rosto estiver no quadro e mãos com função clara.
- Configurações de câmera funcionam como vocabulário visual; não garantem simulação física exata.
- Respeite consentimento, direitos de imagem e regras da plataforma.

## Licenciamento

Os textos dos prompts são originais e podem ser adaptados livremente. Marcas e ferramentas citadas pertencem aos respectivos proprietários.
