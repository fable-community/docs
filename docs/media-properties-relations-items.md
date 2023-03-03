# Untitled object in \[object Object] Schema

```txt
media.json#/properties/relations/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json\*](../out/media.json "open original schema") |

## items Type

`object` ([Details](media-properties-relations-items.md))

# items Properties

| Property              | Type          | Required | Nullable       | Defined by                                                                                                                                |
| :-------------------- | :------------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| [relation](#relation) | Not specified | Required | cannot be null | [\[object Object\]](media-properties-relations-items-properties-relation.md "media.json#/properties/relations/items/properties/relation") |
| [mediaId](#mediaid)   | `string`      | Required | cannot be null | [\[object Object\]](media-properties-relations-items-properties-mediaid.md "media.json#/properties/relations/items/properties/mediaId")   |

## relation

Choose the kind of relationship between this media a different media

`relation`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [\[object Object\]](media-properties-relations-items-properties-relation.md "media.json#/properties/relations/items/properties/relation")

### relation Type

unknown

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

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-relations-items-properties-mediaid.md "media.json#/properties/relations/items/properties/mediaId")

### mediaId Type

`string`

### mediaId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
