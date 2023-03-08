## character Type

`object` ([character](character.md))

# character Properties

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                            |
| :------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                       | `string`  | Optional | cannot be null | [character](character-properties-id.md "https://fable.deno.dev/character.json#/properties/id")                        |
| [name](#name)                   | Merged    | Optional | cannot be null | [character](alias.md "https://fable.deno.dev/alias.json#/properties/name")                                            |
| [description](#description)     | `string`  | Optional | cannot be null | [character](character-properties-description.md "https://fable.deno.dev/character.json#/properties/description")      |
| [popularity](#popularity)       | `integer` | Optional | cannot be null | [character](character-properties-popularity.md "https://fable.deno.dev/character.json#/properties/popularity")        |
| [gender](#gender)               | `string`  | Optional | cannot be null | [character](character-properties-gender.md "https://fable.deno.dev/character.json#/properties/gender")                |
| [age](#age)                     | `string`  | Optional | cannot be null | [character](character-properties-age.md "https://fable.deno.dev/character.json#/properties/age")                      |
| [images](#images)               | `array`   | Optional | cannot be null | [character](image.md "https://fable.deno.dev/image.json#/properties/images")                                          |
| [externalLinks](#externallinks) | `array`   | Optional | cannot be null | [character](character-properties-external-links.md "https://fable.deno.dev/character.json#/properties/externalLinks") |
| [media](#media)                 | `array`   | Optional | cannot be null | [character](character-properties-media.md "https://fable.deno.dev/character.json#/properties/media")                  |

## id

A unique alphanumeric id

`id`

*   is optional

*   Type: `string` ([id](character-properties-id.md))

*   cannot be null

*   defined in: [character](character-properties-id.md "https://fable.deno.dev/character.json#/properties/id")

### id Type

`string` ([id](character-properties-id.md))

### id Constraints

**maximum length**: the maximum number of characters for this string is: `20`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[-_a-z0-9]+$
```

[try pattern](https://regexr.com/?expression=%5E%5B-_a-z0-9%5D%2B%24 "try regular expression with regexr.com")

## name

The name of the character

`name`

*   is optional

*   Type: `object` ([alias](alias.md))

*   cannot be null

*   defined in: [character](alias.md "https://fable.deno.dev/alias.json#/properties/name")

### name Type

`object` ([alias](alias.md))

any of

*   [Untitled undefined type in alias](alias-anyof-0.md "check type definition")

*   [Untitled undefined type in alias](alias-anyof-1.md "check type definition")

*   [Untitled undefined type in alias](alias-anyof-2.md "check type definition")

## description

Add a description about this character

`description`

*   is optional

*   Type: `string` ([description](character-properties-description.md))

*   cannot be null

*   defined in: [character](character-properties-description.md "https://fable.deno.dev/character.json#/properties/description")

### description Type

`string` ([description](character-properties-description.md))

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## popularity

Set the popularity of the character (the number of followers or people who likes them)

`popularity`

*   is optional

*   Type: `integer` ([popularity](character-properties-popularity.md))

*   cannot be null

*   defined in: [character](character-properties-popularity.md "https://fable.deno.dev/character.json#/properties/popularity")

### popularity Type

`integer` ([popularity](character-properties-popularity.md))

### popularity Constraints

**maximum**: the value of this number must smaller than or equal to: `2147483647`

**minimum**: the value of this number must greater than or equal to: `0`

## gender

The gender of the character

`gender`

*   is optional

*   Type: `string` ([gender](character-properties-gender.md))

*   cannot be null

*   defined in: [character](character-properties-gender.md "https://fable.deno.dev/character.json#/properties/gender")

### gender Type

`string` ([gender](character-properties-gender.md))

## age

The age of the character

`age`

*   is optional

*   Type: `string` ([age](character-properties-age.md))

*   cannot be null

*   defined in: [character](character-properties-age.md "https://fable.deno.dev/character.json#/properties/age")

### age Type

`string` ([age](character-properties-age.md))

## images

A set of images featuring this character

`images`

*   is optional

*   Type: `object[]` ([image](image-image.md))

*   cannot be null

*   defined in: [character](image.md "https://fable.deno.dev/image.json#/properties/images")

### images Type

`object[]` ([image](image-image.md))

## externalLinks

A list of urls for the media's pages on various platforms

`externalLinks`

*   is optional

*   Type: `object[]` ([external link](character-properties-external-links-external-link.md))

*   cannot be null

*   defined in: [character](character-properties-external-links.md "https://fable.deno.dev/character.json#/properties/externalLinks")

### externalLinks Type

`object[]` ([external link](character-properties-external-links-external-link.md))

## media

A list of media that the character appears in

`media`

*   is optional

*   Type: `object[]` ([media](character-properties-media-media.md))

*   cannot be null

*   defined in: [character](character-properties-media.md "https://fable.deno.dev/character.json#/properties/media")

### media Type

`object[]` ([media](character-properties-media-media.md))
