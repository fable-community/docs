## manifest Type

`object` ([manifest](schema.md))

# manifest Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                |
| :-------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------- |
| [id](#id)                   | `string`  | Required | cannot be null | [manifest](schema-properties-id.md "https://fable.deno.dev/schema.json#/properties/id")                   |
| [title](#title)             | `string`  | Optional | cannot be null | [manifest](schema-properties-title.md "https://fable.deno.dev/schema.json#/properties/title")             |
| [description](#description) | `string`  | Optional | cannot be null | [manifest](schema-properties-description.md "https://fable.deno.dev/schema.json#/properties/description") |
| [nsfw](#nsfw)               | `boolean` | Optional | cannot be null | [manifest](schema-properties-nsfw.md "https://fable.deno.dev/schema.json#/properties/nsfw")               |
| [author](#author)           | `string`  | Optional | cannot be null | [manifest](schema-properties-author.md "https://fable.deno.dev/schema.json#/properties/author")           |
| [image](#image)             | `string`  | Optional | cannot be null | [manifest](schema-properties-image.md "https://fable.deno.dev/schema.json#/properties/image")             |
| [url](#url)                 | `string`  | Optional | cannot be null | [manifest](schema-properties-url.md "https://fable.deno.dev/schema.json#/properties/url")                 |
| [depends](#depends)         | `array`   | Optional | cannot be null | [manifest](schema-properties-depends.md "https://fable.deno.dev/schema.json#/properties/depends")         |
| [conflicts](#conflicts)     | `array`   | Optional | cannot be null | [manifest](schema-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/conflicts")     |
| [media](#media)             | `object`  | Optional | cannot be null | [manifest](schema-properties-media.md "https://fable.deno.dev/schema.json#/properties/media")             |
| [characters](#characters)   | `object`  | Optional | cannot be null | [manifest](schema-properties-characters.md "https://fable.deno.dev/schema.json#/properties/characters")   |

## id

A unique alphanumeric id

`id`

*   is required

*   Type: `string` ([id](schema-properties-id.md))

*   cannot be null

*   defined in: [manifest](schema-properties-id.md "https://fable.deno.dev/schema.json#/properties/id")

### id Type

`string` ([id](schema-properties-id.md))

### id Constraints

**maximum length**: the maximum number of characters for this string is: `20`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[-_a-z0-9]+$
```

[try pattern](https://regexr.com/?expression=%5E%5B-_a-z0-9%5D%2B%24 "try regular expression with regexr.com")

## title

The display name of the pack

`title`

*   is optional

*   Type: `string` ([title](schema-properties-title.md))

*   cannot be null

*   defined in: [manifest](schema-properties-title.md "https://fable.deno.dev/schema.json#/properties/title")

### title Type

`string` ([title](schema-properties-title.md))

### title Constraints

**maximum length**: the maximum number of characters for this string is: `128`

## description

Small description about the pack and what it contains

`description`

*   is optional

*   Type: `string` ([description](schema-properties-description.md))

*   cannot be null

*   defined in: [manifest](schema-properties-description.md "https://fable.deno.dev/schema.json#/properties/description")

### description Type

`string` ([description](schema-properties-description.md))

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## nsfw

If the pack contains any nsfw (adult) content

`nsfw`

*   is optional

*   Type: `boolean` ([nsfw](schema-properties-nsfw.md))

*   cannot be null

*   defined in: [manifest](schema-properties-nsfw.md "https://fable.deno.dev/schema.json#/properties/nsfw")

### nsfw Type

`boolean` ([nsfw](schema-properties-nsfw.md))

## author

The name of the pack's author

`author`

*   is optional

*   Type: `string` ([author](schema-properties-author.md))

*   cannot be null

*   defined in: [manifest](schema-properties-author.md "https://fable.deno.dev/schema.json#/properties/author")

### author Type

`string` ([author](schema-properties-author.md))

## image

The icon of the pack or its author

`image`

*   is optional

*   Type: `string` ([image](schema-properties-image.md))

*   cannot be null

*   defined in: [manifest](schema-properties-image.md "https://fable.deno.dev/schema.json#/properties/image")

### image Type

`string` ([image](schema-properties-image.md))

## url

A url to pack's homepage

`url`

*   is optional

*   Type: `string` ([url](schema-properties-url.md))

*   cannot be null

*   defined in: [manifest](schema-properties-url.md "https://fable.deno.dev/schema.json#/properties/url")

### url Type

`string` ([url](schema-properties-url.md))

## depends

A list of packs that are required to make your pack function properly

`depends`

*   is optional

*   Type: `string[]` ([dependency](schema-properties-depends-dependency.md))

*   cannot be null

*   defined in: [manifest](schema-properties-depends.md "https://fable.deno.dev/schema.json#/properties/depends")

### depends Type

`string[]` ([dependency](schema-properties-depends-dependency.md))

## conflicts

A list of packs that might conflict with your pack

`conflicts`

*   is optional

*   Type: `string[]` ([conflict](schema-properties-conflicts-conflict.md))

*   cannot be null

*   defined in: [manifest](schema-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/conflicts")

### conflicts Type

`string[]` ([conflict](schema-properties-conflicts-conflict.md))

## media

Media to add, disable or overwrite

`media`

*   is optional

*   Type: `object` ([media](schema-properties-media.md))

*   cannot be null

*   defined in: [manifest](schema-properties-media.md "https://fable.deno.dev/schema.json#/properties/media")

### media Type

`object` ([media](schema-properties-media.md))

## characters

Characters to add, disable or overwrite

`characters`

*   is optional

*   Type: `object` ([characters](schema-properties-characters.md))

*   cannot be null

*   defined in: [manifest](schema-properties-characters.md "https://fable.deno.dev/schema.json#/properties/characters")

### characters Type

`object` ([characters](schema-properties-characters.md))
