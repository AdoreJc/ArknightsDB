# TransmitFileOptions

**Namespace:** `System.Net.Sockets`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | UseDefaultWorkerThread |

| 1 | Disconnect |

| 2 | ReuseSocket |

| 4 | WriteBehind |

| 16 | UseSystemThread |

| 32 | UseKernelApc |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public enum TransmitFileOptions
{
	public Int32 value__; // 0x10
	public const TransmitFileOptions UseDefaultWorkerThread = 0; // 0x0
	public const TransmitFileOptions Disconnect = 1; // 0x0
	public const TransmitFileOptions ReuseSocket = 2; // 0x0
	public const TransmitFileOptions WriteBehind = 4; // 0x0
	public const TransmitFileOptions UseSystemThread = 16; // 0x0
	public const TransmitFileOptions UseKernelApc = 32; // 0x0


}
```