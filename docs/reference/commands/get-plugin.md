---
external help file: Builtin-help.xml
online version: 
schema: 2.0.0
---

# Get-Plugin

## SYNOPSIS
Get the details of a specific plugin or list all plugins.

## SYNTAX

```
Get-Plugin -Bot <Object> [[-Name] <String>] [[-Version] <String>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
!get-plugin builtin
```

Get the details of the \[builtin\] plugin.

### -------------------------- EXAMPLE 2 --------------------------
```
!get-plugin --name builtin --version 0.5.0
```

Get the details of version \[0.5.0\] of the \[builtin\] plugin.

## PARAMETERS

### -Bot
{{Fill Bot Description}}

```yaml
Type: Object
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The name of the plugin to get.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
The version of the plugin to get.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

