# relation Schema

```txt
https://fable.deno.dev/media.json#/properties/relations/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json\*](../out/media.json "open original schema") |

## items Type

`object` ([relation](media-properties-relations-relation.md))

# items Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                              |
| :-------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [relation](#relation) | `string` | Required | cannot be null | [media](media-properties-relations-relation-properties-relation.md "https://fable.deno.dev/media.json#/properties/relations/items/properties/relation") |
| [mediaId](#mediaid)   | `string` | Required | cannot be null | [media](media-properties-relations-relation-properties-mediaid.md "https://fable.deno.dev/media.json#/properties/relations/items/properties/mediaId")   |

## relation

Choose the kind of relationship between this media a different media

`relation`

*   is required

*   Type: `string` ([relation](media-properties-relations-relation-properties-relation.md))

*   cannot be null

*   defined in: [media](media-properties-relations-relation-properties-relation.md "https://fable.deno.dev/media.json#/properties/relations/items/properties/relation")

### relation Type

`string` ([relation](media-properties-relations-relation-properties-relation.md))

### relation Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"PREQUEL"`    |             |
| `"SEQUEL"`     |             |
| `"PARENT"`     |             |
| `"CONTAINS"`   |             |
| `"SIDE_STORY"` |             |
| `"SPIN_OFF"`   |             |
| `"ADAPTATION"` |             |
| `"OTHER"`      |             |

## mediaId

Reference an existing media (\[pack:]id)

`mediaId`

*   is required

*   Type: `string` ([mediaId](media-properties-relations-relation-properties-mediaid.md))

*   cannot be null

*   defined in: [media](media-properties-relations-relation-properties-mediaid.md "https://fable.deno.dev/media.json#/properties/relations/items/properties/mediaId")

### mediaId Type

`string` ([mediaId](media-properties-relations-relation-properties-mediaid.md))

### mediaId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
