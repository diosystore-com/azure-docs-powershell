---
external help file:
Module Name: Az.MachineLearningServices
online version: https://learn.microsoft.com/powershell/module/az.MLWorkspace/New-AzMLWorkspaceDatastoreKeyCredentialObject
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/MachineLearningServices/help/New-AzMLWorkspaceDatastoreKeyCredentialObject.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/MachineLearningServices/help/New-AzMLWorkspaceDatastoreKeyCredentialObject.md
---

# New-AzMLWorkspaceDatastoreKeyCredentialObject

## SYNOPSIS
Create an in-memory object for AccountKeyDatastoreCredentials.

> [!NOTE]
>This is the previous version of our documentation. Please consult [the most recent version](/powershell/module/az.machinelearningservices/new-azmlworkspacedatastorekeycredentialobject) for up-to-date information.

## SYNTAX

```
New-AzMLWorkspaceDatastoreKeyCredentialObject -Key <String> [<CommonParameters>]
```

## DESCRIPTION
Create an in-memory object for AccountKeyDatastoreCredentials.

## EXAMPLES

### Example 1: Create an in-memory object for AccountKeyDatastoreCredentials
```powershell
New-AzMLWorkspaceDatastoreKeyCredentialObject
```

Create an in-memory object for AccountKeyDatastoreCredentials

## PARAMETERS

### -Key
[Required] Storage account key.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.MachineLearningServices.Models.Api20220501.AccountKeyDatastoreCredentials

## NOTES

ALIASES

## RELATED LINKS

