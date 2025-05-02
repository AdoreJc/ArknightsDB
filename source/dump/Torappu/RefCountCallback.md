# RefCountCallback

**Namespace:** `Torappu`


## Fields

- `Action callback`

- `Int32 refCnt`


## Methods

- `Boolean DecAndInvoke()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class RefCountCallback
{
	public Action callback; // 0x10
	public Int32 refCnt; // 0x18


	// RVA: 0x67474d8 VA: 0x7598d5f4d8
	public Boolean DecAndInvoke() { }
	// RVA: 0x674753c VA: 0x7598d5f53c
	public static Void Reset(RefCountCallback inst) { }
	// RVA: 0x6747554 VA: 0x7598d5f554
	public Void .ctor() { }
}
```