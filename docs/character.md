# Untitled object in undefined Schema

```txt
character.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [character.json](../out/character.json "open original schema") |

## Untitled object in undefined Type

`object` ([Details](character.md))

# Untitled object in undefined Properties

| Property                        | Type      | Required | Nullable       | Defined by                                                                                          |
| :------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------- |
| [id](#id)                       | `string`  | Optional | cannot be null | [Untitled schema](character-properties-id.md "character.json#/properties/id")                       |
| [name](#name)                   | Merged    | Optional | cannot be null | [Untitled schema](character-properties-name.md "alias.json#/properties/name")                       |
| [description](#description)     | `string`  | Optional | cannot be null | [Untitled schema](character-properties-description.md "character.json#/properties/description")     |
| [popularity](#popularity)       | `integer` | Optional | cannot be null | [Untitled schema](character-properties-popularity.md "character.json#/properties/popularity")       |
| [gender](#gender)               | `string`  | Optional | cannot be null | [Untitled schema](character-properties-gender.md "character.json#/properties/gender")               |
| [age](#age)                     | `string`  | Optional | cannot be null | [Untitled schema](character-properties-age.md "character.json#/properties/age")                     |
| [images](#images)               | `array`   | Optional | cannot be null | [Untitled schema](character-properties-images.md "image.json#/properties/images")                   |
| [externalLinks](#externallinks) | `array`   | Optional | cannot be null | [Untitled schema](character-properties-externallinks.md "character.json#/properties/externalLinks") |
| [media](#media)                 | `array`   | Optional | cannot be null | [Untitled schema](character-properties-media.md "character.json#/properties/media")                 |

## id

A unique alphanumeric id

`id`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](character-properties-id.md "character.json#/properties/id")

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

## name

The name of the character

`name`

*   is optional

*   Type: `object` ([Details](character-properties-name.md))

*   cannot be null

*   defined in: [Untitled schema](character-properties-name.md "alias.json#/properties/name")

### name Type

`object` ([Details](character-properties-name.md))

any of

*   [Untitled schema](alias-anyof-0.md "check type definition")

*   [Untitled schema](alias-anyof-1.md "check type definition")

*   [Untitled schema](alias-anyof-2.md "check type definition")

## description

Add a description about this character

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](character-properties-description.md "character.json#/properties/description")

### description Type

`string`

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## popularity

Set the popularity of the character (the number of followers or people who likes them)

`popularity`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](character-properties-popularity.md "character.json#/properties/popularity")

### popularity Type

`integer`

### popularity Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## gender

The gender of the character

`gender`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](character-properties-gender.md "character.json#/properties/gender")

### gender Type

`string`

## age

The age of the character

`age`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](character-properties-age.md "character.json#/properties/age")

### age Type

`string`

## images

A set of images featuring this character

`images`

*   is optional

*   Type: `object[]` ([Details](image-items.md))

*   cannot be null

*   defined in: [Untitled schema](character-properties-images.md "image.json#/properties/images")

### images Type

`object[]` ([Details](image-items.md))

## externalLinks

A list of urls for the media's pages on various platforms

`externalLinks`

*   is optional

*   Type: `object[]` ([Details](character-properties-externallinks-items.md))

*   cannot be null

*   defined in: [Untitled schema](character-properties-externallinks.md "character.json#/properties/externalLinks")

### externalLinks Type

`object[]` ([Details](character-properties-externallinks-items.md))

## media

A list of media that the character appears in

`media`

*   is optional

*   Type: `object[]` ([Details](character-properties-media-items.md))

*   cannot be null

*   defined in: [Untitled schema](character-properties-media.md "character.json#/properties/media")

### media Type

`object[]` ([Details](character-properties-media-items.md))
