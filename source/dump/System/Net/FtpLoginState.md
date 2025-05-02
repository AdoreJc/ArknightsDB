# FtpLoginState

**Namespace:** `System.Net`


## Fields

- `Byte value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NotLoggedIn |

| 1 | LoggedIn |

| 2 | LoggedInButNeedsRelogin |

| 3 | ReloginFailed |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal enum FtpLoginState
{
	public Byte value__; // 0x10
	public const FtpLoginState NotLoggedIn = 0; // 0x0
	public const FtpLoginState LoggedIn = 1; // 0x0
	public const FtpLoginState LoggedInButNeedsRelogin = 2; // 0x0
	public const FtpLoginState ReloginFailed = 3; // 0x0


}
```