# Untitled schema Schema

```txt
schema.builtin.json
```



> Only used for the builtin packs. Those properties don't work on normal community packs.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [schema.builtin.json](../out/schema.builtin.json "open original schema") |

## Untitled schema Type

merged type ([Details](schema-1.md))

all of

*   [Untitled object in undefined](schema-1-allof-0.md "check type definition")

# Untitled schema Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                    |
| :-------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------- |
| [type](#type)         | `string` | Required | cannot be null | [Untitled schema](schema-1-properties-type.md "schema.builtin.json#/properties/type")         |
| [commands](#commands) | `object` | Optional | cannot be null | [Untitled schema](schema-1-properties-commands.md "schema.builtin.json#/properties/commands") |

## type



`type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](schema-1-properties-type.md "schema.builtin.json#/properties/type")

### type Type

`string`

### type Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
builtin
```

[try pattern](https://regexr.com/?expression=builtin "try regular expression with regexr.com")

## commands

Register new slash commands

`commands`

*   is optional

*   Type: `object` ([Details](schema-1-properties-commands.md))

*   cannot be null

*   defined in: [Untitled schema](schema-1-properties-commands.md "schema.builtin.json#/properties/commands")

### commands Type

`object` ([Details](schema-1-properties-commands.md))
