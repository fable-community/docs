# Untitled object in \[object Object] Schema

```txt
schema.json#/properties/media
```

Media to add, or overwrite

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [schema.json\*](../out/schema.json "open original schema") |

## media Type

`object` ([Details](schema-properties-media.md))

# media Properties

| Property                | Type    | Required | Nullable       | Defined by                                                                                                                |
| :---------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------ |
| [new](#new)             | `array` | Optional | cannot be null | [\[object Object\]](schema-properties-media-properties-new.md "schema.json#/properties/media/properties/new")             |
| [conflicts](#conflicts) | `array` | Optional | cannot be null | [\[object Object\]](schema-properties-media-properties-conflicts.md "schema.json#/properties/media/properties/conflicts") |

## new

A list of new media to add

`new`

*   is optional

*   Type: an array of merged types ([Details](schema-properties-media-properties-new-items.md))

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-media-properties-new.md "schema.json#/properties/media/properties/new")

### new Type

an array of merged types ([Details](schema-properties-media-properties-new-items.md))

## conflicts

A list of media that might conflict with your pack. All media listed here will be entirely disabled.

`conflicts`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [\[object Object\]](schema-properties-media-properties-conflicts.md "schema.json#/properties/media/properties/conflicts")

### conflicts Type

`string[]`
