---
external help file: JamfPSPro-help.xml
Module Name: JamfPSPro
online version:
schema: 2.0.0
---

# Get-Jamf

## SYNOPSIS
Get data from Jamf Pro

## SYNTAX

```
Get-Jamf [-Component] <String> [[-Params] <String[]>] [<CommonParameters>]
```

## DESCRIPTION
Get data from Jamf Pro

## EXAMPLES

### EXAMPLE 1
```
Get-Jamf -Component computers -Path 'computers/name/{name}' -Param 'HostName'
```

### EXAMPLE 2
```
Get-Jamf -Component local-admin-password -Path 'local-admin-password/{clientManagementId}/account/{username}/audit' -Param 69,myUser
```

## PARAMETERS

### -Component
Specify the 'component' name

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Params
Specify params outlined by '{}' in component path

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS