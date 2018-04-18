---
external help file: UniversalDashboard-help.xml
online version: 
schema: 2.0.0
---

# Write-UDLog

## SYNOPSIS
Writes a log messge to the Universal Dashboard log.

## SYNTAX

```
Write-UDLog [-Message] <String> [-Level <String>] [-LoggerName <String>]
```

## DESCRIPTION
Writes a log messge to the Universal Dashboard log. This can be helpful for debugging endpoints. 

## EXAMPLES

### Example 1
```
PS C:\> Write-UDLog -Level Debug -Message "Test message" 
```

Writes a debug message to the Universal Dashboard log.

## PARAMETERS

### -Level
The log level for this log message.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: Debug, Info, Warning, Error

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LoggerName
The name of the logger. This is useful for grouping log messages together.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Message
The message to log.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### None


## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
