# BattleReusableUI

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UInt32 <instanceUid>k__BackingField`


## Properties

- `UInt32 instanceUid`


## Methods

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class BattleReusableUI : MonoBehaviour, IHotfixable, IReusableObject, IReusable, IPtrObject
{
	private static UInt32 s_globalCounter; // 0x0
	private UInt32 <instanceUid>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x8
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x10
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x18
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UInt32 instanceUid { get; set; }

	// RVA: 0x2079d78 VA: 0x7594691d78
	public UInt32 get_instanceUid() { }
	// RVA: 0x2079de0 VA: 0x7594691de0
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x2079e5c VA: 0x7594691e5c
	public virtual Void OnAllocate() { }
	// RVA: 0x2079ed0 VA: 0x7594691ed0
	public virtual Void OnRecycle() { }
	// RVA: 0x2079f3c VA: 0x7594691f3c
	public Void .ctor() { }
}
```