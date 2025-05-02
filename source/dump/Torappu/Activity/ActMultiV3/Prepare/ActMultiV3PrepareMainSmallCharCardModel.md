# ActMultiV3PrepareMainSmallCharCardModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `Int32 <innerInstId>k__BackingField`

- `ActMultiV3IdentityType <identityType>k__BackingField`

- `Param <baseParam>k__BackingField`

- `CharacterCardViewModel <baseViewModel>k__BackingField`


## Properties

- `Int32 innerInstId`

- `ActMultiV3IdentityType identityType`

- `Param baseParam`

- `CharacterCardViewModel baseViewModel`

- `Boolean isEmpty`


## Methods

- `Int32 get_innerInstId()`

- `Void set_innerInstId(Int32)`

- `ActMultiV3IdentityType get_identityType()`

- `Void set_identityType(ActMultiV3IdentityType)`

- `Param get_baseParam()`

- `Void set_baseParam(Param)`

- `CharacterCardViewModel get_baseViewModel()`

- `Void set_baseViewModel(CharacterCardViewModel)`

- `Boolean get_isEmpty()`

- `Void Load(Int32, CharacterCardViewModel, ActMultiV3IdentityType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSmallCharCardModel : IHotfixable
{
	private Int32 <innerInstId>k__BackingField; // 0x10
	private ActMultiV3IdentityType <identityType>k__BackingField; // 0x14
	private Param <baseParam>k__BackingField; // 0x18
	private CharacterCardViewModel <baseViewModel>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_innerInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_innerInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_identityType; // 0x10
	private static DelegateBridge __Hotfix0_set_identityType; // 0x18
	private static DelegateBridge __Hotfix0_get_baseParam; // 0x20
	private static DelegateBridge __Hotfix0_set_baseParam; // 0x28
	private static DelegateBridge __Hotfix0_get_baseViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_baseViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x40
	private static DelegateBridge __Hotfix0_Load; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 innerInstId { get; set; }
	public ActMultiV3IdentityType identityType { get; set; }
	public Param baseParam { get; set; }
	public CharacterCardViewModel baseViewModel { get; set; }
	public Boolean isEmpty { get; }

	// RVA: 0x3162858 VA: 0x759577a858
	public Int32 get_innerInstId() { }
	// RVA: 0x3162930 VA: 0x759577a930
	private Void set_innerInstId(Int32 value) { }
	// RVA: 0x31626e0 VA: 0x759577a6e0
	public ActMultiV3IdentityType get_identityType() { }
	// RVA: 0x31629ac VA: 0x759577a9ac
	private Void set_identityType(ActMultiV3IdentityType value) { }
	// RVA: 0x3162748 VA: 0x759577a748
	public Param get_baseParam() { }
	// RVA: 0x3162a28 VA: 0x759577aa28
	private Void set_baseParam(Param value) { }
	// RVA: 0x3162aac VA: 0x759577aaac
	public CharacterCardViewModel get_baseViewModel() { }
	// RVA: 0x3162b14 VA: 0x759577ab14
	private Void set_baseViewModel(CharacterCardViewModel value) { }
	// RVA: 0x3162b98 VA: 0x759577ab98
	public Boolean get_isEmpty() { }
	// RVA: 0x3162c2c VA: 0x759577ac2c
	public Void Load(Int32 instId, CharacterCardViewModel cardViewModel, ActMultiV3IdentityType iType) { }
	// RVA: 0x3162d44 VA: 0x759577ad44
	public Void .ctor() { }
}
```