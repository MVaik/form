---
id: StandardSchemaV1Issue
title: StandardSchemaV1Issue
---

<!-- DO NOT EDIT: this page is autogenerated from the type comments -->

# Interface: StandardSchemaV1Issue

Defined in: [packages/form-core/src/standardSchemaValidator.ts:144](https://github.com/TanStack/form/blob/main/packages/form-core/src/standardSchemaValidator.ts#L144)

The issue interface of the failure output.

## Properties

### message

```ts
readonly message: string;
```

Defined in: [packages/form-core/src/standardSchemaValidator.ts:148](https://github.com/TanStack/form/blob/main/packages/form-core/src/standardSchemaValidator.ts#L148)

The error message of the issue.

***

### path?

```ts
readonly optional path: readonly (PropertyKey | StandardSchemaV1PathSegment)[];
```

Defined in: [packages/form-core/src/standardSchemaValidator.ts:152](https://github.com/TanStack/form/blob/main/packages/form-core/src/standardSchemaValidator.ts#L152)

The path of the issue, if any.
