# InfiniteTimer

**Namespace:** ` `


## Fields

- `Int32 cancelled`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class InfiniteTimer : Timer
{
	private Int32 cancelled; // 0x18

	internal override Boolean HasExpired { get; }

	// RVA: 0x6435a78 VA: 0x7598a4da78
	internal Void .ctor() { }
	// RVA: 0x6435c54 VA: 0x7598a4dc54
	internal override Boolean get_HasExpired() { }
	// RVA: 0x6435c5c VA: 0x7598a4dc5c
	internal override Boolean Cancel() { }
}
```