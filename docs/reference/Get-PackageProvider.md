---
external help file: AnyPackage.dll-Help.xml
Module Name: AnyPackage
online version: https://go.anypackage.dev/Get-PackageProvider
schema: 2.0.0
parent: AnyPackage
---

# Get-PackageProvider

## Synopsis

Gets imported package providers.

## Syntax

```powershell
Get-PackageProvider [[-Name] <String[]>] [<CommonParameters>]
```

## Description

Gets imported package providers.

## Examples

### Example 1

```powershell
PS C:\> Get-PackageProvider

Name                 Priority Operations
----                 -------- ----------
msu                       100 Get
PowerShellGet             100 Find, Get, Publish, Install, Save, Uninstall, Update, GetSource, SetSource
```

The command gets the imported package providers.

## Parameters

### -Name

Specifies the package provider name.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Provider

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: True
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## Inputs

### System.String

You can pipe a package provider name to this cmdlet.

## Outputs

### AnyPackage.Provider.PackageProviderInfo

This cmdlet returns objects that represent a package provider.

## Notes

## Related Links

[Import-Module](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/import-module)

[Remove-Module](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/remove-module)
