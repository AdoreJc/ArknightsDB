# TargetEnterExitHandler

**Namespace:** ` `


## Fields

- `Options m_options`

- `PeriodicTicker m_triggerTicker`


## Methods

- `Void OnTargetEnter(Entity, UInt32)`

- `Void OnTargetExit(Entity, UInt32)`

- `Void OnTick()`

- `Void _UpdateInvalidTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TargetEnterExitHandler : MultiEnterExitHandler`1
{
	private Options m_options; // 0x18
	private ListSet`1 m_invalidTarget; // 0x30
	private PeriodicTicker m_triggerTicker; // 0x38


	// RVA: 0x1e3cf08 VA: 0x7594454f08
	public Void .ctor(Options options) { }
	// RVA: 0x1e3f8bc VA: 0x75944578bc
	public override Void Clear() { }
	// RVA: 0x1e3f028 VA: 0x7594457028
	public Void OnTargetEnter(Entity target, UInt32 abilityUniqueId) { }
	// RVA: 0x1e3f2e0 VA: 0x75944572e0
	public Void OnTargetExit(Entity target, UInt32 abilityUniqueId) { }
	// RVA: 0x1e3f664 VA: 0x7594457664
	public Void OnTick() { }
	// RVA: 0x1e3faf4 VA: 0x7594457af4
	protected override Void OnRealEnter(Entity target) { }
	// RVA: 0x1e3fba8 VA: 0x7594457ba8
	protected override Void OnRealExit(Entity target) { }
	// RVA: 0x1e3f940 VA: 0x7594457940
	private Void _UpdateInvalidTarget() { }
}
```