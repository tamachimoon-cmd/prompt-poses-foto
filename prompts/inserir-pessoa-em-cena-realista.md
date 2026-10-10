# Inserir pessoa em nova cena (img2img com identidade)

## Uso

Colocar a pessoa de uma foto de referência em um novo cenário com aparência de foto real, sem visual cinematográfico exagerado.

## Prompt

```text
Generate a highly realistic action scene where this person is running away from a large, realistic brown bear attacking a campsite. The image should look like a real photograph someone could have taken, not an overly enhanced or cinematic movie-poster image.
She is centered in the image but looking away from the camera, wearing outdoorsy camping attire, with dirt on her face and tears in her clothing. She is clearly afraid but focused on escaping, running away from the bear as it destroys the campsite behind her.
The campsite is in Yosemite National Park, with believable natural details. The time of day is dusk, with natural lighting and realistic colors. Everything should feel grounded, authentic, and unstyled, as if captured in a real moment. Avoid cinematic lighting, dramatic color grading, or stylized composition.
```

## Fonte

- OpenAI Cookbook — Gpt-image-1.5 Prompting Guide
- https://developers.openai.com/cookbook/examples/multimodal/image-gen-1.5-prompting_guide

## Dicas

Estrutura reaproveitável: ação + posição no quadro + direção do olhar + figurino + cenário + hora do dia + 'Avoid cinematic lighting...'. A fonte usa input_fidelity="high" para preservar a semelhança.
