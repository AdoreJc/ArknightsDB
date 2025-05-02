# ActMultiV3PrepareMainCharCardModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `Int32 <innerInstId>k__BackingField`

- `ActMultiV3IdentityType <identityType>k__BackingField`

- `Param baseParam`

- `Int32 skipNum`


## Properties

- `Int32 innerInstId`

- `ActMultiV3IdentityType identityType`

- `Boolean isEmpty`


## Methods

- `Int32 get_innerInstId()`

- `Void set_innerInstId(Int32)`

- `ActMultiV3IdentityType get_identityType()`

- `Void set_identityType(ActMultiV3IdentityType)`

- `Boolean get_isEmpty()`

- `Void Load(Int32, CharacterCardViewModel, ActMultiV3IdentityType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharCardModel : IHotfixable
{
	private Int32 <innerInstId>k__BackingField; // 0x10
	private ActMultiV3IdentityType <identityType>k__BackingField; // 0x14
	public Param baseParam; // 0x18
	public Int32 skipNum; // 0x20
	private static DelegateBridge __Hotfix0_get_innerInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_innerInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_identityType; // 0x10
	private static DelegateBridge __Hotfix0_set_identityType; // 0x18
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x20
	private static DelegateBridge __Hotfix0_Load; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 innerInstId { get; set; }
	public ActMultiV3IdentityType identityType { get; set; }
	public Boolean isEmpty { get; }

	// RVA: 0x315ef30 VA: 0x7595776f30
	public Int32 get_innerInstId() { }
	// RVA: 0x315f304 VA: 0x7595777304
	private Void set_innerInstId(Int32 value) { }
	// RVA: 0x315f380 VA: 0x7595777380
	public ActMultiV3IdentityType get_identityType() { }
	// RVA: 0x315f3e8 VA: 0x75957773e8
	private Void set_identityType(ActMultiV3IdentityType value) { }
	// RVA: 0x315f464 VA: 0x7595777464
	public Boolean get_isEmpty() { }
	// RVA: 0x315f4f0 VA: 0x75957774f0
	public Void Load(Int32 instId, CharacterCardViewModel cardViewModel, ActMultiV3IdentityType iType, Boolean showSkillAndEquip) { }
	// RVA: 0x315f5c0 VA: 0x75957775c0
	public Void .ctor() { }
}
```