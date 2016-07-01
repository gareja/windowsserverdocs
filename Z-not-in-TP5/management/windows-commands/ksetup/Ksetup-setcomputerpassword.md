---
title: Ksetup:setcomputerpassword
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: e307d8f6-3b93-4c24-ac04-f31549f7dc7d
---
# Ksetup:setcomputerpassword
Sets the password for the local computer. For examples of how this command can be used, see [Examples](#BKMK_Examples).

## Syntax

```
ksetup /setcomputerpassword <Password>
```

### Parameters

|Parameter|Description|
|-------------|---------------|
|<Password>|Uses the supplied password to set the computer account on the local computer.<br /><br />The password can only be set by using an account with administrative privileges. The password can be from 1 to 156 alphanumeric or special characters.|

## Remarks
This command affects the computer account only.

You must restart the computer for the password change to take effect.

The computer account password is not displayed in the registry or as output from the **ksetup** command.

## <a name="BKMK_Examples"></a>Examples
Change the computer account password on the local computer from IPops897 to IPop$897!.

```
ksetup /setcomputerpassword IPop$897!
```

## Additional references

-   [Ksetup](../Ksetup.md)

-   [Command-Line Syntax Key](../Command-Line-Syntax-Key.md)

