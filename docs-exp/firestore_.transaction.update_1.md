<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [Transaction](./firestore_.transaction.md) &gt; [update](./firestore_.transaction.update_1.md)

## Transaction.update() method

Updates fields in the document referred to by the provided [DocumentReference](./firestore_.documentreference.md)<!-- -->. The update will fail if applied to a document that does not exist.

Nested fields can be updated by providing dot-separated field path strings or by providing `FieldPath` objects.

<b>Signature:</b>

```typescript
update(documentRef: DocumentReference<unknown>, field: string | FieldPath, value: unknown, ...moreFieldsAndValues: unknown[]): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  documentRef | [DocumentReference](./firestore_.documentreference.md)<!-- -->&lt;unknown&gt; | A reference to the document to be updated. |
|  field | string \| [FieldPath](./firestore_.fieldpath.md) | The first field to update. |
|  value | unknown | The first value. |
|  moreFieldsAndValues | unknown\[\] | Additional key/value pairs. |

<b>Returns:</b>

this

This `Transaction` instance. Used for chaining method calls.

