---
title: Using the remove-ImageGroup Command
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 5b2c9813-5df2-4272-8449-26f3bb16f82b
---
# Using the remove-ImageGroup Command
Removes an image group from a server.

## Syntax

```
WDSUTIL [Options] /Remove-ImageGroumediaGroup:<Image group name> [/Server:<Server name>]
```

## Parameters

|Parameter|Description|
|-------------|---------------|
mediaGroup:<Image group name>|Specifies the name of the image group to be removed|
|[/Server:<Server name>]|Specifies the name of the server. This can be either the NetBIOS name or the fully qualified domain name (FQDN). If no server name is specified, the local server will be used.|

## <a name="BKMK_examples"></a>Examples
To remove the image group, type one of the following:

```
WDSUTIL /Remove-ImageGroumediaGroup:ImageGroup1
WDSUTIL /Verbose /Remove-ImageGroumediaGroup:"My Image Group" /Server:MyWDSServer 
```

#### Additional references
[Command-Line Syntax Key](../../Command-Line-Syntax-Key.md)

[Using the add-ImageGroup Command](../using-the-add-command/Using-the-add-ImageGroup-Command.md)

[Using the get-AllImageGroups Command](../using-the-get-command/Using-the-get-AllImageGroups-Command.md)

[Using the get-ImageGroup Command](../using-the-get-command/Using-the-get-ImageGroup-Command.md)

[Subcommand: set-ImageGroup](../the-set-command/Subcommand--set-ImageGroup.md)

