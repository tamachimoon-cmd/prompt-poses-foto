# Referências e Metodologia

Pesquisa inicial realizada em **2 de agosto de 2026** e ampliada continuamente até **31 de agosto de 2026**. A curadoria prioriza documentação oficial, fabricantes reconhecidos, instituições acadêmicas, museus, literatura técnica e pesquisa primária quando a técnica exige base óptica, computacional, espectral ou temporal.

> O snapshot integral das referências acumuladas até o ID 145 foi preservado em [`prompts/references-through-145.md`](prompts/references-through-145.md).

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
- Imagem multiespectral combina bandas visíveis e invisíveis, com calibração e alinhamento entre exposições.
- Câmeras de eventos registram mudanças assíncronas de intensidade por pixel, não quadros convencionais completos.
- Materiais retrorefletivos de microesferas devolvem grande parte da luz em direção próxima à fonte; a proximidade fonte–câmera altera fortemente a aparência.
- Metamerismo ocorre quando duas amostras coincidem sob um iluminante e divergem sob outro por terem curvas espectrais de reflectância diferentes.
- Luminescência VIS-excited IR é emissão no infravermelho provocada por excitação visível; deve ser distinguida de reflectância NIR e de termografia.
- Para geração de imagens, lente, abertura, iluminação, pose, composição e restrições devem ser explicitadas quando determinantes.

## Fontes verificadas em 31 de agosto de 2026

1. Phase One — Multispectral Imaging Camera Systems  
   https://www.phaseone.com/heritage-solutions/multispectral-imaging/

2. Phase One — Modular Digitization at Herzogin Anna Amalia Library  
   https://www.phaseone.com/inspiration/modular-digitization-at-the-herzogin-anna-amalia-library/

3. Prophesee — Event-Based Metavision Sensor GENX320  
   https://www.prophesee.ai/event-based-sensor-genx320/

4. 3M — Scotchlite Reflective Material 8712 Series  
   https://www.3m.com/3M/sl_SI/p/d/b00015045/

5. X-Rite — What is Metamerism?  
   https://www.xrite.com/service-support/what_is_metamerism

6. X-Rite — Illuminants available in X-Rite hardware and software  
   https://www.xrite.com/service-support/what_illuminants_are_available_in_xrite_hardware_and_software

7. OpenAI Academy — Creating images with ChatGPT — 10/04/2026  
   https://openai.com/academy/image-generation/

8. Adobe Learn — Explore prompting basics for photographers — 20/08/2026  
   https://www.adobe.com/learn/firefly/web/firefly-photographers-prompting-basics

9. Adobe Learn — Generate realistic photos with a prompt formula in Firefly — 2026  
   https://www.adobe.com/learn/firefly/web/generate-realistic-photos

## Atualização de 31 de agosto de 2026

Foram selecionados cinco mecanismos ausentes dos 145 títulos anteriores:

- **reflectância multiespectral VIS–NIR alinhada**, para comparar resposta material em bandas distintas sem confundir NIR com termografia;
- **câmera de eventos**, para representar movimento como nuvem temporal assíncrona em vez de blur de quadro convencional;
- **retroreflexão por microesferas no figurino**, usando flash quase coaxial e iluminação facial separada;
- **metamerismo controlado por iluminante**, com a mesma composição fotografada sob D50 e iluminante A;
- **luminescência VIS-excited IR**, na qual um acessório emite no infravermelho após excitação por luz visível.

Na direção de modelos, os prompts privilegiam poses estáveis quando a técnica exige alinhamento multiquadro e gestos deliberados quando o movimento é o dado principal. Na engenharia de prompts, mecanismo, relações espaciais, iluminação, banda espectral, plano de foco e restrições negativas são explicitados, alinhados às recomendações atuais da OpenAI e Adobe.

## Autoria

Os prompts são textos originais derivados de princípios técnicos sintetizados das fontes. Não são cópias de prompts de terceiros nem representam certificação oficial das plataformas citadas.
