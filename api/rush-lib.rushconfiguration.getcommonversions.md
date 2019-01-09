[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfiguration](./rush-lib.rushconfiguration.md) &gt; [getCommonVersions](./rush-lib.rushconfiguration.getcommonversions.md)

## RushConfiguration.getCommonVersions() method

Gets the settings from the common-versions.json config file for a specific variant.

<b>Signature:</b>

```typescript
getCommonVersions(variant?: string | undefined): CommonVersionsConfiguration;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  variant | `string | undefined` | The name of the current variant in use by the active command. |

<b>Returns:</b>

`CommonVersionsConfiguration`
