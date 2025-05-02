# WaitWhileForSeconds

**Namespace:** `Torappu`


## Fields

- `Single m_endTime`


## Properties

- `Single endTime`


## Methods

- `Single get_endTime()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class WaitWhileForSeconds : CustomYieldInstruction
{
	private Single m_endTime; // 0x10
	private Func`1 m_predicate; // 0x18

	public override Boolean keepWaiting { get; }
	public Single endTime { get; }

	// RVA: 0x677b680 VA: 0x7598d93680
	public override Boolean get_keepWaiting() { }
	// RVA: 0x677b6cc VA: 0x7598d936cc
	public Single get_endTime() { }
	// RVA: 0x677b6d4 VA: 0x7598d936d4
	public Void .ctor(Func`1 predicate, Single time) { }
}
```