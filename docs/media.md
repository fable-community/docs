# media Schema

```txt
https://fable.deno.dev/media.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json](../out/media.json "open original schema") |

## media Type

`object` ([media](media.md))

# media Properties

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                |
| :------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------- |
| [id](#id)                       | `string`  | Optional | cannot be null | [media](media-properties-id.md "https://fable.deno.dev/media.json#/properties/id")                        |
| [type](#type)                   | `string`  | Optional | cannot be null | [media](media-properties-type.md "https://fable.deno.dev/media.json#/properties/type")                    |
| [format](#format)               | `string`  | Optional | cannot be null | [media](media-properties-format.md "https://fable.deno.dev/media.json#/properties/format")                |
| [title](#title)                 | Merged    | Optional | cannot be null | [media](alias.md "https://fable.deno.dev/alias.json#/properties/title")                                   |
| [popularity](#popularity)       | `integer` | Optional | cannot be null | [media](media-properties-popularity.md "https://fable.deno.dev/media.json#/properties/popularity")        |
| [description](#description)     | `string`  | Optional | cannot be null | [media](media-properties-description.md "https://fable.deno.dev/media.json#/properties/description")      |
| [images](#images)               | `array`   | Optional | cannot be null | [media](image.md "https://fable.deno.dev/image.json#/properties/images")                                  |
| [trailer](#trailer)             | `object`  | Optional | cannot be null | [media](media-properties-trailer.md "https://fable.deno.dev/media.json#/properties/trailer")              |
| [externalLinks](#externallinks) | `array`   | Optional | cannot be null | [media](media-properties-external-links.md "https://fable.deno.dev/media.json#/properties/externalLinks") |
| [relations](#relations)         | `array`   | Optional | cannot be null | [media](media-properties-relations.md "https://fable.deno.dev/media.json#/properties/relations")          |
| [characters](#characters)       | `array`   | Optional | cannot be null | [media](media-properties-characters.md "https://fable.deno.dev/media.json#/properties/characters")        |

## id

A unique alphanumeric id

`id`

*   is optional

*   Type: `string` ([id](media-properties-id.md))

*   cannot be null

*   defined in: [media](media-properties-id.md "https://fable.deno.dev/media.json#/properties/id")

### id Type

`string` ([id](media-properties-id.md))

### id Constraints

**maximum length**: the maximum number of characters for this string is: `20`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[-_a-z0-9]+$
```

[try pattern](https://regexr.com/?expression=%5E%5B-_a-z0-9%5D%2B%24 "try regular expression with regexr.com")

## type

Choose what type of media this is

`type`

*   is optional

*   Type: `string` ([type](media-properties-type.md))

*   cannot be null

*   defined in: [media](media-properties-type.md "https://fable.deno.dev/media.json#/properties/type")

### type Type

`string` ([type](media-properties-type.md))

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"ANIME"` |             |
| `"MANGA"` |             |

## format

Choose what format of media this is

`format`

*   is optional

*   Type: `string` ([format](media-properties-format.md))

*   cannot be null

*   defined in: [media](media-properties-format.md "https://fable.deno.dev/media.json#/properties/format")

### format Type

`string` ([format](media-properties-format.md))

### format Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"TV"`       |             |
| `"TV_SHORT"` |             |
| `"MOVIE"`    |             |
| `"SPECIAL"`  |             |
| `"OVA"`      |             |
| `"ONA"`      |             |
| `"MUSIC"`    |             |
| `"MANGA"`    |             |
| `"NOVEL"`    |             |
| `"ONE_SHOT"` |             |

## title

The title of the media

`title`

*   is optional

*   Type: `object` ([alias](alias.md))

*   cannot be null

*   defined in: [media](alias.md "https://fable.deno.dev/alias.json#/properties/title")

### title Type

`object` ([alias](alias.md))

any of

*   [Untitled undefined type in alias](alias-anyof-0.md "check type definition")

*   [Untitled undefined type in alias](alias-anyof-1.md "check type definition")

*   [Untitled undefined type in alias](alias-anyof-2.md "check type definition")

## popularity

Set the popularity of the media (the number of followers or people who read/watch it)

`popularity`

*   is optional

*   Type: `integer` ([popularity](media-properties-popularity.md))

*   cannot be null

*   defined in: [media](media-properties-popularity.md "https://fable.deno.dev/media.json#/properties/popularity")

### popularity Type

`integer` ([popularity](media-properties-popularity.md))

### popularity Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## description

Add a description about this media

`description`

*   is optional

*   Type: `string` ([description](media-properties-description.md))

*   cannot be null

*   defined in: [media](media-properties-description.md "https://fable.deno.dev/media.json#/properties/description")

### description Type

`string` ([description](media-properties-description.md))

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## images

A set of images featuring this media

`images`

*   is optional

*   Type: `object[]` ([image](image-image.md))

*   cannot be null

*   defined in: [media](image.md "https://fable.deno.dev/image.json#/properties/images")

### images Type

`object[]` ([image](image-image.md))

## trailer

A url to a trailer about the media

`trailer`

*   is optional

*   Type: `object` ([trailer](media-properties-trailer.md))

*   cannot be null

*   defined in: [media](media-properties-trailer.md "https://fable.deno.dev/media.json#/properties/trailer")

### trailer Type

`object` ([trailer](media-properties-trailer.md))

## externalLinks

A list of urls for the media's pages on various platforms

`externalLinks`

*   is optional

*   Type: `object[]` ([external link](media-properties-external-links-external-link.md))

*   cannot be null

*   defined in: [media](media-properties-external-links.md "https://fable.deno.dev/media.json#/properties/externalLinks")

### externalLinks Type

`object[]` ([external link](media-properties-external-links-external-link.md))

## relations

Define the relations between this media and other media

`relations`

*   is optional

*   Type: `object[]` ([relation](media-properties-relations-relation.md))

*   cannot be null

*   defined in: [media](media-properties-relations.md "https://fable.deno.dev/media.json#/properties/relations")

### relations Type

`object[]` ([relation](media-properties-relations-relation.md))

## characters

A list of characters that appear in the media

`characters`

*   is optional

*   Type: `object[]` ([character](media-properties-characters-character.md))

*   cannot be null

*   defined in: [media](media-properties-characters.md "https://fable.deno.dev/media.json#/properties/characters")

### characters Type

`object[]` ([character](media-properties-characters-character.md))
