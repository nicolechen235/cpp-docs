---
title: "_RTC_NumErrors"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
apiname: 
  - "_RTC_NumErrors"
apilocation: 
  - "msvcrt.dll"
  - "msvcr80.dll"
  - "msvcr90.dll"
  - "msvcr100.dll"
  - "msvcr100_clr0400.dll"
  - "msvcr110.dll"
  - "msvcr110_clr0400.dll"
  - "msvcr120.dll"
  - "msvcr120_clr0400.dll"
  - "ucrtbase.dll"
apitype: "DLLExport"
f1_keywords: 
  - "_RTC_NumErrors"
  - "RTC_NumErrors"
dev_langs: 
  - "C++"
  - "C"
helpviewer_keywords: 
  - "run-time errors"
  - "_RTC_NumErrors function"
  - "RTC_NumErrors function"
ms.assetid: 7e82adae-38e2-4f8b-bc0b-37bda8109fd1
caps.latest.revision: 12
ms.author: "corob"
manager: "ghogen"
translation.priority.mt: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# _RTC_NumErrors
Returns the total number of errors that can be detected by run-time error checks (RTC). You can use this number as the control in a **for** loop, where each value in the loop is passed to [_RTC_GetErrDesc](../crt/_rtc_geterrdesc.md).  
  
## Syntax  
  
```  
  
int _RTC_NumErrors( void );  
  
```  
  
## Return Value  
 An integer whose value represents the total number of errors that can be detected by the Visual C++ run-time error checks.  
  
## Requirements  
  
|Routine|Required header|  
|-------------|---------------------|  
|`_RTC_NumErrors`|\<rtcapi.h>|  
  
 For more information, see [Compatibility](../crt/compatibility.md).  
  
## Libraries  
 All versions of the [C run-time libraries](../crt/crt-library-features.md).  
  
## .NET Framework Equivalent  
 Not applicable. To call the standard C function, use `PInvoke`. For more information, see [Platform Invoke Examples](../Topic/Platform%20Invoke%20Examples.md).  
  
## See Also  
 [_RTC_GetErrDesc](../crt/_rtc_geterrdesc.md)   
 [Run-Time Error Checking](../crt/run-time-error-checking.md)