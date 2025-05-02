# RareAnimalExtraInfo

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Int32 hpRatio`

- `Boolean found`


## Properties

- `Single extraInfoHpRatio`


## Methods

- `Single get_extraInfoHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class RareAnimalExtraInfo
{
	private Int32 hpRatio; // 0x10
	public Boolean found; // 0x14

	public Single extraInfoHpRatio { get; }

	// RVA: 0x1df8900 VA: 0x7594410900
	public Single get_extraInfoHpRatio() { }
	// RVA: 0x1df8918 VA: 0x7594410918
	public Void .ctor(Int32 hpRatio, Boolean found) { }
}
```