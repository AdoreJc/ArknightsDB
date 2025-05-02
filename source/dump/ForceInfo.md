# ForceInfo

**Namespace:** ` `


## Fields

- `FP xAxisForce`

- `FP yAxisForce`

- `FP dmgValue`


## Methods

- `Void Add(ForceInfo)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ForceInfo : IForceInfo, IHotfixable
{
	public FP xAxisForce; // 0x10
	public FP yAxisForce; // 0x18
	public FP dmgValue; // 0x20
	private static DelegateBridge __Hotfix0_Add; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1c22700 VA: 0x759423a700
	public Void Add(ForceInfo other) { }
	// RVA: 0x1c22bd8 VA: 0x759423abd8
	public Void Reset() { }
	// RVA: 0x1c22060 VA: 0x759423a060
	public Void .ctor() { }
}
```