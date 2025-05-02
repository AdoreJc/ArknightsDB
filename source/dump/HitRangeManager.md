# HitRangeManager

**Namespace:** ` `


## Methods

- `Void Reset()`

- `Void Register(String, IHitRangeProvider)`

- `Void Unregister(String)`

- `Boolean IsTargetIn(HitRangeOption)`

- `Boolean IsInHitRange(HitRangeOption)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HitRangeManager : IHotfixable
{
	private Dictionary`2 m_providers; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_Register; // 0x8
	private static DelegateBridge __Hotfix0_Unregister; // 0x10
	private static DelegateBridge __Hotfix0_IsTargetIn; // 0x18
	private static DelegateBridge __Hotfix0_IsInHitRange; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3fd3ec0 VA: 0x75965ebec0
	public Void Reset() { }
	// RVA: 0x3fd3f48 VA: 0x75965ebf48
	public Void Register(String id, IHitRangeProvider provider) { }
	// RVA: 0x3fd4064 VA: 0x75965ec064
	public Void Unregister(String id) { }
	// RVA: 0x3fd4104 VA: 0x75965ec104
	public Boolean IsTargetIn(HitRangeOption option) { }
	// RVA: 0x3fd444c VA: 0x75965ec44c
	public Boolean IsInHitRange(HitRangeOption option) { }
	// RVA: 0x3fd4790 VA: 0x75965ec790
	public Void .ctor() { }
}
```