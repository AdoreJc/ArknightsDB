# HudPlugin

**Namespace:** ` `


## Fields

- `Unit m_owner`

- `UInt32 <instanceUid>k__BackingField`

- `Boolean <isAttached>k__BackingField`


## Properties

- `UInt32 instanceUid`

- `Unit owner`

- `Boolean isAttached`


## Methods

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Unit get_owner()`

- `Boolean get_isAttached()`

- `Void set_isAttached(Boolean)`

- `Void Attach(Unit)`

- `Void Detach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HudPlugin : MonoBehaviour, IHotfixable, IReusableObject, IReusable, IPtrObject
{
	private Unit m_owner; // 0x18
	private static UInt32 s_globalCounter; // 0x0
	private UInt32 <instanceUid>k__BackingField; // 0x20
	private Boolean <isAttached>k__BackingField; // 0x24
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x8
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x10
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x18
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x20
	private static DelegateBridge __Hotfix0_get_owner; // 0x28
	private static DelegateBridge __Hotfix0_get_isAttached; // 0x30
	private static DelegateBridge __Hotfix0_set_isAttached; // 0x38
	private static DelegateBridge __Hotfix0_Attach; // 0x40
	private static DelegateBridge __Hotfix0_Detach; // 0x48
	private static DelegateBridge __Hotfix0_DoAttach; // 0x50
	private static DelegateBridge __Hotfix0_DoDetach; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public UInt32 instanceUid { get; set; }
	protected Unit owner { get; }
	public Boolean isAttached { get; set; }

	// RVA: 0x406a0e0 VA: 0x75966820e0
	public UInt32 get_instanceUid() { }
	// RVA: 0x406a148 VA: 0x7596682148
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x406a1c4 VA: 0x75966821c4
	public virtual Void OnAllocate() { }
	// RVA: 0x406a238 VA: 0x7596682238
	public virtual Void OnRecycle() { }
	// RVA: 0x406a2a4 VA: 0x75966822a4
	protected Unit get_owner() { }
	// RVA: 0x406a30c VA: 0x759668230c
	public Boolean get_isAttached() { }
	// RVA: 0x406a374 VA: 0x7596682374
	private Void set_isAttached(Boolean value) { }
	// RVA: 0x4069a14 VA: 0x7596681a14
	public Void Attach(Unit owner) { }
	// RVA: 0x4069c94 VA: 0x7596681c94
	public Void Detach() { }
	// RVA: 0x406a3f4 VA: 0x75966823f4
	protected virtual Void DoAttach(Unit owner) { }
	// RVA: 0x406a46c VA: 0x759668246c
	protected virtual Void DoDetach() { }
	// RVA: 0x406a4d0 VA: 0x75966824d0
	public Void .ctor() { }
}
```