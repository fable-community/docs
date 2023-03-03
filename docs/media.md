# Untitled object in undefined Schema

```txt
media.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                             |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json](../out/media.json "open original schema") |

## Untitled object in undefined Type

`object` ([Details](media.md))

# Untitled object in undefined Properties

| Property                        | Type          | Required | Nullable       | Defined by                                                                                    |
| :------------------------------ | :------------ | :------- | :------------- | :-------------------------------------------------------------------------------------------- |
| [id](#id)                       | `string`      | Optional | cannot be null | [\[object Object\]](media-properties-id.md "media.json#/properties/id")                       |
| [type](#type)                   | Not specified | Optional | cannot be null | [\[object Object\]](media-properties-type.md "media.json#/properties/type")                   |
| [format](#format)               | Not specified | Optional | cannot be null | [\[object Object\]](media-properties-format.md "media.json#/properties/format")               |
| [title](#title)                 | Merged        | Optional | cannot be null | [\[object Object\]](character-properties-name.md "alias.json#/properties/title")              |
| [popularity](#popularity)       | `integer`     | Optional | cannot be null | [\[object Object\]](media-properties-popularity.md "media.json#/properties/popularity")       |
| [description](#description)     | `string`      | Optional | cannot be null | [\[object Object\]](media-properties-description.md "media.json#/properties/description")     |
| [images](#images)               | `array`       | Optional | cannot be null | [\[object Object\]](character-properties-images.md "image.json#/properties/images")           |
| [trailer](#trailer)             | `object`      | Optional | cannot be null | [\[object Object\]](media-properties-trailer.md "media.json#/properties/trailer")             |
| [externalLinks](#externallinks) | `array`       | Optional | cannot be null | [\[object Object\]](media-properties-externallinks.md "media.json#/properties/externalLinks") |
| [relations](#relations)         | `array`       | Optional | cannot be null | [\[object Object\]](media-properties-relations.md "media.json#/properties/relations")         |
| [characters](#characters)       | `array`       | Optional | cannot be null | [\[object Object\]](media-properties-characters.md "media.json#/properties/characters")       |

## id

A unique alphanumeric id

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-id.md "media.json#/properties/id")

### id Type

`string`

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

*   Type: unknown

*   cannot be null

*   defined in: [\[object Object\]](media-properties-type.md "media.json#/properties/type")

### type Type

unknown

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

*   Type: unknown

*   cannot be null

*   defined in: [\[object Object\]](media-properties-format.md "media.json#/properties/format")

### format Type

unknown

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

The name of the character

`title`

*   is optional

*   Type: `object` ([Details](character-properties-name.md))

*   cannot be null

*   defined in: [\[object Object\]](character-properties-name.md "alias.json#/properties/title")

### title Type

`object` ([Details](character-properties-name.md))

any of

*   [Untitled schema](alias-anyof-0.md "check type definition")

*   [Untitled schema](alias-anyof-1.md "check type definition")

*   [Untitled schema](alias-anyof-2.md "check type definition")

## popularity

Set the popularity of the media (the number of followers or people who read/watch it)

`popularity`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-popularity.md "media.json#/properties/popularity")

### popularity Type

`integer`

### popularity Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## description

Add a description about this media

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-description.md "media.json#/properties/description")

### description Type

`string`

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## images

A set of images featuring this character

`images`

*   is optional

*   Type: `object[]` ([Details](image-items.md))

*   cannot be null

*   defined in: [\[object Object\]](character-properties-images.md "image.json#/properties/images")

### images Type

`object[]` ([Details](image-items.md))

## trailer

A url to a trailer about the media

`trailer`

*   is optional

*   Type: `object` ([Details](media-properties-trailer.md))

*   cannot be null

*   defined in: [\[object Object\]](media-properties-trailer.md "media.json#/properties/trailer")

### trailer Type

`object` ([Details](media-properties-trailer.md))

## externalLinks

A list of urls for the media's pages on various platforms

`externalLinks`

*   is optional

*   Type: `object[]` ([Details](media-properties-externallinks-items.md))

*   cannot be null

*   defined in: [\[object Object\]](media-properties-externallinks.md "media.json#/properties/externalLinks")

### externalLinks Type

`object[]` ([Details](media-properties-externallinks-items.md))

## relations

Define the relations between this media and other media

`relations`

*   is optional

*   Type: `object[]` ([Details](media-properties-relations-items.md))

*   cannot be null

*   defined in: [\[object Object\]](media-properties-relations.md "media.json#/properties/relations")

### relations Type

`object[]` ([Details](media-properties-relations-items.md))

## characters

A list of characters that appear in the media

`characters`

*   is optional

*   Type: `object[]` ([Details](media-properties-characters-items.md))

*   cannot be null

*   defined in: [\[object Object\]](media-properties-characters.md "media.json#/properties/characters")

### characters Type

`object[]` ([Details](media-properties-characters-items.md))
