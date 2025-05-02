# LifeCycleStatus

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | PropagationStopped |

| 2 | ImmediatePropagationStopped |

| 4 | DefaultPrevented |

| 8 | Dispatching |

| 16 | Pooled |

| 32 | IMGUIEventIsValid |

| 64 | StopDispatch |

| 128 | PropagateToIMGUI |

| 512 | Dispatched |

| 1024 | Processed |

| 2048 | ProcessedByFocusController |

## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private enum LifeCycleStatus
{
	public Int32 value__; // 0x10
	public const LifeCycleStatus None = 0; // 0x0
	public const LifeCycleStatus PropagationStopped = 1; // 0x0
	public const LifeCycleStatus ImmediatePropagationStopped = 2; // 0x0
	public const LifeCycleStatus DefaultPrevented = 4; // 0x0
	public const LifeCycleStatus Dispatching = 8; // 0x0
	public const LifeCycleStatus Pooled = 16; // 0x0
	public const LifeCycleStatus IMGUIEventIsValid = 32; // 0x0
	public const LifeCycleStatus StopDispatch = 64; // 0x0
	public const LifeCycleStatus PropagateToIMGUI = 128; // 0x0
	public const LifeCycleStatus Dispatched = 512; // 0x0
	public const LifeCycleStatus Processed = 1024; // 0x0
	public const LifeCycleStatus ProcessedByFocusController = 2048; // 0x0


}
```