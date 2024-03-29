## items Type

`object` ([image](image-image.md))

# items Properties

| Property          | Type          | Required | Nullable       | Defined by                                                                                             |
| :---------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------- |
| [url](#url)       | `string`      | Required | cannot be null | [image](image-image-properties-url.md "https://fable.deno.dev/image.json#/items/properties/url")       |
| [nsfw](#nsfw)     | `boolean`     | Optional | cannot be null | [image](image-image-properties-nsfw.md "https://fable.deno.dev/image.json#/items/properties/nsfw")     |
| [artist](#artist) | Not specified | Optional | cannot be null | [image](image-image-properties-artist.md "https://fable.deno.dev/image.json#/items/properties/artist") |

## url

A url of the image (Fable forces the aspect-ratio of all images to 230:325) (recommended size: 450x635)

`url`

*   is required

*   Type: `string` ([url](image-image-properties-url.md))

*   cannot be null

*   defined in: [image](image-image-properties-url.md "https://fable.deno.dev/image.json#/items/properties/url")

### url Type

`string` ([url](image-image-properties-url.md))

### url Examples

```json
"https://i.imgur.com/U2U8Uuo.jpg"
```

```json
"https://i.redd.it/xozj7btis2na1.jpg"
```

## nsfw

Whether or not or not the image should be blurred on sfw channels

`nsfw`

*   is optional

*   Type: `boolean` ([nsfw](image-image-properties-nsfw.md))

*   cannot be null

*   defined in: [image](image-image-properties-nsfw.md "https://fable.deno.dev/image.json#/items/properties/nsfw")

### nsfw Type

`boolean` ([nsfw](image-image-properties-nsfw.md))

## artist

The artist responsible for the image

`artist`

*   is optional

*   Type: unknown ([artist](image-image-properties-artist.md))

*   cannot be null

*   defined in: [image](image-image-properties-artist.md "https://fable.deno.dev/image.json#/items/properties/artist")

### artist Type

unknown ([artist](image-image-properties-artist.md))
