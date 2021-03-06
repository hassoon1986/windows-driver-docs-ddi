---
UID: NF:wdm.WRITE_REGISTER_BUFFER_ULONG64
title: WRITE_REGISTER_BUFFER_ULONG64 function (wdm.h)
description: The WRITE_REGISTER_BUFFER_ULONG64 function writes a number of ULONG64 values from a buffer to the specified register.
old-location: kernel\write_register_buffer_ulong64.htm
tech.root: kernel
ms.assetid: 18858A87-D7D8-4387-AD84-6717EC3DAC25
ms.date: 02/26/2018
ms.keywords: WRITE_REGISTER_BUFFER_ULONG64, WRITE_REGISTER_BUFFER_ULONG64 function, kernel.write_register_buffer_ulong64, kernel.write_register_buffer_ulong64, wudfddi_hwaccess/WRITE_REGISTER_BUFFER_ULONG64
ms.topic: function
req.header: wdm.h
req.include-header: Wdm.h, Miniport.h, Wudfwdm.h
req.target-type: Desktop
req.target-min-winverclnt: 64-bit Windows
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library:
req.lib: NtosKrnl.exe
req.dll:
req.irql:
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	DllExport
api_location:
-	NtosKrnl.exe
api_name:
-	WRITE_REGISTER_BUFFER_ULONG64
product:
- Windows
targetos: Windows
req.typenames: WORK_QUEUE_TYPE
req.product: Windows 10 or later.
---

# WRITE_REGISTER_BUFFER_ULONG64 function


## -description


The <b>WRITE_REGISTER_BUFFER_ULONG64</b> function writes a number of ULONG64 values from a buffer to the specified register.



## -parameters




### -param Register [in]

A pointer to the register, which must be a mapped range in memory space.


### -param Buffer [in]

A pointer to a buffer into which an array of ULONG64 values is to be written.


### -param Count [in]

Specifies the number of ULONG64 values to write to the register.




## -returns



This function does not return a value.




## -remarks



The size of the buffer must be large enough to contain at least the specified number of bytes.

For more information, see <a href="https://docs.microsoft.com/windows-hardware/drivers/wdf/reading-and-writing-to-device-registers-in-umdf-1-x-drivers">Reading and Writing to Device Registers in UMDF 1.x Drivers</a>.



