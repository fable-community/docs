# Untitled object in \[object Object] Schema

```txt
media.json#/properties/characters/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json\*](../out/media.json "open original schema") |

## items Type

`object` ([Details](media-properties-characters-items.md))

# items Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                        |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [role](#role)               | Not specified | Required | cannot be null | [\[object Object\]](media-properties-characters-items-properties-role.md "media.json#/properties/characters/items/properties/role")               |
| [characterId](#characterid) | `string`      | Required | cannot be null | [\[object Object\]](media-properties-characters-items-properties-characterid.md "media.json#/properties/characters/items/properties/characterId") |

## role

Choose the role the character plays in the media

`role`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [\[object Object\]](media-properties-characters-items-properties-role.md "media.json#/properties/characters/items/properties/role")

### role Type

unknown

### role Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"MAIN"`       |             |
| `"SUPPORTING"` |             |
| `"BACKGROUND"` |             |

## characterId

Reference an existing character (\[pack:]id)

`characterId`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-characters-items-properties-characterid.md "media.json#/properties/characters/items/properties/characterId")

### characterId Type

`string`

### characterId Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^([-_a-z0-9]+)(:[-_a-z0-9]+)?$
```

[try pattern](https://regexr.com/?expression=%5E\(%5B-_a-z0-9%5D%2B\)\(%3A%5B-_a-z0-9%5D%2B\)%3F%24 "try regular expression with regexr.com")
