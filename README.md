<a href="https://gola.apimart.ai/k-yZjTzJ"><img src="https://raw.githubusercontent.com/fujc683/awesome-gpt-image-2-6-prompts/main/banner.jpg" width="100%" /></a>

# Colección de prompts de GPT Image 2.6

> 252 prompts seleccionados con imágenes de vista previa, ordenados por caso de uso. Flare y Sunburst.

**[👉 Usar GPT Image 2.6 en APIMart](https://gola.apimart.ai/k-yZjTzJ)**

`https://gola.apimart.ai/k-yZjTzJ`

[💰 Precios](https://gola.apimart.ai/k-usjHNG) · [🔑 Obtener clave API](https://gola.apimart.ai/k-AQ7hME)

---

## Endpoint

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H "Authorization: Bearer $APIMART_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2.6-flare","prompt":"a red apple","n":1,"size":"1024x1024"}'
```

## Models

| ID | Variant |
|---|---|
| `gpt-image-2.6-flare` | Flare |
| `gpt-image-2.6-sunburst` | Sunburst |

## Parameters

| Field | Type | Description |
|---|---|---|
| `model` | string | model id |
| `prompt` | string | text prompt |
| `n` | int | 1-4 |
| `size` | string | `1024x1024` / `1536x1024` / `1024x1536` |

## Poll

```bash
curl https://api.apimart.ai/v1/tasks/<task_id> -H "Authorization: Bearer $APIMART_API_KEY"
```

---

## License

CC BY 4.0
