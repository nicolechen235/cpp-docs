---
title: "-X (Ignore Standard Include Paths)"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "/x"
  - "VC.Project.VCCLCompilerTool.IgnoreStandardIncludePath"
  - "VC.Project.VCCLWCECompilerTool.IgnoreStandardIncludePath"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "/X compiler option [C++]"
  - "include files, ignore standard path"
  - "-X compiler option [C++]"
  - "include directories, ignore standard"
  - "X compiler option"
  - "Ignore Standard Include Paths compiler option"
ms.assetid: 16bdf2cc-c8dc-46e4-bdcc-f3caeba5e1ef
caps.latest.revision: 9
ms.author: "corob"
manager: "ghogen"
translation.priority.ht: 
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
# /X (Ignore Standard Include Paths)
Prevents the compiler from searching for include files in directories specified in the PATH and INCLUDE environment variables.  
  
## Syntax  
  
```  
/X  
```  
  
## Remarks  
 You can use this option with the [/I (Additional Include Directories)](../buildref/-i--additional-include-directories-.md) (**/I**`directory`) option.  
  
### To set this compiler option in the Visual Studio development environment  
  
1.  Open the project's **Property Pages** dialog box. For details, see [How to: Open Project Property Pages](../notintoc/how-to--open-project-property-pages.md).  
  
2.  Click the **C/C++** folder.  
  
3.  Click the **Preprocessor** property page.  
  
4.  Modify the **Ignore Standard Include Path** property.  
  
### To set this compiler option programmatically  
  
-   See \<xref:Microsoft.VisualStudio.VCProjectEngine.VCCLCompilerTool.IgnoreStandardIncludePath*>.  
  
## Example  
 In the following command, `/X` tells the compiler to ignore locations specified by the PATH and INCLUDE environment variables, and `/I` specifies the directory in which to look for include files:  
  
```  
CL /X /I \ALT\INCLUDE MAIN.C  
```  
  
## See Also  
 [Compiler Options](../buildref/compiler-options.md)   
 [Setting Compiler Options](../buildref/setting-compiler-options.md)