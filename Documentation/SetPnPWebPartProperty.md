# Set-PnPWebPartProperty

## SYNOPSIS
Sets a web part property

## SYNTAX 

```powershell
Set-PnPWebPartProperty -ServerRelativePageUrl <String>
                       -Identity <GuidPipeBind>
                       -Key <String>
                       -Value <PSObject>
                       [-Web <WebPipeBind>]
```

## PARAMETERS

### -Identity


```yaml
Type: GuidPipeBind
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -Key


```yaml
Type: String
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -ServerRelativePageUrl


```yaml
Type: String
Parameter Sets: (All)
Aliases: PageUrl

Required: True
Position: Named
Accept pipeline input: False
```

### -Value


```yaml
Type: PSObject
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -Web
The GUID, server relative url (i.e. /sites/team1) or web instance of the web to apply the command to. Omit this parameter to use the current web.

```yaml
Type: WebPipeBind
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)