# Untitled object in undefined Schema

```txt
schema.json#/allOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [schema.builtin.json\*](../out/schema.builtin.json "open original schema") |

## 0 Type

`object` ([Details](schema-1-allof-0.md))

# 0 Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                  |
| :-------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------ |
| [id](#id)                   | `string`  | Required | cannot be null | [\[object Object\]](schema-properties-id.md "schema.json#/properties/id")                   |
| [title](#title)             | `string`  | Optional | cannot be null | [\[object Object\]](schema-properties-title.md "schema.json#/properties/title")             |
| [description](#description) | `string`  | Optional | cannot be null | [\[object Object\]](schema-properties-description.md "schema.json#/properties/description") |
| [nsfw](#nsfw)               | `boolean` | Optional | cannot be null | [\[object Object\]](schema-properties-nsfw.md "schema.json#/properties/nsfw")               |
| [author](#author)           | `string`  | Optional | cannot be null | [\[object Object\]](schema-properties-author.md "schema.json#/properties/author")           |
| [image](#image)             | `string`  | Optional | cannot be null | [\[object Object\]](schema-properties-image.md "schema.json#/properties/image")             |
| [url](#url)                 | `string`  | Optional | cannot be null | [\[object Object\]](schema-properties-url.md "schema.json#/properties/url")                 |
| [depends](#depends)         | `array`   | Optional | cannot be null | [\[object Object\]](schema-properties-depends.md "schema.json#/properties/depends")         |
| [conflicts](#conflicts)     | `array`   | Optional | cannot be null | [\[object Object\]](schema-properties-conflicts.md "schema.json#/properties/conflicts")     |
| [media](#media)             | `object`  | Optional | cannot be null | [\[object Object\]](schema-properties-media.md "schema.json#/properties/media")             |
| [characters](#characters)   | `object`  | Optional | cannot be null | [\[object Object\]](schema-properties-characters.md "schema.json#/properties/characters")   |

## id

A unique alphanumeric id

`id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-id.md "schema.json#/properties/id")

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

## title

The display title of the pack

`title`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-title.md "schema.json#/properties/title")

### title Type

`string`

### title Constraints

**maximum length**: the maximum number of characters for this string is: `128`

## description

Small description about the pack and what it contains

`description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-description.md "schema.json#/properties/description")

### description Type

`string`

### description Constraints

**maximum length**: the maximum number of characters for this string is: `2048`

## nsfw

If the pack contains nsfw (adult) content

`nsfw`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-nsfw.md "schema.json#/properties/nsfw")

### nsfw Type

`boolean`

## author

The name of the pack's author

`author`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-author.md "schema.json#/properties/author")

### author Type

`string`

## image

The icon of the pack or its author

`image`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-image.md "schema.json#/properties/image")

### image Type

`string`

## url

The url to pack's homepage

`url`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-url.md "schema.json#/properties/url")

### url Type

`string`

## depends

A list of packs that are required to make your pack function properly.

`depends`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-depends.md "schema.json#/properties/depends")

### depends Type

`string[]`

## conflicts

A list of packs that might conflict with your pack.

`conflicts`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-conflicts.md "schema.json#/properties/conflicts")

### conflicts Type

`string[]`

## media

Media to add, or overwrite

`media`

*   is optional

*   Type: `object` ([Details](schema-properties-media.md))

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-media.md "schema.json#/properties/media")

### media Type

`object` ([Details](schema-properties-media.md))

## characters

Characters to add, or overwrite

`characters`

*   is optional

*   Type: `object` ([Details](schema-properties-characters.md))

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-characters.md "schema.json#/properties/characters")

### characters Type

`object` ([Details](schema-properties-characters.md))
