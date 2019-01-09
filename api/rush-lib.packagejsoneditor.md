[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [PackageJsonEditor](./rush-lib.packagejsoneditor.md)

## PackageJsonEditor class

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 


<b>Signature:</b>

```typescript
export declare class PackageJsonEditor 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [dependencyList](./rush-lib.packagejsoneditor.dependencylist.md) |  | `ReadonlyArray<PackageJsonDependency>` | <b><i>(BETA)</i></b> The list of dependencies of type DependencyType.Regular, DependencyType.Optional, or DependencyType.Peer. |
|  [devDependencyList](./rush-lib.packagejsoneditor.devdependencylist.md) |  | `ReadonlyArray<PackageJsonDependency>` | <b><i>(BETA)</i></b> The list of dependencies of type DependencyType.Dev. |
|  [filePath](./rush-lib.packagejsoneditor.filepath.md) |  | `string` | <b><i>(BETA)</i></b> |
|  [name](./rush-lib.packagejsoneditor.name.md) |  | `string` | <b><i>(BETA)</i></b> |
|  [version](./rush-lib.packagejsoneditor.version.md) |  | `string` | <b><i>(BETA)</i></b> |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addOrUpdateDependency(packageName, newVersion, dependencyType)](./rush-lib.packagejsoneditor.addorupdatedependency.md) |  | <b><i>(BETA)</i></b> |
|  [fromObject(object, filename)](./rush-lib.packagejsoneditor.fromobject.md) | `static` | <b><i>(BETA)</i></b> |
|  [load(filePath)](./rush-lib.packagejsoneditor.load.md) | `static` | <b><i>(BETA)</i></b> |
|  [saveIfModified()](./rush-lib.packagejsoneditor.saveifmodified.md) |  | <b><i>(BETA)</i></b> |
|  [tryGetDependency(packageName)](./rush-lib.packagejsoneditor.trygetdependency.md) |  | <b><i>(BETA)</i></b> |
|  [tryGetDevDependency(packageName)](./rush-lib.packagejsoneditor.trygetdevdependency.md) |  | <b><i>(BETA)</i></b> |
