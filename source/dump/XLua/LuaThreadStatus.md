# LuaThreadStatus

**Namespace:** `XLua`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 4294967295 | LUA_RESUME_ERROR |

| 0 | LUA_OK |

| 1 | LUA_YIELD |

| 2 | LUA_ERRRUN |

| 3 | LUA_ERRSYNTAX |

| 4 | LUA_ERRMEM |

| 5 | LUA_ERRERR |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public enum LuaThreadStatus
{
	public Int32 value__; // 0x10
	public const LuaThreadStatus LUA_RESUME_ERROR = 4294967295; // 0x0
	public const LuaThreadStatus LUA_OK = 0; // 0x0
	public const LuaThreadStatus LUA_YIELD = 1; // 0x0
	public const LuaThreadStatus LUA_ERRRUN = 2; // 0x0
	public const LuaThreadStatus LUA_ERRSYNTAX = 3; // 0x0
	public const LuaThreadStatus LUA_ERRMEM = 4; // 0x0
	public const LuaThreadStatus LUA_ERRERR = 5; // 0x0


}
```