# Referências e Metodologia

Pesquisa inicial realizada em **2 de agosto de 2026** e ampliada continuamente até **1 de setembro de 2026**. A curadoria prioriza documentação oficial, fabricantes reconhecidos, instituições acadêmicas, museus, literatura técnica e pesquisa primária quando a técnica exige base óptica, computacional, espectral ou temporal.

> O snapshot integral das referências acumuladas até o ID 145 foi preservado em [`prompts/references-through-145.md`](prompts/references-through-145.md). As referências de 146–150 permanecem no histórico permanente do Git e a rodada atual acrescenta as fontes abaixo.

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
- Uma focal de 85 mm é uma referência clássica para retrato por oferecer perspectiva facial natural e isolamento do fundo.
- Em iluminação de estúdio, posição, tamanho aparente, feathering, flags e relação entre fundo e sujeito devem ser descritos de forma operacional.
- Schlieren e shadowgraph não são equivalentes: schlieren usa um cutoff no foco para converter pequenos desvios por gradiente de densidade em contraste.
- UV refletido registra a radiação UV refletida pelo material; não deve ser confundido com fluorescência visível induzida por UV.
- Rear projection usa projetor atrás de tela translúcida, combinando foreground e plate na própria captura.
- Cross-processing altera quimicamente contraste e reprodução de cor ao processar o filme em um processo para o qual ele não foi projetado.
- Banding sob LED pode surgir da interação temporal entre flicker/PWM e leitura sequencial do shutter; quando usado criativamente, deve ser distinguido de overlay digital.
- Para geração de imagens, lente, abertura, iluminação, pose, composição e restrições devem ser explicitadas quando determinantes.

## Fontes verificadas em 1 de setembro de 2026

1. NASA Glenn Research Center — Schlieren Flow Visualization  
   https://www.grc.nasa.gov/WWW/K-12/airplane/tunvschlrn.html

2. NASA Technology Transfer — Filtered Ronchi Rulings for Enhanced Schlieren Imaging  
   https://technology.nasa.gov/patent/LAR-TOPS-396

3. Canadian Conservation Institute — Lighting Techniques for Photographing Heritage Objects — 03/02/2025  
   https://www.canada.ca/en/conservation-institute/services/learning-activities/lighting-techniques.html

4. Canadian Conservation Institute — Germain Wiseman: reflected ultraviolet photography and scientific imaging  
   https://www.canada.ca/en/conservation-institute/corporate/org-structure/germain-wiseman.html

5. Columbia Film Language Glossary — Rear Projection  
   https://filmglossary.ccnmtl.columbia.edu/term/rear-projection/

6. Motion University — Using Rear Projection for Interior Car Scenes  
   https://blog.motionuniversity.org/production/rear-projection/

7. Kodak — Essential Reference Guide for Filmmakers: Cross-processing  
   https://www.kodak.com/content/products-brochures/Film/kodak-essential-reference-guide-for-filmmakers.pdf

8. Sony USA — How to reduce camera flickering / banding — atualizado em 12/07/2026  
   https://www.sony.com/electronics/support/camcorders-and-video-cameras-interchangeable-lens-camcorders/nex-vg20/articles/00122281

9. Sony USA — Banding during high-speed sync shooting — 20/01/2026  
   https://www.sony.com/electronics/support/e-mount-body-zv-e-series/zv-e10m2k/articles/00280549

10. Nikon USA — NIKKOR Z 85mm f/1.8 S: portrait perspective and bokeh  
    https://www.nikonusa.com/p/nikkor-z-85mm-f18-s/20090/overview

11. Profoto — 5 portrait lighting setups with one B10  
    https://www.profoto.com/ro/en/still-photography/tips-tricks/5-portrait-lighting-setups-with-one-b10-light

12. OpenAI Academy — Criando imagens com o ChatGPT — 10/04/2026  
    https://openai.com/pt-BR/academy/image-generation/

13. Adobe Learn — Explore prompting basics for photographers — 20/08/2026  
    https://www.adobe.com/learn/firefly/web/firefly-photographers-prompting-basics

14. Adobe Learn — Generate realistic photos with a prompt formula in Firefly — 13/04/2026  
    https://www.adobe.com/us/learn/firefly/web/generate-realistic-photos

## Atualização de 1 de setembro de 2026

Foram selecionados cinco mecanismos ausentes dos 150 títulos anteriores:

- **schlieren por knife-edge**, com fluxo térmico fisicamente isolado atrás da silhueta e iluminação facial independente;
- **UV refletido em acessório**, confinado ao objeto e explicitamente separado de fluorescência UV e de exposição do rosto;
- **rear projection**, usando tela translúcida, plate projetado por trás e foreground real na mesma captura;
- **cross-processing de filme reversível**, explorando alteração química real de contraste, saturação e reprodução cromática;
- **banding temporal por LED PWM + shutter eletrônico**, usando o artefato de leitura temporal como linguagem visual em vez de overlay de pós-produção.

Na direção de modelos, os prompts privilegiam poses estáveis quando a técnica exige separação temporal/espectral e funções claras para braços e mãos. Na engenharia de prompts, mecanismo, relações espaciais, iluminação, lente, plano de foco e restrições negativas são explicitados, em linha com recomendações atuais da OpenAI e Adobe.

## Autoria

Os prompts são textos originais derivados de princípios técnicos sintetizados das fontes. Não são cópias de prompts de terceiros nem representam certificação oficial das plataformas citadas.
