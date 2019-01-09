[Home](./index) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [FileSystem](./node-core-library.filesystem.md) &gt; [createHardLink](./node-core-library.filesystem.createhardlink.md)

## FileSystem.createHardLink() method

Creates a hard link. Behind the scenes it uses `fs.linkSync()`<!-- -->.

<b>Signature:</b>

```typescript
static createHardLink(options: IFileSystemCreateLinkOptions): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | `IFileSystemCreateLinkOptions` |  |

<b>Returns:</b>

`void`
