# PrecisePeriodicTimer

**Namespace:** `Torappu`


## Methods

- `Int32 UpdateMultiple(FP)`

- `Boolean NextMultiple(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PrecisePeriodicTimer : PeriodicTimer
{

	public override Boolean isReady { get; }

	// RVA: 0x3103934 VA: 0x759571b934
	public override Boolean get_isReady() { }
	// RVA: 0x31039cc VA: 0x759571b9cc
	public Void .ctor() { }
	// RVA: 0x3103a2c VA: 0x759571ba2c
	public Void .ctor(FP periodTime) { }
	// RVA: 0x3103a30 VA: 0x759571ba30
	public override Boolean Update(FP deltaTime) { }
	// RVA: 0x3103ab0 VA: 0x759571bab0
	public override Boolean Next() { }
	// RVA: 0x3103b38 VA: 0x759571bb38
	public Int32 UpdateMultiple(FP deltaTime) { }
	// RVA: 0x3103c34 VA: 0x759571bc34
	public Boolean NextMultiple(Int32 count) { }
}
```