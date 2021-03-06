<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [Settings](./firestore_.settings.md) &gt; [cacheSizeBytes](./firestore_.settings.cachesizebytes.md)

## Settings.cacheSizeBytes property

An approximate cache size threshold for the on-disk data. If the cache grows beyond this size, Firestore will start removing data that hasn't been recently used. The size is not a guarantee that the cache will stay below that size, only that if the cache exceeds the given size, cleanup will be attempted.

The default value is 40 MB. The threshold must be set to at least 1 MB, and can be set to `CACHE_SIZE_UNLIMITED` to disable garbage collection.

<b>Signature:</b>

```typescript
cacheSizeBytes?: number;
```
