# Set-PnPFileCheckedOut

## SYNOPSIS
Checks out a file

## SYNTAX 

```powershell
Set-PnPFileCheckedOut -Url <String>
                      [-Web <WebPipeBind>]
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
PS:>Set-PnPFileCheckedOut -Url "/sites/testsite/subsite/Documents/Contract.docx"
```

Checks out the file "Contract.docx" in the "Documents" library.

## PARAMETERS

### -Url
The server relative url of the file to check out

```yaml
Type: String
Parameter Sets: (All)

Required: True
Position: 0
Accept pipeline input: True
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