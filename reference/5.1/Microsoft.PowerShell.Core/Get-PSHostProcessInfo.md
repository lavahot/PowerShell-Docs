---
ms.date:  2017-06-09
schema:  2.0.0
locale:  en-us
keywords:  powershell,cmdlet
online version:  http://go.microsoft.com/fwlink/?LinkId=821487
external help file:  System.Management.Automation.dll-Help.xml
title:  Get-PSHostProcessInfo
---

# Get-PSHostProcessInfo

## SYNOPSIS

## SYNTAX

### ProcessNameParameterSet (Default)
```
Get-PSHostProcessInfo [[-Name] <String[]>] [<CommonParameters>]
```

### ProcessParameterSet
```
Get-PSHostProcessInfo [-Process] <Process[]> [<CommonParameters>]
```

### ProcessIdParameterSet
```
Get-PSHostProcessInfo [-Id] <Int32[]> [<CommonParameters>]
```

## DESCRIPTION

## EXAMPLES

### 1:
```
PS C:\>
```

### 2:
```
PS C:\>
```

## PARAMETERS

### -Id


```yaml
Type: Int32[]
Parameter Sets: ProcessIdParameterSet
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name


```yaml
Type: String[]
Parameter Sets: ProcessNameParameterSet
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Process
Specifies a process by the process object.
The simplest way to use this parameter is to save the results of a **Get-Process** command that returns process that you want to enter in a variable, and then specify the variable as the value of this parameter.

```yaml
Type: Process[]
Parameter Sets: ProcessParameterSet
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

