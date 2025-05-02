# SandboxPlacedItemStatusValue

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Int32 hpRatio`

- `Direction direction`


## Properties

- `Single statusHpRatio`


## Methods

- `Void set_statusHpRatio(Single)`

- `Single get_statusHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxPlacedItemStatusValue
{
	public Int32 hpRatio; // 0x10
	public Direction direction; // 0x14

	public Single statusHpRatio { get; set; }

	// RVA: 0x1df8b64 VA: 0x7594410b64
	public Void set_statusHpRatio(Single value) { }
	// RVA: 0x1df8c10 VA: 0x7594410c10
	public Single get_statusHpRatio() { }
	// RVA: 0x1df8c28 VA: 0x7594410c28
	public override Boolean Equals(Object obj) { }
	// RVA: 0x1df8b5c VA: 0x7594410b5c
	public Void .ctor() { }
}
```