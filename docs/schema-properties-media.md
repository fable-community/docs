# media Schema

```txt
https://fable.deno.dev/schema.json#/properties/media
```

Media to add, or overwrite

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [schema.json\*](../out/schema.json "open original schema") |

## media Type

`object` ([media](schema-properties-media.md))

# media Properties

| Property                | Type    | Required | Nullable       | Defined by                                                                                                                              |
| :---------------------- | :------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| [new](#new)             | `array` | Optional | cannot be null | [manifest](schema-properties-media-properties-new.md "https://fable.deno.dev/schema.json#/properties/media/properties/new")             |
| [conflicts](#conflicts) | `array` | Optional | cannot be null | [manifest](schema-properties-media-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/media/properties/conflicts") |

## new

A list of new media to add

`new`

*   is optional

*   Type: an array of merged types ([media](schema-properties-media-properties-new-media.md))

*   cannot be null

*   defined in: [manifest](schema-properties-media-properties-new.md "https://fable.deno.dev/schema.json#/properties/media/properties/new")

### new Type

an array of merged types ([media](schema-properties-media-properties-new-media.md))

## conflicts

A list of media that might conflict with your pack. All media listed here will be entirely disabled.

`conflicts`

*   is optional

*   Type: `string[]` ([conflict](schema-properties-media-properties-conflicts-conflict.md))

*   cannot be null

*   defined in: [manifest](schema-properties-media-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/media/properties/conflicts")

### conflicts Type

`string[]` ([conflict](schema-properties-media-properties-conflicts-conflict.md))
