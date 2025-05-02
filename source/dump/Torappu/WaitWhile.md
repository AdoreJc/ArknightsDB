# WaitWhile

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class WaitWhile : CustomYieldInstruction
{
	private Func`1 m_predicate; // 0x10

	public override Boolean keepWaiting { get; }

	// RVA: 0x677b62c VA: 0x7598d9362c
	public override Boolean get_keepWaiting() { }
	// RVA: 0x677b650 VA: 0x7598d93650
	public Void .ctor(Func`1 predicate) { }
}
```