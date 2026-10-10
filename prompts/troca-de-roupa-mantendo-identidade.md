# Troca de roupa mantendo identidade (virtual try-on)

## Uso

Editar uma foto existente vestindo a pessoa com peças de outras imagens, sem mudar rosto, corpo, pose, fundo ou enquadramento.

## Prompt

```text
Edit the image to dress the woman using the provided clothing images. Do not change her face, facial features, skin tone, body shape, pose, or identity in any way. Preserve her exact likeness, expression, hairstyle, and proportions. Replace only the clothing, fitting the garments naturally to her existing pose and body geometry with realistic fabric behavior. Match lighting, shadows, and color temperature to the original photo so the outfit integrates photorealistically, without looking pasted on. Do not change the background, camera angle, framing, or image quality, and do not add accessories, text, logos, or watermarks.
```

## Fonte

- OpenAI Cookbook — Gpt-image-1.5 Prompting Guide
- https://developers.openai.com/cookbook/examples/multimodal/image-gen-1.5-prompting_guide

## Dicas

Envie a foto da pessoa como 1ª imagem e as peças em seguida. O segredo, segundo a fonte, é travar explicitamente a identidade e liberar só a roupa.
