# Referências e Metodologia

Pesquisa inicial realizada em **2 de agosto de 2026** e ampliada continuamente até **30 de agosto de 2026**. A curadoria prioriza documentação oficial, fabricantes reconhecidos, instituições acadêmicas, museus, literatura técnica e pesquisa primária quando a técnica exige base óptica, computacional, espectral ou temporal.

> O snapshot integral das referências acumuladas até o ID 140 foi preservado em [`prompts/references-through-140.md`](prompts/references-through-140.md).

## Critérios usados

1. Variedade real de enquadramento, pose e iluminação.
2. Direção anatômica concreta, com distribuição de peso e função das mãos.
3. Prompts reutilizáveis e independentes de plataforma.
4. Lentes e luz usadas como vocabulário visual coerente.
5. Restrições explícitas para reduzir deformações e deriva de composição.
6. Não duplicação dos esquemas já presentes no catálogo.
7. Separação clara entre técnica fotográfica, direção corporal e acabamento.
8. Preferência por mecanismos físicos ou computacionais identificáveis em vez de efeitos apenas descritivos.

## Fundamentos consolidados

- Clareza e especificidade superam listas ornamentais de adjetivos.
- Propósito, assunto, ação, composição, iluminação, textura e restrições formam uma estrutura robusta.
- Instruções espaciais reduzem ambiguidades.
- Light Stage registra a resposta do rosto sob muitas direções de iluminação; polarização pode ajudar a separar componentes especulares e difusas/subsuperficiais.
- Light-field/plenoptic captura informação angular por múltiplas subvisões, permitindo refoco e pequeno ajuste de ponto de vista depois da captura.
- Telecentricidade reduz parallax e variação de magnificação com profundidade; soluções pseudo-telecêntricas de grande campo podem usar uma Fresnel, aceitando compromissos ópticos.
- Separação polarimétrica difusa-especular não é sinônimo de uma única foto cross-polarized: a finalidade é decompor componentes da reflectância.
- Iluminação coaxial usa beamsplitter para sobrepor o caminho da iluminação ao eixo de imagem, reduzindo sombras e tornando reflexos frontais previsíveis.
- Para geração de imagens, lente, abertura, iluminação, pose, composição e restrições devem ser explicitadas quando determinantes.

## Fontes verificadas em 30 de agosto de 2026

1. USC Institute for Creative Technologies — The Digital Emily Project  
   https://vgl.ict.usc.edu/Research/DigitalEmily/

2. USC Institute for Creative Technologies — Light Stage 2.0  
   https://vgl.ict.usc.edu/Research/LS2/

3. USC Institute for Creative Technologies — The Light Stages  
   https://vgl.ict.usc.edu/LightStages/

4. Adobe Research — PlenoPatch: Patch-based Plenoptic Image Manipulation  
   https://research.adobe.com/publication/plenopatch-patch-based-plenoptic-image-manipulation/

5. Edmund Optics — The Advantages of Telecentricity  
   https://www.edmundoptics.com/knowledge-center/application-notes/imaging/advantages-of-telecentricity/

6. Edmund Optics — Telecentric Lens Size Control  
   https://www.edmundoptics.com/knowledge-center/application-notes/imaging/telecentric-lens-size-control

7. PubMed / Optics Express — Snapshot polarimetric diffuse-specular separation  
   https://pubmed.ncbi.nlm.nih.gov/36242441/

8. Edmund Optics — In-line Illumination  
   https://www.edmundoptics.com/knowledge-center/application-notes/illumination/in-line-illumination-considerations/

9. Edmund Optics / CCS — Half Mirror Coaxial Light  
   https://www.edmundoptics.com/p/27x27mm-half-mirror-coaxial-light-white/48003/

10. OpenAI Academy — Creating images with ChatGPT — 10/04/2026  
    https://openai.com/academy/image-generation/

11. Adobe Learn — Explore prompting basics for photographers — 20/08/2026  
    https://www.adobe.com/learn/firefly/web/firefly-photographers-prompting-basics

12. Adobe Learn — Generate realistic photos with a prompt formula in Firefly — 2026  
    https://www.adobe.com/learn/firefly/web/generate-realistic-photos

## Atualização de 30 de agosto de 2026

Foram selecionados cinco mecanismos ausentes dos 140 títulos anteriores:

- **Light Stage com gradientes esféricos**, para captura de reflectância e relighting facial;
- **imagem plenóptica/light-field**, para refoco e parallax pós-captura;
- **pseudo-telecentricidade com Fresnel**, para reduzir variação aparente de escala com profundidade;
- **separação polarimétrica difusa-especular**, para decompor a reflectância em componentes alinhados;
- **iluminação coaxial por beamsplitter**, para beauty frontal com sombra mínima e reflexos previsíveis.

Na direção de modelos, os cinco prompts usam poses estáveis e funcionais compatíveis com captura multiquadro ou óptica especializada. Na engenharia de prompts, as instruções explicitam mecanismo, relações espaciais, plano de foco, percurso da luz e restrições negativas, seguindo as recomendações atuais da OpenAI e Adobe.

## Autoria

Os prompts são textos originais derivados de princípios técnicos sintetizados das fontes. Não são cópias de prompts de terceiros nem representam certificação oficial das plataformas citadas.
