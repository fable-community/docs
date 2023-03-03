# relation Schema

```txt
https://fable.deno.dev/media.json#/properties/relations/items/properties/relation
```

Choose the kind of relationship between this media a different media

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [media.json\*](../out/media.json "open original schema") |

## relation Type

`string` ([relation](media-properties-relations-relation-properties-relation.md))

## relation Constraints

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
