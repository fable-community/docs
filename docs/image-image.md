# image Schema

```txt
https://fable.deno.dev/image.json#/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [image.json\*](../out/image.json "open original schema") |

## items Type

`object` ([image](image-image.md))

# items Properties

| Property          | Type          | Required | Nullable       | Defined by                                                                                             |
| :---------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------- |
| [url](#url)       | `string`      | Required | cannot be null | [image](image-image-properties-url.md "https://fable.deno.dev/image.json#/items/properties/url")       |
| [artist](#artist) | Not specified | Optional | cannot be null | [image](image-image-properties-artist.md "https://fable.deno.dev/image.json#/items/properties/artist") |

## url

A url of the image (recommended: 450x635)

`url`

*   is required

*   Type: `string` ([url](image-image-properties-url.md))

*   cannot be null

*   defined in: [image](image-image-properties-url.md "https://fable.deno.dev/image.json#/items/properties/url")

### url Type

`string` ([url](image-image-properties-url.md))

## artist

The artist responsible for the image

`artist`

*   is optional

*   Type: unknown ([artist](image-image-properties-artist.md))

*   cannot be null

*   defined in: [image](image-image-properties-artist.md "https://fable.deno.dev/image.json#/items/properties/artist")

### artist Type

unknown ([artist](image-image-properties-artist.md))
