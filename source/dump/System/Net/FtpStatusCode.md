# FtpStatusCode

**Namespace:** `System.Net`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Undefined |

| 110 | RestartMarker |

| 120 | ServiceTemporarilyNotAvailable |

| 125 | DataAlreadyOpen |

| 150 | OpeningData |

| 200 | CommandOK |

| 202 | CommandExtraneous |

| 212 | DirectoryStatus |

| 213 | FileStatus |

| 215 | SystemType |

| 220 | SendUserCommand |

| 221 | ClosingControl |

| 226 | ClosingData |

| 227 | EnteringPassive |

| 230 | LoggedInProceed |

| 234 | ServerWantsSecureSession |

| 250 | FileActionOK |

| 257 | PathnameCreated |

| 331 | SendPasswordCommand |

| 332 | NeedLoginAccount |

| 350 | FileCommandPending |

| 421 | ServiceNotAvailable |

| 425 | CantOpenData |

| 426 | ConnectionClosed |

| 450 | ActionNotTakenFileUnavailableOrBusy |

| 451 | ActionAbortedLocalProcessingError |

| 452 | ActionNotTakenInsufficientSpace |

| 500 | CommandSyntaxError |

| 501 | ArgumentSyntaxError |

| 502 | CommandNotImplemented |

| 503 | BadCommandSequence |

| 530 | NotLoggedIn |

| 532 | AccountNeeded |

| 550 | ActionNotTakenFileUnavailable |

| 551 | ActionAbortedUnknownPageType |

| 552 | FileActionAborted |

| 553 | ActionNotTakenFilenameNotAllowed |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public enum FtpStatusCode
{
	public Int32 value__; // 0x10
	public const FtpStatusCode Undefined = 0; // 0x0
	public const FtpStatusCode RestartMarker = 110; // 0x0
	public const FtpStatusCode ServiceTemporarilyNotAvailable = 120; // 0x0
	public const FtpStatusCode DataAlreadyOpen = 125; // 0x0
	public const FtpStatusCode OpeningData = 150; // 0x0
	public const FtpStatusCode CommandOK = 200; // 0x0
	public const FtpStatusCode CommandExtraneous = 202; // 0x0
	public const FtpStatusCode DirectoryStatus = 212; // 0x0
	public const FtpStatusCode FileStatus = 213; // 0x0
	public const FtpStatusCode SystemType = 215; // 0x0
	public const FtpStatusCode SendUserCommand = 220; // 0x0
	public const FtpStatusCode ClosingControl = 221; // 0x0
	public const FtpStatusCode ClosingData = 226; // 0x0
	public const FtpStatusCode EnteringPassive = 227; // 0x0
	public const FtpStatusCode LoggedInProceed = 230; // 0x0
	public const FtpStatusCode ServerWantsSecureSession = 234; // 0x0
	public const FtpStatusCode FileActionOK = 250; // 0x0
	public const FtpStatusCode PathnameCreated = 257; // 0x0
	public const FtpStatusCode SendPasswordCommand = 331; // 0x0
	public const FtpStatusCode NeedLoginAccount = 332; // 0x0
	public const FtpStatusCode FileCommandPending = 350; // 0x0
	public const FtpStatusCode ServiceNotAvailable = 421; // 0x0
	public const FtpStatusCode CantOpenData = 425; // 0x0
	public const FtpStatusCode ConnectionClosed = 426; // 0x0
	public const FtpStatusCode ActionNotTakenFileUnavailableOrBusy = 450; // 0x0
	public const FtpStatusCode ActionAbortedLocalProcessingError = 451; // 0x0
	public const FtpStatusCode ActionNotTakenInsufficientSpace = 452; // 0x0
	public const FtpStatusCode CommandSyntaxError = 500; // 0x0
	public const FtpStatusCode ArgumentSyntaxError = 501; // 0x0
	public const FtpStatusCode CommandNotImplemented = 502; // 0x0
	public const FtpStatusCode BadCommandSequence = 503; // 0x0
	public const FtpStatusCode NotLoggedIn = 530; // 0x0
	public const FtpStatusCode AccountNeeded = 532; // 0x0
	public const FtpStatusCode ActionNotTakenFileUnavailable = 550; // 0x0
	public const FtpStatusCode ActionAbortedUnknownPageType = 551; // 0x0
	public const FtpStatusCode FileActionAborted = 552; // 0x0
	public const FtpStatusCode ActionNotTakenFilenameNotAllowed = 553; // 0x0


}
```