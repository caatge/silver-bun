# Description

 * Module and Memory hacking package for x64 applications.

## Instructions

Add files to your solution, libraries used are included in the header files of the package.
A define is present to instead make this package use precompiled headers.

Example from **module.h**:

```cpp
#ifndef USE_PRECOMPILED_HEADERS
#include "memaddr.h"
#include <iostream>
#include <string>
#include <vector>
#include <windows.h>
#include <psapi.h>
#include <intrin.h>
#elif
#pragma message("ADD PRECOMPILED HEADERS TO SILVER-BUN.")
#endif // !USE_PRECOMPILED_HEADERS
```