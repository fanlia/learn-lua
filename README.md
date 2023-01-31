# learn-lua
learn some lua

## source code order

- luaconf.h
- lua.h

## std header file used

```json
[
  [ '#include <string.h>', 48 ],
  [ '#include <stdlib.h>', 32 ],
  [ '#include <limits.h>', 30 ],
  [ '#include <stddef.h>', 28 ],
  [ '#include <stdio.h>', 24 ],
  [ '#include <math.h>', 12 ],
  [ '#include <stdarg.h>', 12 ],
  [ '#include <locale.h>', 10 ],
  [ '#include <ctype.h>', 10 ],
  [ '#include <time.h>', 8 ],
  [ '#include <float.h>', 8 ],
  [ '#include <assert.h>', 8 ],
  [ '#include <errno.h>', 8 ],
  [ '#include <signal.h>', 4 ],
  [ '#include <unistd.h>', 4 ],
  [ '#include <windows.h>', 4 ],
  [ '#include <stdint.h>', 2 ],
  [ '#include <readline/history.h>', 2 ],
  [ '#include <readline/readline.h>', 2 ],
  [ '#include <io.h>', 2 ],
  [ '#include <dlfcn.h>', 2 ],
  [ '#include <sys/types.h>', 2 ],
  [ '#include <setjmp.h>', 2 ],
  [ '#include <sys/wait.h>', 2 ]
]
```

## local header file used

```json
[
  [ '#include "lua.h"', 82 ],
  [ '#include "lprefix.h"', 68 ],
  [ '#include "lobject.h"', 58 ],
  [ '#include "lstate.h"', 44 ],
  [ '#include "ldo.h"', 34 ],
  [ '#include "ldebug.h"', 34 ],
  [ '#include "lauxlib.h"', 30 ],
  [ '#include "lstring.h"', 28 ],
  [ '#include "lmem.h"', 28 ],
  [ '#include "lualib.h"', 26 ],
  [ '#include "lgc.h"', 24 ],
  [ '#include "ltable.h"', 22 ],
  [ '#include "lzio.h"', 18 ],
  [ '#include "ltm.h"', 18 ],
  [ '#include "lfunc.h"', 18 ],
  [ '#include "lopcodes.h"', 16 ],
  [ '#include "llimits.h"', 16 ],
  [ '#include "lvm.h"', 16 ],
  [ '#include "lparser.h"', 10 ],
  [ '#include "llex.h"', 10 ],
  [ '#include "lundump.h"', 10 ],
  [ '#include "lapi.h"', 8 ],
  [ '#include "lctype.h"', 6 ],
  [ '#include "lcode.h"', 6 ],
  [ '#include "luaconf.h"', 4 ],
  [ '#include "ljumptab.h"', 2 ],
  [ '#include LUA_USER_H', 2 ],
  [ '#include "lopnames.h"', 2 ]
]
```
