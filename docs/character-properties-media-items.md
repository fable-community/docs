# Untitled object in undefined Schema

```txt
character.json#/properties/media/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [character.json\*](../out/character.json "open original schema") |

## items Type

`object` ([Details](character-properties-media-items.md))

# items Properties

| Property            | Type          | Required | Nullable       | Defined by                                                                                                                            |
| :------------------ | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------ |
| [role](#role)       | Not specified | Required | cannot be null | [Untitled schema](character-properties-media-items-properties-role.md "character.json#/properties/media/items/properties/role")       |
| [mediaId](#mediaid) | `string`      | Required | cannot be null | [Untitled schema](character-properties-media-items-properties-mediaid.md "character.json#/properties/media/items/properties/mediaId") |

## role

Choose the role the character plays in the media

`role`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [Untitled schema](character-properties-media-items-properties-role.md "character.json#/properties/media/items/properties/role")

### role Type

unknown

### role Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"MAIN"`       |             |
| `"SUPPORTING"` |             |
| `"BACKGROUND"` |             |

## mediaId

Reference an existing character (\[pack:]id)

`mediaId`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](character-properties-media-items-properties-mediaid.md "character.json#/properties/media/items/properties/mediaId")

### mediaId Type

`string`

### mediaId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
