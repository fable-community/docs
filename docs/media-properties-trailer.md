# Untitled object in \[object Object] Schema

```txt
media.json#/properties/trailer
```

A url to a trailer about the media

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [media.json\*](../out/media.json "open original schema") |

## trailer Type

`object` ([Details](media-properties-trailer.md))

# trailer Properties

| Property      | Type          | Required | Nullable       | Defined by                                                                                                        |
| :------------ | :------------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------- |
| [site](#site) | Not specified | Required | cannot be null | [\[object Object\]](media-properties-trailer-properties-site.md "media.json#/properties/trailer/properties/site") |
| [id](#id)     | `string`      | Required | cannot be null | [\[object Object\]](media-properties-trailer-properties-id.md "media.json#/properties/trailer/properties/id")     |

## site

The name of the site (only supports youtube)

`site`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [\[object Object\]](media-properties-trailer-properties-site.md "media.json#/properties/trailer/properties/site")

### site Type

unknown

### site Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"youtube"` |             |

## id

The id of the video

`id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [\[object Object\]](media-properties-trailer-properties-id.md "media.json#/properties/trailer/properties/id")

### id Type

`string`

### id Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
([A-Za-z0-9_\-]{11})
```

[try pattern](https://regexr.com/?expression=\(%5BA-Za-z0-9_%5C-%5D%7B11%7D\) "try regular expression with regexr.com")
