---
external help file: Microsoft.Azure.Commands.Profile.dll-Help.xml
ms.assetid: 3E0927A7-EBB9-4463-826E-9B6A3F52E0C9
online version: 
schema: 2.0.0
---

# Disable-AzureRmDataCollection

## SYNOPSIS
Disables collection of data to improve user experience.

## SYNTAX

```
Disable-AzureRmDataCollection [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Disable-AzureRmDataCollection** cmdlet disables collection of data to improve the user experience with APS cmdlets.

APS does not collect data unless you explicitly opt in, either by using the Enable-AzureRmDataCollection cmdlet or when APS prompts you about collecting data the first time that you run a cmdlet.

If you run the current cmdlet before you run any APS cmdlets, APS does not prompt you about data collection the first time that you run a cmdlet.

To enable data collection for the current user, run **Enable-AzureRmDataCollection**.

## EXAMPLES

### Example 1: Disable data collection
```
PS C:\>Disable-AzureRmDataCollection
```

This command disables data collection for the current user on the current computer.

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Enable-AzureRmDataCollection](./Enable-AzureRmDataCollection.md)


