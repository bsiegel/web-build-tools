[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [ApprovedPackagesConfiguration](./rush-lib.approvedpackagesconfiguration.md)

## ApprovedPackagesConfiguration class

This represents the JSON file specified via the "approvedPackagesFile" option in rush.json.

<b>Signature:</b>

```typescript
export declare class ApprovedPackagesConfiguration 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [items](./rush-lib.approvedpackagesconfiguration.items.md) |  | `ApprovedPackagesItem[]` |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addOrUpdatePackage(packageName, reviewCategory)](./rush-lib.approvedpackagesconfiguration.addorupdatepackage.md) |  |  |
|  [clear()](./rush-lib.approvedpackagesconfiguration.clear.md) |  | Clears all the settings, returning to an empty state. |
|  [getItemByName(packageName)](./rush-lib.approvedpackagesconfiguration.getitembyname.md) |  |  |
|  [loadFromFile()](./rush-lib.approvedpackagesconfiguration.loadfromfile.md) |  | Loads the configuration data from the filename that was passed to the constructor. |
|  [saveToFile()](./rush-lib.approvedpackagesconfiguration.savetofile.md) |  | Loads the configuration data to the filename that was passed to the constructor. |
|  [tryLoadFromFile(approvedPackagesPolicyEnabled)](./rush-lib.approvedpackagesconfiguration.tryloadfromfile.md) |  | If the file exists, calls loadFromFile(). |
