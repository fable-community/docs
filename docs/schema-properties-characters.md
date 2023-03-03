# characters Schema

```txt
https://fable.deno.dev/schema.json#/properties/characters
```

Characters to add, or overwrite

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [schema.json\*](../out/schema.json "open original schema") |

## characters Type

`object` ([characters](schema-properties-characters.md))

# characters Properties

| Property                | Type    | Required | Nullable       | Defined by                                                                                                                                        |
| :---------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [new](#new)             | `array` | Optional | cannot be null | [manifest](schema-properties-characters-properties-new.md "https://fable.deno.dev/schema.json#/properties/characters/properties/new")             |
| [conflicts](#conflicts) | `array` | Optional | cannot be null | [manifest](schema-properties-characters-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/characters/properties/conflicts") |

## new

A list of new characters to add

`new`

*   is optional

*   Type: an array of merged types ([character](schema-properties-characters-properties-new-character.md))

*   cannot be null

*   defined in: [manifest](schema-properties-characters-properties-new.md "https://fable.deno.dev/schema.json#/properties/characters/properties/new")

### new Type

an array of merged types ([character](schema-properties-characters-properties-new-character.md))

## conflicts

A list of characters that might conflict with your pack (All characters listed here will be entirely disabled).

`conflicts`

*   is optional

*   Type: `string[]` ([conflict](schema-properties-characters-properties-conflicts-conflict.md))

*   cannot be null

*   defined in: [manifest](schema-properties-characters-properties-conflicts.md "https://fable.deno.dev/schema.json#/properties/characters/properties/conflicts")

### conflicts Type

`string[]` ([conflict](schema-properties-characters-properties-conflicts-conflict.md))
